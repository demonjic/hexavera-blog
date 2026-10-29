---
title: "Hexavera: odluke o radnoj snazi koje možete objasniti"
description: "Hexavera je sustav evidencije odluka o radnoj snazi u industriji: svaka odluka o smjeni, pristupu i radnom vremenu donesena, provedena i objašnjena."
url: ""
slug: "home"
locale: "hr"
localization_id: "page-home"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Sustav evidencije odluka o radnoj snazi u industriji"
    title: "Svaka odluka o radnoj snazi donesena, provedena, zabilježena i objašnjena"
    subtitle: "Hexavera u vašem pogonu upravlja pristupom, evidencijom radnog vremena i samoposlugom zaposlenika, a u vašem okruženju u oblaku pravilima, automatizacijom i predviđanjem. Kad pravilo blokira smjenu ili vrata, zapis pokazuje koje je to pravilo, na kojim se činjenicama temelji i zašto."
    highlights:
      - "Pravila s navedenim pravnim izvorom"
      - "Provode se u pogonu, i bez veze s oblakom"
      - "Trag koji radničko vijeće može pročitati"
    primary_action: { text: "Zatražite dijagnostiku", url: "/diagnostic" }
    secondary_action: { text: "Pogledajte prikaz proizvoda", url: "/demo" }
    aside:
      type: record
      title: "Raspored u noćnu smjenu, linija 3"
      status: "Blokirano"
      tone: danger
      rows:
        - { label: "Zaposlenik", value: "E-2041, pakiranje" }
        - { label: "Pravilo", value: "Najkraći dnevni odmor, 12 h (Zakon o radu, čl. 75.)" }
        - { label: "Zadnji odlazak", value: "utorak 14:06, terminal T-04" }
        - { label: "Predloženi početak", value: "utorak 22:00, zahtjev za zamjenu smjene" }
        - { label: "Izračunati odmor", value: "7 h 54 min" }
        - { label: "Ishod", value: "Blokirano: manje od propisanih 12 h" }
      caption: "Ogledni podaci"
  - type: steps
    eyebrow: "Put jedne odluke"
    title: "Svaka odluka prolazi četiri koraka i svaki ostavlja trag"
    description: "Vaš kadrovski sustav, obračun plaće i ERP ostaju mjerodavni za podatke o ljudima, plaćama i proizvodnji. Hexavera vodi evidenciju odluka koje se donose između njih."
    items:
      - title: "Donesena"
        description: "Raspored u smjenu, ovlaštenje za vrata ili ispravak evidencije radnog vremena provjerava se prema pravilima koja vrijede za tu osobu, u tom pogonu, toga dana."
      - title: "Provedena"
        description: "Odluka koja krši obvezno pravilo blokira se ondje gdje nastaje. Odmori i najdulje radno vrijeme provjeravaju se u pogonu, pa blokada ne ovisi o internetskoj vezi."
      - title: "Zabilježena"
        description: "Svaka se provjera pohranjuje s verzijom pravila, vrijednostima parametara, ulaznim činjenicama i njihovim izvorima. Zapisi se samo dodaju i nikad se ne prepisuju."
      - title: "Objašnjena"
        description: "Svaki se zapis može otvoriti kao objašnjenje jasnim jezikom: što je odlučeno, koje je pravilo primijenjeno, odakle potječe njegova vrijednost i koje su bile činjenice."
  - type: cards
    eyebrow: "Jedna platforma"
    title: "Tri proizvoda u pogonu, četiri mogućnosti u oblaku"
    description: "Access, Attendance i Presence rade lokalno u svakom pogonu. Connect, Govern, Automate i Predict rade u vašem okruženju u oblaku. Svi dijele jednu evidenciju odluka. [Pogledajte kako se platforma uklapa u cjelinu](/platform)."
    columns: 4
    items:
      - title: "Access"
        description: "Vrata, čitači, identifikatori, alarmi, posjetitelji i obilasci zaštitara, na poslužitelju u vašem pogonu."
        url: "/products/access"
        link_text: "O modulu Access"
      - title: "Attendance"
        description: "Evidencija radnog vremena, smjene, ispravci, zatvaranje razdoblja i izvoz za obračun plaće, uz provjeru zakonskih pravila u pogonu."
        url: "/products/attendance"
        link_text: "O modulu Attendance"
      - title: "Presence"
        description: "Samoposluga za zaposlenike na kiosku ili u pregledniku: dolasci i odlasci, pregled radnog vremena, raspored, stanja i odsutnosti."
        url: "/products/presence"
        link_text: "O modulu Presence"
      - title: "Connect"
        description: "Vaše okruženje u oblaku: podaci o ljudima, radnom vremenu i pristupu iz sustava koje već koristite, uz izvor svakog zapisa."
        url: "/platform#connect"
        link_text: "O modulu Connect"
      - title: "Govern"
        description: "Pravila s pravnim izvorima, postavke opsega, simulacija, zapisi o usklađenosti i izvješća koja se na njima temelje."
        url: "/platform#govern"
        link_text: "O modulu Govern"
      - title: "Automate"
        description: "Korak nakon odluke: odobrenje koje treba zatražiti, osoba koju treba obavijestiti."
        url: "/platform#automate"
        link_text: "O modulu Automate"
      - title: "Predict"
        description: "Pogled unaprijed na temelju vaše vlastite povijesti i Vera, asistentica koja odgovara na pitanja o podacima vašeg okruženja."
        url: "/platform#predict"
        link_text: "O modulu Predict"
  - type: split
    eyebrow: "Za radnička vijeća"
    title: "Pokažite radničkom vijeću pravilo prije nego što se počne primjenjivati"
    markdown: |
      Sustav radnog vremena koji blokira ili označava zaposlenike sustav je o kojem radničko vijeće ima pravo reći svoje. Vijeće mora moći pročitati svako pravilo, vidjeti odakle potječe svaka vrijednost i isprobati promjenu prije nego što ona ikoga pogodi.

      U sustavu Hexavera pravila su podaci, a ne kod koji piše administrator. Uz svaku je vrijednost naveden njezin izvor: zakon, kolektivni ugovor ili vlastita postavka pogona. Simulacija primjenjuje predloženu promjenu na protekle smjene i navodi svaku odluku koja bi ispala drukčije, a da pritom ne dira nijedan stvarni zapis.

      [Kako se odluke objašnjavaju i simuliraju](/explained)
    aside:
      type: checklist
      title: "Što se pri provjeri može vidjeti"
      items:
        - { text: "Pravilo i njegov pravni izvor", description: "Članak, stavak ili odredba, pohranjeni uz pravilo." }
        - { text: "Svaki parametar i tko ga je postavio", description: "Razina zakona, kolektivnog ugovora, društva ili odjela." }
        - { text: "Ulazne činjenice", description: "Svaka sa sustavom i zapisom iz kojeg potječe." }
        - { text: "Učinak promjene", description: "Simulacija na proteklim odlukama, odvojena od stvarnih zapisa." }
  - type: split
    eyebrow: "Hrana i piće"
    title: "Za pogone koji rade danonoćno i u kojima se sve provjerava"
    markdown: |
      U pogonima za proizvodnju hrane i pića susreću se higijenske zone, neprekidan rad u smjenama, sezonski vrhunci i agencijski radnici, a sve se to vidi na svakom auditu. Hexavera provjerava tko smije ući u zonu visoke higijene, tko smije raditi u kojoj smjeni i jesu li poštovana pravila o odmoru i radnom vremenu te čuva zapis koji auditor traži.

      [Hexavera u proizvodnji hrane i pića](/food-beverage)
    aside_position: start
    aside:
      type: checklist
      title: "Odakle dolaze pitanja"
      items:
        - { text: "Higijenske zone i HACCP", description: "Evidencija o osposobljavanju određuje tko smije proći." }
        - { text: "Rad u tri smjene i vikendom", description: "Odmor i radno vrijeme provjeravaju se pri svakoj zamjeni." }
        - { text: "Sezonski i agencijski radnici", description: "Ista pravila za sve na liniji." }
  - type: section
    eyebrow: "Sigurnost i uvođenje"
    title: "Vaš pogon radi samostalno, a vaše okruženje u oblaku pripada samo vama"
    markdown: |
      Access, Attendance i Presence rade na poslužitelju u svakom pogonu. Vrata se otvaraju, dolasci i odlasci se bilježe, a obvezna pravila provode se i kad je veza s oblakom u prekidu.

      U oblaku svaki kupac ima vlastito okruženje s vlastitom shemom baze podataka. Svaki se račun prijavljuje uz drugi faktor autentifikacije, svaka radnja operatera zahtijeva ovlaštenje, vjerodajnice konektora pohranjuju se šifrirane, a promjene ostavljaju revizijski trag. Ne tvrdimo da imamo certifikat koji nemamo, a na vaš sigurnosni upitnik odgovaramo prema kontrolama kakve su stvarno izgrađene.

      [Sigurnost u sustavu Hexavera](/security)
  - type: cta
    variant: dark
    eyebrow: "Dijagnostika usklađenosti"
    title: "Pogledajte što vaša povijest govori o odmorima, radnom vremenu i kvalifikacijama"
    description: "Pošaljite nam evidenciju smjena i radnog vremena za određeno razdoblje, uz ugovor o obradi podataka. Primijenit ćemo pravila na te podatke i s vama proći kroz svaki nalaz, uz njegovo objašnjenje."
    primary_action: { text: "Zatražite dijagnostiku", url: "/diagnostic" }
    secondary_action: { text: "Pogledajte prikaz proizvoda", url: "/demo" }
---
