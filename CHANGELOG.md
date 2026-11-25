# Änderungsprotokoll

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
