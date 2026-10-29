---
title: "Integrationen: Ihre Systeme bleiben, Hexavera bindet sie an"
description: "Hexavera bindet HR-System, Lohnabrechnung, ERP, Zutrittshardware, Identitätsdienst und MES an. Sie bleiben; der Nachweis jeder Entscheidung liegt in Hexavera."
url: "integrations"
slug: "integrations"
locale: "de"
localization_id: "page-integrations"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Integrationen"
    title: "Ihre Systeme bleiben. Hexavera bindet sie an."
    subtitle: "HR, Lohnabrechnung, ERP, Zutrittshardware, Identitätsdienste und Produktionssysteme bleiben maßgeblich für die Daten, die sie führen. Hexavera führt den Nachweis der Personalentscheidungen, die auf Grundlage dieser Daten getroffen werden."
    primary_action: { text: "Diagnose anfragen", url: "/diagnostic" }
    secondary_action: { text: "Über Ihre Systeme sprechen", url: "/contact" }
  - type: cards
    id: "systems-that-stay"
    title: "Die Systeme, die bleiben"
    description: "Hexavera ersetzt kein führendes System. Es liest, was eine Entscheidung braucht, und schreibt nur das zurück, was Sie vereinbaren."
    columns: 3
    items:
      - title: "HR-System"
        description: "Personen, Beschäftigungsverhältnisse, Organisation und Stellen bleiben in Ihrem HR-System. Hexavera liest sie und hält sie aktuell."
      - title: "Lohnabrechnung"
        description: "Die Lohnabrechnung rechnet weiter die Entgelte ab. Hexavera liefert ihr die Stunden und die Belege dazu, in einem Format, das Ihr Abrechnungssystem verarbeitet."
      - title: "ERP"
        description: "Kostenstellen und Unternehmensstruktur bleiben in Ihrem ERP- oder HR-System. Hexavera nutzt sie, um Regeln und Berichte zuzuordnen."
      - title: "Zutrittshardware"
        description: "Türcontroller und Leser bleiben, wo sie sind. Hexavera Access steuert sie, oder Connect liest aus dem Zutrittssystem, das Sie bereits betreiben."
      - title: "Identität"
        description: "Beschäftigte melden sich mit den Arbeitskonten an, die Ihre Organisation bereits verwaltet. Rollen und Berechtigungen werden in Hexavera geführt."
      - title: "MES"
        description: "Produktionssysteme planen weiterhin Linien und Aufträge. Hexavera liest die Pläne, von denen eine Personalentscheidung abhängt."
  - type: steps
    id: "how-connect-works"
    title: "So funktioniert Connect"
    description: "Connect ist der Teil des Cloud-Mandanten, der mit Ihren anderen Systemen kommuniziert."
    items:
      - title: "Verbinden"
        description: "Ein Konnektor greift mit Zugangsdaten, die Sie eigens dafür ausstellen, auf genau ein System zu. Hexavera speichert diese Zugangsdaten verschlüsselt."
      - title: "Zuordnen"
        description: "Sie ordnen Gesellschaften, Schlüssel und Felder der Quelle den Datenbereichen von Hexavera zu, etwa Personal und Organisation oder Zeit und Entgelt."
      - title: "Synchronisieren"
        description: "Jeder Synchronisationslauf wird protokolliert: was eingegangen ist, was sich geändert hat und was abgewiesen wurde. So kann ein Prüfer jeden Wert bis zu seiner Quelle zurückverfolgen."
      - title: "Entscheiden"
        description: "Die Regeln laufen auf den synchronisierten Daten. Die Entscheidung, ihre Eingangsdaten und ihre Erklärung werden in Hexavera gespeichert, neben den Quell-IDs, aus denen sie stammen."
  - type: section
    id: "record-stays"
    title: "Der Nachweis bleibt in Hexavera"
    markdown: |
      Ein Quellsystem teilt Hexavera mit, was über eine Person, eine Schicht oder eine Tür zutrifft. Hexavera hält fest, was daraus entschieden wurde: wer eingelassen wurde, welche Stunden zählen, welche Einteilung gesperrt wurde und nach welcher Regel.

      Dieses Entscheidungsprotokoll wird nicht in die Quellsysteme zurückgeschrieben. Es bleibt in Ihrem Hexavera-Mandanten, wo Betriebsrat, Auditor oder Ihr eigenes Team es lesen können. Jeder Mandant gehört genau einer Gesellschaft, auch wenn ein Konzern ein gemeinsames HR-System nutzt.
  - type: cards
    id: "connectors"
    title: "Konnektoren"
    description: "Jede Seite nennt, was in welche Richtung fließt, was Sie konfigurieren und wie der Stand ist. **Geplant** nennt den Liefermeilenstein: M1 Access am Standort, M2 die erste Auslieferung von Connect, M3 die Compliance-Diagnose, M4 Attendance und Presence, M5 Govern."
    columns: 3
    items:
      - title: "Hikvision-Zutrittskontrolle"
        description: "Personen, Karten und Zeitprofile an die Controller, Zutrittsereignisse zurück. Gesteuert von Hexavera Access am Standort."
        url: "/integrations/hikvision"
        link_text: "Hikvision-Konnektor"
        items: ["Entwickelt; erstes Standort-Release mit M1"]
      - title: "Hexavera Access an Attendance"
        description: "Der Strom der Zutrittsereignisse, mit gekennzeichneten Lücken, als Grundlage für die Zeitergebnisse."
        url: "/integrations/access-to-attendance"
        link_text: "Access an Attendance"
        items: ["Geplant: M1 und M4"]
      - title: "Andere Zutrittssysteme"
        description: "Behalten Sie Ihr bestehendes Zutrittskontrollsystem. Connect liest Personen, Identmedien und Ereignisse daraus."
        url: "/integrations/access-systems"
        link_text: "Andere Zutrittssysteme"
        items: ["Reihenfolge nach Kundenbedarf"]
      - title: "SAP SuccessFactors"
        description: "Personen, Organisation, Stellen, Kostenstellen und Zeitdaten hinein, Zeitdaten zurück."
        url: "/integrations/sap-successfactors"
        link_text: "SAP-SuccessFactors-Konnektor"
        items: ["In Entwicklung; geplant: M2"]
      - title: "Microsoft Entra ID"
        description: "Anmeldung mit den Arbeitskonten Ihrer Organisation. Hexavera schreibt nicht in Ihr Verzeichnis."
        url: "/integrations/microsoft-entra-id"
        link_text: "Anmeldung mit Microsoft Entra ID"
        items: ["Geplant: M2"]
      - title: "Dateiimport"
        description: "CSV-Dateien für Personal, Organisation und Zeit, mit Validierung und einem Bericht über jede abgewiesene Zeile."
        url: "/integrations/file-import"
        link_text: "Dateiimport"
        items: ["Geplant: M2"]
      - title: "Lohnabrechnung"
        description: "Zuerst ein Auszug der Zutrittsereignisse je Abrechnungsperiode, danach Zeitergebnisse im Format Ihrer Lohnabrechnung."
        url: "/integrations/payroll"
        link_text: "Export an die Lohnabrechnung"
        items: ["Geplant: M2 und M4"]
      - title: "MES und Produktionssysteme"
        description: "Linien- und Auftragspläne hinein, damit Besetzung und Eignung für Arbeitsplätze gegen die tatsächliche Planung geprüft werden."
        url: "/integrations/mes"
        link_text: "MES-Konnektor"
        items: ["Geplant nach M2"]
  - type: section
    id: "further-connectors"
    title: "Weitere Konnektoren"
    markdown: |
      Wir entwickeln Konnektoren für eine Branche, die Lebensmittel- und Getränkeindustrie, und wir setzen sie sauber um, bevor wir weitere bauen. Die Reihenfolge weiterer Konnektoren richtet sich nach dem Kundenbedarf. Betreiben Sie ein System, das hier nicht aufgeführt ist, nennen Sie uns das System und was Sie davon brauchen. Ihre Anfrage wird festgehalten und fließt in die Festlegung der Reihenfolge ein.

      Herstellernamen auf diesen Seiten beschreiben ausschließlich die Kompatibilität. Sie bedeuten weder eine Partnerschaft noch eine Zertifizierung noch einen Marktplatzeintrag.
  - type: cta
    title: "Erfassen Sie Ihre Systemlandschaft mit uns"
    description: "Bringen Sie die Liste der Systeme in Ihrem Werk mit. Wir sagen Ihnen, was heute angebunden werden kann, was geplant ist und was für Sie entwickelt würde."
    primary_action: { text: "Diagnose anfragen", url: "/diagnostic" }
    secondary_action: { text: "Kontakt aufnehmen", url: "/contact" }
---
