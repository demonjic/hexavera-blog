---
title: "Konnektor für SAP SuccessFactors"
description: "Connect liest Personal, Organisation, Stellen, Kostenstellen und Zeitdaten aus SAP SuccessFactors in Ihren Hexavera-Mandanten und schreibt Zeitdaten zurück."
url: "integrations/sap-successfactors"
slug: "integration-sap-successfactors"
locale: "de"
localization_id: "page-integration-sap-successfactors"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Konnektor: HR-System"
    title: "SAP SuccessFactors bleibt Ihr führendes HR-System"
    subtitle: "Connect arbeitet über die OData-API mit SAP SuccessFactors. Ihre HR-Daten bleiben dort maßgeblich; Hexavera liest, was Personalentscheidungen brauchen."
    primary_action: { text: "Über Ihre Systemlandschaft sprechen", url: "/contact" }
    secondary_action: { text: "Alle Integrationen", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "Was in welche Richtung fließt"
    markdown: |
      **Von SuccessFactors an Hexavera**

      - Personen und ihre Beschäftigungsdaten.
      - Die Organisation: Gesellschaften, Abteilungen und Stellen.
      - Kostenstellen.
      - Vergütungsdaten, sofern Ihr Vertrag den Datenbereich Zeit und Entgelt umfasst.
      - Zeitdaten, die in SuccessFactors geführt werden.

      **Von Hexavera an SuccessFactors**

      - Zeitdaten, zurückgeschrieben als externe Zeitdaten.

      Zutritt, Regeln und Entscheidungen werden nicht in SuccessFactors geschrieben. Sie bleiben in Hexavera.
    aside:
      type: record
      title: "Konnektor für SAP SuccessFactors"
      status: "In Entwicklung"
      tone: info
      rows:
        - { label: "Läuft", value: "Im Cloud-Mandanten (Connect)" }
        - { label: "Schnittstelle", value: "SuccessFactors OData API" }
        - { label: "Richtung", value: "Überwiegend eingehend; Zeitdaten ausgehend" }
        - { label: "Meilenstein", value: "M2, die erste Auslieferung von Connect" }
  - type: checklist
    id: "what-you-configure"
    title: "Was Sie konfigurieren"
    items:
      - text: "Der API-Server"
        description: "Die SuccessFactors-API-Adresse Ihres Rechenzentrums und Ihre Company ID."
      - text: "Der OAuth-Client"
        description: "Ein OAuth-2.0-Client, den Sie in SuccessFactors für Hexavera registrieren. Seine Zugangsdaten werden verschlüsselt gespeichert. Verlangt Ihr Konzern den SAML Bearer Grant, kommt er mit M2 hinzu."
      - text: "Ihre Gesellschaft"
        description: "Die Gesellschaft, deren Beschäftigte dieser Mandant erhält. Ab M2 wird der Filter an der Quelle angewendet, sodass ein Mandant nie Datensätze einer anderen Gesellschaft enthält."
      - text: "Die Datenbereiche"
        description: "Welche Bereiche Sie synchronisieren: Personal und Organisation oder zusätzlich Zeit und Entgelt."
      - text: "Der Zeitplan"
        description: "Wie oft die Verbindung synchronisiert. Jeder Lauf wird mit den Änderungen und den abgewiesenen Datensätzen protokolliert."
  - type: section
    id: "groups"
    title: "Konzerne mit einem gemeinsamen SuccessFactors"
    markdown: |
      Viele Konzerne betreiben eine SuccessFactors-Instanz für mehrere Gesellschaften. In Hexavera ist jede Gesellschaft ein eigener Mandant. Jeder Mandant hat eine eigene Verbindung, gefiltert auf die eigene Gesellschaft. So landen die HR-Daten einer Gesellschaft nie im Mandanten einer anderen.
  - type: section
    id: "status"
    title: "Stand"
    markdown: |
      Der Konnektor ist in Entwicklung: Das Lesen und das Zurückschreiben der Zeitdaten sind bereits umgesetzt. Die produktive Auslieferung ist für Meilenstein M2 geplant, mit regelmäßigem Zeitplan, Filterung an der Quelle sowie Konfliktprüfung und Synchronisationsverlauf in der Oberfläche.

      SAP und SuccessFactors werden ausschließlich zur Beschreibung der Kompatibilität genannt. Hexavera unterhält keine Partnerschaft mit SAP.
  - type: cta
    title: "Sie nutzen SuccessFactors konzernweit?"
    description: "Zeigen Sie uns, wie Ihre Gesellschaften in SuccessFactors angelegt sind. Wir zeigen Ihnen, wie sich Mandanten und Verbindungen darauf abbilden würden."
    primary_action: { text: "Kontakt aufnehmen", url: "/contact" }
    secondary_action: { text: "Diagnose anfragen", url: "/diagnostic" }
---
