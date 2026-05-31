# Dycers — Legal documents

This folder contains the three documents the user is asked to accept inside the Dycers app:

| File | What it is |
|------|-----------|
| `TERMS_OF_USE.md` | The contract between the user and the publisher (account, subscriptions, acceptable use, IP, liability, governing law). |
| `PRIVACY_POLICY.md` | GDPR-compliant explanation of what personal data is collected, why, who it's shared with, and the user's rights. |
| `RISK_DISCLOSURE.md` | Sport-betting / arbitrage-specific risk warning that the user must acknowledge. |

## Notes for Quentin

- **Drafted for:** Quentin Ameline, individual publisher, EU-generic jurisdiction, app positioned as an **information tool only** (no betting operator, no licence).
- **Placeholders to confirm or replace before launch:**
  - `support@dycers.com` — general contact (swap if you've registered a different address)
  - `privacy@dycers.com` — data-subject requests (swap if different)
  - The "Last updated" / "Effective date" — already set to 28 May 2026; update on every revision.
- **What you still need to do before going live:**
  1. **Have a French (or your home-jurisdiction) lawyer review these.** I wrote them carefully but I am not your lawyer; for a paid product you don't want to ship legal text without a human pass.
  2. **Register a company** as soon as the App generates meaningful revenue and replace "individual publisher" with the company's legal form, registration number and address.
  3. **Add an in-app screen** that displays these three documents (or links to them, hosted publicly) and requires the user to tap **"I agree"** during onboarding. Store the user's acceptance (date + version) on the server.
  4. **Host these documents at a stable URL** (e.g. `https://dycers.com/terms`, `/privacy`, `/risk`) — Apple and Google require a public Privacy Policy URL in your App Store / Play Store listing.
  5. **Translate them** into your 11 supported languages once the English version is final. Mark the English version as the authoritative one.
  6. **Update the Privacy Policy** whenever you add or remove a third-party processor (e.g. analytics, a new payment provider, a new ads SDK).
