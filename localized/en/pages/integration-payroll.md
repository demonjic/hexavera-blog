---
title: "Payroll: hours and their evidence, in your format"
description: "Hexavera gives payroll an access-event extract per period first, then approved time results from Attendance in the format your payroll system reads."
permalink: "/integrations/payroll"
slug: "integration-payroll"
lang: "en"
id: "page-integration-payroll"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Connector: payroll"
    title: "Payroll keeps calculating pay. Hexavera supplies the hours."
    subtitle: "Your payroll system stays. Hexavera hands it what it needs per period, with the evidence that shows where each figure came from."
    primary_action: { text: "Talk to us about your payroll", url: "/contact" }
    secondary_action: { text: "All integrations", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "What flows, in which direction"
    markdown: |
      All of it flows out, from Hexavera to payroll, in two steps.

      **Step 1: the access-event extract (M2)**

      - A documented, versioned extract of access events per payroll period.
      - The data quality report attached: which passages are attributable to a person and a direction, which readers were offline, and what the events cannot tell payroll.

      **Step 2: time results from Attendance (M4)**

      - Worked hours per person and day, with rounding and the working-time rules applied on site.
      - Only after corrections are made and the period is closed with approval.
      - In the file format of your payroll system.
    aside:
      type: record
      title: "Payroll"
      status: "On the plan"
      tone: info
      rows:
        - { label: "Direction", value: "Out, to payroll" }
        - { label: "Step 1", value: "Access-event extract, M2" }
        - { label: "Step 2", value: "Time results from Attendance, M4" }
        - { label: "Format", value: "Your payroll's import format" }
  - type: checklist
    id: "what-you-configure"
    title: "What you configure"
    items:
      - text: "The payroll period"
        description: "Weekly, fortnightly or monthly, and the day it closes."
      - text: "Employee numbers"
        description: "How a person in Hexavera matches the person in payroll."
      - text: "Pay codes"
        description: "Which time result goes to which pay code: normal hours, overtime, night work, absence."
      - text: "Delivery"
        description: "Where the file goes and who approves the period before it is sent."
  - type: section
    id: "status"
    title: "Status"
    markdown: |
      The access-event extract is on the plan for milestone M2. Time results in your payroll's format follow with Attendance at milestone M4. The first export format is the payroll system of our first Attendance customer; further formats are sequenced behind customer demand.

      Door events alone are not working time. The extract says so, and the data quality report shows where the gaps are. Attendance is what turns events and shifts into hours payroll can rely on.
  - type: cta
    title: "Which payroll do you run?"
    description: "Tell us the system and the file it imports. We tell you where it sits in the sequence."
    primary_action: { text: "Contact us", url: "/contact" }
    secondary_action: { text: "Hexavera Attendance", url: "/products/attendance" }
---
