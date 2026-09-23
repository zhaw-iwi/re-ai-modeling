# Copilot Instructions – AI-gestützte Modellierung

Dieses Repository ist eine Lernumgebung für das Modul Requirements Engineering. Studierende nutzen GitHub Copilot im Agent Mode, um bestehende Modelle anhand von Requirements und Change Requests weiterzuentwickeln.

## Rollenverteilung

- Copilot darf Modelle erstellen und verändern.
- Die Studierenden sind für die fachliche und syntaktische Validierung der Ergebnisse verantwortlich. Copilot ersetzt diese Prüfung nicht.

## Grundregeln für jede Modelländerung

- Requirements und Change Requests sind die fachliche Grundlage. Erfinde keine zusätzlichen fachlichen Anforderungen.
- Verändere bestehende Modelle inkrementell. Erstelle sie nicht ohne Grund neu.
- Ändere nur die Elemente, die aufgrund des jeweiligen Requirements oder Change Requests notwendig sind.
- Erhalte bestehende korrekte Elemente und das bestehende Layout so weit wie möglich.
- Weise bei fachlichen Mehrdeutigkeiten im Requirement oder Change Request explizit darauf hin, statt selbst Annahmen zu treffen.
- Diagramme werden als native, editierbare `.drawio`-Dateien gepflegt (kein Export als Bild oder PDF als Ersatz für die Quelle).

## Konzeptionelle ER-Modelle in Chen-Notation

- Entitätstypen werden als Rechtecke dargestellt.
- Beziehungstypen werden als Rauten dargestellt.
- Attribute werden als Ovale dargestellt.
- Kardinalitäten stehen an den Kanten der Beziehungen.
- Keine relationalen Tabellen, Primärschlüssel oder Fremdschlüssel ergänzen, sofern dies nicht ausdrücklich im Requirement oder Change Request verlangt wird.

## Ausblick

Später werden in diesem Repository auch UML-Aktivitätsdiagramme und UML-Zustandsdiagramme unterstützt. Solange keine spezifischen Regeln dafür ergänzt wurden, gelten die obigen Grundregeln entsprechend.
