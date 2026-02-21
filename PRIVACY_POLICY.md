# Privacy Policy for Apka Rakshak

**Effective Date:** February 21, 2026  
**Last Updated:** February 21, 2026  
**Developers:** Rajveer Khanvilkar & Swarali Adhau

---

## Introduction

Thank you for choosing **Apka Rakshak** (Your Protector). Your privacy is our top priority. This Privacy Policy explains how Apka Rakshak functions as a security layer and our commitment to protecting your data.

**The Short Version:**
- ✅ We **DO NOT** collect your personal information.
- ✅ We **DO NOT** read your WhatsApp messages or private chats.
- ✅ We **DO NOT** send your data to any servers or third parties.
- ✅ Everything happens locally on your device in real-time.
- ✅ We **DO NOT** use the `REQUEST_INSTALL_PACKAGES` permission.

---

## How Apka Rakshak Works

Apka Rakshak acts as a **Security Interceptor**. It is designed to evaluate APK files at the moment of installation to protect you from malware and scams.

### Information We Evaluate (Local Only)
1. **APK File Metadata**: When you tap an APK to install, we check the file path and origin (e.g., if it is located in a WhatsApp media folder).
2. **Installation Intent**: We intercept the system's "View" intent for APK files to provide a security check before handing it off to the final installer.
3. **App Settings**: We store your "Strict Mode" preference locally to determine how aggressive the security warnings should be.

---

## Information We DO NOT Collect

We are committed to "Data Minimization." We do not access:
- ❌ **Identity**: No name, email, phone number, or account info.
- ❌ **Communications**: No chat logs, SMS, or call history.
- ❌ **Location**: No GPS or movement tracking.
- ❌ **Media**: No access to your personal photos, videos, or documents.
- ❌ **Usage**: No analytics or tracking of which other apps you use.

---

## Data Sharing & Storage

### 1. No External Transmission
Apka Rakshak operates **100% offline**. It does not have permission to access the internet, meaning no data can ever leave your device. We have no external servers and no backend database.

### 2. No Third-Party Analytics
We do NOT use Google Analytics, Firebase, Crashlytics, or any other tracking SDKs. Your app usage is completely private.

### 3. Local Storage Only
Any configuration (like Strict Mode) is stored using Android's local SharedPreferences, which are deleted automatically when you uninstall the app.

---

## Permissions Simplified

We only use the minimum permissions required to protect your device:

1. **READ_EXTERNAL_STORAGE**: Specifically used to scan the APK files you have downloaded into folders like WhatsApp Media for potential threats.
2. **FOREGROUND_SERVICE**: Allows the app to monitor your download folders in real-time so it can warn you as soon as a suspicious file arrives.
3. **VIBRATE / NOTIFICATIONS**: Used to provide immediate feedback and alerts when a threat is detected.
4. **NO INSTALL PERMISSION**: Unlike other security apps, we **do not** use `REQUEST_INSTALL_PACKAGES`. We rely on safe intent-forwarding to the official Android system installer.

---

## Your Rights

Since all data stays on your device, you have total control:
- **To Delete Data**: Simply "Clear Cache/Data" in Android Settings or uninstall the app.
- **To Stop Monitoring**: Turn off "Strict Mode" in the dashboard or disable the monitoring service.
- **Transparency**: Our logic is transparent—we act only as a warning layer and always hand off to the official system installer for the actual installation.

---

## Updates to This Policy

We may update this policy to reflect changes in our security features. We recommend checking the "Last Updated" date at the top of this document. Continued use of the app implies acceptance of the current policy.

---

## Contact Us

If you have any questions regarding your privacy while using Apka Rakshak:

**Developers:** Rajveer Khanvilkar & Swarali Adhau  
**Primary Email:** rakshakapps@gmail.com  
**Developer Email:** rajveer.khanvilkarbhosle70@gmail.com  
**Developer Email:** swaralii.178@gmail.com  


---

© 2026 Apka Rakshak Team. All rights reserved.
