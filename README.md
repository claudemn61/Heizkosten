# Heizkosten Bellwald

PWA zur Erfassung der Heiztage, Stromkosten und kWh (Verbrauch / PV-Produktion) im Ferienhaus Zer Tanne, Bellwald.

- Version: siehe `CHANGELOG.md` (Start bei 0.01.00)
- Reine statische Seite (keine Build-Schritte), offline-fähig, Daten nur lokal im Browser
- Hosting: GitHub Pages (Repo-Root, Branch `main`)

## Dateien
- `index.html` – gesamte App
- `sw.js` – Service Worker (bei jeder Version `VERSION` anpassen)
- `manifest.webmanifest`, `icons/` – Installation als Homescreen-App

## Version erhöhen
`VERSION` in `index.html` **und** `sw.js` ändern, Eintrag in `CHANGELOG` (in `index.html`) und `CHANGELOG.md` ergänzen.

## Daten
Die Daten (Heiztage, Kosten) gehören **nicht** ins öffentliche Repo. Sie liegen im Browser und werden über *Daten → Sicherung exportieren (JSON)* gesichert.
Die Startdaten (`Startdaten_Heiztage_Bellwald.json`) einmalig über *Daten → Sicherung importieren* laden.
Dateien `*.json` sind in `.gitignore` ausgeschlossen.

## Kostenmodell
Siehe in der App: Kosten → «Wie wird gerechnet?».

## Tele Butler
Import über *Daten → CSV-Import*: Datum + Solltemperatur (Heiztag ab einstellbarer Schwelle) oder Heiztag-Spalte, optional kWh. Ein direkter API-Abruf ist noch nicht umgesetzt.
