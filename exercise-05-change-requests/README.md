# Übung 5 – Change Requests

Diese Übung enthält die konzeptionellen ER-Modelle (Chen-Notation) sowie die zugehörigen Requirements und Change Requests, anhand derer die Modelle mit GitHub Copilot im Agent Mode weiterentwickelt werden sollen.

Ablage:
- `.drawio`-Dateien: die zu bearbeitenden ER-Modelle
- Requirements und Change Requests: fachliche Grundlage für die Modelländerungen

## Vorgehen bei mehreren Teilaufgaben/Schritten

Diese Übung wird schrittweise bearbeitet. Für jeden Schritt (Requirement oder Change Request) wird in der `.drawio`-Datei eine neue Seite (Tab) angelegt, die eine Kopie der Seite des vorherigen Schritts ist. So bleibt der Modellstand jedes Schritts nachvollziehbar erhalten, und Copilot verändert nur die neue Seite.

- Seite 1: Ausgangsmodell
- Seite 2: Ergebnis nach Schritt 1 (Kopie von Seite 1 + Änderungen)
- Seite 3: Ergebnis nach Schritt 2 (Kopie von Seite 2 + Änderungen)
- usw.

Copilot kann dazu die Draw.io-MCP-Tools `list-pages`, `copy-page` und `rename-page` nutzen, um die vorherige Seite zu duplizieren, bevor die Änderungen des aktuellen Requirements bzw. Change Requests darauf angewendet werden.

### Benennung der Seiten (Teilaufgaben a–g)

Die Übung besteht aus den Teilaufgaben a) bis g). Die Seiten werden entsprechend benannt:

- `Start` – Ausgangsmodell
- `a) Fahrzeughalter` – genau eine, aber beliebige Person darf Fahrzeughalter sein
- `b) Nachfolgevertrag` – Nachfolgevertrag eines Leasingvertrags
- `c) Rahmenvertrag` – Rahmenvertrag bestimmt monatliche Km und Monatsrate zu einem Leasingvertrag
- `d) Autonummer` – Autonummer wiederverwenden
- `e) Firmenkunde` – Erweiterung für Firmenkunden (mit Vererbung)
- `f) Hauptansprechpartner` – Hauptansprechpartner der Firma festlegen
- `g) Firma als Halter` – Firma als Fahrzeughalter ermöglichen

Die alphanumerische Benennung sorgt dafür, dass die Tab-Reihenfolge in Draw.io der Bearbeitungsreihenfolge entspricht.
