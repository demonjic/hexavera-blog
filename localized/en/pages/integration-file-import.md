---
title: "File import: people, organisation and time"
description: "Import CSV files of people, organisation and time records into your Hexavera tenant, with validation and a report that names every refused row."
url: "integrations/file-import"
slug: "integration-file-import"
locale: "en"
localization_id: "page-integration-file-import"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Connector: files"
    title: "When a system has no API, a file will do"
    subtitle: "Some systems only export files. Some history only exists in files. File import brings both into your tenant, checked row by row."
    primary_action: { text: "Book a diagnostic", url: "/diagnostic" }
    secondary_action: { text: "All integrations", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "What flows, in which direction"
    markdown: |
      **From your files to Hexavera**

      - People and organisation: employees, departments, positions, cost centres.
      - Time: punches, worked hours and absences, including years of history.

      **Back to you**

      - A rejection report. Every refused row is listed with the reason, so you fix it at the source and import again.

      Imported history is what the compliance diagnostic runs on: the rules are evaluated over your own past records.
    aside:
      type: record
      title: "File import"
      status: "On the plan"
      tone: info
      rows:
        - { label: "Runs", value: "In the cloud tenant (Connect)" }
        - { label: "Format", value: "CSV" }
        - { label: "Direction", value: "In, with a rejection report" }
        - { label: "Milestone", value: "M2, the first Connect delivery" }
  - type: checklist
    id: "what-you-configure"
    title: "What you configure"
    items:
      - text: "The domain"
        description: "Whether a file holds people and organisation, or time."
      - text: "The column mapping"
        description: "Which column is the employee number, the date, the start and the end."
      - text: "Dates and time zone"
        description: "The date format and the time zone the source wrote its times in."
      - text: "What happens to a bad row"
        description: "Refused rows never enter the record. They come back in the report."
  - type: section
    id: "status"
    title: "Status"
    markdown: |
      File import is on the plan for milestone M2, first for people, organisation and time history.

      Files with personal data are accepted only under a data processing agreement. That agreement is signed before the first file is sent.
  - type: cta
    title: "Have years of time records in files?"
    description: "Tell us what you hold and in which format. We tell you what the diagnostic can read from it."
    primary_action: { text: "Book a diagnostic", url: "/diagnostic" }
    secondary_action: { text: "Contact us", url: "/contact" }
---
