# Privacy Policy

**Last Updated: July 13, 2026**

This document is the Privacy Policy for **Protractor ("the App")** and explains how **we** handle matters related to your information.

---

## 1. What Information Do We Collect?

**We do NOT actively collect any personally identifiable information (PII).**
The App is a standalone AR measurement utility. No account registration, no login, and no personal profile is created or transmitted.

The App only processes necessary information **locally on your device**, and never uploads it to any server:

| Information Type | How It Is Used | Uploaded to Server? |
|---|---|---|
| **Camera Feed** | Passed in real time to the iOS ARKit framework for plane detection and AR anchor placement. The frames remain inside the iOS Metal/ARKit rendering pipeline, never written to disk nor leaving the App process. | ❌ No |
| **Measurement Coordinates** | Used to compute distance, angle, area and volume; held only in memory. Not persisted unless you manually save a screenshot. | ❌ No |
| **User Preferences (units, point size, etc.)** | Stored in local `UserDefaults` to remember your settings. | ❌ No |
| **In-App Purchase Unlock Status** | Marked locally via `UserDefaults`. The Apple App Store processes the entire transaction; we never receive payment data. | ❌ No |
| **Crash & Performance Logs** | If you enable "Share crash & performance data with App developers" in iOS, Apple may anonymously send diagnostics to fix bugs. This mechanism is fully controlled by Apple and outside the scope of the App itself. | 🟡 Apple-controlled |

---

## 2. Permissions We Request

| Permission | Purpose | When Granted |
|---|---|---|
| **Camera (NSCameraUsageDescription)** | Required by ARKit to detect real-world planes and place measurement anchors; core functionality of the App. | Requested at first launch |

**You may disable camera permission at any time in iOS Settings → this App's name.** Doing so only disables AR measurement; saved preferences remain intact.

---

## 3. Third-Party Services, SDKs & Frameworks

The App currently **does not integrate** any third-party ad SDK, analytics SDK, tracking SDK or social login SDK.

All system frameworks used by the App are built-in Apple frameworks:

- `ARKit` / `RealityKit` — AR plane detection and rendering
- `SwiftUI` / `UIKit` — User interface
- `StoreKit` — One-time non-consumable in-app purchase (the transaction process is handled exclusively by Apple)

---

## 4. Children's Privacy

The App is not directed at children under 13 (or similar age thresholds per applicable jurisdiction). We do not knowingly collect information from children. If you, as a guardian, believe a child has used the App without consent and that we hold related information, please contact us via the channels listed below to request deletion.

---

## 5. Your Data Rights

Because the App **stores no PII at all**, you have full local control:

- **Erase preferences & unlock status:** Delete the App from your Home screen and reinstall.
- **Disable camera access:** iOS Settings → App name → Camera → Off.

Where applicable law (e.g., GDPR, CCPA, Personal Information Protection Law of the PRC) grants you specific rights (access, rectification, erasure, restriction, portability, withdrawal of consent, etc.), since we hold no PII about you, any rights regarding App Store account or payment history should be asserted directly with Apple.

---

## 6. International Data Transfers

The App itself initiates **zero network data transfers** across regions. Any cross-border handling related to Apple crash reports or App Store billing is Apple's own responsibility.

---

## 7. Changes to This Policy

For material changes (new permission usages, new third-party integrations, etc.), we will:

1. Submit an updated App version and refresh the Privacy Policy link on the App Store page;
2. Display an in-app banner or modal to notify you of the change;
3. Update the "Last Updated" date at the top.

---

## 8. Contact Us

If you have any questions, complaints, or requests about this Privacy Policy or our handling of personal information, please contact:

- **Email:** `ss0593@qq.com`

---
