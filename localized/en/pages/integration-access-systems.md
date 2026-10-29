---
title: "Other access control systems"
description: "Already run an access control system? It stays. Connect reads people, credentials and access events from it, and each new system is sequenced behind demand."
permalink: "/integrations/access-systems"
slug: "integration-access-systems"
lang: "en"
id: "page-integration-access-systems"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Connector: access systems"
    title: "Keep the access control system you have"
    subtitle: "If your plant already runs access control, Hexavera does not ask you to replace it. Connect reads from it, so its events feed the same decisions."
    primary_action: { text: "Tell us what you run", url: "/contact" }
    secondary_action: { text: "All integrations", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "What flows, in which direction"
    markdown: |
      **From your access system to Hexavera**

      - People and their credentials, so a passage is attributed to the right person.
      - Access events: passages, denials and alarms, with the reader and the direction.
      - Reader and controller status, so an offline reader is known to be offline.

      **From Hexavera to your access system**

      - Agreed per system. Your access system stays in charge of who may open which door.
    aside:
      type: record
      title: "Other access systems"
      status: "Sequenced behind demand"
      tone: neutral
      rows:
        - { label: "Runs", value: "In the cloud tenant (Connect)" }
        - { label: "Direction", value: "In; writes only where agreed" }
        - { label: "Order", value: "Set by customer requests" }
  - type: checklist
    id: "what-you-configure"
    title: "What you configure"
    items:
      - text: "The source"
        description: "Your access system's server and an account for Hexavera, stored encrypted."
      - text: "Readers and doors"
        description: "Which reader serves which door and direction."
      - text: "People matching"
        description: "How a cardholder in your system matches a person in Hexavera."
  - type: section
    id: "status"
    title: "Status"
    markdown: |
      Every access connector is built on one contract: what a vendor's system can do, stated per capability, with typed results. Hikvision is the first. A further vendor is added when a customer needs it, and it passes the same conformance tests before it ships.

      If you want Hexavera to supply access control instead, that is Hexavera Access.
  - type: cta
    title: "Which access system do you run?"
    description: "Tell us the system, its version and how many sites run it."
    primary_action: { text: "Contact us", url: "/contact" }
    secondary_action: { text: "Hexavera Access", url: "/products/access" }
---
