---
title: "Hexavera Attendance: Zeit, Schichten und Lohnexport"
description: "Zeiterfassung, Schichten, Korrekturen, Periodenabschluss und Lohnexport im Werk. Ruhe- und Höchstarbeitszeiten werden vor Ort geprüft, bevor die Schicht steht."
permalink: "/products/attendance"
slug: "attendance"
lang: "de"
id: "page-attendance"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Standortprodukt: Attendance"
    title: "Von der Buchung bis zur Lohnabrechnung, mit geprüften Regeln auf dem ganzen Weg"
    subtitle: "Hexavera Attendance läuft in Ihrem Werk. Das System macht aus Durchgängen und Buchungen Zeitergebnisse, plant und veröffentlicht Schichten, schließt die Periode ab und erstellt den Export an die Lohnabrechnung. Ruhezeiten und Höchstarbeitszeiten werden vor Ort geprüft, bevor eine Schicht eingeteilt wird."
    highlights:
      - "Schichten, Rotationen, Schichttausch und Abwesenheitsvertretung"
      - "Korrekturen und Periodenabschluss mit Genehmigung"
      - "Gesetzliche Regeln durchgesetzt, auch ohne Cloud-Verbindung"
    primary_action: { text: "Diagnose anfragen", url: "/diagnostic" }
    secondary_action: { text: "Zur Produkttour", url: "/demo" }
  - type: steps
    eyebrow: "Was Attendance am Standort leistet"
    title: "Vier Stufen vor der Lohnabrechnung, jede mit ihrer Historie"
    items:
      - title: "Erfassen"
        description: "Durchgänge kommen aus Hexavera Access, Buchungen von Presence-Terminals und aus dem Browser. Jede Angabe behält ihre Quelle: den Leser, das Terminal, die Person."
      - title: "Berechnen"
        description: "Die Zeitergebnisse folgen Ihren Einstellungen für Schichten, Rundung, Pausen, Überstunden und Abwesenheiten. Eine Abteilung kann eine eigene Toleranzzeit haben, ohne dass sich für den Rest des Werks etwas ändert."
      - title: "Korrigieren und genehmigen"
        description: "Fehlende Buchungen und Abweichungen gehen an den Vorgesetzten. Jede Korrektur bewahrt den ursprünglichen Wert, die Änderung, den Grund und den Genehmigenden."
      - title: "Abschließen und exportieren"
        description: "Aus der abgeschlossenen Periode entsteht der Export im Format Ihres Lohnabrechnungssystems. In einer abgeschlossenen Periode ändert sich nichts, ohne dass sie nachvollziehbar wieder geöffnet wird."
  - type: split
    eyebrow: "Schichten"
    title: "Schichten planen, die die Regeln bereits geprüft haben"
    markdown: |
      Schichtleiter legen Schichten und Rotationen an, teilen Personen ein, nehmen Tauschanfragen an, organisieren Vertretungen bei Abwesenheit und veröffentlichen dann den Plan. Die Besetzungsübersicht zeigt, wo eine Linie unterbesetzt ist, bevor die Schicht beginnt.

      Jede Einteilung und jeder Tausch wird noch im selben Moment gegen Ruhezeiten, tägliche und wöchentliche Höchstarbeitszeiten und vertragliche Grenzen geprüft. Ein Tausch, der jemandem zu wenig Ruhezeit ließe, wird gesperrt, und der Schichtleiter sieht den Grund.
    aside:
      type: record
      title: "Tauschantrag SW-118"
      status: "Gesperrt"
      tone: danger
      rows:
        - { label: "Beantragt", value: "E-2041 übernimmt die Nachtschicht am Dienstag, Linie 3" }
        - { label: "Regel", value: "Tägliche Mindestruhezeit, 11 Std." }
        - { label: "Letzte Gehen-Buchung", value: "Di. 14:06" }
        - { label: "Ruhezeit bis Schichtbeginn", value: "7 Std. 54 Min." }
        - { label: "Nächster Schritt", value: "Schicht der nächsten geeigneten Person anbieten" }
      caption: "Beispieldaten"
  - type: checklist
    eyebrow: "Für wen"
    title: "Eine Periode, mehrere Personen, die sie freigeben"
    items:
      - text: "Vorgesetzte und Schichtleiter"
        description: "Planen, tauschen, vertreten und korrigieren, mit der Regelprüfung direkt vor Augen."
      - text: "HR und Lohnabrechnung"
        description: "Korrekturen genehmigen, die Periode abschließen und einen einzigen Export senden, mit jeder Änderung nachvollziehbar dahinter."
      - text: "Werkleiter und Produktionsleiter"
        description: "Die Besetzung je Linie und Schicht sowie die gesperrten Entscheidungen, die den Plan im gesetzlichen Rahmen gehalten haben."
      - text: "Betriebsräte"
        description: "Jede Regel lesen, die das System anwendet, und sehen, woher ihre Werte stammen."
  - type: section
    eyebrow: "Was Attendance erfasst und wie es Govern versorgt"
    title: "Jede Sperre, jede Korrektur und jeder Abschluss ist eine Entscheidung mit Beleg"
    markdown: |
      Attendance erfasst Zeitergebnisse, Korrekturen, Genehmigungen und Periodenabschlüsse. Sperrt oder markiert eine Regel eine Entscheidung, schreibt Attendance ein Prüfprotokoll: die Regel und ihre Version, die verwendeten Werte und ihre Herkunft, die Eingangsdaten und das Ergebnis.

      Diese Protokolle gehen an Ihren Cloud-Mandanten. Dort wertet Govern sie standortübergreifend aus, simuliert vorgeschlagene Regeländerungen und ermöglicht es Betriebsrat oder Auditor, jede Entscheidung als Erklärung in Klartext zu öffnen. Die Regeln selbst sind am Standort und in der Cloud dieselben.

      [Wie eine Entscheidung erklärt wird](/explained)
  - type: cta
    title: "Wenden Sie die Regeln auf Ihre eigenen Zeitdaten an"
    description: "Die Compliance-Diagnose zeigt Befunde zu Ruhezeiten, Arbeitszeiten und Überstunden aus Ihrer Historie, jeweils mit Erklärung."
    primary_action: { text: "Diagnose anfragen", url: "/diagnostic" }
    secondary_action: { text: "Zur Produkttour", url: "/demo" }
---
