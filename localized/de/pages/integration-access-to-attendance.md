---
title: "Hexavera Access an Attendance"
description: "Hexavera Access übergibt jeden Durchgang samt markierter Lücken. Attendance liest diese Daten am Standort und macht daraus mit den Schichten Zeitergebnisse."
url: "integrations/access-to-attendance"
slug: "integration-access-to-attendance"
locale: "de"
localization_id: "page-integration-access-to-attendance"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Konnektor: Hexavera-Produkte"
    title: "Von Türereignissen zur Arbeitszeit, mit offen sichtbaren Lücken"
    subtitle: "Access und Attendance laufen nebeneinander an Ihrem Standort. Access übergibt, was an den Türen geschehen ist; Attendance liest es und leitet ab, was es für die Arbeitszeit bedeutet."
    primary_action: { text: "Diagnose anfragen", url: "/diagnostic" }
    secondary_action: { text: "Alle Integrationen", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "Was in welche Richtung fließt"
    markdown: |
      **Von Access an Attendance**

      - Jeder Durchgang: Person, Leser, Tür, Richtung und Uhrzeit.
      - Abdeckung: welche Leser offline waren, welche Ereignisse verloren gingen und wie weit die Uhr jedes Controllers abgewichen ist.

      **Von Attendance an Access**

      - Nichts. Korrekturen der Arbeitszeit erfolgen in Attendance und ändern das Zutrittsprotokoll nicht.

      Weil der Ereignisstrom seine eigenen Lücken kennzeichnet, deutet Attendance einen stummen Leser nie als Person, die zu Hause geblieben ist.
    aside:
      type: record
      title: "Access an Attendance"
      status: "Geplant"
      tone: info
      rows:
        - { label: "Läuft", value: "Am Standort" }
        - { label: "Richtung", value: "Von Access an Attendance" }
        - { label: "Ereignisstrom und Datenqualitätsbericht", value: "M1" }
        - { label: "Attendance liest den Ereignisstrom", value: "M4" }
  - type: checklist
    id: "what-you-configure"
    title: "Was Sie konfigurieren"
    items:
      - text: "Welche Leser zählen"
        description: "Die Leser, deren Durchgänge als Beginn oder Ende der Arbeit gelten, und in welcher Richtung."
      - text: "Schichten"
        description: "Die Schichten und Rotationen, mit denen Attendance die Durchgänge abgleicht."
      - text: "Regeln"
        description: "Rundung, Toleranzzeiten und die Arbeitszeitregeln, die für jeden Standort, jede Abteilung oder Gruppe gelten."
  - type: section
    id: "status"
    title: "Stand"
    markdown: |
      Der Ereignisstrom und der Datenqualitätsbericht sind für Meilenstein M1 geplant, zusammen mit Hexavera Access am Standort. Der Datenqualitätsbericht zeigt je Leser und Tag, was Ihre Türereignisse der Lohnabrechnung sagen können und was nicht. Attendance liest den Ereignisstrom ab Meilenstein M4.
  - type: cta
    title: "Was sagen Ihre Türereignisse der Lohnabrechnung heute?"
    description: "Der Datenqualitätsbericht beantwortet das anhand Ihrer eigenen Ereignisse."
    primary_action: { text: "Kontakt aufnehmen", url: "/contact" }
    secondary_action: { text: "Hexavera Attendance", url: "/products/attendance" }
---
