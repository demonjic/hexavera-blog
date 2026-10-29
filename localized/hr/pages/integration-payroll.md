---
title: "Obračun plaće: sati i njihovi dokazi, u vašem formatu"
description: "Hexavera obračunu plaće najprije daje izvadak događaja pristupa za svako razdoblje, a zatim odobreno radno vrijeme iz modula Attendance u formatu vašeg sustava."
url: "integrations/payroll"
slug: "integration-payroll"
locale: "hr"
localization_id: "page-integration-payroll"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Konektor: obračun plaće"
    title: "Obračun plaće i dalje izračunava plaće. Hexavera isporučuje sate."
    subtitle: "Vaš sustav za obračun plaće ostaje. Hexavera mu za svako razdoblje predaje ono što mu je potrebno, uz dokaze koji pokazuju odakle potječe svaka brojka."
    primary_action: { text: "Razgovarajte s nama o obračunu plaće", url: "/contact" }
    secondary_action: { text: "Sve integracije", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "Što se prenosi i u kojem smjeru"
    markdown: |
      Sve se prenosi prema van, iz Hexavere u obračun plaće, u dva koraka.

      **1. korak: izvadak događaja pristupa (M2)**

      - Dokumentiran izvadak događaja pristupa s oznakom verzije, za svako obračunsko razdoblje.
      - Priloženo izvješće o kvaliteti podataka: koji se prolazi mogu pripisati osobi i smjeru, koji su čitači bili izvan mreže i što događaji ne mogu reći obračunu plaće.

      **2. korak: radno vrijeme iz modula Attendance (M4)**

      - Odrađeni sati po osobi i danu, uz zaokruživanje i pravila o radnom vremenu primijenjena u pogonu.
      - Tek nakon unosa ispravaka i zatvaranja razdoblja uz odobrenje.
      - U formatu datoteke vašeg sustava za obračun plaće.
    aside:
      type: record
      title: "Obračun plaće"
      status: "U planu"
      tone: info
      rows:
        - { label: "Smjer", value: "Izlazni, prema obračunu plaće" }
        - { label: "1. korak", value: "Izvadak događaja pristupa, M2" }
        - { label: "2. korak", value: "Radno vrijeme iz modula Attendance, M4" }
        - { label: "Format", value: "Uvozni format vašeg sustava za obračun plaće" }
  - type: checklist
    id: "what-you-configure"
    title: "Što konfigurirate"
    items:
      - text: "Obračunsko razdoblje"
        description: "Tjedno, dvotjedno ili mjesečno te dan zatvaranja."
      - text: "Brojeve zaposlenika"
        description: "Kako se osoba u Hexaveri povezuje s osobom u obračunu plaće."
      - text: "Vrste primitaka"
        description: "Koje se radno vrijeme knjiži na koju šifru: redovni sati, prekovremeni rad, noćni rad, odsutnost."
      - text: "Isporuku"
        description: "Kamo datoteka odlazi i tko odobrava razdoblje prije slanja."
  - type: section
    id: "status"
    title: "Status"
    markdown: |
      Izvadak događaja pristupa u planu je za etapu M2. Radno vrijeme u formatu vašeg sustava za obračun plaće slijedi s modulom Attendance u etapi M4. Prvi format izvoza bit će format sustava za obračun plaće našeg prvog kupca modula Attendance; redoslijed daljnjih formata određuje potražnja kupaca.

      Sami događaji na vratima nisu radno vrijeme. Izvadak to izričito navodi, a izvješće o kvaliteti podataka pokazuje gdje su praznine. Attendance je ono što događaje i smjene pretvara u sate na koje se obračun plaće može osloniti.
  - type: cta
    title: "Koji sustav za obračun plaće koristite?"
    description: "Navedite nam sustav i datoteku koju uvozi. Reći ćemo vam gdje je u redoslijedu."
    primary_action: { text: "Kontaktirajte nas", url: "/contact" }
    secondary_action: { text: "Hexavera Attendance", url: "/products/attendance" }
---
