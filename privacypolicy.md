# Privacy Policy — Motionary (`com.unithandy.motionary`)

**Effective date:** October 8, 2026

Motionary (package ID: `com.unithandy.motionary`) is developed by HDApps ("we", "our", or "us"). This Privacy Policy explains what workout data is stored locally on your device, what data is collected and shared off-device by integrated third-party SDKs (Google AdMob, Google Firebase Analytics, and Google Firebase Crashlytics), and how you can control or delete your data.

---

## 1. Workout Data You Create (Stored Locally on Your Device)

All of your workout plans, exercise logs, streaks, XP, and app preferences are stored locally on your device. We do not require user accounts, sign-in, name, email, or phone number, and we do not operate our own user-account servers. Uninstalling the app removes your local workout data from your device.

---

## 2. Google Play Data Safety Disclosure (Data Collected & Shared Off-Device)

Motionary integrates third-party SDKs provided by Google (**Google Mobile Ads / AdMob**, **Google Firebase Analytics**, and **Google Firebase Crashlytics**). These SDKs automatically collect and transmit the following categories of user data off your device to Google servers:

- **Device or other IDs (Collected & Shared):**
  Includes your Android Advertising ID (`AD_ID` / AAID), Firebase Installation ID (FID), App Set ID, and device/instance identifiers.
  *Purpose:* Collected and shared with Google AdMob and its advertising partners for advertising or marketing (serving and measuring banner, interstitial, and rewarded ads), analytics, app functionality, and fraud prevention, security, and compliance.
- **App info and performance — Crash logs, Diagnostics & Other app performance data (Collected & Shared):**
  Includes crash stack traces, ANR (Application Not Responding) reports, app launch/loading diagnostics, device model, OS version, and SDK performance metrics collected by Firebase Crashlytics and Google AdMob.
  *Purpose:* Analytics, app stability/functionality, and fraud prevention.
- **App activity — App interactions (Collected & Shared):**
  Includes aggregate screen views, feature interaction events (such as workout started/completed counts, exercise viewed, settings changed), and advertisement views/clicks collected by Firebase Analytics and Google AdMob.
  *Purpose:* Analytics, advertising or marketing, and app functionality.
- **Location — Approximate location (Collected & Shared):**
  Derived automatically from your device's IP address by Google AdMob and Google Firebase (Motionary does not request GPS or precise location permissions).
  *Purpose:* Advertising or marketing (geographically relevant ads), analytics, and fraud prevention, security, and compliance.

**Encryption in Transit:** All data collected and transmitted off your device by these SDKs is encrypted in transit using industry-standard HTTPS / TLS protocols.

---

## 3. Information Collected Automatically (Analytics & Crash Reporting)

Motionary uses **Google Firebase Analytics** and **Google Firebase Crashlytics** to understand aggregate app usage and to diagnose crashes and errors:

- Device model, operating system version, app version, and Firebase Installation ID
- General usage events — for example workout started or completed, exercise viewed, settings changed
- Crash reports and error stack traces

Motionary also periodically requests a small public version file over HTTPS to check for updates. If you choose to report a problem with an exercise video, the app opens your own email app with a pre-written message; nothing is sent unless you send it yourself.

---

## 4. Advertising and Consent (Google AdMob)

Motionary uses **Google AdMob** (`react-native-google-mobile-ads`) to display advertisements:

- **Banner ads** at the bottom of the screen and inside the workout rest timer
- An **interstitial ad** after a workout is completed
- An optional **rewarded interstitial ad** when you choose to support the app (heart button)

Google AdMob collects and shares **Device or other IDs** (including the Android Advertising ID `AD_ID`), IP address (approximate location), device information, and ad interaction data in order to select, personalize (where consented), and measure ads, and to detect fraud. Where required, Motionary asks for your consent via Google's User Messaging Platform (UMP) before serving personalized ads; you can review or change that choice at any time from **Settings → Privacy Options**.

You can also reset, delete, or opt out of your Advertising ID via your Android device settings:
- **Android:** Settings → Google → All services → Ads → Reset advertising ID or Delete advertising ID

See Google's Privacy Policy: [https://policies.google.com/privacy](https://policies.google.com/privacy)

---

## 5. Required Permissions

| Permission | Purpose |
|------------|---------|
| `INTERNET` & `ACCESS_NETWORK_STATE` | Required by Google AdMob and Firebase SDKs to transmit ads, analytics, crash logs, and update checks over HTTPS |
| `com.google.android.gms.permission.AD_ID` | Allows Google AdMob and Firebase to access the Android Advertising ID (Device or other IDs) |
| `VIBRATE` | Rest-timer and workout haptic feedback |
| `MODIFY_AUDIO_SETTINGS` | Rest-timer beep playback |
| `POST_NOTIFICATIONS` | Optional local workout reminders (Android 13+) |

---

## 6. Data Retention, Deletion & Your Controls

- **Reset or Delete Advertising ID (Device ID):** Go to Android *Settings → Google → Ads → Delete advertising ID* (or *Reset advertising ID*).
- **Change Ad Consent:** Open Motionary → *Settings → Privacy Options*.
- **Delete Local Workout Data:** Uninstall Motionary or clear app storage in Android settings.
- **Request Deletion of Analytics / Crash Data:** Email us at **support@hdapps07.com** and we will process your deletion request within 30 days.

---

## 7. Children's Privacy

Motionary is not directed at children under 13. We do not knowingly collect personal information from children. If you believe a child has provided such information, contact us and we will delete it.

---

## 8. Contact

If you have questions about this privacy policy or your data, contact us at: **support@hdapps07.com**

---

> Hosted HTML version (the canonical copy, linked from Google Play Console): `https://hdapps07.com/motionary-privacy.html`