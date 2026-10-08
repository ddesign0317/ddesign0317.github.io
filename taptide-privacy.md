# Privacy Policy — TapTide (`com.unithandy.taptide`)

**Effective date:** October 8, 2026

TapTide (package ID: `com.unithandy.taptide`) is developed by HDApps ("we", "our", or "us"). This Privacy Policy explains what data is stored locally on your device, what data is collected and shared off-device by integrated third-party SDKs (Google AdMob, Google Firebase Analytics, and Google Firebase Crashlytics), and how you can control or delete your data.

## 1. Information You Create (Stored Locally on Your Device)

Your routines, habits, progress, streaks, notes, and daily wins are stored on your device in a local SQLite database. This user-created habit content is not transmitted to our own servers — we do not require user accounts, login, or cloud registration. Uninstalling the app deletes your local SQLite database from your device.

## 2. Google Play Data Safety Disclosure (Data Collected & Shared Off-Device)

While we do not operate our own user-account servers, TapTide integrates third-party SDKs provided by Google (**Google Mobile Ads / AdMob**, **Google Firebase Analytics**, and **Google Firebase Crashlytics**). These SDKs automatically collect and transmit the following categories of user data off your device to Google servers:

- **Device or other IDs (Collected & Shared):**
  Includes your Android Advertising ID (`AD_ID` / AAID), Firebase Installation ID (FID), App Set ID, and device/instance identifiers.
  *Purpose:* Collected and shared with Google AdMob and its advertising partners for advertising or marketing (serving and measuring banner, interstitial, and rewarded ads), analytics, app functionality, and fraud prevention, security, and compliance.
- **App info and performance — Crash logs, Diagnostics & Other app performance data (Collected & Shared):**
  Includes crash stack traces, ANR (Application Not Responding) reports, app launch/loading diagnostics, device model, OS version, and SDK performance metrics collected by Firebase Crashlytics and Google AdMob.
  *Purpose:* Analytics, app stability/functionality, and fraud prevention.
- **App activity — App interactions (Collected & Shared):**
  Includes aggregate screen views, feature interaction events (such as onboarding completion, routine creation/completion counts, badge unlocks), and advertisement views/clicks collected by Firebase Analytics and Google AdMob.
  *Purpose:* Analytics, advertising or marketing, and app functionality. (We never transmit the custom text of your habit names, notes, or daily-win entries.)
- **Location — Approximate location (Collected & Shared):**
  Derived automatically from your device's IP address by Google AdMob and Google Firebase (TapTide does not request GPS or precise location permissions).
  *Purpose:* Advertising or marketing (geographically relevant ads), analytics, and fraud prevention, security, and compliance.

**Encryption in Transit:** All data collected and transmitted off your device by these SDKs is encrypted in transit using industry-standard HTTPS / TLS protocols.

## 3. Information Collected Automatically (Analytics & Crash Reporting)

TapTide uses **Google Firebase Analytics** to measure aggregate usage of the app, and **Google Firebase Crashlytics** to collect crash and error diagnostics so that defects can be fixed:

- **Usage events** — for example onboarding completed, routine created (with its category and reminder period), routine completed, reminder enabled, badge earned, and whether a system permission prompt was granted or denied.
- **Diagnostic & device data** — crash reports, error traces, Firebase Installation ID, device model, operating system version, and app version.

TapTide also periodically requests a small public version file over HTTPS in order to check for updates.

## 4. Advertisements and Consent (Google AdMob)

TapTide displays advertisements served by **Google AdMob** (`react-native-google-mobile-ads`):

- **Banner ads** at the bottom of the screen
- An optional **interstitial ad** once per day when all habits are completed
- An optional **rewarded ad** to support the app (user-initiated)

Google AdMob collects and shares **Device or other IDs** (including the Android Advertising ID `AD_ID`), IP address (approximate location), device information, and ad interaction data in order to serve, personalize (where consented), and measure ads, and to detect fraud. Where required, TapTide requests your consent via Google's User Messaging Platform (UMP) before serving personalized ads; you can review or change that choice at any time from **Settings → Privacy Options** inside the app. You can also reset, delete, or opt out of your Advertising ID in your Android device settings:

- Android: **Settings → Google → All services → Ads → Reset advertising ID** or **Delete advertising ID** (or *Opt out of Ads Personalization*)

See Google's Privacy Policy for details: [https://policies.google.com/privacy](https://policies.google.com/privacy)

## 5. Notifications

TapTide uses **local** notifications to remind you of your routines. All notifications are scheduled locally on your device. No notification data is sent to any server.

## 6. Device Permissions

| Permission | Purpose |
|------------|---------|
| `INTERNET` & `ACCESS_NETWORK_STATE` | Required by Google AdMob and Firebase SDKs to transmit ads, analytics, crash logs, and update checks over HTTPS |
| `com.google.android.gms.permission.AD_ID` | Allows Google AdMob and Firebase to access the Android Advertising ID (Device or other IDs) |
| `POST_NOTIFICATIONS` | Local habit reminders (Android 13+) |
| `VIBRATE` | Haptic feedback on habit tap |

## 7. Third-Party Services & SDKs

- **Google AdMob (Google Mobile Ads SDK)** — serves ads; collects and shares Device or other IDs, Approximate location, App interactions, and Diagnostics.
- **Google Firebase Analytics** — aggregate usage measurement; collects Device or other IDs, App interactions, and Approximate location.
- **Google Firebase Crashlytics** — crash and error diagnostics; collects Crash logs, Diagnostics, and Device or other IDs (Firebase Installation ID).
- **expo-notifications** — handles local notification scheduling.
- **Expo / React Native** — application framework.

These providers process data in accordance with [Google's Privacy Policy](https://policies.google.com/privacy). We do not sell your personal contact information.

## 8. Data Retention, Deletion & Your Controls

- **Reset or Delete Advertising ID (Device ID):** Go to Android *Settings → Google → Ads → Delete advertising ID* (or *Reset advertising ID*).
- **Change Ad Consent:** Open TapTide → *Settings → Privacy Options*.
- **Delete Local Habit Data:** Uninstall TapTide or clear app storage in Android settings to permanently erase all local SQLite data.
- **Request Deletion of Analytics / Crash Data:** Email us at **support@hdapps07.com** (optionally including your Advertising ID or device details) and we will process your deletion request within 30 days.

## 9. Children's Privacy

TapTide is not directed at children under 13. It does not knowingly collect personal information from children. If you believe a child has provided such information, contact us and we will delete it.

## 10. Changes to This Policy

If this policy changes, the effective date at the top will be revised. Material changes will also be reflected in the app.

## 11. Contact

For questions or requests about this privacy policy or your data, contact: **support@hdapps07.com**

---

© 2026 HDApps. All rights reserved.

> Hosted HTML version (use in Google Play Console): `https://hdapps07.com/taptide-privacy.html`