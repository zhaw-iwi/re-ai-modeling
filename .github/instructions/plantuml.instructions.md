---
applyTo: "**/*.puml"
---

# PlantUML Instructions

- Bearbeite die vorhandene `.puml`-Datei.
- Erzeuge keine zusätzlichen Diagrammdateien, sofern dies nicht ausdrücklich verlangt wird.
- Bilde die Requirements vollständig und fachlich korrekt ab.
- Verwende die in der Aufgabe verlangte UML-Notation.
- Verwende dafür passende PlantUML-Konstrukte.
- Erfinde keine zusätzlichen Prozessschritte, Zustände, Bedingungen oder Abläufe.
- Fachliche Korrektheit und korrekte UML-Notation haben Vorrang vor Layout-Optimierung.
- Optimiere das automatische PlantUML-Layout nicht unnötig mit Layout-Hacks.
- Weise bei fachlichen Mehrdeutigkeiten im Requirement oder Change Request explizit darauf hin, statt selbst Annahmen zu treffen.

## UML Activity Diagrams

- Verwende Swimlanes (Activity Partitions), wenn aus den Requirements unterschiedliche verantwortliche Rollen oder Organisationseinheiten hervorgehen.
- Ordne Actions sowie Decision Nodes der fachlich verantwortlichen Swimlane zu.
- Decision Nodes werden als unbeschriftete Rauten dargestellt. Schreibe keine Entscheidungsfragen in die Raute.
- Beschrifte ausgehende Control Flows von Decision Nodes mit aussagekräftigen Guard Conditions in eckigen Klammern, z. B. `[erfolgreich]` und `[nicht erfolgreich]`.
- Guard Conditions eines Decision Nodes müssen die fachlich beschriebenen Alternativen eindeutig abbilden.
- Verwende Fork und Join für parallele Abläufe und deren Synchronisation.
- Verwende Merge Nodes zum Zusammenführen alternativer Abläufe und verwechsle sie nicht mit Join Nodes.
- Verwende für Wiederholungen nach Möglichkeit strukturierte PlantUML-Konstrukte wie `repeat`, sodass fachlich identische Actions nicht unnötig mehrfach dargestellt werden.
- Verwende Initial Nodes, Activity Final Nodes und Flow Final Nodes entsprechend ihrer UML-Semantik.
- Stelle sicher, dass das erzeugte PlantUML-Modell syntaktisch gültig und als Diagramm renderbar ist.