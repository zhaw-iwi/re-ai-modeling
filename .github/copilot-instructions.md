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
- Beschreibe vor dem Zeichnen die geplante Änderung kurz in Textform und warte die Bestätigung der Studierenden ab, bevor die Elemente im Diagramm angelegt oder verändert werden.
- Neue bzw. geänderte Elemente eines Schritts werden grün dargestellt (grüne Linien, grüner Text; Flächenobjekte mit leichter grüner Füllung), damit die Änderung gegenüber dem Vorzustand erkennbar bleibt.
- Verbindungslinien werden gerade gezeichnet, ohne Ecken/Knicke.
- Bei Attributen und anderen beschrifteten Elementen auf ausreichend Platz für den Text achten (Form ggf. vergrössern, statt den Text abzuschneiden).
- Neue Elemente mit ausreichend Abstand zu bestehenden Elementen platzieren, damit sich Formen nicht berühren oder überlappen.
- Verbindungspunkte so wählen, dass die Linie an einer sinnvollen Stelle der Form beginnt bzw. endet (z. B. Seiten- oder Kantenmitte in Richtung des Verbindungspartners), nicht an einer beliebigen bzw. ungünstig wirkenden Stelle.

## Konzeptionelle ER-Modelle in Chen-Notation

- Entitätstypen werden als Rechtecke dargestellt.
- Beziehungstypen werden als Rauten dargestellt.
- Attribute werden als Ovale dargestellt.
- Kardinalitäten stehen an den Kanten der Beziehungen.
- Keine relationalen Tabellen, Primärschlüssel oder Fremdschlüssel ergänzen, sofern dies nicht ausdrücklich im Requirement oder Change Request verlangt wird.

## Ausblick

Später werden in diesem Repository auch UML-Aktivitätsdiagramme und UML-Zustandsdiagramme unterstützt. Solange keine spezifischen Regeln dafür ergänzt wurden, gelten die obigen Grundregeln entsprechend.
