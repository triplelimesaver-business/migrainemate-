# PRIVACY POLICY FOR MIGRAINEMATE

**Effective Date:** November 15, 2026  
**Last Updated:** November 15, 2026  
**Developer Name:** TripleLimeSaver  
**Application Name:** MigraineMate  
**Package Name:** `com.triplelimesaver.migrainemate`  
**Contact Email:** support@triplelimesaver.co.uk  

---

## 1. INTRODUCTION

Welcome to **MigraineMate** ("we," "our," or "us"). MigraineMate is a personal health diary and tracking application designed to help individuals record migraine attacks, track headache patterns, log triggers and medications, monitor lifestyle factors, and prepare structured clinical reports for healthcare consultations.

We respect your privacy and are committed to protecting your personal and health information. This Privacy Policy explains how data is collected, stored, processed, and protected when you use our Android application.

By installing or using MigraineMate, you agree to the practices described in this Privacy Policy.

---

## 2. HEALTH DATA & LOCAL-FIRST ARCHITECTURE

### A. Local Device Storage
MigraineMate operates on a **local-first architecture**. All personal health records, including:
- Migraine attack duration, pain intensity, and location
- Symptoms, aura experiences, and suspected triggers
- Non-migraine headache logs
- Medication logs, dosages, and effectiveness notes
- Daily check-ins (sleep hours, hydration, stress levels)
- Personal emergency contacts and clinician appointment notes

are stored **locally on your Android device** using an encrypted SQLite database. 

### B. No Sale or External Commercialization of Health Data
- **We do NOT collect, transmit, store, sell, or rent your health data to external servers or third parties.**
- **Your health records, medications, symptoms, and triggers are NEVER shared with advertising networks (including Google AdMob) or used for targeted advertising.**

---

## 3. DATA COLLECTION & THIRD-PARTY SERVICES

While core health logging remains offline and local to your device, MigraineMate integrates limited third-party services to support app functionality, monetization, and in-app purchases:

### A. Google Play Billing (In-App Subscriptions)
- **Purpose**: Facilitates optional monthly subscriptions (`sub_premium_no_ads`) to remove advertisements.
- **Data Processed**: Subscription status, active purchase tokens, and entitlement status.
- **Financial Privacy**: All payments and billing information (credit cards, billing addresses) are processed directly and securely by Google Play. MigraineMate does not collect, receive, or store your financial or credit card data.
- **Privacy Policy**: [Google Play Services Privacy Policy](https://policies.google.com/privacy)

### B. Google AdMob (Advertisements for Free-Tier Users)
- **Purpose**: Displays non-intrusive banner and interstitial advertisements for users on the free plan.
- **Data Processed**: Standard AdMob SDK device identifiers, Advertising ID, coarse location (IP address level), and ad interaction telemetry for frequency capping and fraud prevention.
- **Ad-Free Option**: Active premium subscribers have all advertisements and AdMob SDK requests disabled completely.
- **Privacy Safeguard**: Health data is strictly excluded from AdMob ad requests.
- **Privacy Policy**: [Google AdMob & Privacy Terms](https://policies.google.com/technologies/ads)

---

## 4. ANDROID DEVICE PERMISSIONS

MigraineMate requests specific Android system permissions strictly to deliver app features:

| Permission | Purpose | Optional / Mandatory |
| :--- | :--- | :--- |
| `POST_NOTIFICATIONS` | Displays optional daily check-in, medication, and weekly summary reminders on Android 13+ (API 33+). | **Optional** (Gated with runtime prompt) |
| `USE_BIOMETRIC` | Enables optional app lock using your device's biometric authentication (fingerprint/face recognition) or PIN/Pattern. | **Optional** (Processed on-device by Android OS) |
| `VIBRATE` | Provides subtle haptic feedback for timers (e.g. relaxation breathing exercises). | System permission |
| `INTERNET` | Communicates with Google Play Billing to verify active subscriptions and load AdMob ads for free users. | System permission |
| `com.android.vending.BILLING` | Enables Google Play billing bottom-sheet checkout for subscription upgrades. | System permission |

---

## 5. USER DATA PORTABILITY, BACKUPS & DELETION

### A. Data Export & PDF Consultation Reports
- **JSON Data Backup**: You can create full user-controlled JSON backups of your health diary using Android's Storage Access Framework (`ACTION_CREATE_DOCUMENT`). Backup files are saved directly to your chosen destination (e.g., local storage, Google Drive, SD Card).
- **Clinical PDF Reports**: You can generate formatted multi-page PDF reports for your doctor. Sharing or emailing PDFs uses Android's secure `FileProvider` mechanism (`content://` URI) with temporary read-only permissions (`FLAG_GRANT_READ_URI_PERMISSION`).

### B. Complete Data Deletion
- You can delete all your stored health data, profile settings, attack history, and custom triggers at any time by going to **Settings > Clear All Data** within the application.
- Uninstalling the MigraineMate application will automatically erase the local SQLite database and all cached app files from your device.

---

## 6. DATA SECURITY

We employ industry-standard technical measures to safeguard your information:
- **On-Device Storage**: Data remains isolated within the app's private sandbox directory.
- **Local Biometric Security**: Optional biometric/PIN authentication prevents unauthorized physical access to your diary.
- **Secure File Sharing**: PDF export files utilize Android `FileProvider` sandboxing to prevent public external storage exposure.

---

## 7. CHILDREN'S PRIVACY

MigraineMate is not directed to children under the age of 13 (or under 16 in the EU/EEA). We do not knowingly collect or solicit personal data from children. If you become aware that a child has provided us with personal information, please contact us at **support@triplelimesaver.co.uk** so we can take immediate appropriate action.

---

## 8. MEDICAL DISCLAIMER

MigraineMate is an information tracking and self-management tool. **It does not provide medical advice, diagnosis, or treatment.** Always seek the advice of your physician, neurologist, or qualified health provider with any questions you may have regarding a medical condition.

---

## 9. CHANGES TO THIS PRIVACY POLICY

We may update this Privacy Policy periodically to reflect app updates, regulatory compliance, or operational changes. The updated version will be indicated by the "Last Updated" date at the top of this policy. We encourage you to review this Privacy Policy periodically.

---

## 10. CONTACT US

If you have questions, concerns, or requests regarding this Privacy Policy or your data privacy, please contact us at:

- **Developer / Publisher**: TripleLimeSaver
- **Email**: support@triplelimesaver.co.uk  
- **Website**: [https://triplelimesaver.co.uk](https://triplelimesaver.co.uk)
