---
title: "Andere Zutrittskontrollsysteme"
description: "Sie betreiben bereits ein Zutrittskontrollsystem? Es bleibt. Connect liest Personen, Identmedien und Ereignisse daraus; neue Systeme folgen dem Kundenbedarf."
permalink: "/integrations/access-systems"
slug: "integration-access-systems"
lang: "de"
id: "page-integration-access-systems"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Konnektor: Zutrittssysteme"
    title: "Behalten Sie Ihr bestehendes Zutrittskontrollsystem"
    subtitle: "Betreibt Ihr Werk bereits eine Zutrittskontrolle, verlangt Hexavera nicht, dass Sie sie ersetzen. Connect liest daraus, sodass ihre Ereignisse in dieselben Entscheidungen einfließen."
    primary_action: { text: "Nennen Sie uns Ihr System", url: "/contact" }
    secondary_action: { text: "Alle Integrationen", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "Was in welche Richtung fließt"
    markdown: |
      **Von Ihrem Zutrittssystem an Hexavera**

      - Personen und ihre Identmedien, damit ein Durchgang der richtigen Person zugeordnet wird.
      - Zutrittsereignisse: Durchgänge, Abweisungen und Alarme, mit Leser und Richtung.
      - Status von Lesern und Controllern, damit ein ausgefallener Leser als ausgefallen bekannt ist.

      **Von Hexavera an Ihr Zutrittssystem**

      - Wird je System vereinbart. Ihr Zutrittssystem entscheidet weiterhin, wer welche Tür öffnen darf.
    aside:
      type: record
      title: "Andere Zutrittssysteme"
      status: "Reihenfolge nach Kundenbedarf"
      tone: neutral
      rows:
        - { label: "Läuft", value: "Im Cloud-Mandanten (Connect)" }
        - { label: "Richtung", value: "Eingehend; schreibt nur, wo vereinbart" }
        - { label: "Reihenfolge", value: "Bestimmt durch Kundenanfragen" }
  - type: checklist
    id: "what-you-configure"
    title: "Was Sie konfigurieren"
    items:
      - text: "Die Quelle"
        description: "Den Server Ihres Zutrittssystems und ein Konto für Hexavera, verschlüsselt gespeichert."
      - text: "Leser und Türen"
        description: "Welcher Leser zu welcher Tür und Richtung gehört."
      - text: "Personenabgleich"
        description: "Wie ein Karteninhaber in Ihrem System einer Person in Hexavera zugeordnet wird."
  - type: section
    id: "status"
    title: "Stand"
    markdown: |
      Jeder Zutrittskonnektor beruht auf einem gemeinsamen Schnittstellenvertrag: was das System eines Herstellers kann, je Funktion festgelegt und mit typisierten Ergebnissen. Hikvision ist der erste. Ein weiterer Hersteller kommt hinzu, wenn ein Kunde ihn braucht, und er besteht vor der Auslieferung dieselben Konformitätstests.

      Soll Hexavera die Zutrittskontrolle selbst übernehmen, ist Hexavera Access die Lösung.
  - type: cta
    title: "Welches Zutrittssystem betreiben Sie?"
    description: "Nennen Sie uns das System, seine Version und die Zahl der Standorte, an denen es läuft."
    primary_action: { text: "Kontakt aufnehmen", url: "/contact" }
    secondary_action: { text: "Hexavera Access", url: "/products/access" }
---
