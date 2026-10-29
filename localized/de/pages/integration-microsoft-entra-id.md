---
title: "Anmeldung mit Microsoft Entra ID"
description: "Bediener und Beschäftigte melden sich mit ihren Microsoft-Entra-ID-Arbeitskonten an. Rollen bleiben in Hexavera; in Ihr Verzeichnis schreibt Hexavera nie."
permalink: "/integrations/microsoft-entra-id"
slug: "integration-microsoft-entra-id"
lang: "de"
id: "page-integration-microsoft-entra-id"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Konnektor: Identität"
    title: "Anmeldung mit den Arbeitskonten, die Sie bereits verwalten"
    subtitle: "Der Identitätsdienst von Hexavera arbeitet mit Microsoft Entra ID als Anmeldeanbieter. Beschäftigte nutzen ihr Arbeitskonto; Konten werden weiterhin in Ihrem Verzeichnis angelegt und geschlossen."
    primary_action: { text: "Über die Anmeldung sprechen", url: "/contact" }
    secondary_action: { text: "Sicherheit", url: "/security" }
  - type: split
    id: "what-flows"
    title: "Was in welche Richtung fließt"
    markdown: |
      **Von Entra ID an Hexavera**

      - Die Anmeldung selbst: Entra ID bestätigt, wer die Person ist.
      - Die Claims, die Hexavera braucht, um das Konto einer Person in Ihrem Mandanten zuzuordnen.

      **Von Hexavera an Entra ID**

      - Nichts. Hexavera legt in Ihrem Verzeichnis keine Konten oder Gruppen an und ändert oder löscht keine.

      Rollen und Berechtigungen werden in Hexavera geführt. Was eine Person tun darf, wird daher an einer Stelle entschieden und dort protokolliert.
    aside:
      type: record
      title: "Microsoft Entra ID"
      status: "Geplant"
      tone: info
      rows:
        - { label: "Läuft", value: "Identitätsdienst von Hexavera" }
        - { label: "Protokoll", value: "OpenID Connect" }
        - { label: "Richtung", value: "Nur Anmeldung" }
        - { label: "Meilenstein", value: "M2, die erste Auslieferung von Connect" }
  - type: checklist
    id: "what-you-configure"
    title: "Was Sie konfigurieren"
    items:
      - text: "Eine App-Registrierung"
        description: "In Ihrem Entra-Mandanten für Hexavera registriert."
      - text: "Ihr Verzeichnis"
        description: "Die ID Ihres Entra-Mandanten. Hexavera akzeptiert Anmeldungen nur aus diesem Verzeichnis."
      - text: "Ihre Domains"
        description: "Die E-Mail-Domains, die nachweislich Ihnen gehören, damit Anmeldungen für diese Domains an Ihr Verzeichnis weitergeleitet werden."
      - text: "Wer sich anmelden darf"
        description: "Welche Personen in Ihrem Hexavera-Mandanten sich mit Entra ID anmelden und welche Rollen sie in Hexavera haben."
  - type: section
    id: "status"
    title: "Stand"
    markdown: |
      Die Anmeldung mit Entra ID ist für Meilenstein M2 geplant. Bis dahin meldet sich jedes Konto beim eigenen Identitätsdienst von Hexavera mit einem zweiten Faktor oder einem Passkey an.

      Das Schreiben in Ihr Verzeichnis, etwa das Anlegen von Konten für neue Beschäftigte, ist Provisionierung. Sie gehört nicht zu diesem Konnektor und wird bei Bedarf gesondert vereinbart.

      Microsoft und Entra werden ausschließlich zur Beschreibung der Kompatibilität genannt. Hexavera unterhält keine Partnerschaft mit Microsoft.
  - type: cta
    title: "Planen Sie die Anmeldung mit Ihrem Identitätsteam"
    description: "Wir gehen mit der Leitung Ihres Identitätsmanagements Registrierung, Domains und Rollen durch, bevor irgendetwas eingeschaltet wird."
    primary_action: { text: "Kontakt aufnehmen", url: "/contact" }
    secondary_action: { text: "Alle Integrationen", url: "/integrations" }
---
