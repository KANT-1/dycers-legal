---
title: Privacy Policy — Dycers
---
# Privacy Policy — Dycers

**Last updated:** 28 May 2026
**Effective date:** 28 May 2026

This Privacy Policy explains how the mobile application "**Dycers**" (the "**App**") collects, uses, shares and protects your personal data. It is drafted to comply with the EU General Data Protection Regulation (Regulation (EU) 2016/679, "**GDPR**") and equivalent local rules.

By using the App you confirm that you have read and understood this Policy.

---

## 1. Data controller

The data controller is **Quentin Ameline**, an individual publisher established in the European Union ("**we**", "**us**", "**our**").

For any privacy-related question or to exercise your rights, contact us at:

**dycersofficial@gmail.com**

---

## 2. Personal data we collect

We collect only the data we need to operate the App. Specifically:

### 2.1 Data you give us

| Data | When we collect it | Purpose |
|------|-------------------|---------|
| **Email address** | Sign-up, login, email change, password reset | Account identification, authentication, transactional emails |
| **Password (hashed)** | Sign-up, password change | Authentication. We never store passwords in clear text — they are hashed with bcrypt. |
| **Verification codes** | Sign-up, password reset, email change | Verify it's really you |
| **Selected bookmakers** | Onboarding and settings | Filter arbitrage alerts to your bookmakers |
| **Selected sports / leagues** | Onboarding and settings | Filter alerts to sports you follow |
| **Bets you record** (event, odds, stake, status, timestamps) | When you add a bet | Track active bets, build history and statistics |
| **Subscription tier** ("free", "pro", "max") | After purchase or restore | Unlock the corresponding features |

### 2.2 Data we receive from third parties

| Data | Source | Purpose |
|------|--------|---------|
| **Apple user identifier + (optional) email + name** | Sign in with Apple | Account creation / login |
| **Google account ID + email + name** | Sign in with Google | Account creation / login |
| **Purchase receipt + entitlement status** | Apple App Store, Google Play, RevenueCat | Verify your subscription |
| **Mobile advertising identifier (IDFA / GAID)** | Your device, only if you grant permission | Serve ads (free tier only — see §6) |
| **Push notification token** (Expo push token) | Your device, if you grant notification permission | Send arbitrage alerts |

### 2.3 Data collected automatically

| Data | Purpose |
|------|---------|
| **Approximate language / locale** | Display the App in your language (`expo-localization`) |
| **App version, OS type and version** | Diagnose technical issues |
| **Server access logs** (IP address, timestamp, endpoint, HTTP status) | Security, abuse prevention, debugging. Retained 30 days. |
| **Crash and error logs** (no personal content) | Stability monitoring |

### 2.4 Data we do **not** collect

- We do not collect your real name (unless Apple/Google passes it during first sign-in, and only with your consent).
- We do not collect your date of birth, postal address, phone number, payment card details, or government ID.
- We do not collect data about wagers placed outside the App.
- We do not collect any data from children. The App is reserved for users aged 18 and over (or the higher local age of majority for sports betting).

---

## 3. Legal bases for processing (GDPR Article 6)

| Purpose | Legal basis |
|---------|-------------|
| Creating and maintaining your account, providing the App's core features | **Performance of a contract** (Art. 6(1)(b)) — these Terms of Use |
| Processing subscriptions and verifying receipts | Performance of a contract |
| Sending account / security emails (verification, password reset) | Performance of a contract |
| Sending arbitrage push notifications | **Your consent** (you grant notification permission on your device) (Art. 6(1)(a)) |
| Showing personalised ads (free tier) | **Your consent** (granted via the mobile-OS App Tracking Transparency prompt on iOS, or equivalent on Android) (Art. 6(1)(a)) |
| Showing non-personalised ads (free tier) | **Legitimate interest** in funding a free tier (Art. 6(1)(f)) |
| Security, abuse prevention, log retention | **Legitimate interest** in protecting the service (Art. 6(1)(f)) |
| Complying with legal obligations (e.g. accounting for paid subscriptions) | **Legal obligation** (Art. 6(1)(c)) |

You can withdraw your consent at any time (see §8). Withdrawal does not affect the lawfulness of processing carried out beforehand.

---

## 4. Who we share your data with (processors and third parties)

We never sell your personal data. We share it only with the service providers and partners listed below, and only to the extent strictly necessary.

| Provider | Role | Data shared | Location |
|----------|------|-------------|----------|
| **Railway (Railway Corp.)** | Hosting our backend server | All account data, bets, settings | USA (covered by Standard Contractual Clauses) |
| **Managed PostgreSQL** (hosted via Railway) | Database | Same as above | USA |
| **Brevo (Sendinblue SAS)** | Transactional email (verification, password reset) | Your email address and one-time codes | France / EU |
| **Apple (Apple Inc.)** | Sign in with Apple, App Store, IAP, push delivery (APNs) | Apple ID identifier, receipts, push tokens | USA |
| **Google (Google LLC / Google Ireland Ltd)** | Sign in with Google, Google Play, IAP, push delivery (FCM), AdMob | Google identifier, receipts, push tokens, ad identifier | USA / Ireland |
| **RevenueCat (RevenueCat, Inc.)** | Subscription entitlement management | Anonymous user ID, receipts | USA |
| **The Odds API (The Odds API Ltd)** | Odds data | None — outbound only (we request odds, we do not send user data) | UK |
| **Football statistics provider** (e.g. football-data / api-football) | Match stats and H2H | None — outbound only | EU / UK |
| **Google AdMob** | Advertising on the free tier | Mobile advertising identifier (if consented), coarse device data | USA / EU |
| **Expo (Expo, Inc.)** | Push notification delivery infrastructure | Push token, notification payload | USA |

Each of these providers is bound by its own privacy and security obligations. Where data is transferred outside the European Economic Area, we rely on **Standard Contractual Clauses** approved by the European Commission, on the EU–US Data Privacy Framework where applicable, and on equivalent safeguards.

We may also disclose your data when required by law (court order, lawful request from a public authority) or to protect our rights, property or the safety of users.

---

## 5. International transfers

Some of our processors are located outside the European Economic Area, in particular in the United States. Where this is the case, we ensure that an adequate level of protection is in place through one of the mechanisms recognised by GDPR (adequacy decision, Standard Contractual Clauses, EU–US Data Privacy Framework, binding corporate rules). You may request a copy of the relevant safeguards by writing to **dycersofficial@gmail.com**.

---

## 6. Advertising and tracking

On the **Free tier**, the App may display advertisements via **Google AdMob**. Depending on your consent:

- If you **accept** App Tracking Transparency (iOS) or its Android equivalent, ads may be personalised using your mobile advertising identifier (IDFA / GAID);
- If you **refuse** or have not granted consent, ads will be **non-personalised** and will not use your advertising identifier for cross-app tracking.

You can change this choice at any time:

- **iOS:** Settings → Privacy & Security → Tracking
- **Android:** Settings → Privacy → Ads

Paid (Pro / Max) users do not see ads.

---

## 7. How long we keep your data

| Data | Retention period |
|------|------------------|
| Account data (email, hashed password, settings, bookmakers, sports, tier) | For as long as your account is active. Deleted within 30 days of account deletion. |
| Bets — active | While the bet is active. |
| Bets — history | For as long as your account is active, or until you delete them manually. |
| Verification / reset codes | 15 minutes maximum. |
| Server access logs | 30 days. |
| Receipts and accounting records for paid subscriptions | As required by applicable tax law (typically up to 10 years), in a restricted-access archive. |
| Push notification tokens | Until you revoke notification permission or uninstall the App. |

Backups are rotated and overwritten within 30 days, so deleted data may persist in encrypted backups for that short additional period before being permanently overwritten.

---

## 8. Your rights

Under GDPR you have the following rights at any time:

- **Access** — obtain a copy of the personal data we hold about you.
- **Rectification** — correct inaccurate or incomplete data.
- **Erasure** ("right to be forgotten") — delete your account and associated data. Available directly in-app at **Settings → Account → Delete account**.
- **Restriction** — ask us to limit the processing of your data.
- **Portability** — receive your data in a structured, commonly used, machine-readable format.
- **Objection** — object to processing based on our legitimate interests.
- **Withdraw consent** — at any time, where processing is based on consent (notifications, personalised ads). Withdrawal does not affect past processing.
- **Lodge a complaint** with your national data-protection authority. In France, this is the **CNIL** (<https://www.cnil.fr>); a list of EU authorities is available at <https://edpb.europa.eu/about-edpb/about-edpb/members_en>.

To exercise these rights, write to **dycersofficial@gmail.com** from the email address linked to your account. We will respond within one (1) month. We may ask for additional information to verify your identity.

---

## 9. Security

We apply technical and organisational measures appropriate to the risk, including:

- **TLS (HTTPS)** encryption for all communication between the App and our servers;
- **Bcrypt** hashing for passwords — we never see your password in clear text;
- **JWT** tokens stored on your device in the platform's secure storage (`expo-secure-store`, which uses iOS Keychain and Android Keystore);
- Restricted access to production systems on a need-to-know basis;
- Regular dependency updates and monitoring.

No system is 100% secure. In the event of a personal-data breach likely to result in a high risk to your rights, we will notify the competent authority within 72 hours and inform you without undue delay where required by GDPR Article 34.

---

## 10. Children

The App is **not intended for children**. We do not knowingly collect data from anyone under 18 (or the higher local age of legal majority for sports betting). If we learn that we have collected data from a minor, we will delete it without delay. If you believe a minor has provided us with personal data, contact us at **dycersofficial@gmail.com**.

---

## 11. Cookies and similar technologies

The App is a native mobile application and does not use traditional web cookies. However, it does use local storage (`expo-secure-store`, `AsyncStorage`) on your device to remember your session, your language and your preferences. Third-party SDKs (AdMob, Google Sign-In, Apple Sign-In, RevenueCat) may use their own storage and identifiers in accordance with their respective privacy policies.

---

## 12. Third-party privacy policies

For convenience, the policies of our main processors:

- Apple — <https://www.apple.com/legal/privacy/>
- Google (incl. AdMob, FCM, Sign-In, Play) — <https://policies.google.com/privacy>
- Railway — <https://railway.com/legal/privacy>
- Brevo — <https://www.brevo.com/legal/privacypolicy/>
- RevenueCat — <https://www.revenuecat.com/privacy/>
- Expo — <https://expo.dev/privacy>
- The Odds API — <https://the-odds-api.com/privacy.html>

---

## 13. Changes to this Policy

We may update this Policy from time to time. The "Last updated" date at the top of this document indicates when the latest version took effect. If we make material changes (in particular new categories of data or new processors), we will notify you in-app or by email at least fifteen (15) days before the change takes effect. Continued use of the App after the effective date constitutes acceptance.

---

## 14. Contact

For any question, request or complaint regarding your personal data:

**dycersofficial@gmail.com**

---

*By tapping "I agree" or by continuing to use Dycers, you confirm that you have read and understood this Privacy Policy.*
