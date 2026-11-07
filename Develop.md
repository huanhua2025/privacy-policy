# Develop Privacy Policy

**Effective date: November 7, 2026**
**Version: 1.0**
**Applies to: the iOS app Develop**

Thank you for using Develop. It is a film-simulation camera app that runs entirely on your device. We have kept this policy plain: **the app does not connect to the internet, does not collect, and does not upload any of your information.**

---

## 1. What We Do Not Collect

Develop does not require an account, and does not collect any of the following:

- Identity information such as name, phone number, email address, or postal address
- Contacts, location, calendar, health data, clipboard, or other system data
- Device identifiers (IDFA, IDFV), advertising identifiers, usage behavior, or analytics
- The content of your photos, or when and where they were taken

The app contains no advertising SDKs, analytics SDKs, crash-reporting SDKs, or any third-party tracking components.

---

## 2. Permissions and Their Purpose

### 1. Camera (NSCameraUsageDescription)

- **Purpose**: live viewfinder, focus, metering, and capture.
- **Processing**: the image is processed in real time on your device to produce the final photo. **It is never uploaded to any server.**
- **You can**: turn off camera access at any time in Settings → Develop → Camera. Without it, only the viewfinder and capture are unavailable; all other features keep working.

### 2. Photos (NSPhotoLibraryUsageDescription)

- **Purpose**: save finished photos to your photo library and create a "Develop" album for easy access; show thumbnails of your shots in the in-app Roll.
- **Processing**: the app only reads and writes photos related to its own features. It does **not upload, scan, or analyze** the contents of your photo library.
- **You can**: adjust or turn off photo access at any time in Settings → Develop → Photos. Photos already saved to your library are managed by you.

Develop does **not** request the microphone, location, contacts, Bluetooth, health, or any other permission unrelated to photography.

---

## 3. Where Data Is Stored

All data stays on your device:

| Data | Location | Notes |
| --- | --- | --- |
| Settings (skin, film, exposure compensation, toggles, etc.) | System UserDefaults | On-device only; deleted when the app is uninstalled |
| Roll index and thumbnails | App sandbox (Application Support) | On-device only; deleted when the app is uninstalled |
| Finished-photo cache and the original frame used by "Switch Film" | App sandbox (Caches) | Capped at about 300 MB; the system may purge it when storage is low |
| Finished photos | Your photo library (the "Develop" album) | Managed by you; uninstalling the app does not delete them |

We run no servers, do no cloud sync, and back up no data to any third party.

---

## 4. Network and Third-Party Services

- Develop itself makes no network requests and contains no third-party SDKs.
- **In-App Purchase**: the one-time purchase, restore purchases, and promotional/redemption codes are all handled by Apple's App Store (StoreKit). Transactions are completed by Apple; we cannot access your payment method, billing address, or other payment information. The app only reads the "purchased" entitlement status locally on your device.
- For how Apple handles related data, please refer to [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).
- **Sharing photos**: when you choose to share a finished photo, the iOS system share sheet opens and the app you select handles it. We do not take part in or retain anything.

---

## 5. Data Deletion

- Uninstalling Develop deletes all data in the app sandbox (settings, roll index, thumbnails, and original-frame cache).
- Finished photos in your photo library must be deleted manually in the Photos app.
- Because we do not collect any server-side data, there is no account or data deletion request to file.

---

## 6. Children's Privacy

Develop does not separately collect any information from children, and does not collect personal information from any user. Parents can let children use the app under supervision without concern; if you have concerns about permissions, you can turn off camera or photo access in system settings.

---

## 7. Your Rights

- **Be informed**: this policy fully describes the app's permissions and data handling.
- **Control**: you can turn off camera/photo permissions in system settings at any time.
- **Deletion**: uninstalling the app clears all local data.
- **Withdrawal**: turning off permissions or uninstalling the app counts as withdrawing the relevant authorization; this does not affect local processing already completed under that authorization.

---

## 8. Policy Updates

If a future version adds features that change how data is handled (for example, cloud sync), we will update this policy in the app and on this page, and will highlight significant changes. Continued use means you accept the updated policy.

---

## 9. Contact Us

If you have any questions, comments, or complaints about this policy, please contact:

- Email: `ss0593@qq.com`
- We will respond within a reasonable time.
