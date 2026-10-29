---
title: "Hexavera Presence: employee self-service, kiosk and web"
description: "Employees punch, check their timecard, schedule and balances, and request time off at a shop-floor kiosk or in the browser. Every request is recorded."
url: "products/presence"
slug: "presence"
locale: "en"
localization_id: "page-presence"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Site product: Presence"
    title: "Employees see their own time and act on it, at a kiosk or in the browser"
    subtitle: "Hexavera Presence is self-service for people on the shop floor and in the office: punches, timecard, schedule, balances and time off. It runs with Attendance at your plant."
    highlights:
      - "Shop-floor kiosk and browser"
      - "Badge plus a site-issued PIN, or badge plus face"
      - "Requests checked by the same rules"
    primary_action: { text: "Book a diagnostic", url: "/diagnostic" }
    secondary_action: { text: "Take the product tour", url: "/demo" }
  - type: cards
    eyebrow: "What it does at the site"
    title: "What an employee can do without asking the office"
    columns: 3
    items:
      - title: "Punch"
        description: "Clock in and out, and start and end breaks, at a kiosk on the shop floor or in the browser where the plant allows it."
      - title: "Timecard"
        description: "See the punches and time results of the current period, and report a missing punch for the supervisor to approve."
      - title: "Schedule"
        description: "See the published plan, own shifts and swaps."
      - title: "Balances"
        description: "Holiday, overtime and other balances as Attendance calculates them."
      - title: "Time off"
        description: "Request leave and follow the request to its decision."
      - title: "Shift swaps"
        description: "Offer or take a shift. The swap is checked against rest and hours rules before it reaches the supervisor."
  - type: split
    eyebrow: "Sign-in at the kiosk"
    title: "The employee number is never the password"
    markdown: |
      Employee numbers are printed on badges and appear in every export, so they cannot prove who is at the kiosk. Presence identifies a person by badge plus a PIN that the site issues and that the employee changes on first use. Where the plant has chosen face recognition, badge plus face replaces the PIN.

      A kiosk shows only the person who signed in, and signs them out after a short time without input.
    aside:
      type: checklist
      title: "Kiosk sign-in"
      items:
        - { text: "Badge plus site-issued PIN", description: "Changed by the employee on first use." }
        - { text: "Or badge plus face", description: "Only where the plant has chosen faces." }
        - { text: "Signed out when idle", description: "The next person starts from a clean screen." }
  - type: section
    eyebrow: "For whom"
    title: "Fewer questions to the office, and answers people can check"
    markdown: |
      **Employees** see the same numbers payroll will use, before the period closes, and can query a missing punch while it is still easy to fix.

      **Supervisors and HR** receive requests that are already checked and complete, instead of notes and phone calls.

      **Works councils** can see that a request is judged by the same written rules for everyone.
  - type: section
    eyebrow: "What it records, and how it feeds Govern"
    title: "Each punch and request is a fact with its source"
    markdown: |
      Presence records each punch with the kiosk or browser it came from, and each request with its answer, the person who decided and the time. Attendance uses the punches for time results. When a swap or a request meets a rule, the evaluation record goes to Govern with the rest, so the decision can be explained to the employee, the works council or an auditor.

      [How a decision is explained](/explained)
  - type: cta
    title: "See Presence with sample data"
    description: "Try the kiosk in the product tour, or book a compliance diagnostic on your own records."
    primary_action: { text: "Book a diagnostic", url: "/diagnostic" }
    secondary_action: { text: "Take the product tour", url: "/demo" }
---
