# Privacy Policy

**Effective Date:** August 4, 2026

This Privacy Policy explains how **PDF Converter & Document Editor** ("we," "us," or "our") collects, uses, and protects your information when you use our mobile application (the "App"). 

We are committed to protecting your privacy. The core philosophy of our App is that your data belongs to you. **All document processing, editing, and scanning happens 100% locally on your device.** We do not upload your documents to any cloud servers.

---

## 1. Information We Do Not Collect
We strongly believe in data minimization. When you use our App, we **do not** collect, store, transmit, or share any of the following:
* **Personal Information:** We do not ask for your name, email address, phone number, or any other personally identifiable information.
* **Document Content:** Your PDF files, scanned images, signatures, and annotations are never uploaded to our servers. All parsing, merging, compressing, and editing happens entirely on your device's local processor.
* **Usage Analytics & Tracking:** We do not use third-party analytics trackers to monitor your behavior across the App. However, we do collect anonymous crash reports to help us fix bugs (see Section 3).

## 2. Device Permissions and How We Use Them
To provide our core functionality, the App requires certain device permissions. We request these permissions solely to operate the App's features locally on your device.

### a) Camera Permission
* **Why it is needed:** We use your device's camera to power the "Smart Scan" feature, allowing you to scan physical documents.
* **How it is used:** The camera feed is processed locally using on-device machine learning (Google ML Kit) to detect document edges and enhance image quality. The resulting images and PDFs are saved directly to your device storage. We do not transmit your camera feed or photos to any external servers.

### b) Storage / Files Permission (Storage Access Framework)
* **Why it is needed:** As a comprehensive PDF editor, the App requires access to your device's file system to read, modify, and save PDF documents.
* **How it is used:** The App uses the Android Storage Access Framework (SAF) to securely request access to specific folders or files you choose. When you merge, compress, or edit a PDF, the App reads the file locally and writes the new file directly to your chosen local directory.

## 3. Third-Party Services
While our App operates primarily offline, we utilize specific third-party services to ensure the App functions correctly and to provide certain features:

### a) Google ML Kit
We utilize the **Google ML Kit Document Scanner API** to provide our Smart Scan feature. 
* Google ML Kit processes images **entirely on-device**. 
* However, as a Google Play Services component, it may periodically download tiny machine learning models from Google to keep the scanner updated. 

### b) Firebase Crashlytics
We use **Firebase Crashlytics** (provided by Google) to collect anonymous crash reports and performance data. 
* **Why it is needed:** If the App crashes, Crashlytics sends us an automated report detailing what went wrong so we can fix it in the next update.
* **What is collected:** This report includes anonymous diagnostic data, such as device model, operating system version, and the line of code that caused the crash. 
* **What is NOT collected:** Crashlytics does not collect your PDF documents, personal data, or scanned images.

You can review Google's privacy practices regarding ML Kit and Firebase in the [Google Privacy Policy](https://policies.google.com/privacy).

## 4. Data Security
Your data's security is guaranteed by the fact that it never leaves your device. We rely on the robust security sandboxing provided by the Android operating system to ensure that your files remain private and inaccessible to unauthorized applications. Furthermore, our App includes a "Lock PDF" tool that allows you to independently encrypt your files with AES encryption passwords.

## 5. Children's Privacy
Our App does not contain content tailored to children, nor do we knowingly collect personally identifiable information from anyone under the age of 13. Since the App operates offline and collects no data, it is safe for all ages.

## 6. Changes to This Privacy Policy
We may update our Privacy Policy from time to time if we add new features (for example, if we were to add an optional cloud-sync feature in the future). Thus, you are advised to review this page periodically for any changes. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Effective Date" at the top.

## 7. Contact Us
If you have any questions, concerns, or suggestions regarding this Privacy Policy or our privacy practices, please contact us at:
**pahan.ranjit.0201@gmail.com**

---
*Note for Play Store Submission: Ensure you replace the bracketed placeholder in section 7 with your actual developer contact email before linking this policy in the Google Play Console.*
