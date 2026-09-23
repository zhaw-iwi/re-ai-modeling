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
- Verbindungslinien werden nach Möglichkeit gerade gezeichnet, ohne Ecken/Knicke. Ist das ohne Kollision mit anderen Elementen nicht möglich, sind maximal zwei Knickpunkte zulässig, um die Linie kollisionsfrei um andere Elemente herumzuführen.
- Verbindungslinien dürfen weder die Raute, mit der sie verbunden sind, noch andere Elemente (Entitäten, Attribute, weitere Verbindungslinien) durchqueren oder kreuzen.
- Bei Attributen und anderen beschrifteten Elementen auf ausreichend Platz für den Text achten (Form ggf. vergrössern, statt den Text abzuschneiden).
- Bei Rauten (Beziehungen) Verbindungspunkte nur an den vier tatsächlichen Eckpunkten (oben/rechts/unten/links) setzen. Andere Bruchteilspositionen liegen ausserhalb der sichtbaren Form und erzeugen eine Lücke zwischen Linie und Form. Zusätzlich muss die Anflugrichtung so gewählt werden, dass die Linie nicht durch die Raute hindurchläuft, bevor sie den Eckpunkt erreicht.
- Neue Elemente mit ausreichend Abstand zu bestehenden Elementen platzieren, damit sich Formen nicht berühren oder überlappen.
- Verbindungspunkte so wählen, dass die Linie an einer sinnvollen Stelle der Form beginnt bzw. endet (z. B. Seiten- oder Kantenmitte in Richtung des Verbindungspartners), nicht an einer beliebigen bzw. ungünstig wirkenden Stelle.
- Bestehende Elemente (z. B. Attribute) dürfen bei Bedarf leicht verschoben werden, um Platz für neue Elemente zu schaffen, sofern die grundsätzliche Layoutstruktur erhalten bleibt.
- Nach einer Layoutänderung auf Überlappungen und Kreuzungen im Bereich der neuen oder verschobenen Elemente prüfen. Bestehende, nicht berührte Bereiche müssen nicht erneut vollständig geprüft werden. Studierende können das Layout anschliessend bei Bedarf weiter optimieren.

## Mehrschritt-Aufgaben

- Bei aufeinander aufbauenden Requirements oder Change Requests vor der Modelländerung die vorherige Draw.io-Seite mit den MCP-Tools `list-pages`, `copy-page` und `rename-page` duplizieren. Die vorgegebene Tabbezeichnung der jeweiligen Übungs-README verwenden.

## Konzeptionelle ER-Modelle in Chen-Notation

- Entitätstypen werden als Rechtecke dargestellt.
- Beziehungstypen werden als Rauten dargestellt.
- Attribute werden als Ovale dargestellt.
- Kardinalitäten stehen an den Kanten der Beziehungen; Kanten tragen darüber hinaus keine frei formulierten Beschriftungen (auch nicht bei rekursiven/unären Beziehungen).
- Keine relationalen Tabellen, Primärschlüssel oder Fremdschlüssel ergänzen, sofern dies nicht ausdrücklich im Requirement oder Change Request verlangt wird.
- Vererbung (IS-A) wird als einfaches Dreieck zwischen Ober- und Subtypen dargestellt. Das Dreieck trägt gut lesbar die Beschriftung `IS-A`.
- Das Dreieck wird so ausgerichtet, dass seine Spitze zum Obertyp und seine gegenüberliegende Kante zu den Subtypen zeigt. Die Verbindung zum Obertyp startet exakt an der Dreiecksspitze. Jede Verbindung von einem Subtyp endet exakt an der gegenüberliegenden Dreieckskante; bei mehreren Subtypen sind die Anschlusspunkte entlang dieser Kante zu verteilen.
- Verbindungslinien dürfen weder das IS-A-Dreieck durchqueren noch in dessen Fläche enden. Dreieck und angeschlossene Entitäten benötigen sichtbaren Abstand und dürfen sich nicht überlappen.
- Zusätzliche Disjunktheits- bzw. Vollständigkeits-Markierungen (d/o) werden nicht verwendet, da diese Notation im Kurs nicht behandelt wird.

## Ausblick

Später werden in diesem Repository auch UML-Aktivitätsdiagramme und UML-Zustandsdiagramme unterstützt. Solange keine spezifischen Regeln dafür ergänzt wurden, gelten die obigen Grundregeln entsprechend.
