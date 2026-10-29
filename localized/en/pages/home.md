---
title: "Hexavera: workforce decisions your plant can explain"
description: "Hexavera is the decision system of record for the industrial workforce: every shift, access and time decision made, enforced, recorded and explained."
url: ""
slug: "home"
locale: "en"
localization_id: "page-home"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Decision system of record for the industrial workforce"
    title: "Every workforce decision, made, enforced, recorded and explained"
    subtitle: "Hexavera runs access, attendance and self-service at your site, and rules, automation and prediction in your cloud tenant. When a rule blocks a shift or a door, the record shows which rule, which facts and why."
    highlights:
      - "Rules with their legal source attached"
      - "Enforced at the site, even without the cloud link"
      - "A trace a works council can read"
    primary_action: { text: "Book a diagnostic", url: "/diagnostic" }
    secondary_action: { text: "Take the product tour", url: "/demo" }
    aside:
      type: record
      title: "Night shift assignment, Line 3"
      status: "Blocked"
      tone: danger
      rows:
        - { label: "Employee", value: "E-2041, packaging" }
        - { label: "Rule", value: "Minimum daily rest, 11 h (EU Working Time Directive, art. 3)" }
        - { label: "Last clock-out", value: "Tue 14:06, terminal T-04" }
        - { label: "Proposed start", value: "Tue 22:00, shift swap request" }
        - { label: "Computed rest", value: "7 h 54 min" }
        - { label: "Verdict", value: "Blocked: below the 11 h minimum" }
      caption: "Sample data"
  - type: steps
    eyebrow: "How a decision moves"
    title: "Four things happen to every decision, and each one leaves a mark"
    description: "Your HR system, payroll and ERP stay the systems of record for people, pay and production. Hexavera holds the record of the decisions taken between them."
    items:
      - title: "Made"
        description: "A shift assignment, a door permission or a timecard correction is checked against the rules that apply to that person, at that site, on that day."
      - title: "Enforced"
        description: "A decision that breaks a hard rule is blocked where it happens. Rest periods and maximum hours are checked at the site, so a block does not depend on the internet connection."
      - title: "Recorded"
        description: "Each evaluation is stored with the rule version, the parameter values, the input facts and their sources. Records are appended, never overwritten."
      - title: "Explained"
        description: "Any record can be opened as a plain-language explanation: what was decided, which rule applied, where its value comes from and what the facts were."
  - type: cards
    eyebrow: "One platform"
    title: "Three products at the site, four capabilities in the cloud"
    description: "Access, Attendance and Presence run on premises at each plant. Connect, Govern, Automate and Predict run in your cloud tenant. They share one record of decisions. [See how the platform fits together](/platform)."
    columns: 4
    items:
      - title: "Access"
        description: "Doors, readers, credentials, alarms, visitors and guard tours, on a server at your site."
        url: "/products/access"
        link_text: "About Access"
      - title: "Attendance"
        description: "Time capture, shifts, corrections, period close and the payroll export, with legal rules checked on site."
        url: "/products/attendance"
        link_text: "About Attendance"
      - title: "Presence"
        description: "Self-service for employees at a kiosk or in the browser: punches, timecard, schedule, balances and time off."
        url: "/products/presence"
        link_text: "About Presence"
      - title: "Connect"
        description: "Your cloud tenant: people, time and access data from the systems you already run, with the source of every record kept."
        url: "/platform#connect"
        link_text: "About Connect"
      - title: "Govern"
        description: "Rules with their legal sources, scope settings, simulation, compliance records and the reports built on them."
        url: "/platform#govern"
        link_text: "About Govern"
      - title: "Automate"
        description: "The step after a decision: an approval to request, a person to notify."
        url: "/platform#automate"
        link_text: "About Automate"
      - title: "Predict"
        description: "Forward views on your own history, and Vera, the assistant that answers questions about your tenant's data."
        url: "/platform#predict"
        link_text: "About Predict"
  - type: split
    eyebrow: "For works councils"
    title: "Show the works council the rule before it runs"
    markdown: |
      A working-time system that blocks or flags people is a system the works council has a say in. It should be able to read every rule, see where each value comes from and test a change before anyone is affected.

      In Hexavera, rules are data, not code written by an administrator. Each value names its source: the statute, the collective agreement or the plant's own setting. A simulation runs a proposed change over past shifts and lists every decision that would come out differently, without touching a live record.

      [How decisions are explained and simulated](/explained)
    aside:
      type: checklist
      title: "What a reviewer can see"
      items:
        - { text: "The rule and its legal source", description: "Article, section or clause, stored with the rule." }
        - { text: "Every parameter and who set it", description: "Statutory, agreement, company or department level." }
        - { text: "The input facts", description: "Each with the system and record it came from." }
        - { text: "The effect of a change", description: "A simulation over past decisions, kept apart from live records." }
  - type: split
    eyebrow: "Food and beverage"
    title: "Built for plants that run around the clock and audit everything"
    markdown: |
      Food and beverage plants combine hygiene zones, continuous shift patterns, seasonal peaks and agency labour, and every one of them shows up in an audit. Hexavera checks who may enter a high-care area, who may work which shift and whether the rest and hours rules held, and keeps the record an auditor asks for.

      [Hexavera in food and beverage](/food-beverage)
    aside_position: start
    aside:
      type: checklist
      title: "Where the questions come from"
      items:
        - { text: "Hygiene zones and HACCP", description: "Training records decide who passes the gate." }
        - { text: "Three-shift and weekend patterns", description: "Rest and hours checked at every swap." }
        - { text: "Seasonal and agency workers", description: "The same rules for everyone on the line." }
  - type: section
    eyebrow: "Security and deployment"
    title: "Your site keeps running on its own; your cloud tenant is yours alone"
    markdown: |
      Access, Attendance and Presence run on a server at each plant. Doors open, punches are recorded and hard rules are enforced even when the link to the cloud is down.

      In the cloud, each customer has its own tenant with its own database schema. Every account signs in with a second factor, every operator action needs a permission, connector credentials are stored encrypted and changes leave an audit trail. We do not claim a certification we do not hold, and we answer your security questionnaire from the controls as built.

      [Security at Hexavera](/security)
  - type: cta
    variant: dark
    eyebrow: "Compliance diagnostic"
    title: "See what your own history says about rest, hours and qualifications"
    description: "Send us a stretch of your shift and time records under a data processing agreement. We run the rules over it and walk you through every finding, each with its explanation."
    primary_action: { text: "Book a diagnostic", url: "/diagnostic" }
    secondary_action: { text: "Take the product tour", url: "/demo" }
---
