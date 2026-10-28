# catch. Legal

Statische Rechtstexte für die App **catch.** (`com.turfgames.app`, Android und iPhone), gehostet über GitHub Pages. Der Code der App liegt im privaten Repo `Jerdna3/CatchMe`.

## Inhalt

- [`privacy-policy/index.html`](privacy-policy/index.html) — Datenschutzerklärung (Deutsch)
- [`privacy-policy/en.html`](privacy-policy/en.html) — Privacy Policy (English)
- [`privacy-policy/style.css`](privacy-policy/style.css) — Gestaltung in den Farben der App (für alle Seiten)
- [`support/index.html`](support/index.html) — Support mit Kontakt und häufigen Fragen (Deutsch)
- [`support/en.html`](support/en.html) — Support (English)

## Veröffentlichen mit GitHub Pages

1. Dieses Repository nach GitHub pushen (`Jerdna3/catchme-legal`, öffentlich).
2. Im GitHub-Repo: **Settings → Pages**.
3. Unter **Build and deployment**:
   - **Source**: „Deploy from a branch“
   - **Branch**: `main`, Ordner **`/ (root)`**
4. Nach dem Deploy sind die Seiten erreichbar unter:
   - Datenschutz DE: `https://jerdna3.github.io/catchme-legal/privacy-policy/`
   - Datenschutz EN: `https://jerdna3.github.io/catchme-legal/privacy-policy/en.html`
   - Support DE: `https://jerdna3.github.io/catchme-legal/support/`
   - Support EN: `https://jerdna3.github.io/catchme-legal/support/en.html`

## Wo die URLs eingetragen sind

- **Google Play Console → App-Inhalte → Datenschutzerklärung:** die englische Seite, weil die Hauptsprache des Store-Eintrags Englisch ist. Sie verlinkt auf die deutsche.
  ```
  https://jerdna3.github.io/catchme-legal/privacy-policy/en.html
  ```
- **App Store Connect → App-Datenschutz:** pro Sprache, Englisch `en.html`, Deutsch die Hauptseite.
- **App Store Connect → Support-URL** (Pflicht): pro Sprache die Support-Seite, Englisch `support/en.html`, Deutsch `support/`.
- **In der App:** Link auf der Startseite, je nach Sprache der App (`apps/mobile` im Repo CatchMe).

## Bei Änderungen

- Inhalt in `index.html` **und** `en.html` anpassen (beide Sprachen synchron halten).
- Das Datum „Zuletzt aktualisiert“ / „Last updated“ in beiden Dateien aktualisieren.
- Committen und pushen. GitHub Pages veröffentlicht automatisch neu.

## Wann die Erklärung angepasst werden muss

Die Erklärung beschreibt den Stand von catch. 0.4.0 (Oktober 2026): kein Konto, Spielername frei wählbar, Standort nur während einer Runde an den Game-Server (Render, Frankfurt), der nichts dauerhaft speichert, Kamera und Sensoren nur auf dem Handy, Google Maps, Updates über Expo, keine Werbung und keine Analyse-Dienste.

Anpassen, sobald sich daran etwas ändert, insbesondere bei:

- **Spenden** oder anderen Käufen (Google Play Billing, Apple In-App-Kauf)
- **Fehlerberichten** aus der App (z.B. Sentry), Analyse-Diensten oder Werbung
- **Spielständen, die gespeichert werden**, z.B. damit Runden einen Neustart des Servers überstehen (dann gibt es eine Speicherdauer)
- **Konten**, Freundeslisten oder Chat
- einem **Wechsel des Hostings** oder der Server-Region oder neuen Drittanbietern
- **neuen Berechtigungen** (z.B. Mikrofon, Kontakte, Fotos)
- einem **Umzug des Herausgebers** in ein anderes Land. Heute: Hamburg (DSGVO, Aufsicht HmbBfDI). Geplant ist der Umzug in die Schweiz um Herbst 2027; dann das Schweizer DSG neben der DSGVO nennen, den EDÖB als Behörde angeben und prüfen, ob ein EU-Vertreter nötig ist (Art. 27 DSGVO).
