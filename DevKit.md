# DevKit Privacy Policy

**Effective date: 2026-10-29**

## In one line

DevKit collects nothing, uploads nothing, and sells nothing. It uses your own App Store Connect key to fetch your own reports directly from Apple, and keeps them on your device.

## 1. No servers, no data collection

There is no account system, no cloud sync, no advertising, no analytics, and no third-party SDK inside this app. We cannot see your reports, your key, or any usage data — not because we choose not to look, but because none of it ever reaches us.

The app also has a "Demo data" mode, which shows fixed sample values and contains no real account information.

## 2. Your API key

The Issuer ID, Key ID, and `.p8` private key you enter in Settings → Apple Connect are stored only in the device's Keychain, marked as **this device only** and never synced through iCloud Keychain.

The key is used solely to sign short-lived JWTs on your device, proving to Apple's App Store Connect API that you own that developer account. It is never sent to the developer or to any third party.

You can remove it at any time with Settings → Data cleanup → Clear everything (including API key), or by deleting the app.

## 3. Data fetched and stored on your device

To show your business data, the app uses your key to fetch the following from Apple:

- Sales and Trends daily reports: sales, proceeds, downloads, territories, product types, and similar fields;
- Subscription reports: active subscriptions, trials, conversions, refunds, and similar fields;
- Analytics reports: impressions, product page views, source types, and similar fields;
- App metadata: name, subtitle, version, release date, SKU, and similar fields;
- Public App Store ratings and icons, through Apple's public lookup endpoint.

All of these are **aggregated reports** supplied by Apple. They do not contain customer names, email addresses, physical addresses, or payment details. The data is cached only in the app's sandbox on this device (JSON files under Application Support) to support offline viewing and avoid repeated requests; you can clear it at any time under Data cleanup.

Your preferences (language, theme, default range, chart style, Face ID toggle, Pro entitlement flag) are stored in the app's local settings (UserDefaults).

## 4. Network requests

The app connects only to Apple's servers:

- `api.appstoreconnect.apple.com` — to read your own App Store Connect reports and metadata;
- `itunes.apple.com` — to read public App Store ratings and icons;
- Purchases, restores, and offer-code redemption are handled by Apple's StoreKit and system sheets.

There is no developer server and no third-party analytics, advertising, or data service. Currency exchange rates are bundled inside the app rather than fetched online. Apple's handling of these requests is governed by Apple's privacy policy.

The app does not request access to contacts, location, photos, or the microphone.

## 5. Face ID and app lock

Face ID unlock is optional. When enabled, the app asks the system's LocalAuthentication framework to verify your identity. Biometric data is handled by the system; the app receives only a success or failure result and never accesses or stores your face data. Turn the switch off or delete the app to stop using it.

## 6. In-app purchases

- The Pro yearly subscription and lifetime purchase are processed by Apple's App Store, including payment, renewal, refunds, and invoices. We never receive your name, address, email, or payment details.
- The app uses StoreKit to check whether the current Apple account owns the relevant entitlement, in order to unlock historical ranges. The result is stored only on this device.
- Offer codes are redeemed through Apple's system redemption sheet; the app never sees the code itself.
- Subscriptions can be managed or cancelled at any time in your App Store account settings.

## 7. Import and export

CSV import and export are always initiated by you, using the system file picker to choose a file or a destination. The app never uploads or shares anything automatically.

## 8. Deleting data

- Settings → Data cleanup → Clear report cache: deletes the on-device report cache and keeps the API key.
- Clear everything (including API key): deletes the cache, subscription reports, analytics data, and the key stored in the Keychain.
- Deleting the app removes all on-device data. We hold no copy that could be restored or provided.
- If iCloud Backup is enabled on the device, the app's sandbox may be included in your own iCloud backup as part of the system's normal behavior. You can turn that off in system settings; we cannot read it.

## 9. Children

DevKit is a business data tool for Apple developers. It is not directed at children, and we do not knowingly collect information from children.

## 10. Changes to this policy

If how the app handles data ever changes (for example, if a new online service is introduced), this page will be updated and the change will be noted in the release notes. As of the effective date above, this policy matches the app's actual behavior.

## 11. Contact

Questions, suggestions, or complaints: ss0593@qq.com
