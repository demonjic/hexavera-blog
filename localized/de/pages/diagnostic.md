---
title: "Compliance-Diagnose: Ihre Historie, Regel für Regel geprüft"
description: "Sie senden einen Auszug Ihrer Schicht- und Zeitdaten unter einem AVV. Wir prüfen ihn gegen die Arbeitszeitregeln und erklären Ihnen jeden Befund."
permalink: "/diagnostic"
slug: "diagnostic"
lang: "de"
id: "page-diagnostic"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Compliance-Diagnose"
    title: "Was Ihre eigenen Daten über Ruhezeiten, Arbeitszeiten und Qualifikationen sagen"
    subtitle: "Sie senden uns einen Auszug Ihrer Schicht- und Zeitdaten. Wir prüfen ihn gegen die Arbeitszeitregeln, die für Ihr Werk gelten, und gehen jeden Befund mit Ihnen durch, jeweils mit seiner Erklärung. So sehen Sie das Nachweismodell an Ihren eigenen Daten, bevor Sie irgendetwas entscheiden."
    primary_action: { text: "Diagnose anfragen", url: "/contact" }
    secondary_action: { text: "Wie Entscheidungen erklärt werden", url: "/explained" }
  - type: checklist
    eyebrow: "Was Sie senden"
    title: "Exporte, die Sie ohnehin haben, auf Wunsch ohne Namen"
    description: "Die Regeln brauchen Datumsangaben, Uhrzeiten, Vertragsdaten und Funktionen. Namen brauchen sie nicht: Ein gleichbleibender Code je Mitarbeiter genügt."
    items:
      - text: "Zeitdaten"
        description: "Kommen- und Gehen-Buchungen oder gearbeitete Zeitintervalle je Mitarbeiter."
      - text: "Schichtpläne"
        description: "Die geplanten Schichten für denselben Zeitraum, einschließlich Schichttausch, sofern Sie ihn erfassen."
      - text: "Vertragsdaten"
        description: "Vertragliche Arbeitszeit und Vertragsart je Mitarbeiter sowie die Angabe, ob der Mitarbeiter minderjährig ist."
      - text: "Qualifikationen, falls diese geprüft werden sollen"
        description: "Welche Schulung oder Zertifizierung jeder Mitarbeiter besitzt und welche Arbeitsplätze sie voraussetzen."
      - text: "Die Rahmenbedingungen des Werks"
        description: "Das Land, der geltende Tarifvertrag und etwaige Werkseinstellungen, zum Beispiel wie die Ruhezeit gemessen wird."
  - type: steps
    eyebrow: "Der Ablauf"
    title: "In vier Schritten vom Export zu den Befunden"
    items:
      - title: "Vereinbaren"
        description: "Bevor wir eine Datei annehmen, schließen wir mit Ihnen einen Auftragsverarbeitungsvertrag (AVV)."
      - title: "Einlesen"
        description: "Wir importieren Ihre Dateien und senden Ihnen einen Fehlerbericht, der jede Zeile auflistet, die wir nicht lesen konnten, mit Begründung."
      - title: "Prüfen"
        description: "Wir wenden die Regeln Ihres Landes und Ihres Tarifvertrags auf den Zeitraum an: tägliche und wöchentliche Ruhezeit, tägliche und wöchentliche Höchstarbeitszeit, Pausen, Überstunden, Nachtarbeit, aufeinanderfolgende Arbeitstage und Qualifikationen."
      - title: "Besprechen"
        description: "Wir gehen die Befunde Regel für Regel mit Ihnen durch und öffnen jeden einzelnen auf Wunsch als Erklärung."
  - type: split
    eyebrow: "Was Sie erhalten"
    title: "Ein Bericht zu Ihren Compliance-Risiken, erstellt aus Ihrer Historie"
    markdown: |
      Der Bericht führt jeden Befund auf: zu kurze Ruhezeiten, Wochen über der Höchstarbeitszeit, Einsätze an Arbeitsplätzen ohne die erforderliche Qualifikation, Überstunden ohne dokumentierte Genehmigung. Jeder Befund lässt sich als vollständige Erklärung öffnen, genau so, wie ein Betriebsrat oder ein Auditor sie im Produkt sehen würde.

      Fehlt in Ihren Daten eine Angabe, die eine Regel braucht, sagt der Bericht das und weist das Ergebnis als „nicht bestimmbar“ aus. Eine fehlende Angabe wird nie als erfüllt gewertet.

      Der Bericht gehört Ihnen. Er ist eine Auswertung Ihrer Daten anhand der Regeln und keine Rechtsberatung. Welche Schlüsse daraus folgen, entscheiden Ihre Rechtsberater.
    aside:
      type: record
      title: "Befund, Abteilung Verpackung"
      status: "Nicht erfüllt"
      tone: danger
      rows:
        - { label: "Regel", value: "Tägliche Mindestruhezeit, 11 Std." }
        - { label: "Mitarbeiter", value: "Code 2041" }
        - { label: "Zwischen", value: "Gehen-Buchung Di. 14:06 und Kommen-Buchung Di. 21:57" }
        - { label: "Berechnete Ruhezeit", value: "7 Std. 51 Min." }
        - { label: "Quellen", value: "Zeitexport, Zeilen 18.233 und 18.240" }
      caption: "Beispieldaten"
  - type: section
    eyebrow: "Umgang mit Ihren Daten"
    title: "Ihre Daten dienen der Diagnose und keinem anderen Zweck"
    markdown: |
      - **Bevor Daten fließen**, schließen wir einen Auftragsverarbeitungsvertrag. Er legt Zweck, Ort der Verarbeitung, Zugriffsberechtigte, Speicherdauer und Löschzeitpunkt fest.
      - **Senden Sie so wenig wie möglich.** Ersetzen Sie Namen durch Codes und lassen Sie Spalten weg, die die Regeln nicht verwenden. Welche das sind, sagen wir Ihnen vor dem Export.
      - **Ihre Daten liegen in einem eigenen Mandanten** mit eigenem Datenbankschema, getrennt von den Daten aller anderen Kunden.
      - **Nur die Personen, die Ihre Diagnose durchführen**, haben Zugriff, jeweils mit einem zweiten Faktor bei der Anmeldung.
      - **Keine andere Verwendung.** Ihre Daten dienen ausschließlich der im Vertrag beschriebenen Diagnose und werden niemandem außerhalb davon gezeigt.
      - **Zum Abschluss** werden die Daten so gelöscht, wie es der Vertrag festlegt.

      Für jede Zeile, die Sie senden, gilt die DSGVO. Wir verarbeiten die Daten nach dem Vertrag als Ihr Auftragsverarbeiter.
  - type: cta
    variant: dark
    title: "Compliance-Diagnose anfragen"
    description: "Erzählen Sie uns von Ihrem Werk, Ihrem Schichtmodell und den Systemen, aus denen Ihre Daten stammen. Wir antworten mit einer Liste der benötigten Exporte und dem Entwurf eines Auftragsverarbeitungsvertrags."
    primary_action: { text: "Diagnose anfragen", url: "/contact" }
    secondary_action: { text: "Wie Entscheidungen erklärt werden", url: "/explained" }
---
