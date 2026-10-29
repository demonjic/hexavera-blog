---
title: "MES und Produktionssysteme"
description: "Connect liest Linien- und Auftragspläne aus Ihrem MES. So werden Besetzung und Eignung für Arbeitsplätze gegen den Plan geprüft, nach dem Ihr Werk produziert."
permalink: "/integrations/mes"
slug: "integration-mes"
lang: "de"
id: "page-integration-mes"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Konnektor: Produktion"
    title: "Personalentscheidungen gegen den tatsächlichen Produktionsplan"
    subtitle: "Ihr MES plant Linien und Aufträge. Hexavera liest den Plan, von dem eine Personalentscheidung abhängt, und überlässt die Produktion weiterhin dem MES."
    primary_action: { text: "Über Ihr MES sprechen", url: "/contact" }
    secondary_action: { text: "Alle Integrationen", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "Was in welche Richtung fließt"
    markdown: |
      **Vom MES an Hexavera**

      - Linienpläne und Fertigungsaufträge mit Beginn und Ende.
      - Die Arbeitsplätze, die jede Linie besetzt haben muss.

      **Von Hexavera an das MES**

      - Nichts. Der Konnektor liest ausschließlich.

      Liegt der Plan in Hexavera vor, lässt sich ein Schichtplan auf die Besetzung je Linie prüfen und eine Einteilung an einem Arbeitsplatz gegen die Qualifikationen, die dieser Arbeitsplatz verlangt.
    aside:
      type: record
      title: "MES-Konnektor"
      status: "Geplant"
      tone: info
      rows:
        - { label: "Läuft", value: "Im Cloud-Mandanten (Connect)" }
        - { label: "Richtung", value: "Eingehend, nur lesend" }
        - { label: "Quelle", value: "Wird mit unserem ersten Kunden aus der Lebensmittel- und Getränkeindustrie ausgewählt" }
        - { label: "Meilenstein", value: "Nach M2" }
  - type: checklist
    id: "what-you-configure"
    title: "Was Sie konfigurieren"
    items:
      - text: "Die Quelle"
        description: "Ihr MES oder Produktionsplanungssystem und ein Konto mit reinem Lesezugriff für Hexavera."
      - text: "Linien und Arbeitsplätze"
        description: "Wie das MES Linien und Arbeitsplätze benennt, zugeordnet zu den Standorten und Bereichen in Hexavera."
      - text: "Der Planungshorizont"
        description: "Wie weit im Voraus der Plan gelesen wird und wie oft."
  - type: section
    id: "status"
    title: "Stand"
    markdown: |
      Der MES-Konnektor ist für die Zeit nach Meilenstein M2 geplant. Seine erste Quelle wählen wir gemeinsam mit unserem ersten Kunden aus der Lebensmittel- und Getränkeindustrie aus, denn Produktionssysteme unterscheiden sich von Werk zu Werk stärker als HR- oder Abrechnungssysteme. Die Reihenfolge weiterer Produktionssysteme richtet sich nach dem Kundenbedarf.
  - type: cta
    title: "Welches Produktionssystem betreiben Sie?"
    description: "Nennen Sie uns das System und was Ihre Schichtplaner heute daraus übernehmen."
    primary_action: { text: "Kontakt aufnehmen", url: "/contact" }
    secondary_action: { text: "Lebensmittel und Getränke", url: "/food-beverage" }
---
