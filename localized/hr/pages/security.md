---
title: "Sigurnost: kontrole opisane onakve kakve su izgrađene"
description: "Kako Hexavera štiti podatke o radnoj snazi: gdje radi, odvojenost okruženja, dvofaktorska prijava, ovlaštenja, šifriranje, revizijski trag i lokacija podataka."
url: "security"
slug: "security"
locale: "hr"
localization_id: "page-security"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Sigurnost"
    title: "Kontrole koje stručnjak za sigurnost može provjeriti"
    subtitle: "Na ovoj su stranici navedene kontrole koje Hexavera danas ima te one koje su u planu isporuke, s pripadajućom etapom. Ništa ovdje nije obećanje koje vam ne možemo pokazati."
    primary_action: { text: "Pošaljite nam svoj upitnik", url: "/contact" }
    secondary_action: { text: "Pravila o privatnosti", url: "/privacy" }
  - type: split
    id: "deployment"
    title: "Gdje Hexavera radi"
    markdown: |
      **U pogonu.** Access, Attendance i Presence rade na poslužitelju u vašem pogonu, u vašoj mreži. Jedan poslužitelj u pogonu sadrži jedno okruženje. Hexavera Access radi dalje i kad je veza s oblakom u prekidu; vrata, identifikatori i događaji ne ovise o njoj.

      **U okruženju u oblaku.** Connect, Govern, Automate i Predict rade u okruženju u oblaku, jednom za svako operativno društvo. Pogon može raditi samostalno, bez ikakvog okruženja u oblaku, ili povezan s njim.
    aside:
      type: checklist
      title: "Već danas"
      items:
        - text: "Drugi faktor autentifikacije"
          description: "Za svaki račun, uz pristupne ključeve"
        - text: "Ovlaštenja"
          description: "Iza svake radnje operatera"
        - text: "Odvojenost okruženja"
          description: "Shema baze podataka za svako okruženje u oblaku"
        - text: "Revizijski trag"
          description: "Bilježe se prijave i radnje operatera"
  - type: cards
    id: "controls"
    title: "Kontrole"
    columns: 3
    items:
      - title: "Odvojenost okruženja"
        description: "U oblaku su podaci svakog okruženja u vlastitoj shemi baze podataka s generiranim nazivom. Poslužitelj u pogonu sadrži jedno okruženje. U grupi administrator matičnog društva upravlja društvima ispod njega i ničim drugim."
      - title: "Identitet i prijava"
        description: "Svaki se račun prijavljuje kroz vlastitu uslugu identiteta Hexavera uz drugi faktor autentifikacije ili pristupni ključ. Sesije imaju ograničeno trajanje i mogu se završiti s jednog mjesta. Prijava putem Microsoft Entra ID-ja u planu je za etapu M2."
      - title: "Ovlaštenja"
        description: "Ovlaštenja temeljena na ulogama stoje iza svake radnje operatera i provjeravaju se na poslužitelju za svaki zahtjev, a ne samo na zaslonu."
      - title: "Šifriranje"
        description: "Promet između vlastitih usluga Hexavere je šifriran. Vjerodajnice kojima Hexavera pristupa vašim sustavima pohranjuju se šifrirane. Od izdanja Access Release 1 (M1) panelima se pristupa preko obostrano autentificirane veze, a PIN-ovi i biometrijski predlošci zapisuju se samo preko provjerenog TLS-a."
      - title: "Revizijski trag"
        description: "Prijave i radnje operatera bilježe se s podatkom o tome tko je i kada djelovao. Od etape M3 svaka se odluka prema pravilu čuva u zapisu u koji se samo dodaje, zajedno s ulaznim podacima koje je upotrijebila."
      - title: "Vera, asistentica"
        description: "Vera čita podatke okruženja kroz isti API i s istim ovlaštenjima kao osoba koja pita. Ne vidi ništa što ta osoba ne bi mogla otvoriti."
  - type: section
    id: "data-residency"
    title: "Gdje se čuvaju vaši podaci"
    markdown: |
      - **Podaci pogona ostaju na vašem poslužitelju.** Događaji pristupa, identifikatori i revizijski trag pogona čuvaju se u pogonu. Pogon koji radi samostalno ne šalje ništa u oblak.
      - **Okruženje u oblaku radi u regiji EU-a.** Prvo produkcijsko okruženje u planu je za etapu M2, u regiji EU-a.
      - **Svako društvo zadržava vlastite podatke.** Kad grupa dijeli jedan kadrovski sustav, veza svakog društva filtrira se u izvoru (M2), pa okruženje nikad ne sadrži zaposlenike drugog društva.
      - **Osobne podatke potencijalnog kupca** primamo za dijagnostiku usklađenosti samo uz ugovor o obradi podataka, potpisan prije slanja prve datoteke.

      Podacima o vašoj radnoj snazi postupa se prema Općoj uredbi o zaštiti podataka (GDPR). Ako vaš pogon podliježe direktivi NIS2, vaša će procjena dobavljača pitati o tim kontrolama, a mi na nju odgovaramo na temelju njih.
  - type: section
    id: "certification"
    title: "Certifikacija"
    markdown: |
      Hexavera danas nema nijedan sigurnosni certifikat ni potvrdu neovisne provjere i ne tvrdimo da ih ima. Pošaljite nam svoj sigurnosni upitnik i odgovorit ćemo na njega prema kontrolama kakve su stvarno izgrađene. Kad se naš status certifikacije promijeni, objavit ćemo to ovdje.
  - type: section
    id: "responsible-disclosure"
    title: "Odgovorno otkrivanje ranjivosti"
    markdown: |
      Ako smatrate da ste pronašli ranjivost u Hexaveri ili na ovim mrežnim stranicama, javite nam to putem [obrasca za kontakt](/contact) i poruku započnite riječju „Sigurnost“. Navedite što ste pronašli i kako se to može ponoviti.

      Molimo vas da nam date razumno vrijeme da ranjivost istražimo i otklonimo prije nego što je objavite te da tijekom testiranja ne pristupate podacima koji nisu vaši niti ih mijenjate ili brišete. Odgovorit ćemo vam kako bismo zajedno dogovorili sljedeće korake.
  - type: cta
    title: "Pregledajte naše kontrole sa svojim timom za sigurnost"
    description: "S vašim voditeljem sigurnosti prolazimo kroz arhitekturu i odgovaramo na vaš upitnik prema kontrolama kakve su stvarno izgrađene."
    primary_action: { text: "Kontaktirajte nas", url: "/contact" }
    secondary_action: { text: "Integracije", url: "/integrations" }
---
