---
title: "Hexavera Access: Zutrittskontrolle am Standort"
description: "Türen, Leser, Identmedien, Alarme, Besucher und Wächterrundgänge auf einem Server im Werk. Jeder Durchgang wird erfasst und fließt in Zeit und Compliance ein."
url: "products/access"
slug: "access"
locale: "de"
localization_id: "page-access"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Standortprodukt: Access"
    title: "Zutrittskontrolle mit Nachweisen, die Lohnabrechnung und Auditoren nutzen können"
    subtitle: "Hexavera Access läuft auf einem Server in Ihrem Werk. Das System entscheidet, wer welche Tür wann passiert, erfasst jeden Durchgang und arbeitet weiter, wenn die Verbindung zur Cloud unterbrochen ist."
    highlights:
      - "Türen, Leser und Controller vor Ort"
      - "Karten, PINs, Fingerabdrücke und Gesichter"
      - "Alarme, Besucher und Wächterrundgänge"
    primary_action: { text: "Diagnose anfragen", url: "/diagnostic" }
    secondary_action: { text: "Zur Produkttour", url: "/demo" }
  - type: cards
    eyebrow: "Was Access am Standort leistet"
    title: "Von der Registrierung bis zum Ereignisprotokoll an einer Stelle"
    columns: 3
    items:
      - title: "Personen und Identmedien"
        description: "Personen registrieren, Karten, PINs, Fingerabdrücke und Gesichter ausgeben und entziehen, den Zutritt sofort sperren, wenn jemand das Unternehmen verlässt."
      - title: "Türen, Zutrittsprofile und Zeitprofile"
        description: "Türen, Leser und Controller zu Bereichen zusammenfassen. Zutritts- und Zeitprofile legen fest, welches Identmedium welche Tür zu welchen Uhrzeiten an welchen Tagen öffnet."
      - title: "Geräte"
        description: "Controller einbinden und automatisch erkennen, ihren Zustand überwachen, ihre Uhren synchron halten und sie aus der Konsole neu starten. Unterstützt werden derzeit Hikvision-Controller."
      - title: "Alarme"
        description: "Aufgebrochene Türen, zu lange offene Türen und abgewiesene Identmedien lösen Alarme aus, die Bediener quittieren und mit einer Notiz abschließen."
      - title: "Besucher"
        description: "Besucher erfassen, ihnen für den Besuch ein Identmedium ausgeben und es beim Verlassen wieder einziehen."
      - title: "Wächterrundgänge"
        description: "Rundgänge als Abfolge von Lesern festlegen und sehen, welche Kontrollpunkte wann erreicht wurden."
  - type: split
    eyebrow: "Für wen"
    title: "Der Werkschutz betreibt die Türen, HR und Produktion nutzen, was die Türen erfassen"
    markdown: |
      **Werkschutz und Facility Management** erledigen das Tagesgeschäft: Identmedien, Türen, Alarme, Besucher und Rundgänge. Jede Bedieneraktion setzt eine Berechtigung voraus und wird im Audit-Trail festgehalten.

      **HR und Werkleitung** erhalten ein ehrliches Bild der Durchgänge: wer wann welchen Bereich betreten hat und wo die Daten Lücken haben.

      **Betriebsräte** können einsehen, was zu einem Durchgang gespeichert wird und wer es einsehen darf.
    aside:
      type: record
      title: "Durchgang, Hygieneschleuse B"
      status: "Gewährt"
      tone: success
      rows:
        - { label: "Inhaber", value: "E-1187, Produktion" }
        - { label: "Identmedium", value: "Karte" }
        - { label: "Leser", value: "Schleuse B, Eingangsseite" }
        - { label: "Uhrzeit", value: "Mo. 05:52" }
        - { label: "Zutrittsprofil", value: "High-Care, Frühschicht" }
      caption: "Beispieldaten"
  - type: checklist
    eyebrow: "Was Access erfasst"
    title: "Jeder Durchgang ist eine Angabe mit Quelle"
    description: "Attendance und Govern stützen sich auf diese Ereignisse. Access hält deshalb genau fest, was jedes Ereignis aussagt und was nicht."
    items:
      - text: "Der Durchgang"
        description: "Person, Identmedium, Leser, Tür, Richtung und Uhrzeit, so wie der Controller sie meldet."
      - text: "Abweisungen und Alarme"
        description: "Warum ein Identmedium abgewiesen wurde und wie und von wem ein Alarm bearbeitet wurde."
      - text: "Änderungen"
        description: "Wer wann ein Identmedium, ein Zutrittsprofil oder ein Zeitprofil geändert hat."
      - text: "Lücken"
        description: "Leser, die verstummt sind, Durchgänge ohne Richtung und abweichende Gerätezeiten, aufgeführt im Datenqualitätsbericht."
  - type: section
    eyebrow: "Wie Access Govern versorgt"
    title: "Der Datenqualitätsbericht zeigt, was Türereignisse der Lohnabrechnung sagen können und was nicht"
    markdown: |
      Türereignisse werden oft wie Anwesenheitszeiten behandelt. Das sind sie aber erst, wenn feststeht, welche Leser die Richtung erfassen, welche offline waren und wie weit ihre Uhren abgewichen sind. Der Datenqualitätsbericht wertet Ihre eigenen Durchgänge je Leser und Tag aus und zeigt, welche sich einer Person und einer Richtung zuordnen lassen und welche nicht.

      Auf dieser Grundlage berechnet Attendance die Zeitergebnisse. In Govern werden dieselben Durchgänge zu Eingangsdaten: Eine verweigerte Zutrittsanfrage zum High-Care-Bereich verweist auf den Durchgang und auf den Schulungsnachweis, auf dem die Regel beruht. So lässt sich die Entscheidung später erklären.

      Betreibt Ihr Werk bereits ein Zutrittskontrollsystem, verlangen wir nicht, dass Sie es ersetzen. Sprechen Sie mit uns über eine Anbindung.
  - type: cta
    title: "Beginnen Sie mit dem, was Ihre Türen bereits wissen"
    description: "Fragen Sie eine Compliance-Diagnose an oder sehen Sie sich Access in der Produkttour mit Beispieldaten an."
    primary_action: { text: "Diagnose anfragen", url: "/diagnostic" }
    secondary_action: { text: "Zur Produkttour", url: "/demo" }
---
