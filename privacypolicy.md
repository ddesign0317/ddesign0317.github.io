# Privacy Policy for Motionary

**Last updated:** September 11, 2026

This privacy policy describes how Motionary ("we", "our", or "the app") handles user data. It applies to the Android app **Motionary** (`com.unithandy.motionary`).

---

## Data Collection

Motionary has **no accounts and no sign-in**, and we do not operate servers. All workout history, streaks, XP, and settings are stored **locally on your device** using `AsyncStorage` (React Native's local key-value storage). This data never leaves your device.

We never ask for your name, email, or phone number.

---

## Information Collected Automatically

Motionary uses **Google Firebase Analytics** and **Google Firebase Crashlytics** to understand how the app is used and to diagnose crashes and errors. These services collect anonymous, aggregated technical data such as:

- App version and device model
- General usage events — for example workout started or completed, exercise viewed, settings changed
- Crash reports and error traces

We never send your name, email, or any text you enter. Motionary also periodically requests a small public version file over HTTPS to check for updates; that request contains no personal information.

If you choose to report a problem with an exercise video, the app opens your own email app with a pre-written message. Nothing is sent until you send it yourself.

---

## Advertising

Motionary uses **Google AdMob** to display advertisements. Ad formats in use are:

- **Banner ads** at the bottom of the screen and inside the workout rest timer
- An **interstitial ad** after a workout is completed
- An optional **rewarded interstitial ad** when you choose to support the app (heart button)

AdMob and its partners may collect device information (such as advertising ID, device type, and IP address) in order to select and measure ads. Where required, Motionary asks for your consent before serving personalized ads; you can review or change that choice at any time from **Settings → Privacy Options**.

This is governed by Google's Privacy Policy:

- [Google Privacy Policy](https://policies.google.com/privacy)
- [AdMob Privacy Policy](https://support.google.com/admob/answer/6128543)

You can also opt out of personalized ads via your device settings:
- **Android:** Settings → Google → Ads → Opt out of Ads Personalization

---

## Data Storage and Backup

- All workout data is stored locally on your device.
- We do not operate servers and never receive your workout data.
- **Android device backup:** if backup is enabled in your Android / Google account settings, the operating system may copy app data to your own encrypted Google backup so it can be restored on a new phone. That backup is controlled by you and Google — we cannot access it. You can turn it off in Android Settings → System → Backup.
- Deleting the app removes the local data. Any copy held in a system backup stays in your Google account until it expires under Google's retention policy.

---

## Required Permissions

| Permission | Purpose |
|------------|---------|
| `INTERNET` | Ads, analytics, and update checks |
| `ACCESS_NETWORK_STATE` | Connectivity checks (from Google's advertising SDK) |
| `VIBRATE` | Rest-timer and workout haptic feedback |
| `MODIFY_AUDIO_SETTINGS` | Rest-timer beep playback |
| `POST_NOTIFICATIONS` | Optional local workout reminders (Android 13+) |
| `AD_ID` (from Google Play services) | Advertising identifier used by AdMob |

Notifications are scheduled locally on your device. No notification data is sent to any server.

---

## Third-Party Services

- **Google AdMob** — advertising
- **Google Firebase (Analytics & Crashlytics)** — anonymous usage statistics and crash diagnostics
- **Expo / React Native** — application framework

These providers process data in accordance with their own privacy policies. We do not sell your personal information.

## Your Choices and Controls

- Change your ad consent choice — Settings → Privacy Options
- Limit ad personalization — your device settings
- Turn reminders off — Settings, or your device notification settings
- Remove all app data — uninstalling the app deletes everything stored locally
- Request deletion of analytics or crash data associated with your app usage — email us and we will action the request

---

## Children's Privacy

Motionary is not directed at children under 13. We do not knowingly collect personal information from children. If you believe a child has provided such information, contact us and we will delete it.

---

## Changes to This Policy

This policy may be updated periodically. Changes will be reflected with a new effective date on this page, and material changes will also be shown in the app.

---

## Contact

If you have questions about this privacy policy, contact us at:

**Email:** ddesign0317@gmail.com

---

> Hosted HTML version (the canonical copy, linked from Google Play Console): `https://ddesign0317.github.io/motionary-privacy.html`