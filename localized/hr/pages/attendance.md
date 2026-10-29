---
title: "Hexavera Attendance: radno vrijeme, smjene i obračun plaće"
description: "Evidencija radnog vremena, smjene, ispravci, zatvaranje razdoblja i izvoz za obračun plaće, uz provjeru odmora i radnog vremena u pogonu prije dodjele smjene."
url: "products/attendance"
slug: "attendance"
locale: "hr"
localization_id: "page-attendance"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Proizvod u pogonu: Attendance"
    title: "Od evidentiranog dolaska do datoteke za obračun plaće, uz provjeru pravila usput"
    subtitle: "Hexavera Attendance radi u vašem pogonu. Prolaze i evidentirane dolaske i odlaske pretvara u radno vrijeme, planira i objavljuje smjene, zatvara razdoblje i izrađuje izvoz za obračun plaće. Odmori i najdulje radno vrijeme provjeravaju se u pogonu, prije dodjele smjene."
    highlights:
      - "Smjene, rotacije, zamjene i pokrivanje odsutnosti"
      - "Ispravci i zatvaranje razdoblja uz odobrenje"
      - "Zakonska pravila provode se i bez veze s oblakom"
    primary_action: { text: "Zatražite dijagnostiku", url: "/diagnostic" }
    secondary_action: { text: "Pogledajte prikaz proizvoda", url: "/demo" }
  - type: steps
    eyebrow: "Što radi u pogonu"
    title: "Četiri faze prije obračuna plaće, svaka sa svojom poviješću"
    items:
      - title: "Bilježenje"
        description: "Prolazi dolaze iz modula Hexavera Access, a dolasci i odlasci s kioska Presence i iz preglednika. Svaki zapis čuva svoj izvor: čitač, terminal i osobu."
      - title: "Izračun"
        description: "Radno vrijeme izračunava se prema vašim smjenama i postavkama zaokruživanja, stanki, prekovremenog rada i odsutnosti. Odjel može imati vlastitu toleranciju kašnjenja, a da se za ostatak pogona ništa ne mijenja."
      - title: "Ispravak i odobrenje"
        description: "Nedostajući dolasci i odlasci te iznimke idu poslovođi. Svaki ispravak čuva izvorni podatak, promjenu, razlog i osobu koja ju je odobrila."
      - title: "Zatvaranje i izvoz"
        description: "Iz zatvorenog razdoblja izrađuje se izvoz u formatu vašeg sustava za obračun plaće. U zatvorenom se razdoblju ništa ne mijenja dok se ono evidentirano ponovno ne otvori."
  - type: split
    eyebrow: "Smjene"
    title: "Planirajte smjene koje su pravila već provjerila"
    markdown: |
      Poslovođe definiraju smjene i rotacije, raspoređuju ljude, prihvaćaju zamjene i pokrivaju odsutnosti, a zatim objavljuju plan. Prikaz popunjenosti pokazuje gdje na liniji nedostaje ljudi prije nego što smjena počne.

      Svaki raspored i svaka zamjena provjeravaju se, u trenutku kad nastaju, prema pravilima o odmoru, najduljem dnevnom i tjednom radnom vremenu i ograničenjima iz ugovora o radu. Zamjena nakon koje bi netko imao premalo odmora blokira se, a poslovođa vidi zašto.
    aside:
      type: record
      title: "Zahtjev za zamjenu smjene SW-118"
      status: "Blokirano"
      tone: danger
      rows:
        - { label: "Zatraženo", value: "E-2041 preuzima noćnu smjenu u utorak, linija 3" }
        - { label: "Pravilo", value: "Najkraći dnevni odmor, 11 h" }
        - { label: "Zadnji odlazak", value: "utorak 14:06" }
        - { label: "Odmor prije početka", value: "7 h 54 min" }
        - { label: "Sljedeći korak", value: "Ponuditi smjenu sljedećoj osobi koja ispunjava uvjete" }
      caption: "Ogledni podaci"
  - type: checklist
    eyebrow: "Za koga"
    title: "Jedno razdoblje, nekoliko ljudi koji ga potvrđuju"
    items:
      - text: "Poslovođe i voditelji smjena"
        description: "Planiraju, zamjenjuju, pokrivaju i ispravljaju, s provjerom pravila pred sobom."
      - text: "Kadrovska služba i obračun plaće"
        description: "Odobravaju ispravke, zatvaraju razdoblje i šalju jedan izvoz, a iza njega je evidentirana svaka promjena."
      - text: "Direktori pogona i direktori proizvodnje"
        description: "Popunjenost po liniji i smjeni te blokirane odluke koje su plan zadržale u zakonskim okvirima."
      - text: "Radnička vijeća"
        description: "Mogu pročitati svako pravilo koje sustav primjenjuje i vidjeti odakle potječu njegove vrijednosti."
  - type: section
    eyebrow: "Što bilježi i kako služi modulu Govern"
    title: "Svaka blokada, svaki ispravak i svako zatvaranje odluka je s dokazima"
    markdown: |
      Attendance bilježi radno vrijeme, ispravke, odobrenja i zatvaranja razdoblja. Kad pravilo blokira ili označi odluku, Attendance upisuje zapis o provjeri: pravilo i njegovu verziju, primijenjene vrijednosti i njihovo podrijetlo, ulazne činjenice i ishod.

      Ti zapisi odlaze u vaše okruženje u oblaku, gdje Govern o njima izvješćuje za sve pogone, provodi simulacije predloženih promjena pravila i omogućuje radničkom vijeću ili auditoru da svaku odluku otvori kao objašnjenje jasnim jezikom. Sama pravila ista su u pogonu i u oblaku.

      [Kako se objašnjava odluka](/explained)
  - type: cta
    title: "Primijenite pravila na vlastitu evidenciju radnog vremena"
    description: "Dijagnostika usklađenosti prikazuje nalaze o odmorima, radnom vremenu i prekovremenom radu iz vaše povijesti, svaki s objašnjenjem."
    primary_action: { text: "Zatražite dijagnostiku", url: "/diagnostic" }
    secondary_action: { text: "Pogledajte prikaz proizvoda", url: "/demo" }
---
