---
title: "Hikvision access control with Hexavera Access"
description: "Hexavera Access drives Hikvision access controllers over ISAPI: people, cards, schedules and door commands out, access events in, at your site."
url: "integrations/hikvision"
slug: "integration-hikvision"
locale: "en"
localization_id: "page-integration-hikvision"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Connector: access hardware"
    title: "Hikvision access controllers, driven by Hexavera Access"
    subtitle: "Hexavera Access works with Hikvision access controllers that expose the ISAPI interface. It runs on a server at your site and talks to the panels on your network."
    primary_action: { text: "Talk to us about your site", url: "/contact" }
    secondary_action: { text: "All integrations", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "What flows, in which direction"
    markdown: |
      **From Hexavera to the panels**

      - People and their cards, and fingerprints or faces where your site enrols them.
      - Access levels and the time schedules that go with them.
      - Door commands: open once, or set a door's mode, each one checked against the operator's permission and recorded.
      - Device operations: discovery, enrolment, health checks, time synchronisation and restart.

      **From the panels to Hexavera**

      - Access events: granted and denied passages, door alarms and device alarms.
      - Device status, so an offline panel or reader is shown as offline, not as a quiet door.

      Events arrive pushed by the panel, and Hexavera also reads them back by sequence, so events held on a panel during a network outage are collected when it returns.
    aside:
      type: record
      title: "Hikvision connector"
      status: "Built"
      tone: success
      rows:
        - { label: "Runs", value: "At the site, with Hexavera Access" }
        - { label: "Interface", value: "Hikvision ISAPI" }
        - { label: "Direction", value: "Both ways" }
        - { label: "Milestone", value: "M1, first site release of Access" }
  - type: checklist
    id: "what-you-configure"
    title: "What you configure"
    items:
      - text: "The panels"
        description: "Each panel's network address, and the account Hexavera uses on it. That account is stored encrypted on the site server and never shown again."
      - text: "Doors and readers"
        description: "Which reader serves which door, and in which direction, so every passage is attributed to a door and a direction."
      - text: "Access levels and schedules"
        description: "Who may pass which doors, and when."
      - text: "Event delivery"
        description: "Where the panels push their events. Hexavera reads back anything a push missed."
      - text: "Link security"
        description: "The TLS mode of each panel's link. With Access Release 1, PINs and biometric templates are written only over a verified TLS link; a panel on plain HTTP takes cards only."
  - type: section
    id: "status"
    title: "Status"
    markdown: |
      The Hikvision connector is built and runs against Hikvision panels. Its first site release ships with Hexavera Access Release 1, milestone M1. Release 1 moves the connector into its own service on the site server, the only process that holds the panel accounts, reaching the panels over a mutually authenticated link.

      Hikvision is named to describe compatibility only. Hexavera holds no partnership with the vendor.
  - type: cta
    title: "Running Hikvision panels today?"
    description: "Tell us the panel models and how many doors you run. We tell you what Hexavera Access does with them."
    primary_action: { text: "Contact us", url: "/contact" }
    secondary_action: { text: "Hexavera Access", url: "/products/access" }
---
