---
title: "How Hexavera explains and simulates a decision"
description: "For works councils and auditors: how a decision is traced to its rule, legal source, plant setting and input facts, and how a rule change is simulated."
url: "explained"
slug: "explained"
locale: "en"
localization_id: "page-explained"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "For works councils and auditors"
    title: "Every decision can be opened, read and tested"
    subtitle: "When Hexavera blocks a shift, refuses a door or flags overtime, it writes down why: the rule, where its value comes from, the facts it used and the result. This page walks through one such record and shows what a simulation adds."
    primary_action: { text: "Book a diagnostic", url: "/diagnostic" }
    secondary_action: { text: "Take the product tour", url: "/demo" }
  - type: split
    eyebrow: "One decision, traced"
    title: "A night shift swap, blocked for lack of rest"
    markdown: |
      A packaging operator worked the early shift on Tuesday and stayed a few minutes over. In the afternoon, a colleague asked them to take over the night shift on Line 3, starting at 22:00. The supervisor accepted the swap in Attendance, and Attendance evaluated it before saving.

      The record beside this text is what Attendance wrote. It is stored at the site and in the cloud tenant, and nobody can edit it afterwards. A correction is a new record that refers to the old one.
    aside:
      type: record
      title: "Evaluation record, shift swap SW-118"
      status: "Blocked"
      tone: danger
      rows:
        - { label: "Decision", value: "Assign E-2041 to the night shift, Line 3, Tue 22:00" }
        - { label: "Rule", value: "DAILY-REST, minimum daily rest, version 3" }
        - { label: "Legal source", value: "EU Working Time Directive 2003/88/EC, art. 3, as transposed in national law: 11 consecutive hours per 24 hours" }
        - { label: "Value used", value: "11 h, statutory level; no collective agreement or company value overrides it" }
        - { label: "Plant setting", value: "Rest is measured from the last clock-out at a time terminal. Set at site level by the plant HR administrator, valid from 1 March 2026" }
        - { label: "Input fact 1", value: "Last clock-out Tue 14:06, terminal T-04 (Attendance, punch record P-88213)" }
        - { label: "Input fact 2", value: "Proposed start Tue 22:00 (shift plan, swap request SW-118)" }
        - { label: "Computed", value: "Rest between them: 7 h 54 min" }
        - { label: "Verdict", value: "Fail: 7 h 54 min is below 11 h. Swap blocked" }
        - { label: "Evaluated", value: "Site runtime, Tue 15:20, by the supervisor's action" }
      caption: "Sample data"
  - type: section
    eyebrow: "The same record, in plain language"
    title: "What the explanation says"
    markdown: |
      > The swap was blocked because the employee would have had 7 hours and 54 minutes of rest before the night shift, and the law requires at least 11 consecutive hours in every 24.
      >
      > The 11 hours come from the EU Working Time Directive, article 3, as written into national law. No collective agreement or company rule changes that value at this plant.
      >
      > The rest was counted from the employee's last clock-out, at 14:06 on terminal T-04, to the start of the night shift at 22:00. The plant measures rest from the clock-out at a time terminal; its HR administrator set this on 1 March 2026.
      >
      > If you believe a fact is wrong, for example the clock-out time, the punch record P-88213 shows where it came from.

      Every explanation follows the same order: what was decided, which rule applied, where the value comes from, which facts were used and where each came from, what was computed, and the result. A works council member, an auditor or the employee can check each step without reading code. Explanations are available in each language the console offers.
  - type: checklist
    eyebrow: "What makes the record trustworthy"
    title: "Rules as data, facts with sources, nothing overwritten"
    items:
      - text: "Rules are data, not code"
        description: "Administrators choose values and scopes. They cannot write expressions, so every rule can be listed and read."
      - text: "Every value has a level and a source"
        description: "Statute, collective agreement, company or department, each with a citation and a validity period."
      - text: "Every fact has a source"
        description: "The system and record it came from, and when it was observed."
      - text: "Missing facts are named"
        description: "If a rule needs a fact the record does not hold, the verdict is 'indeterminate', never 'pass'."
      - text: "Records are appended"
        description: "Rule versions and evaluation records are kept. A correction refers to what it corrects."
  - type: split
    eyebrow: "Simulation"
    title: "Test a rule change on past decisions before it applies to anyone"
    markdown: |
      Suppose management and the works council discuss a collective agreement clause that allows rest to be shortened to 10 hours twice a month, with compensatory rest later in the week. Before agreeing, both sides want to know what it would change.

      A simulation runs the same rules over a past period with the proposed values. It lists every decision whose verdict would change, by department and shift, with the explanation for each. Nothing in the simulation becomes a live record, and no employee's data leaves the tenant.

      The works council sees the effect of the clause on real shift patterns, not on an example chosen to persuade it.
    aside:
      type: checklist
      title: "What a simulation shows"
      items:
        - { text: "The values compared", description: "Current and proposed, side by side." }
        - { text: "Every decision that changes", description: "Blocked to allowed, or allowed to blocked." }
        - { text: "Where it changes", description: "By department, line and shift pattern." }
        - { text: "Why, per decision", description: "The same explanation as a live record." }
  - type: cta
    title: "See your own decisions explained"
    description: "The compliance diagnostic runs the rules over your history and gives you every finding with its explanation."
    primary_action: { text: "Book a diagnostic", url: "/diagnostic" }
    secondary_action: { text: "Take the product tour", url: "/demo" }
---
