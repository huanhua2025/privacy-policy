# Moonlamp Privacy Policy

**Effective date:** 2026-10-20
**Version:** 1.0

Moonlamp ("the App") is a screen night light and sleep sound app for iPhone. This policy explains how the App handles your information. Please read it before you use the App; by continuing to use it you acknowledge that you have understood this policy.

---

## 1. In short

- The App requires **no sign-up and no sign-in, and it does not collect your personal information**.
- The App has **no server and makes no network requests of its own**: no advertising, no analytics, no third-party SDKs, and no App Tracking Transparency (ATT) tracking.
- All of your settings and app state **stay in local storage on your device**.
- The one exception is the in-app purchase: the transaction is handled by Apple, and we neither receive nor store your payment details. See section 4.

## 2. What we do not collect

The App never asks for, reads, or uploads any of the following:

- Identity details such as your name, phone number, email address, or postal address (there is no account system)
- Device identifiers (IDFA, IDFV, serial number), advertising identifiers, device fingerprints
- Location (no location permission is requested)
- Contacts, calendar, photos, files, microphone, camera, health data, motion data
- Usage analytics, crash reports, performance telemetry (no crash-reporting or analytics service is integrated)

The App requests no system permissions at all — not camera, microphone, photo library, contacts, location, or health.

## 3. Data stored on your device

The App records the following in its **sandboxed storage** on your device, only so that it keeps working the way you left it:

| Data | Purpose |
| --- | --- |
| Language, brightness level, color temperature, whether to follow the real moon, moon size and position | Restoring your last light setup |
| The nature sound you picked, its volume, and the remaining sleep-timer time | Resuming playback and the countdown |
| Guided breathing setting and current stage | Resuming your practice |
| A flag recording that Pro is unlocked | So the App does not have to ask Apple again on every launch |
| A flag recording that onboarding is finished | So the walkthrough is not shown again |

All of this is read and written on the device only: nothing is uploaded, nothing syncs to a cloud, and nothing is shared with other apps or companies. Pure mode applies to the current session only and is never written to storage.

The App and its Lock Screen widget share one system-provided **App Group container**. The widget and the Control Center item use it to show the current moon phase, the brightness percentage, the sound name, and whether the light is on. That container also exists only on your device.

The App uses the system's background **audio** mode so that sleep sounds and guided breathing keep playing after you lock the screen or switch to another app. **The App never records audio.**

The App registers the URL scheme `moonlamp://light`, used only so that the Lock Screen widget and the Control Center item can turn the light on locally when you tap them. No data is transmitted.

## 4. In-app purchase and offer codes

Pro is a **one-time purchase** (a non-consumable in-app purchase). There is no subscription.

- Pricing, payment, receipts, and refunds are handled entirely by **Apple** through the App Store. **We neither receive nor store your payment method, order number, Apple ID, or purchase records.**
- The App asks the system's StoreKit once whether this Apple account already owns the purchase, only to decide whether to keep showing the upgrade entry. That check happens between your device and Apple, not through us.
- "Restore purchase" opens Apple's own system interface, which re-checks your entitlement on the device.
- "Redeem Code" opens the offer-code form provided by Apple's system. **The code you enter goes to Apple only; we never see it.**
- In the **App Privacy** declaration in App Store Connect, the App therefore reports: data is collected, limited to **Purchase History**, for the purpose of **App Functionality**, **not linked to your identity**, and **not used for tracking**.

## 5. Feedback you choose to send

"Feedback" in Settings opens **your own Mail app** with a draft that is pre-filled with: the App version, your device model and iOS version, and the language currently selected in the App.

- Those details are generated on the device while the draft is prepared. The App uploads nothing.
- The message reaches our support address through your own mail provider only if you press Send yourself.
- Any email address and message content you choose to send is kept only as long as needed to handle that feedback, is used for no other purpose, and is not given to third parties. You can ask us to delete it at any time by writing from the same address.

## 6. Where data is stored, transfers, and retention

- Data created by the App stays on your device and is kept until you delete the App.
- The App has no server, so there is no cross-border storage or transfer. **The only transfer that can happen is the feedback email you choose to send**, which your mail provider handles under its own policy.

## 7. Deletion

Deleting the App removes its sandbox and its App Group container with it, so no App data remains on the device.

The App has no accounts, so there is no account-deletion step — App Store Review Guideline 5.1.1(v) applies only to apps that support registration. If you have sent us a feedback email, write to the address below and we will delete it.

## 8. Children

The App is not directed at children, and we do not knowingly collect information from them. If you are under the age of digital consent in your country, use the App only with a parent's or guardian's involvement. A parent or guardian who believes we received a child's feedback can ask us to delete it at the address below.

## 9. Your rights

Depending on where you live — for example under the PRC Personal Information Protection Law (PIPL), the EU/EEA GDPR, the UK GDPR, the Brazilian LGPD, or the California CCPA/CPRA — you may have the right to access, correct, or delete your information, to restrict or object to processing, to withdraw consent, to opt out of the sale or sharing of personal information, and to lodge a complaint with a supervisory authority.

Because the App does not process personal information, the practical way to exercise these rights is to **delete the App**, which clears all local data. If you did write to us, email us to request access to or deletion of that message. You may also complain to the data protection authority in your jurisdiction (in the EU, the authority of your country of residence or of your place of work).

## 10. Changes to this policy

We may update this policy. When we do, we revise the effective date and version number at the top of the page. If a change materially affects your rights, we will point it out inside the App before it takes effect. Continuing to use the App after an update means you accept the updated policy.

## 11. Governing text

This policy is published in English, and the English text is the operative version for every country and storefront where the App is available.

## 12. Contact

- Email: **ss0593@qq.com**

---

*This policy describes what the App actually does today, and each statement maps to the code: no networking code, no third-party SDK, no advertising or analytics, and no camera, microphone, photo library, contacts, location, or health permission.*
