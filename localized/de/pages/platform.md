---
title: "Die Hexavera-Plattform: Standort und Cloud-Mandant"
description: "Access, Attendance und Presence laufen in jedem Werk, Connect, Govern, Automate und Predict im Cloud-Mandanten. Alle schreiben in ein Entscheidungsprotokoll."
permalink: "/platform"
slug: "platform"
lang: "de"
id: "page-platform"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Die Plattform"
    title: "Eine Plattform, zwei Hälften: der Standort und der Cloud-Mandant"
    subtitle: "Access, Attendance und Presence laufen auf einem Server in jedem Werk und arbeiten weiter, wenn die Internetverbindung ausfällt. Connect, Govern, Automate und Predict laufen in Ihrem eigenen Cloud-Mandanten. Beide Hälften schreiben in ein gemeinsames Entscheidungsprotokoll. Eine Sperre an der Schleuse und ein Befund im Audit verweisen deshalb auf denselben Nachweis."
    highlights:
      - "Standortsystem vor Ort, eines je Werk"
      - "Cloud-Mandant je Gesellschaft"
      - "Ein Entscheidungsprotokoll für beide"
    primary_action: { text: "Diagnose anfragen", url: "/diagnostic" }
    secondary_action: { text: "Zur Produkttour", url: "/demo" }
  - type: split
    id: "access"
    eyebrow: "Am Standort: Access"
    title: "Access entscheidet, wer welche Tür passiert, und protokolliert jeden Durchgang"
    markdown: |
      Access verwaltet Personen und ihre Identmedien (Karten, PINs, Fingerabdrücke und Gesichter), die Türen und Leser, die sie nutzen, sowie die Zutritts- und Zeitprofile, die festlegen, wann ein Identmedium eine Tür öffnet. Alarme, Besucher und Wächterrundgänge werden am selben Standort auf demselben Server verwaltet.

      Jeder Durchgang wird mit Leser, Richtung und Uhrzeit gespeichert. Attendance und Govern stützen sich auf diese Ereignisse. Deshalb meldet Access auch, was sich aus ihnen nicht ablesen lässt: Leser, die verstummt sind, Durchgänge ohne Richtung, Gerätezeiten, die abweichen.

      [Access im Detail](/products/access)
    aside:
      type: record
      title: "Durchgang, Hygieneschleuse B"
      status: "Verweigert"
      tone: warning
      rows:
        - { label: "Identmedium", value: "Karte, Inhaber E-3310" }
        - { label: "Leser", value: "Schleuse B, Eingangsseite" }
        - { label: "Regel", value: "Zutritt zum High-Care-Bereich nur mit gültiger Hygieneschulung" }
        - { label: "Angabe", value: "Schulung seit 2 Tagen abgelaufen (Schulungsnachweis)" }
      caption: "Beispieldaten"
  - type: section
    id: "attendance"
    eyebrow: "Am Standort: Attendance"
    title: "Attendance macht aus Durchgängen und Buchungen die Grundlage der Lohnabrechnung"
    markdown: |
      Attendance liest die Durchgänge aus Access und die Buchungen aus Presence und berechnet daraus Zeitergebnisse nach Ihren Einstellungen für Rundung, Pausen und Überstunden. Schichtleiter arbeiten mit Schichten und Rotationen, Schichttausch, Abwesenheitsvertretung und einer Besetzungsübersicht und veröffentlichen anschließend den Plan. Korrekturen werden genehmigt, die Periode wird abgeschlossen, und aus der abgeschlossenen Periode entsteht der Export an die Lohnabrechnung.

      Ruhezeiten, tägliche und wöchentliche Höchstarbeitszeiten und vertragliche Grenzen werden vor Ort geprüft, sobald eine Schicht eingeteilt oder getauscht wird. Eine Sperre wartet nicht auf die Cloud.

      [Attendance im Detail](/products/attendance)
  - type: section
    id: "presence"
    eyebrow: "Am Standort: Presence"
    title: "Mit Presence sehen Mitarbeitende ihre eigene Zeit und handeln selbst"
    markdown: |
      Mitarbeitende buchen Kommen und Gehen, sehen Zeitnachweis, Dienstplan und Salden ein und beantragen Urlaub, im Browser oder an einem Terminal in der Produktion. Ein Terminal erkennt eine Person am Ausweis und an einer PIN, die der Standort vergibt und die bei der ersten Nutzung geändert wird, oder am Ausweis und am Gesicht, sofern sich das Werk für Gesichtserkennung entschieden hat. Die Personalnummer ist nie das Passwort.

      [Presence im Detail](/products/presence)
  - type: section
    id: "connect"
    eyebrow: "In der Cloud: Connect"
    title: "Connect führt Ihre Systeme in einem Mandanten zusammen, ohne sie zu ersetzen"
    markdown: |
      Ihr HR-System, Ihre Lohnabrechnung und Ihr ERP bleiben maßgeblich. Connect liest daraus, was die Entscheidungen brauchen (Personal und Organisation, Zeit und Entgelt, Zutritt und Geräte), in Ihren Mandanten ein und speichert bei jedem Datensatz das Quellsystem und die Quell-ID. Die Standortprodukte von Hexavera binden sich ohne Konnektor an. Über einen Dateiimport lassen sich Historie und Systeme ohne Schnittstelle einlesen.

      Jede Gesellschaft ist ein eigener Mandant mit eigenem Datenbankschema, auch wenn ein Konzern ein gemeinsames HR-System betreibt. Ein Mandant enthält nur die Beschäftigten der eigenen Gesellschaft.
  - type: split
    id: "govern"
    eyebrow: "In der Cloud: Govern"
    title: "Govern verwaltet die Regeln und das Protokoll, in das jede Entscheidung geschrieben wird"
    markdown: |
      Govern speichert jede Regel als Daten: was sie prüft, ihre Rechtsgrundlage und ihre Werte auf vier Ebenen (Gesetz, Tarifvertrag, Unternehmen, Abteilung). Eine Abteilung kann eine andere Toleranzzeit haben als der Rest des Werks, ohne dass jemand Code schreibt. Zertifizierungs- und Qualifikationsanforderungen legen fest, wer an einem Arbeitsplatz eingesetzt werden darf.

      Hier treffen die beiden Hälften zusammen. Eine Entscheidung, die am Standort fällt, wird dort geprüft und zuerst in das Protokoll des Standorts geschrieben, danach in Ihren Mandanten. Das Entscheidungsprotokoll ist an beiden Orten identisch: Regelversion, verwendete Werte, Eingangsdaten und Ergebnis. Berichte, Simulationen und Audits greifen auf dieses eine Protokoll zu.

      [Wie eine Entscheidung erklärt wird](/explained)
    aside:
      type: checklist
      title: "In jedem Entscheidungsprotokoll"
      items:
        - { text: "Regelcode und Version" }
        - { text: "Jeder verwendete Wert, mit Ebene und Quelle" }
        - { text: "Eingangsdaten, jeweils mit ihrem Quelldatensatz" }
        - { text: "Der berechnete Wert und das Ergebnis" }
        - { text: "Wo und wann geprüft wurde" }
  - type: section
    id: "automate"
    eyebrow: "In der Cloud: Automate"
    title: "Automate erledigt den Schritt, der auf eine Entscheidung folgt"
    markdown: |
      Eine gesperrte Einteilung braucht Ersatz, eine Korrektur die Genehmigung des Vorgesetzten, eine auslaufende Qualifikation eine Erinnerung. Automate führt diese Folgeschritte nach Vorlagen aus, die Sie anpassen: wer genehmigt, wer benachrichtigt wird und über welchen Kanal. Workflows werden mit jedem Kunden gemeinsam festgelegt, ausgehend von den Entscheidungen, die Govern bereits protokolliert.
  - type: section
    id: "predict"
    eyebrow: "In der Cloud: Predict"
    title: "Predict blickt auf Basis Ihrer Historie nach vorn, Vera beantwortet Fragen"
    markdown: |
      Predict arbeitet mit den geregelten, nachvollziehbaren Daten in Ihrem Mandanten, nie mit denen eines anderen Kunden. Die Modelle werden mit Ihrer eigenen Historie trainiert, zuerst für Abwesenheiten.

      Vera ist die Assistentin in Predict. Fragen Sie sie, wer morgen Nachtschicht hat oder wo die Besetzung knapp ist, und sie antwortet aus den Daten Ihres Mandanten, im Rahmen der Berechtigungen der fragenden Person. Sie liest dieselben Daten wie Ihre Berichte.
---
