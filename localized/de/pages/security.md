---
title: "Sicherheit: die Maßnahmen, wie sie umgesetzt sind"
description: "Wie Hexavera Personaldaten schützt: Betrieb, Mandantentrennung, Anmeldung mit zweitem Faktor, Berechtigungen, Verschlüsselung, Audit-Trail und Datenstandort."
url: "security"
slug: "security"
locale: "de"
localization_id: "page-security"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Sicherheit"
    title: "Maßnahmen, die ein Sicherheitsprüfer nachprüfen kann"
    subtitle: "Diese Seite führt die Maßnahmen auf, die Hexavera heute umgesetzt hat, und die Maßnahmen im Lieferplan mit ihrem Meilenstein. Nichts davon ist ein Versprechen, das wir Ihnen nicht belegen können."
    primary_action: { text: "Fragebogen senden", url: "/contact" }
    secondary_action: { text: "Datenschutzerklärung", url: "/privacy" }
  - type: split
    id: "deployment"
    title: "Wo Hexavera läuft"
    markdown: |
      **Am Standort.** Access, Attendance und Presence laufen auf einem Server in Ihrem Werk, in Ihrem Netzwerk. Ein Standortserver enthält genau einen Mandanten. Hexavera Access arbeitet weiter, wenn die Verbindung zur Cloud unterbrochen ist; Türen, Identmedien und Ereignisse hängen nicht von ihr ab.

      **Im Cloud-Mandanten.** Connect, Govern, Automate und Predict laufen in einem Cloud-Mandanten, einem je Gesellschaft. Ein Standort kann eigenständig ohne jeden Cloud-Mandanten betrieben oder mit einem verbunden werden.
    aside:
      type: checklist
      title: "Heute umgesetzt"
      items:
        - text: "Zweiter Faktor"
          description: "Für jedes Konto, mit Passkeys"
        - text: "Berechtigungen"
          description: "Hinter jeder Bedieneraktion"
        - text: "Mandantentrennung"
          description: "Ein Datenbankschema je Cloud-Mandant"
        - text: "Audit-Trail"
          description: "Anmeldungen und Bedieneraktionen protokolliert"
  - type: cards
    id: "controls"
    title: "Die Maßnahmen"
    columns: 3
    items:
      - title: "Mandantentrennung"
        description: "In der Cloud liegen die Daten jedes Mandanten in einem eigenen Datenbankschema mit generiertem Namen. Ein Standortserver enthält einen Mandanten. In einem Konzern verwaltet der Administrator der Muttergesellschaft die Gesellschaften unter ihr und sonst nichts."
      - title: "Identität und Anmeldung"
        description: "Jedes Konto meldet sich über den eigenen Identitätsdienst von Hexavera mit einem zweiten Faktor oder einem Passkey an. Sitzungen sind zeitlich begrenzt und lassen sich zentral beenden. Die Anmeldung mit Microsoft Entra ID ist für M2 geplant."
      - title: "Berechtigungen"
        description: "Rollenbasierte Berechtigungen stehen hinter jeder Bedieneraktion und werden bei jeder Anfrage auf dem Server geprüft, nicht nur in der Oberfläche."
      - title: "Verschlüsselung"
        description: "Der Datenverkehr zwischen den Diensten von Hexavera ist verschlüsselt. Die Zugangsdaten, mit denen Hexavera Ihre Systeme erreicht, werden verschlüsselt gespeichert. Mit Access Release 1 (M1) werden Controller über eine gegenseitig authentifizierte Verbindung angesprochen, und PINs und biometrische Templates werden nur über verifiziertes TLS übertragen."
      - title: "Audit-Trail"
        description: "Anmeldungen und Bedieneraktionen werden mit handelnder Person und Zeitpunkt protokolliert. Mit M3 wird jede Regelentscheidung mit den verwendeten Eingangsdaten in einem Protokoll gespeichert, das nur ergänzt werden kann."
      - title: "Vera, die Assistentin"
        description: "Vera liest Mandantendaten über dieselbe API und mit denselben Berechtigungen wie die fragende Person. Sie sieht nichts, was diese Person nicht selbst öffnen könnte."
  - type: section
    id: "data-residency"
    title: "Wo Ihre Daten liegen"
    markdown: |
      - **Standortdaten bleiben auf Ihrem Server.** Zutrittsereignisse, Identmedien und der Audit-Trail des Standorts werden am Standort gespeichert. Ein eigenständiger Standort sendet nichts in die Cloud.
      - **Der Cloud-Mandant läuft in einer EU-Region.** Der erste produktive Mandant ist für Meilenstein M2 in einer EU-Region geplant.
      - **Jede Gesellschaft behält ihre eigenen Daten.** Nutzt ein Konzern ein gemeinsames HR-System, wird die Anbindung jeder Gesellschaft bereits an der Quelle gefiltert (M2). Ein Mandant enthält so nie die Beschäftigten einer anderen Gesellschaft.
      - **Personenbezogene Daten eines Interessenten** nehmen wir für die Compliance-Diagnose nur auf Grundlage eines Auftragsverarbeitungsvertrags (AVV) an, der vor der ersten Datei unterzeichnet wird.

      Für Ihre Personaldaten gilt die DSGVO. Fällt Ihr Werk unter NIS2, wird Ihre Lieferantenbewertung nach diesen Maßnahmen fragen, und wir beantworten sie auf dieser Grundlage.
  - type: section
    id: "certification"
    title: "Zertifizierung"
    markdown: |
      Hexavera besitzt heute keine Sicherheitszertifizierung und kein Testat, und wir behaupten auch keines. Senden Sie uns Ihren Sicherheitsfragebogen, und wir beantworten ihn anhand der tatsächlich umgesetzten Maßnahmen. Ändert sich unser Zertifizierungsstatus, veröffentlichen wir das hier.
  - type: section
    id: "responsible-disclosure"
    title: "Verantwortungsvolle Offenlegung"
    markdown: |
      Wenn Sie glauben, eine Schwachstelle in Hexavera oder auf dieser Website gefunden zu haben, teilen Sie uns dies bitte über das [Kontaktformular](/contact) mit und beginnen Sie Ihre Nachricht mit „Security“. Beschreiben Sie, was Sie gefunden haben und wie es sich reproduzieren lässt.

      Bitte geben Sie uns angemessen Zeit, die Schwachstelle zu untersuchen und zu beheben, bevor Sie sie veröffentlichen. Greifen Sie bei Ihren Tests nicht auf fremde Daten zu und ändern oder löschen Sie keine Daten, die Ihnen nicht gehören. Wir melden uns, um die nächsten Schritte mit Ihnen abzustimmen.
  - type: cta
    title: "Prüfen Sie unsere Maßnahmen mit Ihrem Sicherheitsteam"
    description: "Wir erläutern der Leitung Ihrer IT-Sicherheit die Architektur und beantworten Ihren Fragebogen anhand der tatsächlich umgesetzten Maßnahmen."
    primary_action: { text: "Kontakt aufnehmen", url: "/contact" }
    secondary_action: { text: "Integrationen", url: "/integrations" }
---
