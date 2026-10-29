---
title: "Hexavera: Personalentscheidungen, die Ihr Werk belegen kann"
description: "Hexavera ist das führende System für Personalentscheidungen in der Produktion: Schicht, Zutritt und Zeit, getroffen, durchgesetzt, belegt und erklärt."
permalink: "/"
slug: "home"
lang: "de"
id: "page-home"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Das führende System für Personalentscheidungen in der Produktion"
    title: "Jede Personalentscheidung getroffen, durchgesetzt, belegt und erklärt"
    subtitle: "Hexavera steuert Zutritt, Zeiterfassung und Self-Service an Ihrem Standort sowie Regeln, Automatisierung und Prognosen in Ihrem Cloud-Mandanten. Sperrt eine Regel eine Schicht oder eine Tür, zeigt das Protokoll, welche Regel gegriffen hat, auf welche Daten sie sich stützt und warum."
    highlights:
      - "Regeln mit hinterlegter Rechtsgrundlage"
      - "Durchgesetzt am Standort, auch ohne Cloud-Verbindung"
      - "Nachvollziehbar für jeden Betriebsrat"
    primary_action: { text: "Diagnose anfragen", url: "/diagnostic" }
    secondary_action: { text: "Zur Produkttour", url: "/demo" }
    aside:
      type: record
      title: "Einteilung Nachtschicht, Linie 3"
      status: "Gesperrt"
      tone: danger
      rows:
        - { label: "Mitarbeiter", value: "E-2041, Verpackung" }
        - { label: "Regel", value: "Tägliche Mindestruhezeit, 11 Std. (§ 5 ArbZG)" }
        - { label: "Letzte Gehen-Buchung", value: "Di. 14:06, Terminal T-04" }
        - { label: "Geplanter Beginn", value: "Di. 22:00, Antrag auf Schichttausch" }
        - { label: "Berechnete Ruhezeit", value: "7 Std. 54 Min." }
        - { label: "Ergebnis", value: "Gesperrt: unter der Mindestruhezeit von 11 Std." }
      caption: "Beispieldaten"
  - type: steps
    eyebrow: "Der Weg einer Entscheidung"
    title: "Jede Entscheidung durchläuft vier Stationen, und jede hinterlässt eine Spur"
    description: "Ihr HR-System, Ihre Lohnabrechnung und Ihr ERP bleiben die führenden Systeme für Personal, Entgelt und Produktion. Hexavera führt den Nachweis der Entscheidungen, die zwischen diesen Systemen fallen."
    items:
      - title: "Getroffen"
        description: "Eine Schichteinteilung, eine Zutrittsberechtigung oder eine Korrektur im Zeitnachweis wird gegen die Regeln geprüft, die für diese Person an diesem Standort und an diesem Tag gelten."
      - title: "Durchgesetzt"
        description: "Verstößt eine Entscheidung gegen eine zwingende Regel, wird sie dort gesperrt, wo sie entsteht. Ruhezeiten und Höchstarbeitszeiten werden am Standort geprüft. Die Sperre hängt also nicht von der Internetverbindung ab."
      - title: "Belegt"
        description: "Jede Prüfung wird mit Regelversion, Parameterwerten, Eingangsdaten und deren Quellen gespeichert. Protokolle werden nur ergänzt, nie überschrieben."
      - title: "Erklärt"
        description: "Jedes Protokoll lässt sich als Erklärung in Klartext öffnen: was entschieden wurde, welche Regel galt, woher ihr Wert stammt und auf welchen Daten das Ergebnis beruht."
  - type: cards
    eyebrow: "Eine Plattform"
    title: "Drei Produkte am Standort, vier Funktionsbereiche in der Cloud"
    description: "Access, Attendance und Presence laufen lokal in jedem Werk. Connect, Govern, Automate und Predict laufen in Ihrem Cloud-Mandanten. Alle schreiben in ein gemeinsames Entscheidungsprotokoll. [So greift die Plattform ineinander](/platform)."
    columns: 4
    items:
      - title: "Access"
        description: "Türen, Leser, Identmedien, Alarme, Besucher und Wächterrundgänge, auf einem Server an Ihrem Standort."
        url: "/products/access"
        link_text: "Mehr zu Access"
      - title: "Attendance"
        description: "Zeiterfassung, Schichtplanung, Korrekturen, Periodenabschluss und Export an die Lohnabrechnung, mit gesetzlichen Regeln, die vor Ort geprüft werden."
        url: "/products/attendance"
        link_text: "Mehr zu Attendance"
      - title: "Presence"
        description: "Self-Service für Mitarbeitende am Terminal oder im Browser: Buchungen, Zeitnachweis, Dienstplan, Salden und Abwesenheiten."
        url: "/products/presence"
        link_text: "Mehr zu Presence"
      - title: "Connect"
        description: "Ihr Cloud-Mandant: Personal-, Zeit- und Zutrittsdaten aus Ihren bestehenden Systemen, bei jedem Datensatz mit Angabe der Quelle."
        url: "/platform#connect"
        link_text: "Mehr zu Connect"
      - title: "Govern"
        description: "Regeln mit ihren Rechtsgrundlagen, Geltungsbereiche, Simulation, Compliance-Nachweise und die darauf aufbauenden Berichte."
        url: "/platform#govern"
        link_text: "Mehr zu Govern"
      - title: "Automate"
        description: "Der nächste Schritt nach einer Entscheidung: eine Genehmigung einholen, eine Person benachrichtigen."
        url: "/platform#automate"
        link_text: "Mehr zu Automate"
      - title: "Predict"
        description: "Vorausschauende Auswertungen auf Basis Ihrer eigenen Historie, dazu Vera, die Assistentin, die Fragen zu den Daten Ihres Mandanten beantwortet."
        url: "/platform#predict"
        link_text: "Mehr zu Predict"
  - type: split
    eyebrow: "Für Betriebsräte"
    title: "Der Betriebsrat sieht die Regel, bevor sie greift"
    markdown: |
      Ein Arbeitszeitsystem, das Beschäftigte sperrt oder markiert, unterliegt der Mitbestimmung des Betriebsrats (in Deutschland nach § 87 BetrVG). Der Betriebsrat sollte daher jede Regel lesen, die Herkunft jedes Werts nachvollziehen und eine Änderung testen können, bevor sie jemanden betrifft.

      In Hexavera sind Regeln Daten und kein Code, den ein Administrator schreibt. Jeder Wert nennt seine Quelle: das Gesetz, den Tarifvertrag oder die Einstellung des Werks. Eine Simulation spielt eine geplante Änderung über vergangene Schichten durch und listet jede Entscheidung auf, die anders ausfallen würde. Kein produktives Protokoll wird dabei verändert.

      [Wie Entscheidungen erklärt und simuliert werden](/explained)
    aside:
      type: checklist
      title: "Was ein Prüfer sieht"
      items:
        - { text: "Die Regel und ihre Rechtsgrundlage", description: "Artikel, Paragraf oder Klausel, gespeichert mit der Regel." }
        - { text: "Jeden Parameter und wer ihn festgelegt hat", description: "Auf Ebene von Gesetz, Tarifvertrag, Unternehmen oder Abteilung." }
        - { text: "Die Eingangsdaten", description: "Jeweils mit dem System und dem Datensatz, aus dem sie stammen." }
        - { text: "Die Wirkung einer Änderung", description: "Eine Simulation über vergangene Entscheidungen, getrennt von den produktiven Protokollen." }
  - type: split
    eyebrow: "Lebensmittel und Getränke"
    title: "Für Werke, die rund um die Uhr produzieren und alles nachweisen müssen"
    markdown: |
      In Werken der Lebensmittel- und Getränkeindustrie treffen Hygienezonen, vollkontinuierliche Schichtmodelle, Saisonspitzen und Leiharbeit zusammen, und jeder dieser Punkte kommt im Audit zur Sprache. Hexavera prüft, wer einen High-Care-Bereich betreten darf, wer welche Schicht übernehmen darf und ob Ruhezeiten und Höchstarbeitszeiten eingehalten wurden. Den Nachweis, den ein Auditor verlangt, hält Hexavera bereit.

      [Hexavera in der Lebensmittel- und Getränkeindustrie](/food-beverage)
    aside_position: start
    aside:
      type: checklist
      title: "Woher die Fragen kommen"
      items:
        - { text: "Hygienezonen und HACCP", description: "Schulungsnachweise entscheiden, wer die Schleuse passiert." }
        - { text: "Dreischicht- und Wochenendmodelle", description: "Ruhezeiten und Arbeitszeiten werden bei jedem Schichttausch geprüft." }
        - { text: "Saisonkräfte und Leiharbeitnehmer", description: "Dieselben Regeln für alle an der Linie." }
  - type: section
    eyebrow: "Sicherheit und Betrieb"
    title: "Ihr Standort läuft eigenständig, Ihr Cloud-Mandant gehört nur Ihnen"
    markdown: |
      Access, Attendance und Presence laufen auf einem Server in jedem Werk. Türen öffnen sich, Buchungen werden erfasst und zwingende Regeln durchgesetzt, auch wenn die Verbindung zur Cloud unterbrochen ist.

      In der Cloud hat jeder Kunde einen eigenen Mandanten mit eigenem Datenbankschema. Jedes Konto meldet sich mit einem zweiten Faktor an, jede Bedieneraktion setzt eine Berechtigung voraus, Zugangsdaten für Konnektoren werden verschlüsselt gespeichert und Änderungen werden im Audit-Trail protokolliert. Wir beanspruchen keine Zertifizierung, die wir nicht besitzen, und beantworten Ihren Sicherheitsfragebogen anhand der tatsächlich umgesetzten Maßnahmen.

      [Sicherheit bei Hexavera](/security)
  - type: cta
    variant: dark
    eyebrow: "Compliance-Diagnose"
    title: "Was Ihre eigene Historie über Ruhezeiten, Arbeitszeiten und Qualifikationen verrät"
    description: "Sie senden uns einen Auszug Ihrer Schicht- und Zeitdaten auf Grundlage eines Auftragsverarbeitungsvertrags (AVV). Wir wenden die Regeln darauf an und gehen jeden Befund mit Ihnen durch, jeweils mit seiner Erklärung."
    primary_action: { text: "Diagnose anfragen", url: "/diagnostic" }
    secondary_action: { text: "Zur Produkttour", url: "/demo" }
---
