---
title: "Prijava putem Microsoft Entra ID-ja"
description: "Operateri i zaposlenici prijavljuju se u Hexaveru poslovnim računima Microsoft Entra ID. Uloge ostaju u Hexaveri, koja nikad ne zapisuje ništa u vaš imenik."
permalink: "/integrations/microsoft-entra-id"
slug: "integration-microsoft-entra-id"
lang: "hr"
id: "page-integration-microsoft-entra-id"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Konektor: identitet"
    title: "Prijava poslovnim računima kojima već upravljate"
    subtitle: "Usluga identiteta u Hexaveri radi s Microsoft Entra ID-jem kao pružateljem prijave. Ljudi koriste svoj poslovni račun, a vaš imenik ostaje mjesto na kojem se računi otvaraju i zatvaraju."
    primary_action: { text: "Razgovarajte s nama o prijavi", url: "/contact" }
    secondary_action: { text: "Sigurnost", url: "/security" }
  - type: split
    id: "what-flows"
    title: "Što se prenosi i u kojem smjeru"
    markdown: |
      **Iz Entra ID-ja u Hexaveru**

      - Sama prijava: Entra ID potvrđuje tko je osoba.
      - Tvrdnje (claims) koje su Hexaveri potrebne da bi račun povezala s osobom u vašem okruženju.

      **Iz Hexavere u Entra ID**

      - Ništa. Hexavera u vašem imeniku ne stvara, ne mijenja i ne briše račune ni grupe.

      Uloge i ovlaštenja vode se u Hexaveri, pa se o tome što osoba smije raditi odlučuje na jednom mjestu i ondje se to i bilježi.
    aside:
      type: record
      title: "Microsoft Entra ID"
      status: "U planu"
      tone: info
      rows:
        - { label: "Radi", value: "Usluga identiteta u Hexaveri" }
        - { label: "Protokol", value: "OpenID Connect" }
        - { label: "Smjer", value: "Samo prijava" }
        - { label: "Etapa", value: "M2, prva isporuka modula Connect" }
  - type: checklist
    id: "what-you-configure"
    title: "Što konfigurirate"
    items:
      - text: "Registraciju aplikacije"
        description: "Registriranu u vašem Entra okruženju (tenantu) za Hexaveru."
      - text: "Vaš imenik"
        description: "Identifikator vašeg Entra tenanta. Hexavera prihvaća prijave samo iz tog imenika."
      - text: "Vaše domene"
        description: "Domene e-pošte za koje dokažete da su vaše, kako bi se prijave za njih usmjeravale u vaš imenik."
      - text: "Tko se smije prijaviti"
        description: "Koje se osobe u vašem okruženju Hexavera prijavljuju putem Entra ID-ja i koje uloge imaju u Hexaveri."
  - type: section
    id: "status"
    title: "Status"
    markdown: |
      Prijava putem Entra ID-ja u planu je za etapu M2. Do tada se svaki račun prijavljuje u vlastitu uslugu identiteta Hexavera uz drugi faktor autentifikacije ili pristupni ključ (passkey).

      Zapisivanje u vaš imenik, primjerice otvaranje računa za novozaposlene, jest dodjela računa (provisioning). Ono nije dio ovog konektora i ugovara se zasebno ako vam je potrebno.

      Microsoft i Entra navode se samo radi opisa kompatibilnosti. Hexavera nema partnerstvo s Microsoftom.
  - type: cta
    title: "Planirajte prijavu zajedno sa svojim timom za identitete"
    description: "S vašim voditeljem za identitete prolazimo kroz registraciju, domene i uloge prije nego što se išta uključi."
    primary_action: { text: "Kontaktirajte nas", url: "/contact" }
    secondary_action: { text: "Sve integracije", url: "/integrations" }
---
