# c) Rahmenvertrag bestimmt monatliche Km und Monatsrate zu einem Leasingvertrag

## Change Request

Es gibt ein grosses Kundenbedürfnis, mehrere Fahrzeuge des jeweils gleichen Modells zu leasen, beispielsweise für Flottenverantwortliche in einem Unternehmen. Deshalb soll ein Rahmenvertrag eingeführt werden, der pro Kunde die Modell-Bezeichnung (z.B. Tesla Model 3), die monatlichen Kilometer sowie die Monatsrate festlegt. Auch der Rahmenvertrag hat ein Vertragsdatum. Ist ein Rahmenvertrag abgeschlossen, so können zu diesen Konditionen beliebig viele Leasingverträge abgeschlossen werden. Umgekehrt gehört jeder Leasingvertrag zu genau einem Rahmenvertrag.

Das Controlling wünscht, für ein Fahrzeug-Modell auf allen betroffenen Rahmenverträgen die Konditionen (monatliche Kilometer und Monatsrate) überprüfen zu können.

Für bestehende Verträge ohne Rahmenvertrag wird für jeden Vertrag ein neuer Rahmenvertrag nachträglich im System erfasst. Ebenfalls wird bei Verträgen über einzelne Fahrzeuge zukünftig ebenfalls ein Rahmenvertrag erfasst (möglicherweise automatisch durch das System selbst).

## Vorgegebene Entitätstypen

- Leasingvertrag
- Fahrzeug
- Modell
- Rahmenvertrag
- Person

## Ein Beispiel für einen Rahmenvertrag:

> **EasyLeasing AG**
>
> **Rahmenvertrag für Fahrzeug-Modell Tesla Model 3**
>
> **Modell:** Tesla Model 3  
> **Monatsrate:** 1250 Fr.  
> **Monatliche Kilometer:** 1500 km
>
> **Vertragsnehmer**
>
> Anthony McGregor, Winterthur  
> Beatrix Weimer, Zürich  
> Catherine Crowden, Winterthur
>
> Es gelten die AGB der EasyLeasing AG.
>
> **Vertragsdatum:** 1.1.2020

## Ein Beispiel für einen Leasingvertrag basierend auf obenstehendem Rahmenvertrag:

> **EasyLeasing AG**
>
> **Leasingvertrag über Fahrzeug**
>
> **Modell:** Tesla Model 3  
> **Zulassung:** 03/2020  
> **Km-Stand:** 10 km  
> **Nummer:** ZH 923456  
> **Halter:** Peter Brown, Luzern
>
> **Vertragsnehmer**
>
> Anthony McGregor, Winterthur  
> Beatrix Weimer, Zürich  
> Catherine Crowden, Winterthur
>
> Es gelten die Preis- und Kilometervereinbarungen gemäss dem Rahmenvertrag vom 1.1.2020:
>
> **Monatsrate:** 1250 Fr.  
> **Monatliche Kilometer:** 1500 km  
> **Vertragsdatum:** 1.2.2020  
> **Beginn:** 1.4.2020  
> **Ende:** 31.3.2024
