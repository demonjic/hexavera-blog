---
title: "Hexavera Presence: samoposluga za zaposlenike, kiosk i web"
description: "Zaposlenici evidentiraju dolazak i odlazak, vide radno vrijeme, raspored i stanja te traže odsutnost na kiosku ili u pregledniku. Svaki se zahtjev bilježi."
url: "products/presence"
slug: "presence"
locale: "hr"
localization_id: "page-presence"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Proizvod u pogonu: Presence"
    title: "Zaposlenici vide svoje radno vrijeme i postupaju prema njemu, na kiosku ili u pregledniku"
    subtitle: "Hexavera Presence samoposluga je za ljude u proizvodnji i u uredu: dolasci i odlasci, pregled radnog vremena, raspored, stanja i odsutnosti. Radi zajedno s modulom Attendance u vašem pogonu."
    highlights:
      - "Kiosk u proizvodnji i preglednik"
      - "Kartica i PIN koji izdaje pogon, ili kartica i lice"
      - "Zahtjeve provjeravaju ista pravila"
    primary_action: { text: "Zatražite dijagnostiku", url: "/diagnostic" }
    secondary_action: { text: "Pogledajte prikaz proizvoda", url: "/demo" }
  - type: cards
    eyebrow: "Što radi u pogonu"
    title: "Što zaposlenik može učiniti a da ne pita ured"
    columns: 3
    items:
      - title: "Dolazak i odlazak"
        description: "Evidentirajte dolazak i odlazak te početak i kraj stanke, na kiosku u proizvodnji ili u pregledniku ondje gdje pogon to dopušta."
      - title: "Pregled radnog vremena"
        description: "Pogledajte evidentirane dolaske i odlaske te radno vrijeme u tekućem razdoblju i prijavite nedostajući zapis koji poslovođa treba odobriti."
      - title: "Raspored"
        description: "Pogledajte objavljeni plan, vlastite smjene i zamjene."
      - title: "Stanja"
        description: "Stanje godišnjeg odmora, prekovremenih sati i ostala stanja kako ih izračunava Attendance."
      - title: "Odsutnost"
        description: "Zatražite odsutnost i pratite zahtjev do odluke."
      - title: "Zamjene smjena"
        description: "Ponudite ili preuzmite smjenu. Zamjena se provjerava prema pravilima o odmoru i radnom vremenu prije nego što stigne do poslovođe."
  - type: split
    eyebrow: "Prijava na kiosku"
    title: "Broj zaposlenika nikad nije lozinka"
    markdown: |
      Brojevi zaposlenika otisnuti su na karticama i pojavljuju se u svakom izvozu, pa ne mogu dokazati tko stoji pred kioskom. Presence prepoznaje osobu po kartici i PIN-u koji izdaje pogon i koji zaposlenik mijenja pri prvoj uporabi. Ondje gdje je pogon odabrao prepoznavanje lica, umjesto PIN-a koristi se kartica i lice.

      Kiosk prikazuje samo osobu koja se prijavila i odjavljuje je nakon kratkog vremena bez unosa.
    aside:
      type: checklist
      title: "Prijava na kiosku"
      items:
        - { text: "Kartica i PIN koji izdaje pogon", description: "Zaposlenik ga mijenja pri prvoj uporabi." }
        - { text: "Ili kartica i lice", description: "Samo ondje gdje je pogon odabrao prepoznavanje lica." }
        - { text: "Odjava nakon neaktivnosti", description: "Sljedeća osoba počinje s praznim zaslonom." }
  - type: section
    eyebrow: "Za koga"
    title: "Manje pitanja uredu i odgovori koje ljudi mogu provjeriti"
    markdown: |
      **Zaposlenici** vide iste brojke koje će koristiti obračun plaće, i to prije zatvaranja razdoblja, pa mogu upozoriti na nedostajući zapis dok ga je još lako ispraviti.

      **Poslovođe i kadrovska služba** primaju zahtjeve koji su već provjereni i potpuni, umjesto poruka i telefonskih poziva.

      **Radnička vijeća** mogu vidjeti da se o svakom zahtjevu odlučuje prema istim pisanim pravilima za sve.
  - type: section
    eyebrow: "Što bilježi i kako služi modulu Govern"
    title: "Svaki dolazak, odlazak i zahtjev činjenica je sa svojim izvorom"
    markdown: |
      Presence bilježi svaki dolazak i odlazak s kioskom ili preglednikom s kojeg je evidentiran te svaki zahtjev s odgovorom, osobom koja je odlučila i vremenom odluke. Attendance koristi te zapise za izračun radnog vremena. Kad se na zamjenu ili zahtjev primijeni pravilo, zapis o provjeri odlazi u Govern zajedno s ostalima, pa se odluka može objasniti zaposleniku, radničkom vijeću ili auditoru.

      [Kako se objašnjava odluka](/explained)
  - type: cta
    title: "Pogledajte Presence s oglednim podacima"
    description: "Isprobajte kiosk u prikazu proizvoda ili zatražite dijagnostiku usklađenosti na vlastitim zapisima."
    primary_action: { text: "Zatražite dijagnostiku", url: "/diagnostic" }
    secondary_action: { text: "Pogledajte prikaz proizvoda", url: "/demo" }
---
