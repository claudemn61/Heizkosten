# Änderungsprotokoll

## 1.2.2 – 25.11.2026
- Jahr: Spaltenwahl um «Ø Temperatur (°C)» je Monat ergänzt (ganz rechts; folgt der Wahl Bellwald/Geschinen)

## 1.2.1 – 25.11.2026
- Jahr: rechts neben der Heiztage-Summe optional Summe kWh und CHF je Monat (geschätzt); Auswahl über das Listen-Symbol oben rechts in der Karte

## 1.2.0 – 25.11.2026
- Synchronisierung zwischen Geräten über ein privates GitHub-Repo (Daten → Synchronisierung), Token nur auf dem jeweiligen Gerät
- Abgleich pro Eintrag (Tag, Quartal, Einstellung) mit Änderungszeitpunkt und Löschmarkern
- Automatischer Abgleich beim Öffnen und nach Änderungen, Nachschreiben nach Offline-Betrieb, Statusanzeige

## 1.1.0 – 25.11.2026
- Jahr: neue Karte «Zeitraum» – für beliebige Daten (oder Jahr, Quartal, Monat, 12 Monate) Heiztage, Frostschutztage, Heizgradtage sowie geschätzte kWh und Kosten, getrennt nach Schätzung/Prognose
- Tag-Dialog: Schätzung für den Tag (Heizgradtage, kWh, CHF)
- Temperaturkorrektur Ulrichen → Bellwald (Einstellungen a/b); Umschalter Bellwald/Geschinen in der Jahresansicht

## 1.0.2 – 25.11.2026
- Monatswerte und Frostfaktor entfernt: Kostenmodell und Prognose rechnen direkt mit Heizgradtagen; künftige Tage mit Klimamittel der Vorjahre
- «CHF je gewichtetem Tag» heisst jetzt «CHF je Heizgradtag»

## 1.0.1 – 25.11.2026
- Heizbedarf je Monat wird automatisch aus den Wetterdaten abgeleitet (abschaltbar)

## 1.0.0 – 25.11.2026
- Erste stabile Version (Funktionsumfang wie 0.05.00)

## 0.05.00 – 25.11.2026
- Heiztage (21 °C) rot statt blau
- Einstellung «Frostschutz heizt bei Tagesmittel unter … °C» mit Vorschlag der besten Schwelle

## 0.04.02 – 25.11.2026
- Analyse: Modell rechnet mit Frostschutztagen mit Heizbetrieb statt mit allen Frostschutztagen; neue Spalte «Frost aktiv» in der Quartalstabelle

## 0.04.01 – 25.11.2026
- Kalender: Frostschutztage mit Tagesmittel unter Frostschutz-Temperatur (Heizung läuft vermutlich) orange markiert; Monatskachel «Frost heizt vermutl.»

## 0.04.00 – 24.11.2026
- Analyse: Durchschnittlicher Verbrauch (Ø je Kalendertag gleitend 12 Monate, Modell kWh je Heiz-/Frostschutztag, kWh je gewichtetem Tag)
- Heizgradtage aus MeteoSchweiz-Wetterdaten (Station Ulrichen), automatisch geladen; kWh je Heizgradtag pro Quartal
- Einstellung Heizgrenze; Wetterdaten manuell aktualisierbar

## 0.03.01 – 24.11.2026
- Einstellung «Tages-Details (kWh je Tag) anzeigen» (Standard: aus) blendet Details-Modus, Details-Knopf, kWh-Felder und kWh-Kacheln aus oder ein

## 0.03.00 – 24.11.2026
- Darstellung wählbar: Automatisch, Hell oder Dunkel (Daten → Einstellungen)

## 0.02.01 – 24.11.2026
- Automatische Updates: Seite wird zuerst vom Server geladen (Cache nur offline), App lädt sich bei neuer Version selbst neu

## 0.02.00 – 24.11.2026
- Kalender: Antippen schaltet einen Tag direkt zwischen Heiztag und Frostschutz um (langes Drücken öffnet die Details)
- Zeitraum direkt im Kalender markieren: ersten und letzten Tag antippen
- Rückgängig-Knopf nach jeder Änderung im Kalender

## 0.01.00 – 24.11.2026
- Erste Version
- Tageserfassung (Heiztag / Frostschutz) mit Feldern für Verbrauch und PV-Produktion (kWh), Zeitraum-Erfassung
- Quartalskosten mit Kostenmodell (Gewichtung nach Monaten), Jahresübersicht (Heatmap)
- Analysen: Jahresvergleich, Heiztage pro Jahr/Monat, Kosten und kWh pro Quartal, Prognose offene Quartale
- Import (JSON, CSV – auch für Tele Butler), Export (JSON, CSV), offline-fähig
