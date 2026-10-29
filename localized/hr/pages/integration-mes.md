---
title: "MES i proizvodni sustavi"
description: "Connect iz vašeg MES-a čita rasporede linija i naloga, pa se popunjavanje smjena i prikladnost za mjesto na liniji provjeravaju prema stvarnom planu pogona."
url: "integrations/mes"
slug: "integration-mes"
locale: "hr"
localization_id: "page-integration-mes"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Konektor: proizvodnja"
    title: "Odluke o popunjavanju smjena prema stvarnom planu proizvodnje"
    subtitle: "Vaš MES planira linije i naloge. Hexavera čita raspored o kojem ovisi odluka o popunjavanju smjena, a upravljanje proizvodnjom ostavlja MES-u."
    primary_action: { text: "Razgovarajte s nama o svojem MES-u", url: "/contact" }
    secondary_action: { text: "Sve integracije", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "Što se prenosi i u kojem smjeru"
    markdown: |
      **Iz MES-a u Hexaveru**

      - Rasporedi linija i proizvodni nalozi, s početkom i završetkom.
      - Mjesta na svakoj liniji koja moraju biti popunjena.

      **Iz Hexavere u MES**

      - Ništa. Konektor samo čita.

      Kad je raspored u Hexaveri, plan smjena može se provjeriti s obzirom na popunjenost svake linije, a raspored na mjesto na liniji s obzirom na kvalifikacije koje to mjesto zahtijeva.
    aside:
      type: record
      title: "Konektor za MES"
      status: "U planu"
      tone: info
      rows:
        - { label: "Radi", value: "U okruženju u oblaku (Connect)" }
        - { label: "Smjer", value: "Ulazni, samo čitanje" }
        - { label: "Izvor", value: "Odabire se s našim prvim kupcem iz prehrambene industrije" }
        - { label: "Etapa", value: "Nakon M2" }
  - type: checklist
    id: "what-you-configure"
    title: "Što konfigurirate"
    items:
      - text: "Izvor"
        description: "Vaš MES ili sustav za planiranje proizvodnje i račun samo za čitanje za Hexaveru."
      - text: "Linije i mjesta"
        description: "Kako MES naziva linije i mjesta, povezano s pogonima i područjima u Hexaveri."
      - text: "Vremenski obzor"
        description: "Koliko se unaprijed raspored čita i koliko često."
  - type: section
    id: "status"
    title: "Status"
    markdown: |
      Konektor za MES u planu je nakon etape M2. Njegov se prvi izvor odabire s našim prvim kupcem iz prehrambene industrije, jer se proizvodni sustavi od pogona do pogona razlikuju više nego kadrovski sustavi ili obračun plaće. Redoslijed ostalih proizvodnih sustava određuje potražnja kupaca.
  - type: cta
    title: "Koji proizvodni sustav koristite?"
    description: "Navedite nam sustav i što planeri smjena danas iz njega preuzimaju."
    primary_action: { text: "Kontaktirajte nas", url: "/contact" }
    secondary_action: { text: "Hrana i piće", url: "/food-beverage" }
---
