---
title: Datenschutzrichtlinie — Dycers
---

# Datenschutzrichtlinie — Dycers

**Zuletzt aktualisiert:** 19. Juni 2026
**Datum des Inkrafttretens:** 19. Juni 2026

Diese Datenschutzrichtlinie erläutert, wie die mobile Anwendung „**Dycers**" (die „**App**") Ihre personenbezogenen Daten erhebt, verwendet, weitergibt und schützt. Sie entspricht der EU-Datenschutz-Grundverordnung (DSGVO) und gleichwertigen lokalen Vorschriften.

---

## 1. Verantwortlicher

Der Verantwortliche ist **LF Digital Ventures**, eine vereinfachte Aktiengesellschaft französischen Rechts (*société par actions simplifiée*, SAS) mit einem Stammkapital von 2 €, eingetragen im Handels- und Gesellschaftsregister (RCS) Nanterre unter der Nummer 106 243 355, mit Sitz in 63 rue Nationale, 92100 Boulogne-Billancourt, Frankreich.

Für datenschutzbezogene Anfragen oder zur Ausübung Ihrer Rechte: **contact@dycers.com**

---

## 2. Personenbezogene Daten, die wir erheben

### 2.1 Daten, die Sie uns mitteilen

| Datum | Wann wir es erheben | Zweck |
|-------|---------------------|-------|
| **E-Mail-Adresse** | Registrierung, Anmeldung, E-Mail-Änderung, Passwort-Reset | Kontoidentifikation, Authentifizierung, transaktionale E-Mails |
| **Passwort (gehasht)** | Registrierung, Passwortänderung | Authentifizierung. Wir speichern Passwörter nie im Klartext — sie werden mit bcrypt gehasht. |
| **Verifizierungscodes** | Registrierung, Passwort-Reset, E-Mail-Änderung | Identitätsverifizierung |
| **Ausgewählte Buchmacher** | Onboarding und Einstellungen | Arbitrage-Alerts filtern |
| **Ausgewählte Sportarten / Ligen** | Onboarding und Einstellungen | Alerts filtern |
| **Erfasste Wetten** | Beim Hinzufügen einer Wette | Aktive Wetten verfolgen, Verlauf und Statistiken |
| **Abonnement-Stufe** | Nach Kauf oder Wiederherstellung | Entsprechende Funktionen freischalten |

### 2.2 Daten von Dritten

| Datum | Quelle | Zweck |
|-------|--------|-------|
| **Apple-Nutzer-ID + E-Mail + Name** | Mit Apple anmelden | Kontoerstellung / Anmeldung |
| **Google-Konto-ID + E-Mail + Name** | Mit Google anmelden | Kontoerstellung / Anmeldung |
| **Kaufbeleg + Abonnementstatus** | App Store, Google Play, RevenueCat | Abonnement verifizieren |
| **Mobile Werbe-ID (IDFA / GAID)** | Ihr Gerät, nur mit Erlaubnis | Werbung anzeigen (nur kostenlose Stufe) |
| **Push-Benachrichtigungs-Token** | Ihr Gerät, mit Erlaubnis | Arbitrage-Alerts senden |

### 2.3 Automatisch erhobene Daten

| Datum | Zweck |
|-------|-------|
| **Ungefähre Sprache / Region** | App in Ihrer Sprache anzeigen |
| **App-Version, Betriebssystemtyp und -version** | Technische Diagnose |
| **Server-Zugriffsprotokolle** (IP, Zeitstempel, Endpunkt, HTTP-Status) | Sicherheit, Missbrauchsprävention. Aufbewahrt 30 Tage. |
| **Absturz- und Fehlerprotokolle** (ohne persönliche Inhalte) | Stabilitätsüberwachung |

---

## 3. Rechtsgrundlagen (Art. 6 DSGVO)

| Zweck | Rechtsgrundlage |
|-------|----------------|
| Kontoerstellung und -verwaltung, Kernfunktionen | **Vertragserfüllung** (Art. 6(1)(b)) |
| Abonnementverarbeitung | Vertragserfüllung |
| Sicherheits-E-Mails | Vertragserfüllung |
| Push-Benachrichtigungen | **Einwilligung** (Art. 6(1)(a)) |
| Personalisierte Werbung (kostenlose Stufe) | **Einwilligung** (Art. 6(1)(a)) |
| Nicht personalisierte Werbung (kostenlose Stufe) | **Berechtigtes Interesse** (Art. 6(1)(f)) |
| Sicherheit und Missbrauchsprävention | **Berechtigtes Interesse** (Art. 6(1)(f)) |
| Erfüllung gesetzlicher Pflichten | **Rechtliche Verpflichtung** (Art. 6(1)(c)) |

---

## 4. Datenweitergabe

Wir verkaufen Ihre Daten nicht. Wir teilen sie nur mit folgenden Dienstleistern:

| Anbieter | Funktion | Geteilte Daten | Standort |
|---------|---------|----------------|----------|
| **Railway** | Backend-Hosting | Alle Kontodaten, Wetten, Einstellungen | USA (SCC) |
| **PostgreSQL** (via Railway) | Datenbank | Wie oben | USA |
| **Brevo** | Transaktionale E-Mails | E-Mail und Einmalbcodes | Frankreich / EU |
| **Apple** | Sign in with Apple, App Store, IAP, APNs | Apple-ID, Belege, Push-Tokens | USA |
| **Google** | Sign in with Google, Google Play, FCM, AdMob | Google-ID, Belege, Push-Tokens, Werbe-ID | USA / Irland |
| **RevenueCat** | Abonnementverwaltung | Anonyme Nutzer-ID, Belege | USA |
| **The Odds API** | Quotendaten | Keine — nur ausgehend | UK |
| **Fußballstatistik-Anbieter** | Match-Statistiken und H2H | Keine — nur ausgehend | EU / UK |
| **Google AdMob** | Werbung kostenlose Stufe | Mobile Werbe-ID (mit Einwilligung) | USA / EU |
| **Expo** | Push-Benachrichtigungsinfrastruktur | Push-Token, Benachrichtigungsinhalt | USA |

---

## 5. Internationale Datenübermittlungen

Für Übermittlungen außerhalb des EWR stützen wir uns auf Standardvertragsklauseln, den EU-US-Datenschutzrahmen oder gleichwertige Garantien. Sie können eine Kopie der relevanten Garantien bei **contact@dycers.com** anfordern.

---

## 6. Werbung und Tracking

In der **kostenlosen Stufe** kann die App Werbung über **Google AdMob** anzeigen. Sie können Ihre Präferenzen jederzeit in den Geräteeinstellungen ändern. Bezahlte Nutzer (Pro / Max) sehen keine Werbung.

---

## 7. Aufbewahrungsfristen

| Datum | Aufbewahrungsfrist |
|-------|-------------------|
| Kontodaten | Solange Ihr Konto aktiv ist. Gelöscht innerhalb von 30 Tagen nach Kontolöschung. |
| Aktive Wetten | Während die Wette aktiv ist. |
| Wettverlauf | Solange Ihr Konto aktiv ist oder bis zur manuellen Löschung. |
| Verifizierungs-/Reset-Codes | Maximal 15 Minuten. |
| Server-Zugriffsprotokolle | 30 Tage. |
| Buchungsbelege für kostenpflichtige Abonnements | Gemäß geltendem Steuerrecht (in der Regel bis zu 10 Jahre). |
| Push-Benachrichtigungs-Tokens | Bis zum Widerruf der Berechtigung oder Deinstallation der App. |

---

## 8. Ihre Rechte

Nach DSGVO haben Sie das Recht auf: **Auskunft**, **Berichtigung**, **Löschung** (direkt in der App unter **Einstellungen → Konto → Konto löschen**), **Einschränkung der Verarbeitung**, **Datenübertragbarkeit**, **Widerspruch** und **Widerruf der Einwilligung**.

Richten Sie Anfragen an **contact@dycers.com**. Wir antworten innerhalb eines (1) Monats. Sie können auch eine Beschwerde bei Ihrer nationalen Datenschutzbehörde einreichen.

---

## 9. Sicherheit

Wir wenden angemessene technische und organisatorische Maßnahmen an: **TLS (HTTPS)**-Verschlüsselung, **bcrypt**-Hashing für Passwörter, **JWT**-Token im sicheren Gerätespeicher (`expo-secure-store`) und eingeschränkter Zugang zu Produktionssystemen.

---

## 10. Kinder

Die App **richtet sich nicht an Kinder**. Wir erheben wissentlich keine Daten von Personen unter 18 Jahren. Kontaktieren Sie uns unter **contact@dycers.com**, wenn Sie glauben, dass ein Minderjähriger uns personenbezogene Daten übermittelt hat.

---

## 11. Cookies und ähnliche Technologien

Die App ist eine native mobile Anwendung und verwendet keine herkömmlichen Web-Cookies. Sie nutzt lokalen Speicher (`expo-secure-store`, `AsyncStorage`) für Sitzung, Sprache und Einstellungen.

---

## 12. Datenschutzrichtlinien Dritter

- Apple — <https://www.apple.com/legal/privacy/>
- Google — <https://policies.google.com/privacy>
- Railway — <https://railway.com/legal/privacy>
- Brevo — <https://www.brevo.com/legal/privacypolicy/>
- RevenueCat — <https://www.revenuecat.com/privacy/>
- Expo — <https://expo.dev/privacy>
- The Odds API — <https://the-odds-api.com/privacy.html>

---

## 13. Änderungen dieser Richtlinie

Bei wesentlichen Änderungen werden wir Sie in der App oder per E-Mail mindestens fünfzehn (15) Tage vor Inkrafttreten informieren.

---

## 14. Kontakt

**contact@dycers.com**

---

*Durch Tippen auf „Ich stimme zu" oder die weitere Nutzung von Dycers bestätigen Sie, dass Sie diese Datenschutzrichtlinie gelesen und verstanden haben.*
