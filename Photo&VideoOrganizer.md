# Privacy Policy

**Effective Date:** July 22, 2026

**Version:** 1.0

---

## Introduction

Photo & Video Organizer ("this App") is a local photo and video organization tool running on the macOS platform. We understand the importance you place on privacy, which is why this App adopts a zero-data-upload, zero-network-tracking design philosophy to ensure your personal data and media files remain securely on your device at all times.

---

## 1. Information Collection

This App **does not collect, store, transmit, or share** any personally identifiable information or sensitive data.

Specifically:
- Does not collect your name, email address, phone number, or any other personally identifiable information
- Does not collect your device information, IP address, or network identifiers
- Does not collect usage statistics or analytics data
- Does not use any third-party analytics tools, trackers, or advertising SDKs

---

## 2. Data Usage

This App processes data only on your local device. All operations are performed locally, and no data is sent to any external server.

### 2.1 File Access

This App only accesses your file system when you **actively select folders**:
- Accesses your specified source and destination folders through macOS's native file selection dialog (NSOpenPanel)
- Access permissions follow the macOS sandbox mechanism, allowing access only to directories you have explicitly authorized
- Does not access files in other locations on your system without your authorization

### 2.2 Metadata Reading

To complete the file organization functionality, this App reads media file metadata:
- **Photo files**: Reads the capture date (DateTimeOriginal) from EXIF information
- **Video files**: Reads the creation date (creationDate) from video metadata
- This metadata is used only for file classification and naming, and is never saved or transmitted

### 2.3 Duplicate File Detection

When you enable the "Filter Duplicate Files" feature, this App computes SHA256 hash values for files:
- Hash values are computed temporarily in memory only for identifying duplicate files
- They are discarded immediately after computation and never saved to disk or sent anywhere
- Hash values are never compared against any external database

### 2.4 Security-Scoped Bookmarks

To support access to external storage devices such as external hard drives and USB flash drives, this App uses macOS's Security-Scoped Bookmark mechanism:
- Bookmarks are used only for legally accessing folders you have authorized within the sandbox environment
- They are not used for tracking or monitoring your file access behavior

---

## 3. Data Sharing

This App **does not share any of your data with any third party**.

- Does not share data with advertisers, analytics companies, or data brokers
- Does not share data with developers or any other entity
- Does not upload your files or metadata to any cloud service

---

## 4. Feedback Feature

This App provides a feedback entry that opens your system's default email client when clicked:
- Email sending is entirely under your control
- This App does not read, store, or send your email content
- The feedback email address is used only for receiving feedback you actively send

---

## 5. Children's Privacy

This App is not designed for children and does not intentionally collect any information from children. If you are a parent or guardian and discover that a child has used this App, please contact us.

---

## 6. Privacy Policy Updates

We may update this privacy policy from time to time. When significant changes are made to the policy, we will post a notification within the App. Your continued use of this App constitutes your acceptance of the updated privacy policy.

---

## 7. Contact Us

If you have any questions or suggestions regarding this privacy policy, please contact us at:

- Email: ss0593@qq.com

---

**Summary:** This App is a fully localized tool. All data processing is completed on your device, no data is uploaded to the network, and no personal information is collected. Your privacy and data security are always our top priority.
