---
title: "SAP SuccessFactors connector"
description: "Connect reads people, organisation, positions, cost centres and time from SAP SuccessFactors into your Hexavera tenant, and writes time records back."
url: "integrations/sap-successfactors"
slug: "integration-sap-successfactors"
locale: "en"
localization_id: "page-integration-sap-successfactors"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Connector: HRIS"
    title: "SAP SuccessFactors stays your HR record"
    subtitle: "Connect works with SAP SuccessFactors through its OData API. Your HR data stays authoritative there; Hexavera reads what workforce decisions need."
    primary_action: { text: "Talk to us about your landscape", url: "/contact" }
    secondary_action: { text: "All integrations", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "What flows, in which direction"
    markdown: |
      **From SuccessFactors to Hexavera**

      - People and their employment records.
      - The organisation: companies, departments and positions.
      - Cost centres.
      - Compensation, where your contract includes the time and pay domain.
      - Time records held in SuccessFactors.

      **From Hexavera to SuccessFactors**

      - Time records, written back as external time records.

      Access, rules and decisions are not written into SuccessFactors. They stay in Hexavera.
    aside:
      type: record
      title: "SAP SuccessFactors connector"
      status: "In development"
      tone: info
      rows:
        - { label: "Runs", value: "In the cloud tenant (Connect)" }
        - { label: "Interface", value: "SuccessFactors OData API" }
        - { label: "Direction", value: "Mostly in; time records out" }
        - { label: "Milestone", value: "M2, the first Connect delivery" }
  - type: checklist
    id: "what-you-configure"
    title: "What you configure"
    items:
      - text: "The API server"
        description: "The SuccessFactors API address of your data centre and your company id."
      - text: "The OAuth client"
        description: "An OAuth 2.0 client you register in SuccessFactors for Hexavera. Its credentials are stored encrypted. Where your group requires the SAML bearer grant, M2 adds it."
      - text: "Your company"
        description: "Which company's employees this tenant receives. With M2 the filter is applied at the source, so a tenant never holds another company's rows."
      - text: "The data domains"
        description: "Which domains you sync: people and organisation, or time and pay as well."
      - text: "The schedule"
        description: "How often the connection syncs. Every run is recorded with what changed and what was refused."
  - type: section
    id: "groups"
    title: "Groups that share one SuccessFactors"
    markdown: |
      Many groups run one SuccessFactors instance for several operating companies. In Hexavera each operating company is its own tenant. Each tenant has its own connection, filtered to its own company, so one company's HR data never lands in another company's tenant.
  - type: section
    id: "status"
    title: "Status"
    markdown: |
      The connector is in development: the reads and the time write-back are built. Production delivery is on the plan for milestone M2, with a recurring schedule, filtering at the source, conflict review on screen and sync history on screen.

      SAP and SuccessFactors are named to describe compatibility only. Hexavera holds no partnership with SAP.
  - type: cta
    title: "Running SuccessFactors across a group?"
    description: "Tell us how your companies are set up in SuccessFactors. We show you how the tenants and connections would map."
    primary_action: { text: "Contact us", url: "/contact" }
    secondary_action: { text: "Book a diagnostic", url: "/diagnostic" }
---
