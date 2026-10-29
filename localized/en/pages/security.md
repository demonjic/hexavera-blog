---
title: "Security: the controls, described as built"
description: "How Hexavera protects workforce data: where it runs, tenant isolation, sign-in with a second factor, permissions, encryption, audit trails and data residency."
permalink: "/security"
slug: "security"
lang: "en"
id: "page-security"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Security"
    title: "Controls a security reviewer can check"
    subtitle: "This page lists the controls Hexavera has in place today, and the ones on the delivery plan with their milestone. Nothing here is a promise we cannot show you."
    primary_action: { text: "Send us your questionnaire", url: "/contact" }
    secondary_action: { text: "Privacy policy", url: "/privacy" }
  - type: split
    id: "deployment"
    title: "Where Hexavera runs"
    markdown: |
      **At the site.** Access, Attendance and Presence run on a server at your plant, on your network. One site server holds one tenant. Hexavera Access keeps working when the link to the cloud is down; doors, credentials and events do not depend on it.

      **In the cloud tenant.** Connect, Govern, Automate and Predict run in a cloud tenant, one per operating company. A site can run standalone, with no cloud tenant at all, or connected to one.
    aside:
      type: checklist
      title: "In place today"
      items:
        - text: "Second factor"
          description: "For every account, with passkeys"
        - text: "Permissions"
          description: "Behind every operator action"
        - text: "Tenant isolation"
          description: "A database schema per cloud tenant"
        - text: "Audit trail"
          description: "Sign-ins and operator actions recorded"
  - type: cards
    id: "controls"
    title: "The controls"
    columns: 3
    items:
      - title: "Tenant isolation"
        description: "In the cloud, each tenant's data lives in its own database schema with a generated name. A site server holds one tenant. In a group, a parent company's administrator manages the companies below it and nothing else."
      - title: "Identity and sign-in"
        description: "Every account signs in through Hexavera's own identity service with a second factor or a passkey. Sessions have limited lifetimes and can be ended from one place. Sign-in with Microsoft Entra ID is on the plan for M2."
      - title: "Permissions"
        description: "Role-based permissions sit behind every operator action and are checked on the server for every request, not only in the screen."
      - title: "Encryption"
        description: "Traffic between Hexavera's own services is encrypted. The credentials Hexavera uses to reach your systems are stored encrypted. With Access Release 1 (M1), panels are reached over a mutually authenticated link, and PINs and biometric templates are written only over verified TLS."
      - title: "Audit trail"
        description: "Sign-ins and operator actions are recorded with who acted and when. With M3, every rule decision is kept in an append-only record with the inputs it used."
      - title: "Vera, the assistant"
        description: "Vera reads tenant data through the same API and the same permissions as the person asking. It sees nothing that person could not open."
  - type: section
    id: "data-residency"
    title: "Where your data is kept"
    markdown: |
      - **Site data stays on your server.** Access events, credentials and the site's audit trail are held at the site. A standalone site sends nothing to the cloud.
      - **The cloud tenant runs in an EU region.** The first production tenant is on the plan for milestone M2, in an EU region.
      - **Each company keeps its own data.** When a group shares one HR system, each company's connection is filtered at the source (M2), so a tenant never holds another company's people.
      - **Personal data from a prospect** is accepted for the compliance diagnostic only under a data processing agreement, signed before the first file is sent.

      The GDPR is the law your workforce data is handled under. If your plant falls under NIS2, your supplier assessment will ask about these controls, and we answer it from them.
  - type: section
    id: "certification"
    title: "Certification"
    markdown: |
      Hexavera holds no security certification or attestation today, and we do not claim one. Send us your security questionnaire and we answer it from the controls as built. We will publish our certification status here as it changes.
  - type: section
    id: "responsible-disclosure"
    title: "Responsible disclosure"
    markdown: |
      If you believe you have found a vulnerability in Hexavera or on this website, please tell us through the [contact form](/contact) and start your message with "Security". Include what you found and how to reproduce it.

      Please give us a reasonable time to investigate and fix it before you make it public, and do not access, change or delete data that is not yours while you test. We reply to agree the next steps with you.
  - type: cta
    title: "Review our controls with your security team"
    description: "We walk your security lead through the architecture and answer your questionnaire from the controls as built."
    primary_action: { text: "Contact us", url: "/contact" }
    secondary_action: { text: "Integrations", url: "/integrations" }
---
