---
title: "Integracije: vaši sustavi ostaju, Hexavera se povezuje"
description: "Hexavera se povezuje s kadrovskim sustavom, obračunom plaće, ERP-om, kontrolom pristupa, identitetima i MES-om. Oni ostaju, a evidencija odluka je u Hexaveri."
url: "integrations"
slug: "integrations"
locale: "hr"
localization_id: "page-integrations"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Integracije"
    title: "Vaši sustavi ostaju. Hexavera se povezuje s njima."
    subtitle: "Kadrovski sustav, obračun plaće, ERP, oprema za kontrolu pristupa, sustav identiteta i proizvodni sustavi ostaju mjerodavna evidencija za podatke koje sadrže. Hexavera vodi evidenciju odluka o radnoj snazi donesenih na temelju njihovih podataka."
    primary_action: { text: "Zatražite dijagnostiku", url: "/diagnostic" }
    secondary_action: { text: "Razgovarajte s nama o svojim sustavima", url: "/contact" }
  - type: cards
    id: "systems-that-stay"
    title: "Sustavi koji ostaju"
    description: "Hexavera ne zamjenjuje nijednu izvornu evidenciju. Čita ono što je odluci potrebno, a natrag zapisuje samo ono što dogovorimo."
    columns: 3
    items:
      - title: "Kadrovski sustav"
        description: "Osobe, radni odnosi, organizacija i radna mjesta ostaju u vašem kadrovskom sustavu. Hexavera ih čita i održava ažurnima."
      - title: "Obračun plaće"
        description: "Obračun plaće i dalje izračunava plaće. Hexavera mu predaje sate i dokaze iza njih, u formatu koji vaš sustav za obračun plaće čita."
      - title: "ERP"
        description: "Mjesta troška i struktura društva ostaju u vašem ERP-u ili kadrovskom sustavu. Hexavera ih koristi za određivanje opsega pravila i izvješća."
      - title: "Oprema za kontrolu pristupa"
        description: "Kontroleri vrata i čitači ostaju na svojem mjestu na zidu. Hexavera Access upravlja njima, ili Connect čita podatke iz sustava kontrole pristupa koji već imate."
      - title: "Identitet"
        description: "Ljudi se prijavljuju poslovnim računima kojima vaša organizacija već upravlja. Uloge i ovlaštenja vode se u Hexaveri."
      - title: "MES"
        description: "Proizvodni sustavi i dalje planiraju linije i naloge. Hexavera čita rasporede o kojima ovisi odluka o popunjavanju smjena."
  - type: steps
    id: "how-connect-works"
    title: "Kako radi Connect"
    description: "Connect je dio okruženja u oblaku koji komunicira s vašim ostalim sustavima."
    items:
      - title: "Povezivanje"
        description: "Konektor pristupa jednom sustavu s vjerodajnicama koje izdate upravo za njega. Hexavera te vjerodajnice pohranjuje šifrirane."
      - title: "Mapiranje"
        description: "Društva, šifre i polja iz izvora povezujete s područjima podataka u Hexaveri, primjerice s ljudima i organizacijom ili s radnim vremenom i plaćama."
      - title: "Sinkronizacija"
        description: "Svaka se sinkronizacija bilježi: što je stiglo, što se promijenilo i što je odbijeno, pa onaj tko provjerava može svaku vrijednost pratiti do njezina izvora."
      - title: "Odlučivanje"
        description: "Pravila se primjenjuju na sinkronizirane podatke. Odluka, njezini ulazni podaci i njezino objašnjenje čuvaju se u Hexaveri, uz izvorne identifikatore iz kojih potječu."
  - type: section
    id: "record-stays"
    title: "Evidencija ostaje u Hexaveri"
    markdown: |
      Izvorni sustav kaže Hexaveri što je istina o osobi, smjeni ili vratima. Hexavera bilježi što je na temelju toga odlučeno: tko je smio ući, koji se sati računaju, koji je raspored blokiran i prema kojem pravilu.

      Taj se zapis o odluci ne vraća u izvorne sustave. Ostaje u vašem okruženju u Hexaveri, gdje ga mogu pročitati radničko vijeće, auditor ili vaš vlastiti tim. Svako okruženje pripada jednom operativnom društvu, čak i kad grupa dijeli jedan kadrovski sustav.
  - type: cards
    id: "connectors"
    title: "Konektori"
    description: "Na svakoj je stranici navedeno što se prenosi i u kojem smjeru, što konfigurirate i kakav je status. **U planu** navodi etapu isporuke: M1 Access u pogonu, M2 prva isporuka modula Connect, M3 dijagnostika usklađenosti, M4 Attendance i Presence, M5 Govern."
    columns: 3
    items:
      - title: "Kontrola pristupa Hikvision"
        description: "Osobe, kartice i rasporedi idu prema panelima, a događaji pristupa vraćaju se. Njima upravlja Hexavera Access u pogonu."
        url: "/integrations/hikvision"
        link_text: "Konektor za Hikvision"
        items: ["Izrađeno; prvo izdanje za pogon u etapi M1"]
      - title: "Hexavera Access prema modulu Attendance"
        description: "Tok događaja pristupa, s označenim prazninama, kao ulazni podatak za izračun radnog vremena."
        url: "/integrations/access-to-attendance"
        link_text: "Access prema modulu Attendance"
        items: ["U planu: M1 i M4"]
      - title: "Drugi sustavi kontrole pristupa"
        description: "Zadržite sustav kontrole pristupa koji imate. Connect iz njega čita osobe, identifikatore i događaje."
        url: "/integrations/access-systems"
        link_text: "Drugi sustavi kontrole pristupa"
        items: ["Redoslijed prema potražnji kupaca"]
      - title: "SAP SuccessFactors"
        description: "Osobe, organizacija, radna mjesta, mjesta troška i evidencija radnog vremena ulaze; evidencija radnog vremena vraća se natrag."
        url: "/integrations/sap-successfactors"
        link_text: "Konektor za SAP SuccessFactors"
        items: ["U razvoju; u planu: M2"]
      - title: "Microsoft Entra ID"
        description: "Prijava poslovnim računima vaše organizacije. Hexavera ne zapisuje ništa u vaš imenik."
        url: "/integrations/microsoft-entra-id"
        link_text: "Prijava putem Microsoft Entra ID-ja"
        items: ["U planu: M2"]
      - title: "Uvoz datoteka"
        description: "CSV datoteke s podacima o osobama, organizaciji i radnom vremenu, uz provjeru valjanosti i izvješće o svakom odbijenom retku."
        url: "/integrations/file-import"
        link_text: "Uvoz datoteka"
        items: ["U planu: M2"]
      - title: "Obračun plaće"
        description: "Najprije izvadak događaja pristupa za svako obračunsko razdoblje, zatim radno vrijeme u formatu vašeg sustava za obračun plaće."
        url: "/integrations/payroll"
        link_text: "Izvoz za obračun plaće"
        items: ["U planu: M2 i M4"]
      - title: "MES i proizvodni sustavi"
        description: "Rasporedi linija i naloga ulaze, pa se popunjenost i prikladnost za mjesto na liniji provjeravaju prema stvarnim planovima."
        url: "/integrations/mes"
        link_text: "Konektor za MES"
        items: ["U planu nakon M2"]
  - type: section
    id: "further-connectors"
    title: "Daljnji konektori"
    markdown: |
      Konektore izrađujemo za jednu granu, proizvodnju hrane i pića, i izrađujemo ih temeljito prije nego što izradimo nove. Redoslijed daljnjih konektora određuje potražnja kupaca. Ako koristite sustav koji ovdje nije naveden, recite nam koji je to sustav i što vam iz njega treba. Vaš se zahtjev evidentira i uzima u obzir kad određujemo redoslijed.

      Nazivi proizvođača na ovim stranicama opisuju samo kompatibilnost. Ne podrazumijevaju partnerstvo, certifikaciju ni uvrštenje u katalog proizvođača.
  - type: cta
    title: "Zajedno s nama popišite svoje sustave"
    description: "Donesite popis sustava u svojem pogonu. Reći ćemo vam što se danas može povezati, što je u planu i što bi se izradilo za vas."
    primary_action: { text: "Zatražite dijagnostiku", url: "/diagnostic" }
    secondary_action: { text: "Kontaktirajte nas", url: "/contact" }
---
