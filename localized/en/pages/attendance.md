---
title: "Hexavera Attendance: time, shifts and the payroll export"
description: "Time capture, shifts, corrections, period close and the payroll export at your plant, with rest and maximum hours checked on site before a shift is set."
permalink: "/products/attendance"
slug: "attendance"
lang: "en"
id: "page-attendance"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Site product: Attendance"
    title: "From a punch to the payroll file, with the rules checked on the way"
    subtitle: "Hexavera Attendance runs at your plant. It turns passages and punches into time results, plans and publishes shifts, closes the period and produces the payroll export. Rest periods and maximum hours are checked on site, before a shift is assigned."
    highlights:
      - "Shifts, rotations, swaps and absence cover"
      - "Corrections and period close with approval"
      - "Legal rules enforced without the cloud link"
    primary_action: { text: "Book a diagnostic", url: "/diagnostic" }
    secondary_action: { text: "Take the product tour", url: "/demo" }
  - type: steps
    eyebrow: "What it does at the site"
    title: "Four stages before payroll, each with its history"
    items:
      - title: "Capture"
        description: "Passages come from Hexavera Access, punches from Presence kiosks and the browser. Each one keeps its source: the reader, the terminal, the person."
      - title: "Calculate"
        description: "Time results follow your shifts, rounding, breaks, overtime and absence settings. A department can have its own grace period without a change for the rest of the plant."
      - title: "Correct and approve"
        description: "Missing punches and exceptions go to the supervisor. Each correction keeps the original, the change, the reason and the approver."
      - title: "Close and export"
        description: "The closed period produces the payroll export in your payroll system's format. Nothing changes in a closed period without reopening it on the record."
  - type: split
    eyebrow: "Shifts"
    title: "Plan shifts that the rules have already checked"
    markdown: |
      Supervisors define shifts and rotations, assign people, accept swaps and cover absences, then publish the plan. The coverage view shows where a line is short before the shift starts.

      Every assignment and swap is checked against rest periods, maximum daily and weekly hours and contract limits as it is made. A swap that would leave someone with too little rest is blocked, and the supervisor sees why.
    aside:
      type: record
      title: "Shift swap request SW-118"
      status: "Blocked"
      tone: danger
      rows:
        - { label: "Requested", value: "E-2041 takes Tue night shift, Line 3" }
        - { label: "Rule", value: "Minimum daily rest, 11 h" }
        - { label: "Last clock-out", value: "Tue 14:06" }
        - { label: "Rest before start", value: "7 h 54 min" }
        - { label: "Next step", value: "Offer the shift to the next eligible person" }
      caption: "Sample data"
  - type: checklist
    eyebrow: "For whom"
    title: "One period, several people who sign it off"
    items:
      - text: "Supervisors and shift leads"
        description: "Plan, swap, cover and correct, with the rule check in front of them."
      - text: "HR and payroll"
        description: "Approve corrections, close the period and send one export, with every change behind it on the record."
      - text: "Plant managers and operations directors"
        description: "Coverage per line and shift, and the blocked decisions that kept the plan within the law."
      - text: "Works councils"
        description: "Read every rule the system applies and where its values come from."
  - type: section
    eyebrow: "What it records, and how it feeds Govern"
    title: "Every block, correction and close is a decision with evidence"
    markdown: |
      Attendance records time results, corrections, approvals and period closes. When a rule blocks or flags a decision, it writes an evaluation record: the rule and its version, the values used and where they come from, the input facts and the verdict.

      Those records go to your cloud tenant, where Govern reports on them across sites, runs simulations on proposed rule changes and lets a works council or an auditor open any decision as a plain-language explanation. The rules themselves are the same at the site and in the cloud.

      [How a decision is explained](/explained)
  - type: cta
    title: "Run the rules over your own time records"
    description: "The compliance diagnostic shows rest, hours and overtime findings from your history, each with its explanation."
    primary_action: { text: "Book a diagnostic", url: "/diagnostic" }
    secondary_action: { text: "Take the product tour", url: "/demo" }
---
