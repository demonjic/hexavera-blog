---
title: "Hexavera Access prema modulu Attendance"
description: "Hexavera Access objavljuje svaki prolaz s označenim prazninama. Attendance taj tok čita u pogonu i zajedno sa smjenama pretvara ga u radno vrijeme."
url: "integrations/access-to-attendance"
slug: "integration-access-to-attendance"
locale: "hr"
localization_id: "page-integration-access-to-attendance"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Konektor: proizvodi Hexavera"
    title: "Od događaja na vratima do radnog vremena, s prazninama na vidjelu"
    subtitle: "Access i Attendance rade jedan uz drugi u vašem pogonu. Access objavljuje što se dogodilo na vratima, a Attendance to čita i kaže što to znači za radno vrijeme."
    primary_action: { text: "Zatražite dijagnostiku", url: "/diagnostic" }
    secondary_action: { text: "Sve integracije", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "Što se prenosi i u kojem smjeru"
    markdown: |
      **Iz modula Access u Attendance**

      - Svaki prolaz: osoba, čitač, vrata, smjer i vrijeme.
      - Pokrivenost: koji su čitači bili izvan mreže, koji su događaji izgubljeni i koliko je odstupao sat svakog panela.

      **Iz modula Attendance u Access**

      - Ništa. Ispravci radnog vremena unose se u Attendance i ne mijenjaju zapise o pristupu.

      Budući da tok sam označava svoje praznine, Attendance čitač koji je utihnuo nikad ne tumači kao osobu koja je ostala kod kuće.
    aside:
      type: record
      title: "Access prema modulu Attendance"
      status: "U planu"
      tone: info
      rows:
        - { label: "Radi", value: "U pogonu" }
        - { label: "Smjer", value: "Iz modula Access u Attendance" }
        - { label: "Tok događaja i izvješće o kvaliteti podataka", value: "M1" }
        - { label: "Attendance čita tok", value: "M4" }
  - type: checklist
    id: "what-you-configure"
    title: "Što konfigurirate"
    items:
      - text: "Koji se čitači računaju"
        description: "Čitači čiji se prolazi računaju kao početak ili kraj rada, i u kojem smjeru."
      - text: "Smjene"
        description: "Smjene i rotacije s kojima Attendance uspoređuje prolaze."
      - text: "Pravila"
        description: "Zaokruživanje, tolerancija kašnjenja i pravila o radnom vremenu koja vrijede za pojedini pogon, odjel ili skupinu."
  - type: section
    id: "status"
    title: "Status"
    markdown: |
      Tok događaja i izvješće o kvaliteti podataka u planu su za etapu M1, s modulom Hexavera Access u pogonu. Izvješće o kvaliteti podataka po čitaču i po danu pokazuje što vaši događaji na vratima mogu, a što ne mogu reći obračunu plaće. Attendance čita tok od etape M4.
  - type: cta
    title: "Što vaši događaji na vratima danas govore obračunu plaće?"
    description: "Izvješće o kvaliteti podataka na to odgovara iz vaših vlastitih događaja."
    primary_action: { text: "Kontaktirajte nas", url: "/contact" }
    secondary_action: { text: "Hexavera Attendance", url: "/products/attendance" }
---
