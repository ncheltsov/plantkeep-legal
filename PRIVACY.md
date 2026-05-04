# Plantkeep — Privacy Policy

**Effective date:** 2026-05-02
**Last updated:** 2026-05-04

Plantkeep is a personal plant-library app developed by NCheltsov ("the developer", "we", "us"). This policy explains what data the app collects, where it goes, and your rights under EU GDPR.

If you have questions, contact: **begimot@gmail.com**.

---

## 1. What Plantkeep does with your data

Plantkeep is **local-first**. Your library of saved plants — including the photos you take — is stored only on your phone, in the app's private storage. We do not run a backend server, do not host your library, and do not have user accounts.

The only time your data leaves the phone is when:

- **You take a photo to identify a plant.** That single photo is sent to Google's Gemini AI service (via Firebase AI Logic) for plant identification. Google processes the image and returns the recognition result. We do not see, store, or have access to these photos at any point.
- **You make an in-app purchase.** The purchase is handled by Google Play Billing. We never see your payment details. Google sends us a confirmation that you purchased the unlock; we store only that "you are entitled" flag locally on your device.
- **The app sends usage analytics or a crash report.** See section 3.

---

## 2. What we collect

**On your device only:**
- Photos of your plants (you took them with the in-app camera).
- Plant identification results returned by Gemini (scientific name, care notes, etc.).
- Trial usage counter and entitlement flag (whether you have unlocked unlimited recognitions).

**Sent to third parties (see section 3):**
- Plant photos (only when you trigger recognition) → Google Gemini.
- Anonymous app usage events → Firebase Analytics.
- Crash diagnostics if the app crashes → Firebase Crashlytics.
- Purchase events → Google Play Billing.

**We do not collect:**
- Your name, email, address, or phone number.
- Your contacts, location, microphone, calendar, or any other phone data.
- Any account credentials.

---

## 3. Third-party services we use

| Service | Provider | What it sees | Why we use it |
|---|---|---|---|
| Firebase AI Logic (Gemini) | Google | Photos you submit for recognition | Plant identification |
| Firebase Analytics | Google | Anonymous app usage events (screen views, app version, etc.) | Understand which features are used |
| Firebase Crashlytics | Google | Crash stack traces, device model, OS version | Fix bugs that affect users |
| Google Play Billing | Google | Your in-app purchase event | Process the one-time unlock payment |

Each of these is governed by Google's own privacy policy: <https://policies.google.com/privacy>.

We do not use any other third-party SDKs that collect data.

---

## 4. Data retention

- **On your device:** photos and saved plants stay until you delete them or uninstall the app. Uninstalling the app removes everything stored locally.
- **At Google:** retention policies are governed by Google. See Google's privacy policy for details.

---

## 5. Children's privacy

Plantkeep is not directed at children under 13. We do not knowingly collect data from anyone under 13. If you believe a child has used the app and you want their data deleted, contact begimot@gmail.com.

---

## 6. Your privacy rights

Different jurisdictions grant different statutory privacy rights. Plantkeep honors the rights granted to you by the privacy law of your country of residence, including (where applicable):

- **EU GDPR** (residents of the EU including Bulgaria) — rights of access, rectification, erasure, restriction, data portability, and objection.
- **UK GDPR / Data Protection Act 2018** (UK residents) — equivalent rights to EU GDPR.
- **California CCPA / CPRA** (California residents) — rights to know, delete, correct, and opt out of sale or sharing of personal information. (Plantkeep does not sell or share personal information.)
- **Brazil LGPD** (Brazilian residents) — rights of access, correction, deletion, portability, and information about data sharing.
- **Equivalent statutes** in other jurisdictions (e.g. Canada's PIPEDA, Australia's Privacy Act, Japan's APPI, South Korea's PIPA).

In practice, because Plantkeep is local-first and stores nothing on our servers:

- **Right of access / portability** — request what data we hold about you. (For Plantkeep, the answer is "nothing on our servers" — but we can confirm in writing.)
- **Right to erasure / deletion** — uninstalling the app removes all on-device data. For data held by Google's services (analytics, crash reports), submit a request via Google's privacy controls or contact us and we will forward your request.
- **Right to object / opt out** — you can disable analytics and crash reporting via your device's Google account-level privacy settings.

Email **begimot@gmail.com** to exercise any of these rights, regardless of where you live. We will respond within the timeframe required by your local law (typically 30 days under GDPR; 45 days under CCPA).

---

## 7. Changes to this policy

If we change this policy, we will update the effective date at the top of this document and, for material changes, surface a notice in the app on next launch.

---

## 8. Contact

**Developer:** NCheltsov
**Email:** begimot@gmail.com
**App:** Plantkeep (Android, package `com.cheltsov.plantkeep`)
