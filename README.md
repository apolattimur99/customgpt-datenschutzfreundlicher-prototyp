# CustomGPT – Datenschutzfreundlicher Angebotsassistent (Prototyp)

Dieses Repository dokumentiert den Prototypen eines CustomGPT, der aus strukturierten Kundenanfragen einen Angebotsentwurf erzeugt und dabei personenbezogene Daten konsequent anonymisiert.

## Was macht der Prototyp?
Der CustomGPT verarbeitet eine Anfrage in drei Schritten:
1. Anonymisierung (Entfernung von personenbezogenen Daten)
2. Strukturierung der Anfrage (Use Case, Leistungen, Rahmenbedingungen)
3. Erstellung eines Angebotsentwurfs auf Basis eines simulierten Produktkatalogs

Die Ausgabe erfolgt in drei Blöcken:
- **Block 1:** JSON (maschinenlesbar)
- **Block 2:** Tabelle (übersichtliche Angebotspositionen)
- **Block 3:** Text (Zusammenfassung und Hinweise)

## Schnelltest
1. Öffne eine Datei aus `tests/input/` und kopiere den JSON-Input.
2. Füge ihn in den CustomGPT ein.
3. Vergleiche das Ergebnis mit der passenden Datei in `tests/output/`.

## Repository-Inhalt
- `custom-gpt/` – Systemprompt und Wissenslog (Produktkatalog/Regeln)
- `tests/` – Testfälle (Eingaben/Ausgaben) inkl. Promptfallen
- `docs/` – Screenshots und zusätzliche Dokumentation
