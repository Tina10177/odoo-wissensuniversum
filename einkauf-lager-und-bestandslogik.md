# Einkauf, Lager und Bestandslogik

Einkauf, Lager und Bestand gehören in Odoo eng zusammen.

Viele praktische Missverständnisse entstehen genau dort, wo diese drei Bereiche im Alltag zwar gemeinsam erlebt, im System aber unterschiedlich abgebildet werden.

## 1. Einkauf ist nicht gleich Lagerbewegung

Der Einkauf beginnt in Odoo in der Regel mit einer **RFQ** oder einem **Purchase Order**.

Damit ist zunächst der Beschaffungsprozess beschrieben:
- Was wird bestellt?
- Bei welchem Lieferanten?
- Zu welchem Preis?
- Unter welchen Bedingungen?

Eine Bestellung allein bedeutet jedoch noch nicht, dass Ware bereits im Lager angekommen ist.

Wichtig ist:
Ein Purchase Order ist noch keine tatsächliche Bestandsveränderung.

## 2. Receipt: Der Moment der Bestandswirkung

Erst mit dem **Receipt** wird die physische oder systemische Warenannahme relevant.

Hier zeigt sich die eigentliche Lagerwirkung:
- Welche Ware ist angekommen?
- In welcher Menge?
- An welchem Lagerort?
- Zu welchem Zeitpunkt?

Der Receipt ist daher ein zentraler Punkt der Bestandslogik.

Nicht die Bestellung verändert den Bestand, sondern die bestätigte Lagerbewegung.

## 3. Bestand ist nicht nur eine Zahl

Bestand in Odoo bedeutet nicht einfach „wie viel da ist“.

Je nach Sichtweise spielen unterschiedliche Fragen eine Rolle:
- physischer Bestand
- verfügbarer Bestand
- reservierter Bestand
- erwarteter Bestand

Deshalb entstehen im Alltag oft Irritationen, wenn Nutzer nur eine Zahl sehen wollen, das System aber verschiedene Bestandszustände unterscheidet.

## 4. Warum Einkauf und Lager oft verwechselt werden

In vielen Unternehmen werden Bestellung und Wareneingang gedanklich zu eng zusammengelegt.

Im System sind es jedoch verschiedene Ebenen:
- Einkauf beschreibt die Beschaffungsentscheidung
- Lager beschreibt die tatsächliche Warenbewegung
- Bestand beschreibt den daraus resultierenden Zustand

Wer diese Ebenen vermischt, erlebt Odoo schnell als „unlogisch“, obwohl das System in sich durchaus konsistent arbeitet.

## 5. Bestand braucht Kontext

Ob ein Bestand „stimmt“, hängt nicht nur von einer Zahl im System ab.

Entscheidend ist auch:
- Welcher Produkttyp liegt vor?
- Wurde der Wareneingang korrekt gebucht?
- Gibt es Reservierungen?
- Welche Lagerorte sind beteiligt?
- Wurde eine interne Bewegung berücksichtigt?

Bestand ist deshalb immer eine Frage von Prozesslogik und Kontext, nicht nur von Sichtbarkeit.

## Warum ist dieses Thema so wichtig?

Viele typische Fragen hängen direkt damit zusammen:
- Warum stimmt der Lagerbestand nicht?
- Warum wurde Ware bestellt, ist aber noch nicht verfügbar?
- Warum ist etwas im System vorhanden, aber nicht nutzbar?
- Warum wirkt der Einkauf abgeschlossen, obwohl der Lagerprozess noch offen ist?

Wer Einkauf, Lager und Bestandslogik voneinander unterscheiden kann, versteht einen wesentlichen Teil der operativen Odoo-Logik.

## Kurz zusammengefasst

Die Grundunterscheidung lautet:

**Einkauf = Beschaffung**  
**Receipt = Warenannahme / Lagerbewegung**  
**Bestand = systemischer Zustand im Lagerkontext**

Diese drei Ebenen hängen zusammen, sind aber nicht identisch.

## Zurück zum Einstieg
[Zur README-Hauptseite](./README.md)
