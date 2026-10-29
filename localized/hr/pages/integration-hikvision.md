---
title: "Kontrola pristupa Hikvision uz Hexavera Access"
description: "Hexavera Access upravlja kontrolerima pristupa Hikvision putem ISAPI-ja: osobe, kartice, rasporedi i naredbe vratima idu prema panelima, a događaji se vraćaju."
url: "integrations/hikvision"
slug: "integration-hikvision"
locale: "hr"
localization_id: "page-integration-hikvision"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Konektor: oprema za kontrolu pristupa"
    title: "Kontroleri pristupa Hikvision kojima upravlja Hexavera Access"
    subtitle: "Hexavera Access radi s kontrolerima pristupa Hikvision koji nude sučelje ISAPI. Radi na poslužitelju u vašem pogonu i s panelima komunicira u vašoj mreži."
    primary_action: { text: "Razgovarajte s nama o svojem pogonu", url: "/contact" }
    secondary_action: { text: "Sve integracije", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "Što se prenosi i u kojem smjeru"
    markdown: |
      **Iz Hexavere prema panelima**

      - Osobe i njihove kartice te otisci prstiju ili lica ondje gdje ih vaš pogon upisuje.
      - Razine pristupa i vremenski rasporedi koji uz njih idu.
      - Naredbe vratima: jednokratno otvaranje ili postavljanje načina rada vrata, pri čemu se svaka naredba provjerava prema ovlaštenju operatera i bilježi.
      - Radnje na uređajima: otkrivanje, upis, provjera stanja, usklađivanje vremena i ponovno pokretanje.

      **Iz panela u Hexaveru**

      - Događaji pristupa: odobreni i odbijeni prolazi, alarmi vrata i alarmi uređaja.
      - Stanje uređaja, pa se panel ili čitač izvan mreže prikazuje kao izvan mreže, a ne kao vrata kroz koja nitko ne prolazi.

      Panel sam šalje događaje, a Hexavera ih i naknadno čita prema rednom broju, pa se događaji koje je panel zadržao tijekom prekida mreže preuzimaju kad se veza vrati.
    aside:
      type: record
      title: "Konektor za Hikvision"
      status: "Izrađeno"
      tone: success
      rows:
        - { label: "Radi", value: "U pogonu, s modulom Hexavera Access" }
        - { label: "Sučelje", value: "Hikvision ISAPI" }
        - { label: "Smjer", value: "U oba smjera" }
        - { label: "Etapa", value: "M1, prvo izdanje modula Access za pogon" }
  - type: checklist
    id: "what-you-configure"
    title: "Što konfigurirate"
    items:
      - text: "Panele"
        description: "Mrežnu adresu svakog panela i račun koji Hexavera na njemu koristi. Taj se račun pohranjuje šifriran na poslužitelju u pogonu i više se nikad ne prikazuje."
      - text: "Vrata i čitače"
        description: "Koji čitač služi kojim vratima i u kojem smjeru, kako bi se svaki prolaz pripisao vratima i smjeru."
      - text: "Razine pristupa i rasporede"
        description: "Tko smije prolaziti kroz koja vrata i kada."
      - text: "Isporuku događaja"
        description: "Kamo paneli šalju svoje događaje. Hexavera naknadno čita sve što slanje nije isporučilo."
      - text: "Sigurnost veze"
        description: "Način TLS-a za vezu sa svakim panelom. Od izdanja Access Release 1 PIN-ovi i biometrijski predlošci zapisuju se samo preko provjerene TLS veze; panel na običnom HTTP-u prima samo kartice."
  - type: section
    id: "status"
    title: "Status"
    markdown: |
      Konektor za Hikvision izrađen je i radi s panelima Hikvision. Njegovo prvo izdanje za pogon isporučuje se s izdanjem Hexavera Access Release 1, u etapi M1. Release 1 premješta konektor u zasebnu uslugu na poslužitelju u pogonu, jedini proces koji čuva račune panela, a do panela dolazi preko obostrano autentificirane veze.

      Hikvision se navodi samo radi opisa kompatibilnosti. Hexavera nema partnerstvo s tim proizvođačem.
  - type: cta
    title: "Već koristite panele Hikvision?"
    description: "Navedite nam modele panela i broj vrata. Reći ćemo vam što Hexavera Access s njima radi."
    primary_action: { text: "Kontaktirajte nas", url: "/contact" }
    secondary_action: { text: "Hexavera Access", url: "/products/access" }
---
