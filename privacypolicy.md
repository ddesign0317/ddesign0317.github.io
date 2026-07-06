# Privacy Policy for Motionary

**Last updated:** June 13, 2026

This privacy policy describes how Motionary ("we", "our", or "the app") handles user data.

---

## Data Collection

Motionary **does not collect, store, or transmit** any personal data. The app:

- ✅ Works **fully offline** — no account required
- ✅ Does **not** collect names, emails, or any personal identifiers
- ✅ Does **not** track location, device ID, or usage analytics
- ✅ Does **not** upload workout data, images, or files to any server
- ✅ Does **not** use cookies or tracking technologies
- ✅ Does **not** share data with third parties

All workout history, streaks, XP, and settings are stored **locally on your device** using `AsyncStorage` (React Native's local key-value storage). This data never leaves your device.

---

## Advertising

Motionary uses **Google AdMob** to display advertisements. AdMob may collect device information (such as advertising ID, device type, and IP address) to serve relevant ads. This is governed by Google's Privacy Policy:

- [Google Privacy Policy](https://policies.google.com/privacy)
- [AdMob Privacy Policy](https://support.google.com/admob/answer/6128543)

You can opt out of personalized ads via your device settings:
- **Android:** Settings → Google → Ads → Opt out of Ads Personalization

---

## Required Permissions

| Permission | Purpose |
|------------|---------|
| `INTERNET` | Required for AdMob ads to load and display |
| `ACCESS_NETWORK_STATE` | Required for AdMob to check connectivity |
| `VIBRATE` | Used for rest timer countdown haptic feedback |
| `MODIFY_AUDIO_SETTINGS` | Used for rest timer beep sound playback |

---

## Children's Privacy

Motionary is not directed at children under 13. We do not knowingly collect any personal information from children.

---

## Changes to This Policy

We may update this policy if app functionality changes. Continued use of the app constitutes acceptance of any changes.

---

## Contact

If you have questions about this privacy policy, contact us at:

**Email:** *(your email address)*

---

---

## HTML Version

An HTML-ready version is available at `release/privacy-policy.html` — drag this file directly to Netlify Drop (no conversion needed).

---

## Hosting Options (No Domain Required)

Since you don't have a domain, use one of these **free** options to host this policy:

### Option 1: GitHub Gist (simplest, no account needed for viewing)

1. Go to [gist.github.com](https://gist.github.com) (requires GitHub login — free)
2. Paste the HTML content from `release/privacy-policy.html`
3. Name the file `privacy-policy.html`
4. Click **Create secret gist**
5. Click **Raw** button → copy that URL
6. Paste the raw URL into Google Play Console

> The raw URL looks like: `https://gist.githubusercontent.com/username/abc123/raw/privacy-policy.html`

### Option 2: App Privacy Policy Generator (hosted for you, no account needed)

- [App Privacy Policy Generator](https://app-privacy-policy-generator.firebaseapp.com/) — fill a form, get a hosted page URL instantly
- [PrivacyPolicies.com](https://www.privacypolicies.com/) — free hosted policy

### Option 3: Google Drive

1. Open `release/privacy-policy.html` in a browser
2. Upload to Google Drive
3. Share → "Anyone with the link can view"
4. Use that link in Play Console

### Option 4: GitHub Pages

1. Create a repo named `yourusername.github.io`
2. Upload `privacy-policy.html`
3. Enable Pages in repo Settings
4. URL: `https://yourusername.github.io/privacy-policy.html`

---

*This policy was generated for Motionary v1.0.0 — com.unithandy.motionary*