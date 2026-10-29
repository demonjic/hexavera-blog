---
title: "MES and production systems"
description: "Connect reads line and order schedules from your MES so staffing, coverage and station eligibility are checked against the plan your plant actually runs."
permalink: "/integrations/mes"
slug: "integration-mes"
lang: "en"
id: "page-integration-mes"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Connector: production"
    title: "Staffing decisions against the real production plan"
    subtitle: "Your MES plans lines and orders. Hexavera reads the schedule a staffing decision depends on, and leaves the MES in charge of production."
    primary_action: { text: "Talk to us about your MES", url: "/contact" }
    secondary_action: { text: "All integrations", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "What flows, in which direction"
    markdown: |
      **From the MES to Hexavera**

      - Line schedules and production orders, with their start and end.
      - The stations each line needs staffed.

      **From Hexavera to the MES**

      - Nothing. The connector reads only.

      With the schedule in Hexavera, a shift plan can be checked for coverage per line, and an assignment to a station can be checked against the qualifications that station requires.
    aside:
      type: record
      title: "MES connector"
      status: "On the plan"
      tone: info
      rows:
        - { label: "Runs", value: "In the cloud tenant (Connect)" }
        - { label: "Direction", value: "In, read only" }
        - { label: "Source", value: "Chosen with our first food and beverage customer" }
        - { label: "Milestone", value: "After M2" }
  - type: checklist
    id: "what-you-configure"
    title: "What you configure"
    items:
      - text: "The source"
        description: "Your MES or production planning system, and a read-only account for Hexavera."
      - text: "Lines and stations"
        description: "How the MES names lines and stations, mapped to the sites and areas in Hexavera."
      - text: "The horizon"
        description: "How far ahead the schedule is read, and how often."
  - type: section
    id: "status"
    title: "Status"
    markdown: |
      The MES connector is on the plan after milestone M2. Its first source is chosen with our first food and beverage customer, because production systems differ more from plant to plant than HR or payroll do. Other production systems are sequenced behind customer demand.
  - type: cta
    title: "Which production system do you run?"
    description: "Tell us the system and what your shift planners take from it today."
    primary_action: { text: "Contact us", url: "/contact" }
    secondary_action: { text: "Food and beverage", url: "/food-beverage" }
---
