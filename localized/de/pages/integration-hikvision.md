---
title: "Hikvision-Zutrittskontrolle mit Hexavera Access"
description: "Hexavera Access steuert Hikvision-Zutrittscontroller über ISAPI: Personen, Karten, Zeitprofile und Türbefehle hin, Zutrittsereignisse zurück, an Ihrem Standort."
permalink: "/integrations/hikvision"
slug: "integration-hikvision"
lang: "de"
id: "page-integration-hikvision"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Konnektor: Zutrittshardware"
    title: "Hikvision-Zutrittscontroller, gesteuert von Hexavera Access"
    subtitle: "Hexavera Access arbeitet mit Hikvision-Zutrittscontrollern, die die ISAPI-Schnittstelle bereitstellen. Access läuft auf einem Server an Ihrem Standort und kommuniziert mit den Controllern in Ihrem Netzwerk."
    primary_action: { text: "Über Ihren Standort sprechen", url: "/contact" }
    secondary_action: { text: "Alle Integrationen", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "Was in welche Richtung fließt"
    markdown: |
      **Von Hexavera an die Controller**

      - Personen und ihre Karten sowie Fingerabdrücke oder Gesichter, sofern Ihr Standort diese erfasst.
      - Zutrittsprofile und die zugehörigen Zeitprofile.
      - Türbefehle: einmalig öffnen oder den Modus einer Tür setzen, jeweils gegen die Berechtigung des Bedieners geprüft und protokolliert.
      - Gerätefunktionen: Erkennung, Einbindung, Zustandsprüfung, Zeitsynchronisation und Neustart.

      **Von den Controllern an Hexavera**

      - Zutrittsereignisse: gewährte und verweigerte Durchgänge, Türalarme und Gerätealarme.
      - Gerätestatus, damit ein ausgefallener Controller oder Leser als offline angezeigt wird und nicht als ruhige Tür.

      Die Controller senden ihre Ereignisse aktiv, und Hexavera liest sie zusätzlich anhand ihrer Sequenznummer zurück. Ereignisse, die ein Controller während eines Netzausfalls zwischengespeichert hat, werden so abgeholt, sobald die Verbindung wieder steht.
    aside:
      type: record
      title: "Hikvision-Konnektor"
      status: "Entwickelt"
      tone: success
      rows:
        - { label: "Läuft", value: "Am Standort, mit Hexavera Access" }
        - { label: "Schnittstelle", value: "Hikvision ISAPI" }
        - { label: "Richtung", value: "In beide Richtungen" }
        - { label: "Meilenstein", value: "M1, erstes Standort-Release von Access" }
  - type: checklist
    id: "what-you-configure"
    title: "Was Sie konfigurieren"
    items:
      - text: "Die Controller"
        description: "Die Netzwerkadresse jedes Controllers und das Konto, das Hexavera darauf nutzt. Dieses Konto wird verschlüsselt auf dem Standortserver gespeichert und nie wieder angezeigt."
      - text: "Türen und Leser"
        description: "Welcher Leser zu welcher Tür gehört und in welcher Richtung, damit jeder Durchgang einer Tür und einer Richtung zugeordnet wird."
      - text: "Zutrittsprofile und Zeitprofile"
        description: "Wer welche Türen wann passieren darf."
      - text: "Ereigniszustellung"
        description: "Wohin die Controller ihre Ereignisse senden. Was beim Senden verloren geht, liest Hexavera nach."
      - text: "Verbindungssicherheit"
        description: "Der TLS-Modus der Verbindung zu jedem Controller. Mit Access Release 1 werden PINs und biometrische Templates nur über eine verifizierte TLS-Verbindung übertragen; ein Controller mit reinem HTTP erhält nur Karten."
  - type: section
    id: "status"
    title: "Stand"
    markdown: |
      Der Hikvision-Konnektor ist entwickelt und läuft mit Hikvision-Controllern. Sein erstes Standort-Release erscheint mit Hexavera Access Release 1, Meilenstein M1. Mit Release 1 wird der Konnektor zu einem eigenen Dienst auf dem Standortserver. Dieser Dienst ist der einzige Prozess, der die Controller-Konten hält, und er erreicht die Controller über eine gegenseitig authentifizierte Verbindung.

      Hikvision wird ausschließlich zur Beschreibung der Kompatibilität genannt. Hexavera unterhält keine Partnerschaft mit dem Hersteller.
  - type: cta
    title: "Sie betreiben bereits Hikvision-Controller?"
    description: "Nennen Sie uns die Controllermodelle und die Zahl Ihrer Türen. Wir sagen Ihnen, was Hexavera Access damit leistet."
    primary_action: { text: "Kontakt aufnehmen", url: "/contact" }
    secondary_action: { text: "Hexavera Access", url: "/products/access" }
---
