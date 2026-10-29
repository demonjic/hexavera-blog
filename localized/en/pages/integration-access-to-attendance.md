---
title: "Hexavera Access to Attendance"
description: "Hexavera Access publishes every passage with its gaps marked. Attendance reads that feed at the site and turns it, with shifts, into time results."
url: "integrations/access-to-attendance"
slug: "integration-access-to-attendance"
locale: "en"
localization_id: "page-integration-access-to-attendance"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Connector: Hexavera products"
    title: "From door events to working time, with the gaps in plain sight"
    subtitle: "Access and Attendance run side by side at your site. Access publishes what happened at the doors; Attendance reads it and says what it means for working time."
    primary_action: { text: "Book a diagnostic", url: "/diagnostic" }
    secondary_action: { text: "All integrations", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "What flows, in which direction"
    markdown: |
      **From Access to Attendance**

      - Each passage: the person, the reader, the door, the direction and the time.
      - Coverage: which readers were offline, which events were lost, and how far each panel's clock drifted.

      **From Attendance to Access**

      - Nothing. Corrections to working time are made in Attendance and do not change the access record.

      Because the feed marks its own gaps, Attendance never reads a silent reader as a person who stayed home.
    aside:
      type: record
      title: "Access to Attendance"
      status: "On the plan"
      tone: info
      rows:
        - { label: "Runs", value: "At the site" }
        - { label: "Direction", value: "Access to Attendance" }
        - { label: "Event feed and data quality report", value: "M1" }
        - { label: "Attendance reading the feed", value: "M4" }
  - type: checklist
    id: "what-you-configure"
    title: "What you configure"
    items:
      - text: "Which readers count"
        description: "The readers whose passages count as the start or end of work, and in which direction."
      - text: "Shifts"
        description: "The shifts and rotations Attendance matches passages against."
      - text: "Rules"
        description: "Rounding, grace and the working-time rules that apply to each site, department or group."
  - type: section
    id: "status"
    title: "Status"
    markdown: |
      The event feed and the data quality report are on the plan for milestone M1, with Hexavera Access at the site. The data quality report shows, per reader and per day, what your door events can and cannot tell payroll. Attendance reads the feed with milestone M4.
  - type: cta
    title: "What do your door events tell payroll today?"
    description: "The data quality report answers that from your own events."
    primary_action: { text: "Contact us", url: "/contact" }
    secondary_action: { text: "Hexavera Attendance", url: "/products/attendance" }
---
