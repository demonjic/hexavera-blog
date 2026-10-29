---
title: "Hexavera Presence: Self-Service am Terminal und im Web"
description: "Mitarbeitende buchen, prüfen Zeitnachweis, Dienstplan und Salden und beantragen Urlaub am Terminal in der Halle oder im Browser. Jeder Antrag wird festgehalten."
url: "products/presence"
slug: "presence"
locale: "de"
localization_id: "page-presence"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Standortprodukt: Presence"
    title: "Mitarbeitende sehen ihre eigene Zeit und handeln selbst, am Terminal oder im Browser"
    subtitle: "Hexavera Presence ist der Self-Service für Beschäftigte in der Produktion und im Büro: Buchungen, Zeitnachweis, Dienstplan, Salden und Abwesenheiten. Presence läuft gemeinsam mit Attendance in Ihrem Werk."
    highlights:
      - "Terminal in der Produktion und Browser"
      - "Ausweis plus PIN vom Standort oder Ausweis plus Gesicht"
      - "Anträge nach denselben Regeln geprüft"
    primary_action: { text: "Diagnose anfragen", url: "/diagnostic" }
    secondary_action: { text: "Zur Produkttour", url: "/demo" }
  - type: cards
    eyebrow: "Was Presence am Standort leistet"
    title: "Was Mitarbeitende erledigen können, ohne im Büro nachzufragen"
    columns: 3
    items:
      - title: "Buchen"
        description: "Kommen und Gehen sowie Beginn und Ende der Pause buchen, am Terminal in der Produktion oder im Browser, sofern das Werk dies zulässt."
      - title: "Zeitnachweis"
        description: "Buchungen und Zeitergebnisse der laufenden Periode einsehen und eine fehlende Buchung melden, die der Vorgesetzte genehmigt."
      - title: "Dienstplan"
        description: "Den veröffentlichten Plan, die eigenen Schichten und Tauschvorgänge einsehen."
      - title: "Salden"
        description: "Urlaubs-, Überstunden- und weitere Salden, so wie Attendance sie berechnet."
      - title: "Abwesenheiten"
        description: "Urlaub beantragen und den Antrag bis zur Entscheidung verfolgen."
      - title: "Schichttausch"
        description: "Eine Schicht anbieten oder übernehmen. Der Tausch wird gegen die Regeln zu Ruhe- und Arbeitszeiten geprüft, bevor er beim Vorgesetzten ankommt."
  - type: split
    eyebrow: "Anmeldung am Terminal"
    title: "Die Personalnummer ist nie das Passwort"
    markdown: |
      Personalnummern stehen auf Ausweisen und in jedem Export. Sie können daher nicht belegen, wer am Terminal steht. Presence erkennt eine Person am Ausweis und an einer PIN, die der Standort vergibt und die der Mitarbeiter bei der ersten Nutzung ändert. Hat sich das Werk für Gesichtserkennung entschieden, ersetzt die Kombination aus Ausweis und Gesicht die PIN.

      Ein Terminal zeigt nur die angemeldete Person an und meldet sie nach kurzer Zeit ohne Eingabe automatisch ab.
    aside:
      type: checklist
      title: "Anmeldung am Terminal"
      items:
        - { text: "Ausweis plus PIN vom Standort", description: "Bei der ersten Nutzung vom Mitarbeiter geändert." }
        - { text: "Oder Ausweis plus Gesicht", description: "Nur wenn sich das Werk für Gesichtserkennung entschieden hat." }
        - { text: "Abmeldung bei Inaktivität", description: "Die nächste Person beginnt mit einem leeren Bildschirm." }
  - type: section
    eyebrow: "Für wen"
    title: "Weniger Rückfragen im Büro und Antworten, die jeder prüfen kann"
    markdown: |
      **Mitarbeitende** sehen dieselben Zahlen, mit denen die Lohnabrechnung arbeiten wird, noch vor dem Periodenabschluss, und können eine fehlende Buchung klären, solange sich das leicht beheben lässt.

      **Vorgesetzte und HR** erhalten Anträge, die bereits geprüft und vollständig sind, statt Zettel und Anrufe.

      **Betriebsräte** sehen, dass jeder Antrag für alle nach denselben schriftlich festgelegten Regeln beurteilt wird.
  - type: section
    eyebrow: "Was Presence erfasst und wie es Govern versorgt"
    title: "Jede Buchung und jeder Antrag ist eine Angabe mit Quelle"
    markdown: |
      Presence speichert jede Buchung mit dem Terminal oder Browser, von dem sie stammt, und jeden Antrag mit der Antwort, der entscheidenden Person und dem Zeitpunkt. Attendance verwendet die Buchungen für die Zeitergebnisse. Greift bei einem Tausch oder Antrag eine Regel, geht das Prüfprotokoll zusammen mit den übrigen an Govern. So lässt sich die Entscheidung dem Mitarbeiter, dem Betriebsrat oder einem Auditor erklären.

      [Wie eine Entscheidung erklärt wird](/explained)
  - type: cta
    title: "Presence mit Beispieldaten erleben"
    description: "Testen Sie das Terminal in der Produkttour oder fragen Sie eine Compliance-Diagnose mit Ihren eigenen Daten an."
    primary_action: { text: "Diagnose anfragen", url: "/diagnostic" }
    secondary_action: { text: "Zur Produkttour", url: "/demo" }
---
