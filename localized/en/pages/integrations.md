---
title: "Integrations: your systems stay, Hexavera connects"
description: "Hexavera connects to the HRIS, payroll, ERP, access hardware, identity and MES you already run. They stay; the record of each decision lives in Hexavera."
url: "integrations"
slug: "integrations"
locale: "en"
localization_id: "page-integrations"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Integrations"
    title: "Your systems stay. Hexavera connects to them."
    subtitle: "HR, payroll, ERP, access hardware, identity and production systems remain the record for what they hold. Hexavera keeps the record of the workforce decisions made from their data."
    primary_action: { text: "Book a diagnostic", url: "/diagnostic" }
    secondary_action: { text: "Talk to us about your systems", url: "/contact" }
  - type: cards
    id: "systems-that-stay"
    title: "The systems that stay"
    description: "Hexavera does not replace a system of record. It reads what a decision needs and writes back only what you agree."
    columns: 3
    items:
      - title: "HRIS"
        description: "People, employment, organisation and positions stay in your HR system. Hexavera reads them and keeps them current."
      - title: "Payroll"
        description: "Payroll keeps calculating pay. Hexavera hands it the hours and the evidence behind them, in a format your payroll reads."
      - title: "ERP"
        description: "Cost centres and the company structure stay in your ERP or HR system. Hexavera uses them to scope rules and reports."
      - title: "Access hardware"
        description: "Door controllers and readers keep their place on the wall. Hexavera Access drives them, or Connect reads from the access system you already run."
      - title: "Identity"
        description: "People sign in with the work accounts your organisation already manages. Roles and permissions are kept in Hexavera."
      - title: "MES"
        description: "Production systems keep planning lines and orders. Hexavera reads the schedules a staffing decision depends on."
  - type: steps
    id: "how-connect-works"
    title: "How Connect works"
    description: "Connect is the part of the cloud tenant that talks to your other systems."
    items:
      - title: "Connect"
        description: "A connector reaches one system with credentials you issue for it. Hexavera stores those credentials encrypted."
      - title: "Map"
        description: "You map the source's companies, codes and fields to Hexavera's data domains, such as people and organisation, or time and pay."
      - title: "Sync"
        description: "Each sync run is recorded: what arrived, what changed and what was refused, so a reviewer can trace any value to its source."
      - title: "Decide"
        description: "Rules run on the synced data. The decision, its inputs and its explanation are kept in Hexavera, next to the source ids they came from."
  - type: section
    id: "record-stays"
    title: "The record stays in Hexavera"
    markdown: |
      A source system tells Hexavera what is true about a person, a shift or a door. Hexavera records what was decided from it: who was allowed in, which hours count, which assignment was blocked and under which rule.

      That decision record does not move back into the source systems. It stays in your Hexavera tenant, where a works council, an auditor or your own team can read it. Each tenant belongs to one operating company, even when a group shares one HR system.
  - type: cards
    id: "connectors"
    title: "Connectors"
    description: "Each page states what flows in which direction, what you configure and the status. **On the plan** names the delivery milestone: M1 Access at the site, M2 the first Connect delivery, M3 the compliance diagnostic, M4 Attendance and Presence, M5 Govern."
    columns: 3
    items:
      - title: "Hikvision access control"
        description: "People, cards and schedules out to the panels; access events back. Driven by Hexavera Access at the site."
        url: "/integrations/hikvision"
        link_text: "Hikvision connector"
        items: ["Built; first site release at M1"]
      - title: "Hexavera Access to Attendance"
        description: "The access event feed, with its gaps marked, as the input to time results."
        url: "/integrations/access-to-attendance"
        link_text: "Access to Attendance"
        items: ["On the plan: M1 and M4"]
      - title: "Other access systems"
        description: "Keep the access control system you run. Connect reads people, credentials and events from it."
        url: "/integrations/access-systems"
        link_text: "Other access systems"
        items: ["Sequenced behind customer demand"]
      - title: "SAP SuccessFactors"
        description: "People, organisation, positions, cost centres and time records in; time records back."
        url: "/integrations/sap-successfactors"
        link_text: "SAP SuccessFactors connector"
        items: ["In development; on the plan: M2"]
      - title: "Microsoft Entra ID"
        description: "Sign-in with your organisation's work accounts. Hexavera does not write to your directory."
        url: "/integrations/microsoft-entra-id"
        link_text: "Microsoft Entra ID sign-in"
        items: ["On the plan: M2"]
      - title: "File import"
        description: "CSV files into people, organisation and time, with validation and a report of every refused row."
        url: "/integrations/file-import"
        link_text: "File import"
        items: ["On the plan: M2"]
      - title: "Payroll"
        description: "An access-event extract per payroll period first, then time results in your payroll's format."
        url: "/integrations/payroll"
        link_text: "Payroll export"
        items: ["On the plan: M2 and M4"]
      - title: "MES and production systems"
        description: "Line and order schedules in, so coverage and station eligibility are checked against real plans."
        url: "/integrations/mes"
        link_text: "MES connector"
        items: ["On the plan after M2"]
  - type: section
    id: "further-connectors"
    title: "Further connectors"
    markdown: |
      We build connectors for one vertical, food and beverage, and we build them properly before we build more. Further connectors are sequenced behind customer demand. If you run a system that is not listed here, tell us which one and what you need from it. Your request is recorded and weighed when we set the order.

      Vendor names on these pages describe compatibility only. They do not imply a partnership, a certification or a marketplace listing.
  - type: cta
    title: "Map your systems with us"
    description: "Bring the list of systems at your plant. We tell you what connects today, what is on the plan and what would be built for you."
    primary_action: { text: "Book a diagnostic", url: "/diagnostic" }
    secondary_action: { text: "Contact us", url: "/contact" }
---
