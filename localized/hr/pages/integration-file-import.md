---
title: "Uvoz datoteka: osobe, organizacija i radno vrijeme"
description: "Uvezite CSV datoteke s osobama, organizacijom i evidencijom radnog vremena u svoje okruženje Hexavera, uz provjeru i izvješće o svakom odbijenom retku."
url: "integrations/file-import"
slug: "integration-file-import"
locale: "hr"
localization_id: "page-integration-file-import"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Konektor: datoteke"
    title: "Kad sustav nema API, poslužit će datoteka"
    subtitle: "Neki sustavi podatke izvoze samo u datoteke. Neka povijest postoji samo u datotekama. Uvoz datoteka i jedno i drugo unosi u vaše okruženje, uz provjeru redak po redak."
    primary_action: { text: "Zatražite dijagnostiku", url: "/diagnostic" }
    secondary_action: { text: "Sve integracije", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "Što se prenosi i u kojem smjeru"
    markdown: |
      **Iz vaših datoteka u Hexaveru**

      - Osobe i organizacija: zaposlenici, odjeli, radna mjesta, mjesta troška.
      - Radno vrijeme: dolasci i odlasci, odrađeni sati i odsutnosti, uključujući višegodišnju povijest.

      **Natrag vama**

      - Izvješće o odbijenim retcima. Svaki odbijeni redak naveden je s razlogom, pa ga ispravite u izvoru i ponovno uvezete.

      Na uvezenoj povijesti provodi se dijagnostika usklađenosti: pravila se primjenjuju na vaše vlastite prošle zapise.
    aside:
      type: record
      title: "Uvoz datoteka"
      status: "U planu"
      tone: info
      rows:
        - { label: "Radi", value: "U okruženju u oblaku (Connect)" }
        - { label: "Format", value: "CSV" }
        - { label: "Smjer", value: "Ulazni, s izvješćem o odbijenim retcima" }
        - { label: "Etapa", value: "M2, prva isporuka modula Connect" }
  - type: checklist
    id: "what-you-configure"
    title: "Što konfigurirate"
    items:
      - text: "Područje podataka"
        description: "Sadrži li datoteka osobe i organizaciju ili radno vrijeme."
      - text: "Mapiranje stupaca"
        description: "Koji je stupac broj zaposlenika, datum, početak i kraj."
      - text: "Datumi i vremenska zona"
        description: "Format datuma i vremenska zona u kojoj je izvor zapisao vremena."
      - text: "Što se događa s neispravnim retkom"
        description: "Odbijeni retci nikad ne ulaze u evidenciju. Vraćaju se u izvješću."
  - type: section
    id: "status"
    title: "Status"
    markdown: |
      Uvoz datoteka u planu je za etapu M2, najprije za osobe, organizaciju i povijest radnog vremena.

      Datoteke s osobnim podacima primamo samo uz ugovor o obradi podataka. Taj se ugovor potpisuje prije slanja prve datoteke.
  - type: cta
    title: "Imate višegodišnju evidenciju radnog vremena u datotekama?"
    description: "Recite nam što imate i u kojem formatu. Reći ćemo vam što dijagnostika iz toga može pročitati."
    primary_action: { text: "Zatražite dijagnostiku", url: "/diagnostic" }
    secondary_action: { text: "Kontaktirajte nas", url: "/contact" }
---
