# ClickCal Privacy Policy

**Effective Date:** September 3, 2026

ClickCal ("the App") is developed and operated by an independent developer ("we," "us," or "our"). We understand how important personal information is to you, and your privacy and data security are always our top priority. This Privacy Policy will help you understand:

1. What personal information we collect, use, and store
2. How we use that information
3. What rights you have regarding your personal information
4. How we protect the security of your personal information

---

## I. Our Position & Design Principles

ClickCal is a personal food-tracking tool built around a **"local-first"** design philosophy. Except for the limited network functionality described in Section III below, **all of your records are stored exclusively on your device** and are never uploaded to any server. We do not collect, view, or retain any of your food diaries or personal data.

The App **does not require account registration** and does not bind a phone number or email address. You can start using it immediately after installation.

---

## II. Information We Collect & Store

| Category                                        | Collected & Uploaded? | Explanation                                                                 |
| ----------------------------------------------- | --------------------- | --------------------------------------------------------------------------- |
| Food diaries (foods, portions, nutrients, meals, dates) | ❌ Never uploaded       | Stored only in the local Core Data database on your device; deleting the App erases everything. |
| Calculated nutrition estimates                  | ❌ Never uploaded       | Kept only on-device as part of your diary entries.                          |
| Settings (daily calorie target, meal reminders, region, appearance, etc.) | ❌ Never uploaded | Stored only in local UserDefaults on your device.                           |
| Custom foods (name, nutrition parameters)       | ❌ Never uploaded       | Stored only on your device.                                                 |
| Recent search history                           | ❌ Never uploaded       | Stored only on your device.                                                 |

### Permission Usage

The current version requests **only one optional system permission — Notifications**. No other hardware permissions are requested (nor declared by the App):

| Permission             | Purpose                                                  | If Denied                                           |
| ---------------------- | -------------------------------------------------------- | --------------------------------------------------- |
| Notifications (optional) | Sends scheduled reminders for Breakfast / Lunch / Dinner / Snacks. | Record-keeping functionality is unaffected; you simply won't receive meal-time reminders. |

---

## III. Network Functionality (What Data Leaves Your Device)

The App initiates network requests **only when you manually trigger the "Search Online" action**. The photo-recognition feature has been removed in the current version and no image data is ever uploaded. The scope of each request is as follows.

### 3.1 Online Food Search

- **Request target:** [Open Food Facts](https://world.openfoodfacts.org) — a global, non-profit, public open food database.
- **Request content:** the search keyword(s) you typed (Chinese and English are supported).
- **Request purpose:** to return nutrition entries that already exist in the open-source database.
- **Privacy note:** Open Food Facts is a public API; its own privacy policy is available at <https://world.openfoodfacts.org/terms-of-use>. You can turn off online search at any time via **Settings → Network**, after which only the built-in local food database is used and no further network requests are made.
- **Regional optimization:** When you select "Mainland China" in settings, network requests use only mainland China endpoints; when you select "Global" or "Follow System" outside mainland China, global endpoints are used.

### 3.2 Content We Never Upload

- ❌ Food diaries and nutrition estimates
- ❌ Custom foods
- ❌ Any other personal files on your device
- ❌ Any personally identifiable information
- ❌ Any photo or image data (the App does not perform photo-based recognition)

---

## IV. Third-Party SDKs & Services

| Provider                                                                 | Purpose                          | Data Scope                                                                   |
| ---------------------------------------------------------------------- | -------------------------------- | ---------------------------------------------------------------------------- |
| **Apple / System frameworks** (Core Data, SwiftUI)                     | Local persistence & UI rendering | Fully on-device processing; no data leaves the device.                       |
| **Apple Notification Service (UNUserNotificationCenter)**              | Meal reminders                   | Scheduled at the system level; payload contains only reminder copy — never your personal records; no advertising push involved. |
| **Open Food Facts — open food database**                                | Online food search               | See Section III — "Network Functionality" above.                              |

The App **does not integrate** any third-party analytics, advertising, tracking, or push-attribution SDKs.

---

## V. Crash Logs & Diagnostics

The App uses only Apple's **system-level crash-reporting** mechanism. If you opt in to "Share Crash & Performance Data with App Developers" in iOS Settings, we may receive anonymous crash stack traces via App Store Connect. This data **does not contain any of your food diaries or any personal identifiers**; it is used solely to fix bugs and improve stability.

You can turn this off at any time in **iOS Settings → Privacy & Security → Analytics & Improvements**.

---

## VI. Children's / Minor's Privacy

If you are a minor under 14 years of age, **please read this policy and use the App in the presence of your guardian or parent**. We do not proactively collect any personal information from minors. If a guardian discovers that a minor has submitted personal information without authorization, please contact us using the email address in Section VIII and we will remove the content as quickly as possible.

---

## VII. Your Rights Regarding Your Personal Information

Because the overwhelming majority of your data lives only on your own device, you have **complete control** over it:

| Right                                                                   | How to Exercise                                                                                                                      |
| ----------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| **Access & view** all of your records                                   | Browse directly in the three main tabs: Today / This Week / History.                                                                 |
| **Export** your data                                                    | **Settings → Data → Export All Records** (formats: JSON / CSV; save via AirDrop / Mail / Files app).                                   |
| **Delete** single entries or entire meals                               | Swipe left on Today cards to remove; custom foods can be deleted individually from the Food Search sheet.                               |
| **Irreversibly delete all local data**                                  | **Settings → Data → Clear All Data** (wipes database, recent search history, custom foods, and all settings).                          |
| **Change** personal settings (region / units / appearance / language / reminder times) | Adjust any time in **Settings** — changes take effect immediately.                                                                    |
| **Revoke permission consent**                                           | Revoke Notifications any time in **iOS Settings → ClickCal**.                                                                         |

If you believe the App is behaving in any way that exceeds this policy: **we have no server-side data to inspect**. Please export or delete data directly on your device as outlined above. For any remaining questions, reach out to the email below.

---

## VIII. Contact Us

If you have any questions, comments, or complaints regarding this Privacy Policy, or if you wish to verify the App's data behaviour, please contact us through the channel below. We commit to responding within **15 business days**.

- 📮 **Email:** <ss0593@qq.com>
- 🌏 Users in mainland China may use the same email.

---

## IX. Policy Updates

As the App evolves, we may make necessary revisions to this Policy. **Any material change (for example, a new feature that adds a data-collection item) will be announced in advance using all of the following:**

1. An in-app dialog to re-obtain your explicit consent.
2. An update to the "Effective Date" at the top of this page.
3. For high-impact changes: a notice via email or a prominent announcement banner inside Settings.

**No update will ever diminish your rights under this Policy without your explicit consent.**

---

**Thank you for trusting ClickCal. Let's eat every meal together, mindfully.** 🍽️
