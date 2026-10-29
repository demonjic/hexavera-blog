---
title: "Wie Hexavera Entscheidungen erklärt und simuliert"
description: "Für Betriebsräte und Auditoren: wie Hexavera eine Entscheidung auf Regel, Rechtsgrundlage, Werkseinstellung und Daten zurückführt und Änderungen simuliert."
permalink: "/explained"
slug: "explained"
lang: "de"
id: "page-explained"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Für Betriebsräte und Auditoren"
    title: "Jede Entscheidung lässt sich öffnen, lesen und prüfen"
    subtitle: "Sperrt Hexavera eine Schicht, verweigert den Zutritt an einer Tür oder markiert Überstunden, hält das System die Begründung fest: die Regel, die Herkunft ihres Werts, die verwendeten Daten und das Ergebnis. Diese Seite geht ein solches Protokoll Schritt für Schritt durch und zeigt, was eine Simulation zusätzlich leistet."
    primary_action: { text: "Diagnose anfragen", url: "/diagnostic" }
    secondary_action: { text: "Zur Produkttour", url: "/demo" }
  - type: split
    eyebrow: "Eine Entscheidung, nachverfolgt"
    title: "Ein Tausch in die Nachtschicht, gesperrt wegen fehlender Ruhezeit"
    markdown: |
      Ein Mitarbeiter aus der Verpackung arbeitete am Dienstag in der Frühschicht und blieb ein paar Minuten länger. Am Nachmittag bat ihn eine Kollegin, ihre Nachtschicht auf Linie 3 ab 22:00 Uhr zu übernehmen. Der Schichtleiter nahm den Tausch in Attendance an, und Attendance prüfte ihn, bevor er gespeichert wurde.

      Das Protokoll neben diesem Text hat Attendance geschrieben. Es wird am Standort und im Cloud-Mandanten gespeichert und kann nachträglich von niemandem bearbeitet werden. Eine Korrektur ist ein neues Protokoll, das auf das alte verweist.
    aside:
      type: record
      title: "Prüfprotokoll, Schichttausch SW-118"
      status: "Gesperrt"
      tone: danger
      rows:
        - { label: "Entscheidung", value: "E-2041 in die Nachtschicht einteilen, Linie 3, Di. 22:00" }
        - { label: "Regel", value: "DAILY-REST, tägliche Mindestruhezeit, Version 3" }
        - { label: "Rechtsgrundlage", value: "§ 5 Abs. 1 Arbeitszeitgesetz (ArbZG), Umsetzung von Art. 3 der EU-Arbeitszeitrichtlinie 2003/88/EG: mindestens 11 Stunden ununterbrochen" }
        - { label: "Verwendeter Wert", value: "11 Std., gesetzliche Ebene; kein Tarifvertrag und kein Unternehmenswert weicht davon ab" }
        - { label: "Werkseinstellung", value: "Die Ruhezeit wird ab der letzten Gehen-Buchung an einem Zeiterfassungsterminal gemessen. Festgelegt auf Standortebene von der Personaladministration des Werks, gültig ab 1. März 2026" }
        - { label: "Eingangsangabe 1", value: "Letzte Gehen-Buchung Di. 14:06, Terminal T-04 (Attendance, Buchung P-88213)" }
        - { label: "Eingangsangabe 2", value: "Geplanter Beginn Di. 22:00 (Schichtplan, Tauschantrag SW-118)" }
        - { label: "Berechnet", value: "Ruhezeit dazwischen: 7 Std. 54 Min." }
        - { label: "Ergebnis", value: "Nicht erfüllt: 7 Std. 54 Min. liegen unter 11 Std. Tausch gesperrt" }
        - { label: "Geprüft", value: "Standortsystem, Di. 15:20, ausgelöst durch die Aktion des Schichtleiters" }
      caption: "Beispieldaten"
  - type: section
    eyebrow: "Dasselbe Protokoll in Klartext"
    title: "Was die Erklärung sagt"
    markdown: |
      > Der Tausch wurde gesperrt, weil der Mitarbeiter vor der Nachtschicht nur 7 Stunden und 54 Minuten Ruhezeit gehabt hätte. Gesetzlich vorgeschrieben sind mindestens 11 zusammenhängende Stunden innerhalb von 24 Stunden.
      >
      > Die 11 Stunden ergeben sich aus § 5 Abs. 1 ArbZG, der Artikel 3 der EU-Arbeitszeitrichtlinie umsetzt. In diesem Werk ändert weder ein Tarifvertrag noch eine Unternehmensregel diesen Wert.
      >
      > Gezählt wurde die Ruhezeit von der letzten Gehen-Buchung des Mitarbeiters um 14:06 Uhr an Terminal T-04 bis zum Beginn der Nachtschicht um 22:00 Uhr. Das Werk misst die Ruhezeit ab der Gehen-Buchung am Zeiterfassungsterminal; die Personaladministration hat dies am 1. März 2026 so festgelegt.
      >
      > Halten Sie eine Angabe für falsch, etwa die Uhrzeit der Gehen-Buchung, zeigt die Buchung P-88213, woher sie stammt.

      Jede Erklärung folgt derselben Reihenfolge: was entschieden wurde, welche Regel galt, woher der Wert stammt, welche Daten verwendet wurden und woher sie jeweils kommen, was berechnet wurde und wie das Ergebnis lautet. Ein Betriebsratsmitglied, ein Auditor oder der betroffene Mitarbeiter kann jeden Schritt prüfen, ohne Code zu lesen. Erklärungen stehen in jeder Sprache zur Verfügung, die die Konsole anbietet.
  - type: checklist
    eyebrow: "Warum das Protokoll belastbar ist"
    title: "Regeln als Daten, Angaben mit Quelle, nichts wird überschrieben"
    items:
      - text: "Regeln sind Daten, kein Code"
        description: "Administratoren wählen Werte und Geltungsbereiche. Ausdrücke können sie nicht schreiben. Deshalb lässt sich jede Regel auflisten und lesen."
      - text: "Jeder Wert hat eine Ebene und eine Quelle"
        description: "Gesetz, Tarifvertrag, Unternehmen oder Abteilung, jeweils mit Fundstelle und Gültigkeitszeitraum."
      - text: "Jede Angabe hat eine Quelle"
        description: "Das System und der Datensatz, aus dem sie stammt, und der Zeitpunkt, zu dem sie erfasst wurde."
      - text: "Fehlende Angaben werden benannt"
        description: "Braucht eine Regel eine Angabe, die nicht vorliegt, lautet das Ergebnis „nicht bestimmbar“, nie „erfüllt“."
      - text: "Protokolle werden nur ergänzt"
        description: "Regelversionen und Prüfprotokolle bleiben erhalten. Eine Korrektur verweist auf das, was sie korrigiert."
  - type: split
    eyebrow: "Simulation"
    title: "Eine Regeländerung an vergangenen Entscheidungen testen, bevor sie gilt"
    markdown: |
      Angenommen, Geschäftsleitung und Betriebsrat verhandeln über eine tarifliche Klausel, nach der die Ruhezeit zweimal im Monat auf 10 Stunden verkürzt werden darf, mit Ausgleich später in derselben Woche. Bevor sie zustimmen, wollen beide Seiten wissen, was sich dadurch ändern würde.

      Eine Simulation wendet dieselben Regeln mit den vorgeschlagenen Werten auf einen vergangenen Zeitraum an. Sie listet jede Entscheidung auf, deren Ergebnis sich ändern würde, nach Abteilung und Schicht, jeweils mit Erklärung. Kein Ergebnis der Simulation wird zum produktiven Protokoll, und keine Mitarbeiterdaten verlassen den Mandanten.

      Der Betriebsrat sieht, wie die Klausel auf die tatsächlichen Schichtmuster wirkt, statt sich auf ein Beispiel verlassen zu müssen, das ihn überzeugen soll.
    aside:
      type: checklist
      title: "Was eine Simulation zeigt"
      items:
        - { text: "Die verglichenen Werte", description: "Aktueller und vorgeschlagener Wert nebeneinander." }
        - { text: "Jede Entscheidung, die sich ändert", description: "Von gesperrt zu zulässig oder von zulässig zu gesperrt." }
        - { text: "Wo sie sich ändert", description: "Nach Abteilung, Linie und Schichtmodell." }
        - { text: "Warum, je Entscheidung", description: "Dieselbe Erklärung wie bei einem produktiven Protokoll." }
  - type: cta
    title: "Sehen Sie Ihre eigenen Entscheidungen erklärt"
    description: "Die Compliance-Diagnose wendet die Regeln auf Ihre Historie an und liefert jeden Befund mit seiner Erklärung."
    primary_action: { text: "Diagnose anfragen", url: "/diagnostic" }
    secondary_action: { text: "Zur Produkttour", url: "/demo" }
---
