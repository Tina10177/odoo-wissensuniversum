---
layout: default
title: Von CRM über Sales zu Delivery und Invoice
---

Diese Prozesskette gehört zu den wichtigsten Grundlinien in Odoo.

Sie zeigt, wie aus einer ersten Vertriebschance schrittweise ein konkreter Geschäftsprozess wird – von der Kundenbeziehung über das Angebot bis hin zu Lieferung und Rechnung.

## 1. CRM: Lead oder Opportunity

Der Einstieg beginnt oft im CRM.

Hier werden Kontakte, Anfragen, Leads und Verkaufschancen erfasst.  
Noch geht es nicht um eine bestätigte Bestellung, sondern um die Frage, ob aus einer Anfrage ein konkretes Geschäft werden kann.

Wichtig ist:
CRM gehört zur Vertriebsanbahnung, nicht zur eigentlichen Auftragsabwicklung.

## 2. Sales: Von der Opportunity zur Quotation

Wenn aus einer Verkaufschance ein konkretes Angebot entsteht, wechselt der Prozess in den Sales-Bereich.

Hier wird eine **Quotation** erstellt.  
Sie beschreibt, was dem Kunden angeboten wird:
- welche Produkte oder Leistungen
- zu welchem Preis
- zu welchen Bedingungen

Eine Quotation ist noch keine bestätigte Bestellung.  
Sie ist zunächst ein Angebot.

## 3. Sales Order: Bestätigung des Verkaufs

Erst wenn das Angebot bestätigt wird, entsteht eine **Sales Order**.

Ab diesem Moment wird der Prozess verbindlicher.  
Je nach Produktart und Konfiguration können nun weitere Folgeprozesse ausgelöst werden, zum Beispiel:
- eine Lieferung
- eine Dienstleistung
- ein Rechnungsprozess

Hier ist ein zentrales Verständnis wichtig:
Nicht jede Sales Order führt automatisch zur gleichen Folge.  
Die weiteren Schritte hängen von Produktart, Lieferpolitik und Systemkonfiguration ab.

## 4. Delivery: Die logistische Folge

Wenn physische Produkte verkauft werden, entsteht in der Regel eine **Delivery**.

Die Delivery gehört zum Lager- bzw. Logistikprozess.  
Hier wird nicht mehr der Verkauf entschieden, sondern die tatsächliche Warenbewegung vorbereitet und dokumentiert.

Typische Fragen in dieser Phase sind:
- Wurde eine Lieferung erzeugt?
- Ist das Produkt überhaupt lagerrelevant?
- Ist genügend Bestand vorhanden?
- Welche Lagerbewegung ist vorgesehen?

## 5. Invoice: Die finanzielle Folge

Die **Invoice** gehört zum buchhalterischen bzw. finanziellen Teil der Kette.

Sie entsteht nicht einfach deshalb, weil etwas im CRM oder Sales passiert ist, sondern auf Grundlage definierter Regeln:
- nach Auftrag
- nach Lieferung
- je nach Rechnungsrichtlinie

Deshalb ist wichtig zu verstehen:
Sales, Delivery und Invoice sind verbunden, aber nicht identisch.

Eine Rechnung ist nicht einfach die „letzte Seite“ eines Verkaufs, sondern Teil einer eigenen Logik zwischen Vertrieb, Logistik und Buchhaltung.

## Warum ist diese Kette so wichtig?

Viele Missverständnisse in Odoo entstehen genau hier.

Zum Beispiel:
- Warum wurde keine Lieferung erzeugt?
- Warum ist der Rechnungsstatus anders als erwartet?
- Warum wurde etwas verkauft, aber noch nicht fakturiert?
- Warum ist ein Produkt sichtbar im Auftrag, aber nicht lagerwirksam?

Wer diese Kette versteht, versteht bereits einen zentralen Teil der Odoo-Logik.

## Kurz zusammengefasst

Die Grundlinie lautet:

**CRM → Quotation → Sales Order → Delivery → Invoice**

Aber diese Kette ist keine starre Automatikkette.  
Sie wird beeinflusst durch:
- Produkttypen
- Einstellungen
- Lieferpolitik
- Rechnungslogik
- reale Prozessschritte im Unternehmen

## Zurück zum Einstieg
[Zur README-Hauptseite](./README.md)
