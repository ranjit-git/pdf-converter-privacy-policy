# Privacy Policy

**Effective Date:** November 14, 2026

This Privacy Policy explains how **PDF Converter & Document Editor** ("we," "us," or "our") collects, uses, and protects your information when you use our mobile application (the "App"). 

We are committed to user privacy and data minimization. The core philosophy of our App is that your documents belong to you: **All PDF conversions, parsing, editing, merging, splitting, compressing, and scanning happen 100% locally on your device.** We do not upload your documents to any cloud servers.

---

## 1. Information We Do Not Collect
We strongly believe in privacy by design. When you use our App, we **do not** collect, store, transmit, or share any of the following:
* **Personal Contact Information:** We do not require account creation, and we do not collect your name, email address, physical address, or phone number.
* **Document Content & Sensitive Data:** Your PDF files, text extracts, scanned photos, signatures, doodles, watermarks, and passwords are processed entirely in-memory and on your device's local storage. None of your document contents ever leave your device.
* **Financial Details:** All optional in-app purchases (such as "Remove Ads") are processed securely by Google Play Billing. We never receive or store credit card numbers, billing addresses, or banking details.

---

## 2. Device Permissions and How We Use Them
The App requests specific Android device permissions solely to operate its local document features.

### a) Camera & Document Scanner
* **Purpose:** Powers the "Smart Scan" tool to scan physical paper documents.
* **How it is used:** Images captured are processed locally using on-device machine learning (Google ML Kit Document Scanner API) to detect document borders, correct perspective, and generate PDF files. Camera feeds and scanned images are never sent to external servers.

### b) Storage Access Framework (SAF)
* **Purpose:** Allows you to browse, open, and save PDF files in folders of your choice.
* **How it is used:** The App uses Android's Storage Access Framework (SAF) system picker to read files you explicitly select and write converted documents directly to your device storage.

### c) All Files Access (`MANAGE_EXTERNAL_STORAGE` / `READ_EXTERNAL_STORAGE`)
* **Purpose:** Exclusively required for the offline **Device PDF Manager** feature.
* **How it is used:** On Android 11+ (API 30+), `MANAGE_EXTERNAL_STORAGE` (and `READ_EXTERNAL_STORAGE` on older Android versions) enables the App to scan, index, organize, search, and manage PDF documents stored across your device's shared storage. This indexing occurs **strictly offline and locally**. No file paths, directory structures, or file contents are ever uploaded or shared.

---

## 3. Advertising & User Consent (Google AdMob)
To keep the core features of the App free, we display third-party advertisements using the **Google Mobile Ads SDK (AdMob)**.

* **Ad Formats:** Banners, Interstitial ads (shown during screen transitions), App Open ads (shown on cold launch or resume), and opt-in Rewarded video ads.
* **Advertising Identifiers:** The App utilizes the standard Android Advertising ID (`com.google.android.gms.permission.AD_ID`) and anonymous device identifiers in compliance with Google Play Developer policies to serve ads, enforce frequency capping, and detect fraudulent or invalid traffic.
* **User Consent (GDPR / UMP):** For users in the European Economic Area (EEA), the United Kingdom, and Switzerland, the App integrates Google's User Messaging Platform (UMP) to obtain explicit consent for personalized or non-personalized advertising in compliance with the GDPR and ePrivacy Directive.
* **Ad-Free Option:** Users can permanently disable all advertisements through an optional one-time in-app purchase ("Remove Ads").

---

## 4. Analytics, Remote Configuration & Diagnostics
To ensure stability, understand general feature popularity, and deliver seamless updates, we utilize trusted Google Firebase services:

### a) Google Analytics for Firebase
* **What is collected:** Anonymous, aggregated interaction metrics (such as app open frequency, which PDF tools are used, and approximate file size categories).
* **What is NOT collected:** Document contents, file names, personal identifiers, or file text. Analytics data is purely statistical and non-personally identifiable.

### b) Firebase Crashlytics
* **What is collected:** Anonymous diagnostic crash logs, stack traces, device model, and operating system version when an unexpected error occurs.
* **Purpose:** Helps us identify and fix software bugs across different device hardware configurations.

### c) Firebase Remote Config
* **Purpose:** Dynamically delivers non-personal application settings (such as ad frequency limits, tool parameters, and notification of new version releases) without collecting user data.

---

## 5. Third-Party Service Providers
Our App integrates the following third-party libraries:
* **Google Play Services & Google Play Billing:** Manages secure in-app purchases and in-app reviews.
* **Google Mobile Ads (AdMob):** Delivers in-app advertising ([Google Privacy & Terms](https://policies.google.com/technologies/ads)).
* **Google Firebase (Analytics, Crashlytics, Remote Config):** Telemetry and dynamic configuration ([Firebase Privacy](https://firebase.google.com/support/privacy)).
* **Google ML Kit:** On-device document edge detection and perspective correction ([ML Kit Terms](https://developers.google.com/ml-kit/terms)).

You can review Google's overall privacy practices in the [Google Privacy Policy](https://policies.google.com/privacy).

---

## 6. URL to PDF Tool (External Web Requests)
When using the optional "URL to PDF" tool, the App makes an outbound HTTP request directly to the public website URL you provide to retrieve and convert its webpage into a local PDF. No personal information is appended to this request beyond standard HTTP network protocol headers necessary to fetch the webpage.

---

## 7. Data Retention & User Control
* **Local Files:** All files created or imported into the App remain on your device. You can view, share, or permanently delete any document at any time using the App's interface or your device's built-in file manager.
* **No Cloud Retention:** Because we do not run user databases or cloud storage servers, we hold no user data on external servers.

---

## 8. Data Security
Your data's security is guaranteed by the fact that it never leaves your device:
* We rely on Android's application sandboxing to keep your documents protected from unauthorized third-party apps.
* The App includes a local "Lock PDF" tool that lets you secure sensitive documents with standard password encryption.

---

## 9. Children's Privacy
Our App does not address anyone under the age of 13, nor do we knowingly collect personally identifiable information from children. Because document processing is entirely local and offline, the App provides a safe environment for all users.

---

## 10. Changes to This Privacy Policy
We may update our Privacy Policy periodically to reflect new features or platform policy updates. We will notify you of any changes by posting the updated Privacy Policy on this page and updating the "Effective Date" at the top.

---

## 11. Contact Us
If you have any questions, concerns, or requests regarding this Privacy Policy or our practices, please contact us at:

* **Developer:** ranjit pahan
* **Support Email:** [pahan.ranjit.0201@gmail.com](mailto:pahan.ranjit.0201@gmail.com)
* **Official Policy URL:** [https://ranjit-git.github.io/pdf-converter-privacy-policy/](https://ranjit-git.github.io/pdf-converter-privacy-policy/)
