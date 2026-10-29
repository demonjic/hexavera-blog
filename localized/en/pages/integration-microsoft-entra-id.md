---
title: "Microsoft Entra ID sign-in"
description: "Operators and employees sign in to Hexavera with their Microsoft Entra ID work accounts. Roles stay in Hexavera, and Hexavera never writes to your directory."
url: "integrations/microsoft-entra-id"
slug: "integration-microsoft-entra-id"
locale: "en"
localization_id: "page-integration-microsoft-entra-id"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Connector: identity"
    title: "Sign in with the work accounts you already manage"
    subtitle: "Hexavera's identity service works with Microsoft Entra ID as a sign-in provider. People use their work account; your directory stays the place where accounts are created and closed."
    primary_action: { text: "Talk to us about sign-in", url: "/contact" }
    secondary_action: { text: "Security", url: "/security" }
  - type: split
    id: "what-flows"
    title: "What flows, in which direction"
    markdown: |
      **From Entra ID to Hexavera**

      - The sign-in itself: Entra ID confirms who the person is.
      - The claims Hexavera needs to match the account to a person in your tenant.

      **From Hexavera to Entra ID**

      - Nothing. Hexavera does not create, change or delete accounts or groups in your directory.

      Roles and permissions are held in Hexavera, so what a person may do is decided in one place and recorded there.
    aside:
      type: record
      title: "Microsoft Entra ID"
      status: "On the plan"
      tone: info
      rows:
        - { label: "Runs", value: "Hexavera identity service" }
        - { label: "Protocol", value: "OpenID Connect" }
        - { label: "Direction", value: "Sign-in only" }
        - { label: "Milestone", value: "M2, the first Connect delivery" }
  - type: checklist
    id: "what-you-configure"
    title: "What you configure"
    items:
      - text: "An app registration"
        description: "Registered in your Entra tenant for Hexavera."
      - text: "Your directory"
        description: "Your Entra tenant's id. Hexavera accepts sign-ins from that directory only."
      - text: "Your domains"
        description: "The email domains you prove are yours, so sign-ins for them are routed to your directory."
      - text: "Who may sign in"
        description: "Which people in your Hexavera tenant sign in with Entra ID, and the roles they hold in Hexavera."
  - type: section
    id: "status"
    title: "Status"
    markdown: |
      Entra ID sign-in is on the plan for milestone M2. Until then, every account signs in to Hexavera's own identity service with a second factor or a passkey.

      Writing to your directory, such as creating accounts for new starters, is provisioning. It is outside this connector and is scoped separately if you need it.

      Microsoft and Entra are named to describe compatibility only. Hexavera holds no partnership with Microsoft.
  - type: cta
    title: "Plan sign-in with your identity team"
    description: "We walk your identity lead through the registration, the domains and the roles before anything is switched on."
    primary_action: { text: "Contact us", url: "/contact" }
    secondary_action: { text: "All integrations", url: "/integrations" }
---
