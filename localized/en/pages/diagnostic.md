---
title: "Compliance diagnostic: your history, checked rule by rule"
description: "Send a stretch of your shift and time records under a data processing agreement. We run the working-time rules over them and explain every finding."
url: "diagnostic"
slug: "diagnostic"
locale: "en"
localization_id: "page-diagnostic"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Compliance diagnostic"
    title: "Find out what your own records say about rest, hours and qualifications"
    subtitle: "You send a stretch of your shift and time records. We run the working-time rules that apply to your plant over them and walk you through every finding, each with its explanation. You see the evidence model on your own data before you decide anything."
    primary_action: { text: "Book a diagnostic", url: "/contact" }
    secondary_action: { text: "How decisions are explained", url: "/explained" }
  - type: checklist
    eyebrow: "What you send"
    title: "Exports you already have, with names replaced if you prefer"
    description: "The rules need dates, times, contracts and roles. They do not need names: a stable code per employee is enough."
    items:
      - text: "Time records"
        description: "Clock-ins and clock-outs, or worked intervals, per employee."
      - text: "Shift plans"
        description: "The planned shifts for the same period, including swaps if you record them."
      - text: "Contract facts"
        description: "Contracted hours and contract type per employee, and whether the employee is a minor."
      - text: "Qualifications, if you want them checked"
        description: "Which training or certification each employee holds, and which stations require it."
      - text: "The plant's context"
        description: "The country, the collective agreement that applies and any plant settings, such as how rest is measured."
  - type: steps
    eyebrow: "How it runs"
    title: "Four steps from your export to the findings"
    items:
      - title: "Agree"
        description: "We sign a data processing agreement with you before we accept any file."
      - title: "Load"
        description: "We import your files and send back a rejection report listing every row we could not read, and why."
      - title: "Run"
        description: "We run the rules for your country and agreement over the period: daily and weekly rest, maximum daily and weekly hours, breaks, overtime, night work, consecutive working days and qualifications."
      - title: "Walk through"
        description: "We go through the findings with you, rule by rule, and open any one of them as an explanation."
  - type: split
    eyebrow: "What you get"
    title: "A compliance exposure report built from your history"
    markdown: |
      The report lists every finding: rest periods that were too short, weeks over the maximum hours, people placed on a station without the qualification it requires, overtime without an approval on record. Each finding opens as a full explanation, the same one a works council or an auditor would see in the product.

      Where your records lack a fact a rule needs, the report says so and marks the result as indeterminate. It never counts a missing fact as a pass.

      The report is yours. It is a reading of your data against the rules, not legal advice; your counsel decides what follows from it.
    aside:
      type: record
      title: "Finding, packaging department"
      status: "Fail"
      tone: danger
      rows:
        - { label: "Rule", value: "Minimum daily rest, 11 h" }
        - { label: "Employee", value: "Code 2041" }
        - { label: "Between", value: "Clock-out Tue 14:06 and clock-in Tue 21:57" }
        - { label: "Computed rest", value: "7 h 51 min" }
        - { label: "Sources", value: "Time export, rows 18 233 and 18 240" }
      caption: "Sample data"
  - type: section
    eyebrow: "How your data is handled"
    title: "Your data is used for the diagnostic and for nothing else"
    markdown: |
      - **Before anything is sent**, we sign a data processing agreement. It names the purpose, where the data is processed, who can access it, how long it is kept and when it is deleted.
      - **Send less where you can.** Replace names with codes, leave out columns the rules do not use. We tell you which columns those are before you export.
      - **Your data stays in its own tenant**, with its own database schema, separate from every other customer's.
      - **Only the people running your diagnostic** can open it, each with a second factor at sign-in.
      - **Nothing is used for anything else.** Your records serve the diagnostic the agreement describes and are not shown to anyone outside it.
      - **At the end**, the data is deleted as the agreement states.

      The GDPR applies to every row you send, and we handle it under the agreement as your processor.
  - type: cta
    variant: dark
    title: "Book a compliance diagnostic"
    description: "Tell us about your plant, your shift pattern and the systems your records come from. We reply with what to export and a draft data processing agreement."
    primary_action: { text: "Book a diagnostic", url: "/contact" }
    secondary_action: { text: "How decisions are explained", url: "/explained" }
---
