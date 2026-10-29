---
title: "Hexavera Access: physical access control at the site"
description: "Doors, readers, credentials, alarms, visitors and guard tours on a server at your plant. Every passage is recorded and feeds attendance and compliance."
url: "products/access"
slug: "access"
locale: "en"
localization_id: "page-access"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Site product: Access"
    title: "Access control that keeps a record your payroll and auditors can use"
    subtitle: "Hexavera Access runs on a server at your plant. It decides who passes which door and when, records every passage, and keeps working when the link to the cloud is down."
    highlights:
      - "Doors, readers and controllers on site"
      - "Cards, PINs, fingerprints and faces"
      - "Alarms, visitors and guard tours"
    primary_action: { text: "Book a diagnostic", url: "/diagnostic" }
    secondary_action: { text: "Take the product tour", url: "/demo" }
  - type: cards
    eyebrow: "What it does at the site"
    title: "From enrolment to the event log, in one place"
    columns: 3
    items:
      - title: "People and credentials"
        description: "Enrol people, issue and revoke cards, PINs, fingerprints and faces, and suspend access the moment someone leaves."
      - title: "Doors, levels and schedules"
        description: "Organise doors, readers and controllers into areas. Access levels and schedules decide which credential opens which door, at which hours, on which days."
      - title: "Devices"
        description: "Enrol and discover controllers, watch their health, keep their clocks in step and restart them from the console. Hikvision controllers are supported today."
      - title: "Alarms"
        description: "Forced doors, doors held open and refused credentials raise alarms that operators acknowledge and close, with a note."
      - title: "Visitors"
        description: "Register visitors, give them a credential for the visit and take it back when they leave."
      - title: "Guard tours"
        description: "Define rounds as a sequence of readers and see which checkpoints were reached and when."
  - type: split
    eyebrow: "For whom"
    title: "Security runs the doors; HR and operations use what the doors record"
    markdown: |
      **Security and facilities** run the daily work: credentials, doors, alarms, visitors and rounds. Each operator action needs a permission, and each is written to the audit trail.

      **HR and plant management** get an honest view of the passages: who entered which area and when, and where the record has gaps.

      **Works councils** can see what is stored about a passage and who may look at it.
    aside:
      type: record
      title: "Passage, hygiene gate B"
      status: "Granted"
      tone: success
      rows:
        - { label: "Holder", value: "E-1187, production" }
        - { label: "Credential", value: "Card" }
        - { label: "Reader", value: "Gate B, entry side" }
        - { label: "Time", value: "Mon 05:52" }
        - { label: "Level", value: "High-care, early shift" }
      caption: "Sample data"
  - type: checklist
    eyebrow: "What it records"
    title: "Every passage is a fact with a source"
    description: "Attendance and Govern rely on these events, so Access is precise about what each one says, and what it does not."
    items:
      - text: "The passage"
        description: "Person, credential, reader, door, direction and time, as reported by the controller."
      - text: "Refusals and alarms"
        description: "Why a credential was refused, and how an alarm was handled and by whom."
      - text: "Changes"
        description: "Who changed a credential, a level or a schedule, and when."
      - text: "Gaps"
        description: "Readers that went silent, passages without a direction and device clocks out of step, listed in the data quality report."
  - type: section
    eyebrow: "How it feeds Govern"
    title: "The data quality report shows what door events can and cannot tell payroll"
    markdown: |
      Door events are often treated as attendance. They are not, until you know which readers record direction, which ones were offline and how far their clocks drifted. The data quality report reads your own passages per reader and per day and says which ones can be attributed to a person and a direction, and which cannot.

      That is the ground Attendance builds time results on. In Govern, the same passages become input facts: a refused entry to a high-care area cites the passage and the training record behind the rule, so the decision can be explained later.

      If your plant already runs an access control system, we do not ask you to replace it. Talk to us about connecting it instead.
  - type: cta
    title: "Start with what your doors already know"
    description: "Book a compliance diagnostic, or walk through Access in the product tour with sample data."
    primary_action: { text: "Book a diagnostic", url: "/diagnostic" }
    secondary_action: { text: "Take the product tour", url: "/demo" }
---
