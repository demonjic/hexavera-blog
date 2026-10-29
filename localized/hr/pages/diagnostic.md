---
title: "Dijagnostika usklađenosti: vaša povijest, pravilo po pravilo"
description: "Pošaljite evidenciju smjena i radnog vremena za neko razdoblje uz ugovor o obradi podataka. Primijenit ćemo pravila o radnom vremenu i objasniti svaki nalaz."
url: "diagnostic"
slug: "diagnostic"
locale: "hr"
localization_id: "page-diagnostic"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Dijagnostika usklađenosti"
    title: "Saznajte što vaši zapisi govore o odmorima, radnom vremenu i kvalifikacijama"
    subtitle: "Pošaljete nam evidenciju smjena i radnog vremena za određeno razdoblje. Na nju primijenimo pravila o radnom vremenu koja vrijede za vaš pogon i s vama prođemo kroz svaki nalaz, uz njegovo objašnjenje. Model dokaza vidite na vlastitim podacima prije nego što bilo što odlučite."
    primary_action: { text: "Zatražite dijagnostiku", url: "/contact" }
    secondary_action: { text: "Kako se odluke objašnjavaju", url: "/explained" }
  - type: checklist
    eyebrow: "Što šaljete"
    title: "Izvoze koje već imate, s imenima zamijenjenima šiframa ako želite"
    description: "Pravilima su potrebni datumi, vremena, ugovori i uloge. Imena im nisu potrebna: dovoljna je stalna šifra za svakog zaposlenika."
    items:
      - text: "Evidencija radnog vremena"
        description: "Dolasci i odlasci ili odrađeni intervali, za svakog zaposlenika."
      - text: "Planovi smjena"
        description: "Planirane smjene za isto razdoblje, uključujući zamjene ako ih evidentirate."
      - text: "Podaci iz ugovora"
        description: "Ugovoreno radno vrijeme i vrsta ugovora za svakog zaposlenika te je li zaposlenik maloljetan."
      - text: "Kvalifikacije, ako želite da se provjere"
        description: "Koje osposobljavanje ili certifikat ima svaki zaposlenik i koja ih mjesta na liniji zahtijevaju."
      - text: "Kontekst pogona"
        description: "Država, kolektivni ugovor koji se primjenjuje i eventualne postavke pogona, primjerice kako se mjeri odmor."
  - type: steps
    eyebrow: "Kako se provodi"
    title: "Četiri koraka od vašeg izvoza do nalaza"
    items:
      - title: "Dogovor"
        description: "Prije nego što primimo ijednu datoteku, s vama potpisujemo ugovor o obradi podataka."
      - title: "Učitavanje"
        description: "Uvozimo vaše datoteke i vraćamo vam izvješće o odbijenim retcima u kojem je naveden svaki redak koji nismo mogli pročitati i razlog."
      - title: "Provjera"
        description: "Na razdoblje primjenjujemo pravila za vašu državu i kolektivni ugovor: dnevni i tjedni odmor, najdulje dnevno i tjedno radno vrijeme, stanke, prekovremeni rad, noćni rad, uzastopne radne dane i kvalifikacije."
      - title: "Zajednički pregled"
        description: "S vama prolazimo kroz nalaze, pravilo po pravilo, i svaki od njih možemo otvoriti kao objašnjenje."
  - type: split
    eyebrow: "Što dobivate"
    title: "Izvješće o izloženosti riziku neusklađenosti izrađeno iz vaše povijesti"
    markdown: |
      Izvješće navodi svaki nalaz: prekratke odmore, tjedne u kojima je premašeno najdulje radno vrijeme, osobe raspoređene na mjesto na liniji bez kvalifikacije koju ono zahtijeva, prekovremeni rad bez evidentiranog odobrenja. Svaki se nalaz otvara kao potpuno objašnjenje, isto ono koje bi u proizvodu vidjeli radničko vijeće ili auditor.

      Ako u vašim zapisima nedostaje činjenica koja je pravilu potrebna, izvješće to navodi i rezultat označava kao neutvrđen. Nedostajuću činjenicu nikad ne računa kao zadovoljenu.

      Izvješće je vaše. Ono je očitanje vaših podataka prema pravilima, a ne pravni savjet; što iz njega slijedi, odlučuje vaš pravni savjetnik.
    aside:
      type: record
      title: "Nalaz, odjel pakiranja"
      status: "Nije zadovoljeno"
      tone: danger
      rows:
        - { label: "Pravilo", value: "Najkraći dnevni odmor, 11 h" }
        - { label: "Zaposlenik", value: "Šifra 2041" }
        - { label: "Između", value: "Odlazak utorak 14:06 i dolazak utorak 21:57" }
        - { label: "Izračunati odmor", value: "7 h 51 min" }
        - { label: "Izvori", value: "Izvoz radnog vremena, retci 18 233 i 18 240" }
      caption: "Ogledni podaci"
  - type: section
    eyebrow: "Kako postupamo s vašim podacima"
    title: "Vaši se podaci koriste za dijagnostiku i ni za što drugo"
    markdown: |
      - **Prije nego što išta pošaljete**, potpisujemo ugovor o obradi podataka. U njemu su navedeni svrha, mjesto obrade podataka, tko im može pristupiti, koliko se dugo čuvaju i kada se brišu.
      - **Pošaljite manje kad god možete.** Zamijenite imena šiframa i izostavite stupce koje pravila ne koriste. Prije izvoza kažemo vam koji su to stupci.
      - **Vaši podaci ostaju u vlastitom okruženju**, s vlastitom shemom baze podataka, odvojeno od podataka svih ostalih kupaca.
      - **Samo ljudi koji provode vašu dijagnostiku** mogu ih otvoriti, i to svatko uz drugi faktor autentifikacije pri prijavi.
      - **Ništa se ne koristi u druge svrhe.** Vaši zapisi služe dijagnostici koju opisuje ugovor i ne prikazuju se nikome izvan nje.
      - **Na kraju** se podaci brišu kako je navedeno u ugovoru.

      Opća uredba o zaštiti podataka (GDPR) primjenjuje se na svaki redak koji pošaljete, a mi s njim postupamo prema ugovoru, kao vaš izvršitelj obrade.
  - type: cta
    variant: dark
    title: "Zatražite dijagnostiku usklađenosti"
    description: "Opišite nam svoj pogon, raspored smjena i sustave iz kojih potječu vaši zapisi. Odgovorit ćemo vam što treba izvesti i poslati nacrt ugovora o obradi podataka."
    primary_action: { text: "Zatražite dijagnostiku", url: "/contact" }
    secondary_action: { text: "Kako se odluke objašnjavaju", url: "/explained" }
---
