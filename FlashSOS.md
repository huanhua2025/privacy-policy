# FlashSOS Privacy Policy

**Effective Date:** July 8, 2026  
**Last Updated:** July 8, 2026

---

## I. Introduction

Thank you for using **FlashSOS (Flashlight SOS Signal & Morse Code Tool, hereinafter referred to as "the App")**. We strictly comply with the *Personal Information Protection Law of the People's Republic of China* (PIPL), the EU General Data Protection Regulation (GDPR), the California Consumer Privacy Act (CCPA), and Apple App Store privacy review requirements.

**Core Principle:**

> *Unless you explicitly grant consent for specific optional features, the App runs **100% locally on your device**. We never upload your input text, message history, recorded rhythms, or location data to any third-party server.*

---

## II. Information We (Do NOT) Collect

### 2.1 Information That Is NEVER Collected — Stored 100% Locally

All data listed below is **stored only on your device**. The developer has no access to it.

| Data Type | Description | Storage Location | Uploaded to the Cloud? |
| :--- | :--- | :--- | :--- |
| Morse Code Input Text | Any Chinese / English text, numbers, or symbols entered in SOS or Morse mode | In-memory (during playback) + local sandbox history records | ❌ Never |
| Morse Code / SOS History | Recent N sent messages and their encoded Morse sequences | iOS App sandbox (`UserDefaults` / `Documents`) | ❌ Never |
| Custom SOS Preset Phrases | User-created custom phrases beyond the built-in HELP / 911 defaults | App sandbox `UserDefaults` | ❌ Never |
| Custom Recorded Rhythms | ON/OFF rhythm patterns recorded via manual tap | App sandbox `Documents/presets/` | ❌ Never |
| App Settings | All items on the Settings screen — base unit duration, mis-touch protection, screen color, etc. | App sandbox `UserDefaults` | ❌ Never |
| Flashlight Runtime Stats | On/off cycles and total duration during SOS / strobe playback | In-memory temporary variables only, **cleared on exit** | ❌ Never |

### 2.2 Permissions Requested ONLY With Your Explicit Consent

The prompt is shown **only when you actively use the flashlight feature**. Refusing any permission does **not** affect the core SOS emergency function. You may revoke any permission at any time in *iOS Settings → FlashSOS*.

| Feature | Permission Requested | Exact Purpose | Uploaded? |
| :--- | :--- | :--- | :--- |
| **Flashlight / Brightness Control** | `NSCameraUsageDescription` (required by iOS — the flash LED is part of the camera module) | Used **exclusively** to power on the torch LED and adjust brightness via `AVCaptureDevice`. **We never access the camera viewfinder, never capture photos or videos, and never activate the microphone for audio recording.** | ❌ Never |

### 2.3 Indirect Information Received — Apple-Owned, Fully Anonymous

To improve crash-free rates and performance, the App may receive Apple's built-in **MetricKit / App Store Connect Crash Reports** (an OS-level feature, anonymous by default):
- **Content:** Crash stack traces, session length, battery usage breakdown;
- **Format:** Aggregated and anonymised statistics only — never contains user-typed text, message history, or location data.

**How to opt out:** iOS *Settings → Privacy & Security → Analytics & Improvements → Share with App Developers*.

---

## III. How We Use Information

| Purpose | Data Used | Notes |
| :--- | :--- | :--- |
| **Core features — SOS / Morse Code / Custom Beats** | Input text, settings, recorded rhythms, flashlight parameters | **Processed entirely on-device, no network connection** |
| **Crash & performance optimization** (only after you opt-in to system analytics) | MetricKit anonymous crash stack traces | Bug fixes only; no personal identifiers |

---

## IV. Data Sharing and Disclosure

We pledge: **We do not sell, trade, rent, or share your personal information with any third party — including ad networks, data brokers, analytics companies, or marketing agencies.**

Data may be disclosed only in these limited, legally-mandated scenarios:
- In response to a court summons, administrative penalty decision, or other legally binding judicial or administrative document;
- When necessary to protect the personal safety of FlashSOS users or the general public;
- When required for Apple App Store compliance audits.

> Even in the above scenarios, because the App does not collect personal information by design, there is effectively no "personal data" available to disclose. This is the privacy-first principle FlashSOS was built on.

---

## V. Data Storage and Security

- **Storage medium:** All user data resides in the iPhone's local sandbox, automatically protected by iOS Data Protection (file-level encryption);
- **How to delete manually:** *Settings → Data → Clear All History* — permanently erases all on-device history, custom phrases, and recorded rhythms;
- **App deletion:** Uninstalling FlashSOS automatically wipes all sandbox user data (native iOS behavior). Please manually copy or export any important content from the History screen first.

---

## VI. Your Rights Over Your Data

Under PIPL / GDPR / CCPA, you have the following rights over personal information:

1. **Right to be informed** — Understand our data practices through this document;
2. **Right of access** — View all message history, saved rhythms, and custom phrases directly inside the App;
3. **Right to rectification** — Edit or delete any custom phrase, recorded rhythm, or history entry at any time;
4. **Right to erasure ("Right to be forgotten"):**
   - In-App path: *Settings → Data → Clear All History*;
   - For assistance with MetricKit anonymous data, email the contact at the end of this policy;
5. **Right to withdraw consent** — Camera (flashlight) permission can be toggled off at any time in *iOS Settings → FlashSOS*;
6. **Right to opt out of automated decision-making** — The App performs **no automated decision-making based on personal data** (no user profiling, no personalised recommendations, no ad targeting).

---

## VII. Children's Privacy

The App is not specifically directed at children under the age of 13 (14 under PIPL and China's juvenile protection regulations). We do not knowingly collect personal information from children under 13. Given that no personally identifiable data is collected by default, the risk of children's personal data being gathered is effectively zero.

If you are a parent or guardian and have concerns, please reach out to the contact email below.

---

## VIII. Updates to This Policy

This privacy policy may be updated when:
1. New features introduce new permissions or new data-usage patterns;
2. Laws, regulations, or supervisory requirements change;
3. A material change occurs to our business structure (acquisition, merger, etc.).

When the policy is updated:
- The **Last Updated** date at the top of this document will be revised;
- Material changes (new permissions / new data collection) will be presented as a mandatory in-app consent dialog on next launch;
- The corresponding Privacy Policy URL in App Store Connect will be updated.

---

## IX. Contact Us

For any questions, complaints, or data-deletion requests regarding this policy, contact:

📧 ss0593@qq.com
