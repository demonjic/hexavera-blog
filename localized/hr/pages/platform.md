---
title: "Platforma Hexavera: proizvodi u pogonu i okruženje u oblaku"
description: "Access, Attendance i Presence rade u svakom pogonu, a Connect, Govern, Automate i Predict u vašem okruženju u oblaku. Svi pišu u jednu evidenciju odluka."
permalink: "/platform"
slug: "platform"
lang: "hr"
id: "page-platform"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Platforma"
    title: "Jedna platforma u dva dijela: pogon i okruženje u oblaku"
    subtitle: "Access, Attendance i Presence rade na poslužitelju u svakom pogonu i ne prestaju raditi kad je internetska veza u prekidu. Connect, Govern, Automate i Predict rade u vašem vlastitom okruženju u oblaku. Oba dijela pišu u jednu evidenciju odluka, pa blokada na ulazu i nalaz u auditu upućuju na iste dokaze."
    highlights:
      - "Lokalni sustav u svakom pogonu, jedan po tvornici"
      - "Okruženje u oblaku za svako operativno društvo"
      - "Jedna evidencija odluka za oba dijela"
    primary_action: { text: "Zatražite dijagnostiku", url: "/diagnostic" }
    secondary_action: { text: "Pogledajte prikaz proizvoda", url: "/demo" }
  - type: split
    id: "access"
    eyebrow: "U pogonu: Access"
    title: "Access određuje tko prolazi kroz koja vrata i čuva svaki prolaz"
    markdown: |
      Access upravlja osobama i njihovim identifikatorima (karticama, PIN-ovima, otiscima prstiju i licima), vratima i čitačima koje koriste te razinama pristupa i rasporedima koji određuju kada identifikator otvara vrata. Alarmi, posjetitelji i obilasci zaštitara vode se u istom pogonu, na istom poslužitelju.

      Svaki se prolaz pohranjuje s čitačem, smjerom i vremenom. Attendance i Govern oslanjaju se na te događaje, pa Access javlja i ono što vam oni sami ne mogu reći: čitače koji su utihnuli, prolaze bez smjera i satove uređaja koji odstupaju.

      [Access u pojedinostima](/products/access)
    aside:
      type: record
      title: "Prolaz, higijenski ulaz B"
      status: "Odbijeno"
      tone: warning
      rows:
        - { label: "Identifikator", value: "Kartica, nositelj E-3310" }
        - { label: "Čitač", value: "Ulaz B, strana ulaska" }
        - { label: "Pravilo", value: "Ulazak u zonu visoke higijene zahtijeva valjano higijensko osposobljavanje" }
        - { label: "Činjenica", value: "Osposobljavanje isteklo prije 2 dana (evidencija o osposobljavanju)" }
      caption: "Ogledni podaci"
  - type: section
    id: "attendance"
    eyebrow: "U pogonu: Attendance"
    title: "Attendance pretvara prolaze i evidentirane dolaske u datoteku za obračun plaće"
    markdown: |
      Attendance čita prolaze iz modula Access i evidentirane dolaske i odlaske iz modula Presence te izračunava radno vrijeme prema vašim postavkama zaokruživanja, stanki i prekovremenog rada. Poslovođe rade sa smjenama i rotacijama, zamjenama, pokrivanjem odsutnosti i prikazom popunjenosti, a zatim objavljuju plan. Ispravci se odobravaju, razdoblje se zatvara, a izvoz za obračun plaće izrađuje se iz zatvorenog razdoblja.

      Dnevni i tjedni odmor, najdulje dnevno i tjedno radno vrijeme te ograničenja iz ugovora o radu provjeravaju se u pogonu, u trenutku dodjele ili zamjene smjene. Blokada ne čeka oblak.

      [Attendance u pojedinostima](/products/attendance)
  - type: section
    id: "presence"
    eyebrow: "U pogonu: Presence"
    title: "Presence omogućuje zaposlenicima da vide svoje radno vrijeme i postupaju prema njemu"
    markdown: |
      Zaposlenici evidentiraju dolazak i odlazak, provjeravaju pregled radnog vremena, raspored i stanja te podnose zahtjeve za odsutnost, u pregledniku ili na kiosku u proizvodnom pogonu. Kiosk prepoznaje osobu po kartici i PIN-u koji izdaje pogon i koji se mijenja pri prvoj uporabi, ili po kartici i licu ondje gdje je pogon odabrao prepoznavanje lica. Broj zaposlenika nikad nije lozinka.

      [Presence u pojedinostima](/products/presence)
  - type: section
    id: "connect"
    eyebrow: "U oblaku: Connect"
    title: "Connect povezuje vaše sustave u jedno okruženje, a da ih ne zamjenjuje"
    markdown: |
      Vaš kadrovski sustav, obračun plaće i ERP ostaju mjerodavni. Connect iz njih u vaše okruženje preuzima ono što je odlukama potrebno (ljude i organizaciju, radno vrijeme i plaće, pristup i uređaje) i uz svaki zapis čuva izvorni sustav i izvorni identifikator. Vlastiti proizvodi Hexavera u pogonu povezuju se s njim bez konektora. Uvoz datoteka učitava povijesne podatke i podatke iz sustava koji nemaju sučelje.

      Svako operativno društvo ima vlastito okruženje s vlastitom shemom baze podataka, čak i kad grupa koristi jedan zajednički kadrovski sustav. Okruženje sadrži samo zaposlenike svojeg društva.
  - type: split
    id: "govern"
    eyebrow: "U oblaku: Govern"
    title: "Govern čuva pravila i evidenciju u koju se upisuje svaka odluka"
    markdown: |
      Govern pohranjuje svako pravilo kao podatak: što provjerava, njegov pravni izvor i njegove vrijednosti na četiri razine (zakon, kolektivni ugovor, društvo, odjel). Odjel može imati drukčiju toleranciju kašnjenja od ostatka pogona, a da nitko ne mora pisati kod. Zahtjevi za certifikatima i vještinama određuju tko smije biti raspoređen na koje mjesto na liniji.

      Ovdje se dva dijela susreću. Odluka donesena u pogonu ondje se i provjerava te se najprije upisuje u evidenciju pogona, a zatim u vaše okruženje. Zapis o odluci isti je na oba mjesta: verzija pravila, primijenjene vrijednosti, ulazne činjenice i ishod. Izvješća, simulacije i auditi čitaju taj jedan zapis.

      [Kako se objašnjava odluka](/explained)
    aside:
      type: checklist
      title: "U svakom zapisu o odluci"
      items:
        - { text: "Oznaka i verzija pravila" }
        - { text: "Svaka primijenjena vrijednost, s razinom i izvorom" }
        - { text: "Ulazne činjenice, svaka sa svojim izvornim zapisom" }
        - { text: "Izračunata veličina i ishod" }
        - { text: "Gdje je i kada provjera obavljena" }
  - type: section
    id: "automate"
    eyebrow: "U oblaku: Automate"
    title: "Automate poduzima korak koji slijedi nakon odluke"
    markdown: |
      Za blokirani raspored treba naći zamjenu, ispravak treba odobrenje poslovođe, a kvalifikacija kojoj ističe rok traži podsjetnik. Automate izvodi te daljnje korake prema predlošcima koje sami prilagođavate: tko odobrava, tko se obavješćuje i kojim kanalom. Tijekovi rada definiraju se zajedno sa svakim kupcem, polazeći od odluka koje Govern već bilježi.
  - type: section
    id: "predict"
    eyebrow: "U oblaku: Predict"
    title: "Predict gleda unaprijed na temelju vaše povijesti, a Vera odgovara na pitanja"
    markdown: |
      Predict radi s upravljanim podacima u vašem okruženju, nikad s podacima drugog kupca. Njegovi se modeli uče na vašoj vlastitoj povijesti, počevši od odsutnosti.

      Vera je asistentica u modulu Predict. Pitajte je tko radi u sutrašnjoj noćnoj smjeni ili gdje nedostaje ljudi, i ona odgovara iz podataka vašeg okruženja, u granicama ovlaštenja osobe koja pita. Čita iste zapise kao i vaša izvješća.
---
