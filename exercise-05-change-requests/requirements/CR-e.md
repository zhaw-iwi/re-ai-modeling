# e) Erweiterung für Firmenkunden (mit Vererbung)

## Change Request

Der Leiter der Abteilung Business Development erkennt ein Potential, die Software auch beim Leasing für Geschäftskunden einzusetzen. Der Vertragsnehmer ist in diesem Fall immer genau eine Firma mit einem Firmennamen. Pro Firma gibt es eine bestimmte Anzahl Mitarbeiter, welche unterschriftsberechtigt und daher auf dem Vertrag aufgeführt sind.

Natürlich soll die Software weiterhin auch für Privatkunden wie gewohnt funktionieren.

## Vorgegebene Entitätstypen

- Leasingvertrag
- Fahrzeug
- Autonummer
- Modell
- Rahmenvertrag
- Rahmenvertrag Firmenkunden
- Rahmenvertrag Privatkunden
- Person
- Firma

## Das Leasingvertragsdokument eines Geschäftskunden (der zugehörige Rahmenvertrag ist nicht abgebildet):

> **EasyLeasing AG**
>
> **Leasingvertrag über Fahrzeug**
>
> **Modell:** VW I.D. Buzz  
> **Zulassung:** 03/2018  
> **Km-Stand:** 10 km  
> **Nummer:** ZH 750251  
> **Halter:** Peter Mayer, Winterthur
>
> **Vertragsnehmer Gärtnerei Blume AG gemäss Rahmenvertrag vom 1.1.2018:**
>
> Anthony McGregor, Winterthur  
> Beatrix Weimer, Zürich  
> Catherine Crowden, Winterthur
>
> Es gelten die Preis- und Kilometervereinbarungen gemäss dem Rahmenvertrag vom 1.1.2018:
>
> **Monatsrate:** 1250 Fr.  
> **Monatliche Kilometer:** 700 km  
> **Vertragsdatum:** 1.1.2018  
> **Beginn:** 1.4.2018  
> **Ende:** 31.3.2024

## Ein weiteres Leasingvertragsdokument:

> **EasyLeasing AG**
>
> **Leasingvertrag über Fahrzeug**
>
> **Modell:** VW Golf  
> **Zulassung:** 04/2018  
> **Km-Stand:** 10 km  
> **Nummer:** ZH 650351  
> **Halter:** Catherine Crowden, Winterthur
>
> **Vertragsnehmer Dance Project AG gemäss Rahmenvertrag vom 1.1.2019:**
>
> Catherine Crowden, Winterthur
>
> Es gelten die Preis- und Kilometervereinbarungen gemäss dem Rahmenvertrag vom 1.1.2019:
>
> **Monatsrate:** 650 Fr.  
> **Monatliche Kilometer:** 2000 km  
> **Vertragsdatum:** 1.2.2019  
> **Beginn:** 1.4.2018  
> **Ende:** 31.3.2023

## Hinweis

Benutzen Sie Vererbung mit der Chen-Notation („IS-A“), um Rahmenverträge für Firmenkunden bzw. Privatkunden abzubilden.
