---
title: "Lohnabrechnung: Stunden mit Belegen in Ihrem Format"
description: "Hexavera liefert der Lohnabrechnung zuerst einen Auszug der Zutrittsereignisse je Periode, danach genehmigte Zeitergebnisse im Format Ihres Abrechnungssystems."
permalink: "/integrations/payroll"
slug: "integration-payroll"
lang: "de"
id: "page-integration-payroll"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Konnektor: Lohnabrechnung"
    title: "Die Lohnabrechnung rechnet weiter ab. Hexavera liefert die Stunden."
    subtitle: "Ihr Abrechnungssystem bleibt. Hexavera übergibt ihm je Periode, was es braucht, zusammen mit den Belegen, die zeigen, woher jede Zahl stammt."
    primary_action: { text: "Über Ihre Lohnabrechnung sprechen", url: "/contact" }
    secondary_action: { text: "Alle Integrationen", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "Was in welche Richtung fließt"
    markdown: |
      Alles fließt in eine Richtung, von Hexavera an die Lohnabrechnung, und zwar in zwei Stufen.

      **Stufe 1: der Auszug der Zutrittsereignisse (M2)**

      - Ein dokumentierter, versionierter Auszug der Zutrittsereignisse je Abrechnungsperiode.
      - Dazu der Datenqualitätsbericht: welche Durchgänge sich einer Person und einer Richtung zuordnen lassen, welche Leser offline waren und was die Ereignisse der Lohnabrechnung nicht sagen können.

      **Stufe 2: Zeitergebnisse aus Attendance (M4)**

      - Gearbeitete Stunden je Person und Tag, mit Rundung und den am Standort angewandten Arbeitszeitregeln.
      - Erst nachdem Korrekturen erfolgt sind und die Periode mit Genehmigung abgeschlossen wurde.
      - Im Dateiformat Ihres Abrechnungssystems.
    aside:
      type: record
      title: "Lohnabrechnung"
      status: "Geplant"
      tone: info
      rows:
        - { label: "Richtung", value: "Ausgehend, an die Lohnabrechnung" }
        - { label: "Stufe 1", value: "Auszug der Zutrittsereignisse, M2" }
        - { label: "Stufe 2", value: "Zeitergebnisse aus Attendance, M4" }
        - { label: "Format", value: "Das Importformat Ihrer Lohnabrechnung" }
  - type: checklist
    id: "what-you-configure"
    title: "Was Sie konfigurieren"
    items:
      - text: "Die Abrechnungsperiode"
        description: "Wöchentlich, zweiwöchentlich oder monatlich, und der Tag, an dem sie schließt."
      - text: "Personalnummern"
        description: "Wie eine Person in Hexavera der Person in der Lohnabrechnung zugeordnet wird."
      - text: "Lohnarten"
        description: "Welches Zeitergebnis auf welche Lohnart geht: Normalstunden, Überstunden, Nachtarbeit, Abwesenheit."
      - text: "Übergabe"
        description: "Wohin die Datei geht und wer die Periode genehmigt, bevor sie gesendet wird."
  - type: section
    id: "status"
    title: "Stand"
    markdown: |
      Der Auszug der Zutrittsereignisse ist für Meilenstein M2 geplant. Zeitergebnisse im Format Ihrer Lohnabrechnung folgen mit Attendance in Meilenstein M4. Das erste Exportformat ist das des Abrechnungssystems unseres ersten Attendance-Kunden; die Reihenfolge weiterer Formate richtet sich nach dem Kundenbedarf.

      Türereignisse allein sind keine Arbeitszeit. Der Auszug sagt das ausdrücklich, und der Datenqualitätsbericht zeigt, wo die Lücken liegen. Erst Attendance macht aus Ereignissen und Schichten Stunden, auf die sich die Lohnabrechnung verlassen kann.
  - type: cta
    title: "Welche Lohnabrechnung nutzen Sie?"
    description: "Nennen Sie uns das System und die Datei, die es importiert. Wir sagen Ihnen, an welcher Stelle der Reihenfolge es steht."
    primary_action: { text: "Kontakt aufnehmen", url: "/contact" }
    secondary_action: { text: "Hexavera Attendance", url: "/products/attendance" }
---
