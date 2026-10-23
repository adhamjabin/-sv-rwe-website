# SV Rot-Weiß Erlinghausen – Website (Neugestaltung)

Modernisierte, handyoptimierte Version von sv-rot-weiss-erlinghausen.de.
Inhalte stammen von der bisherigen Vereinsseite.

## Aufbau
- `index.html` – komplette Seite (HTML, CSS und JavaScript in einer Datei)
- `img/` – Vereinslogo und Sponsorenlogos

Die Unterseiten (News, Termine, Mannschaften, …) sind Bereiche in `index.html`
und werden über den Link-Anker umgeschaltet (z. B. `index.html#termine`).

## Lokal ansehen
    python3 -m http.server 8080
dann http://localhost:8080 öffnen.

## Hinweise
- Der fussball.de-Vereinsspielplan ist für die Domain sv-rot-weiss-erlinghausen.de registriert.
- PDFs, Impressum, Datenschutz, Fotogalerie und Archiv verlinken noch auf die bisherige Seite.
- Die Box „Letzte Ergebnisse“ auf der Startseite wird von Hand gepflegt.
