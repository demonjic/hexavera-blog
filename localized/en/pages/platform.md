---
title: "The Hexavera platform: site products and cloud tenant"
description: "Access, Attendance and Presence run at each plant; Connect, Govern, Automate and Predict run in your cloud tenant. All of them write to one record of decisions."
url: "platform"
slug: "platform"
locale: "en"
localization_id: "page-platform"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "The platform"
    title: "One platform in two halves: the site and the cloud tenant"
    subtitle: "Access, Attendance and Presence run on a server at each plant and keep working when the internet link is down. Connect, Govern, Automate and Predict run in your own cloud tenant. Both halves write to one record of decisions, so a block at the gate and a finding in an audit point to the same evidence."
    highlights:
      - "Site runtime on premises, one per plant"
      - "Cloud tenant per operating company"
      - "One decision record across both"
    primary_action: { text: "Book a diagnostic", url: "/diagnostic" }
    secondary_action: { text: "Take the product tour", url: "/demo" }
  - type: split
    id: "access"
    eyebrow: "At the site: Access"
    title: "Access decides who passes which door, and keeps every passage"
    markdown: |
      Access manages people and their credentials (cards, PINs, fingerprints and faces), the doors and readers they use, and the levels and schedules that decide when a credential opens a door. Alarms, visitors and guard tours are handled at the same site, on the same server.

      Every passage is stored with its reader, direction and time. Attendance and Govern rely on those events, so Access also reports what they cannot tell you: readers that went silent, passages without a direction, device clocks out of step.

      [Access in detail](/products/access)
    aside:
      type: record
      title: "Passage, hygiene gate B"
      status: "Refused"
      tone: warning
      rows:
        - { label: "Credential", value: "Card, holder E-3310" }
        - { label: "Reader", value: "Gate B, entry side" }
        - { label: "Rule", value: "High-care entry needs valid hygiene training" }
        - { label: "Fact", value: "Training expired 2 days earlier (training record)" }
      caption: "Sample data"
  - type: section
    id: "attendance"
    eyebrow: "At the site: Attendance"
    title: "Attendance turns passages and punches into the file that pays people"
    markdown: |
      Attendance reads the passages from Access and the punches from Presence and calculates time results with your rounding, break and overtime settings. Supervisors work with shifts and rotations, swaps, absence cover and a coverage view, then publish the plan. Corrections are approved, the period is closed and the payroll export is produced from the closed period.

      Rest periods, maximum daily and weekly hours and contract limits are checked on site, when a shift is assigned or swapped. A block does not wait for the cloud.

      [Attendance in detail](/products/attendance)
  - type: section
    id: "presence"
    eyebrow: "At the site: Presence"
    title: "Presence lets employees see and act on their own time"
    markdown: |
      Employees punch in and out, check their timecard, schedule and balances, and request time off, in the browser or at a kiosk on the shop floor. A kiosk identifies a person by badge plus a PIN the site issues and rotates on first use, or by badge plus face where the plant has chosen faces. The employee number is never the password.

      [Presence in detail](/products/presence)
  - type: section
    id: "connect"
    eyebrow: "In the cloud: Connect"
    title: "Connect brings your systems into one tenant without replacing them"
    markdown: |
      Your HR system, payroll and ERP stay authoritative. Connect reads what the decisions need from them (people and organisation, time and pay, access and devices) into your tenant, and keeps the source system and source id with every record. Hexavera's own site products connect to it without a connector. A file import loads history and systems without an interface.

      Each operating company is its own tenant with its own database schema, even when a group runs one shared HR system. A tenant only holds its own company's people.
  - type: split
    id: "govern"
    eyebrow: "In the cloud: Govern"
    title: "Govern holds the rules and the record every decision is written to"
    markdown: |
      Govern stores each rule as data: what it checks, its legal source, and its values at four levels (statute, collective agreement, company, department). A department can have a different grace period from the rest of the plant without anyone writing code. Certification and skills requirements gate who may be assigned to a station.

      This is where the two halves meet. A decision taken at the site is evaluated there and written to the site's record first, then to your tenant. The decision record is the same in both places: the rule version, the values used, the input facts and the verdict. Reports, simulations and audits read that one record.

      [How a decision is explained](/explained)
    aside:
      type: checklist
      title: "In every decision record"
      items:
        - { text: "Rule code and version" }
        - { text: "Each value used, with its level and source" }
        - { text: "Input facts, each with its source record" }
        - { text: "The computed quantity and the verdict" }
        - { text: "Where and when it was evaluated" }
  - type: section
    id: "automate"
    eyebrow: "In the cloud: Automate"
    title: "Automate takes the step that follows a decision"
    markdown: |
      A blocked assignment needs a replacement; a correction needs a supervisor's approval; an expiring qualification needs a reminder. Automate runs those follow-up steps from templates you adjust: who approves, who is notified, through which channel. Workflows are scoped with each customer, starting from the decisions Govern already records.
  - type: section
    id: "predict"
    eyebrow: "In the cloud: Predict"
    title: "Predict looks forward from your own history, and Vera answers questions"
    markdown: |
      Predict works on the governed data in your tenant, never on another customer's. Its models are trained on your own history, starting with absence.

      Vera is the assistant in Predict. Ask it who is on tomorrow's night shift or where coverage is short, and it answers from your tenant's data within the permissions of the person asking. It reads the same records your reports do.
---
