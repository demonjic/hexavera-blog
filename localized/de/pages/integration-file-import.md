---
title: "Dateiimport: Personal, Organisation und Zeit"
description: "Importieren Sie CSV-Dateien mit Personal-, Organisations- und Zeitdaten in Ihren Hexavera-Mandanten, mit Validierung und Bericht über jede abgewiesene Zeile."
permalink: "/integrations/file-import"
slug: "integration-file-import"
lang: "de"
id: "page-integration-file-import"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Konnektor: Dateien"
    title: "Hat ein System keine API, genügt eine Datei"
    subtitle: "Manche Systeme exportieren nur Dateien. Manche Historie existiert nur in Dateien. Der Dateiimport bringt beides in Ihren Mandanten, Zeile für Zeile geprüft."
    primary_action: { text: "Diagnose anfragen", url: "/diagnostic" }
    secondary_action: { text: "Alle Integrationen", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "Was in welche Richtung fließt"
    markdown: |
      **Aus Ihren Dateien an Hexavera**

      - Personal und Organisation: Beschäftigte, Abteilungen, Stellen, Kostenstellen.
      - Zeit: Buchungen, gearbeitete Stunden und Abwesenheiten, auch über viele Jahre zurück.

      **Zurück an Sie**

      - Ein Fehlerbericht. Jede abgewiesene Zeile wird mit Begründung aufgeführt. So beheben Sie den Fehler an der Quelle und importieren erneut.

      Auf der importierten Historie setzt die Compliance-Diagnose auf: Die Regeln werden auf Ihre eigenen vergangenen Daten angewendet.
    aside:
      type: record
      title: "Dateiimport"
      status: "Geplant"
      tone: info
      rows:
        - { label: "Läuft", value: "Im Cloud-Mandanten (Connect)" }
        - { label: "Format", value: "CSV" }
        - { label: "Richtung", value: "Eingehend, mit Fehlerbericht" }
        - { label: "Meilenstein", value: "M2, die erste Auslieferung von Connect" }
  - type: checklist
    id: "what-you-configure"
    title: "Was Sie konfigurieren"
    items:
      - text: "Der Datenbereich"
        description: "Ob eine Datei Personal und Organisation oder Zeitdaten enthält."
      - text: "Die Spaltenzuordnung"
        description: "Welche Spalte die Personalnummer, das Datum, den Beginn und das Ende enthält."
      - text: "Datumsformat und Zeitzone"
        description: "Das Datumsformat und die Zeitzone, in der die Quelle ihre Uhrzeiten geschrieben hat."
      - text: "Was mit einer fehlerhaften Zeile geschieht"
        description: "Abgewiesene Zeilen gelangen nie in den Datenbestand. Sie kommen im Bericht zu Ihnen zurück."
  - type: section
    id: "status"
    title: "Stand"
    markdown: |
      Der Dateiimport ist für Meilenstein M2 geplant, zunächst für Personal, Organisation und Zeithistorie.

      Dateien mit personenbezogenen Daten nehmen wir nur auf Grundlage eines Auftragsverarbeitungsvertrags (AVV) an. Dieser Vertrag wird vor der ersten Datei unterzeichnet.
  - type: cta
    title: "Sie haben jahrelange Zeitdaten in Dateien?"
    description: "Sagen Sie uns, was Sie vorliegen haben und in welchem Format. Wir sagen Ihnen, was die Diagnose daraus lesen kann."
    primary_action: { text: "Diagnose anfragen", url: "/diagnostic" }
    secondary_action: { text: "Kontakt aufnehmen", url: "/contact" }
---
