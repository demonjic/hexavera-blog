---
title: "Kako Hexavera objašnjava i simulira odluku"
description: "Za radnička vijeća i auditore: kako se odluka prati do pravila, pravnog izvora, postavke pogona i ulaznih činjenica te kako se simulira promjena pravila."
permalink: "/explained"
slug: "explained"
lang: "hr"
id: "page-explained"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Za radnička vijeća i auditore"
    title: "Svaku odluku možete otvoriti, pročitati i provjeriti"
    subtitle: "Kad Hexavera blokira smjenu, odbije prolaz kroz vrata ili označi prekovremeni rad, zapisuje i zašto: pravilo, podrijetlo njegove vrijednosti, činjenice koje je upotrijebila i rezultat. Ova stranica prolazi kroz jedan takav zapis i pokazuje što simulacija tome dodaje."
    primary_action: { text: "Zatražite dijagnostiku", url: "/diagnostic" }
    secondary_action: { text: "Pogledajte prikaz proizvoda", url: "/demo" }
  - type: split
    eyebrow: "Jedna odluka, korak po korak"
    title: "Zamjena noćne smjene, blokirana zbog nedovoljnog odmora"
    markdown: |
      Radnik na pakiranju u utorak je radio u jutarnjoj smjeni i ostao nekoliko minuta dulje. Poslijepodne ga je kolega zamolio da preuzme noćnu smjenu na liniji 3 s početkom u 22:00. Poslovođa je prihvatio zamjenu u modulu Attendance, a Attendance ju je provjerio prije spremanja.

      Zapis uz ovaj tekst upravo je ono što je Attendance zapisao. Pohranjen je u pogonu i u okruženju u oblaku i nitko ga poslije ne može mijenjati. Ispravak je novi zapis koji upućuje na stari.
    aside:
      type: record
      title: "Zapis o provjeri, zamjena smjene SW-118"
      status: "Blokirano"
      tone: danger
      rows:
        - { label: "Odluka", value: "Rasporediti E-2041 u noćnu smjenu, linija 3, utorak 22:00" }
        - { label: "Pravilo", value: "DAILY-REST, najkraći dnevni odmor, verzija 3" }
        - { label: "Pravni izvor", value: "Zakon o radu, čl. 75. st. 1.: najmanje 12 sati neprekidno u svakom razdoblju od 24 sata (više od najmanje razine iz čl. 3. Direktive 2003/88/EZ)" }
        - { label: "Primijenjena vrijednost", value: "12 h, zakonska razina; ni kolektivni ugovor ni vrijednost društva ne mijenjaju je" }
        - { label: "Postavka pogona", value: "Odmor se mjeri od zadnjeg odlaska evidentiranog na terminalu. Postavio ju je na razini pogona administrator kadrovske službe, vrijedi od 1. ožujka 2026." }
        - { label: "Ulazna činjenica 1", value: "Zadnji odlazak utorak 14:06, terminal T-04 (Attendance, zapis o evidentiranju P-88213)" }
        - { label: "Ulazna činjenica 2", value: "Predloženi početak utorak 22:00 (plan smjena, zahtjev za zamjenu SW-118)" }
        - { label: "Izračunato", value: "Odmor između njih: 7 h 54 min" }
        - { label: "Ishod", value: "Nije zadovoljeno: 7 h 54 min manje je od 12 h. Zamjena blokirana" }
        - { label: "Provjereno", value: "Lokalni sustav pogona, utorak 15:20, na temelju radnje poslovođe" }
      caption: "Ogledni podaci"
  - type: section
    eyebrow: "Isti zapis, jasnim jezikom"
    title: "Što kaže objašnjenje"
    markdown: |
      > Zamjena je blokirana jer bi zaposlenik prije noćne smjene imao 7 sati i 54 minute odmora, a zakon zahtijeva najmanje 12 uzastopnih sati u svaka 24 sata.
      >
      > Tih 12 sati propisuje Zakon o radu, članak 75., strože od najmanje razine iz članka 3. Direktive 2003/88/EZ. Ni kolektivni ugovor ni pravilo društva ne mijenjaju tu vrijednost u ovom pogonu.
      >
      > Odmor je računat od zaposlenikova zadnjeg evidentiranog odlaska, u 14:06 na terminalu T-04, do početka noćne smjene u 22:00. Pogon mjeri odmor od odlaska evidentiranog na terminalu; to je 1. ožujka 2026. postavio administrator kadrovske službe.
      >
      > Ako smatrate da je neka činjenica pogrešna, primjerice vrijeme odlaska, zapis o evidentiranju P-88213 pokazuje odakle potječe.

      Svako objašnjenje slijedi isti redoslijed: što je odlučeno, koje je pravilo primijenjeno, odakle potječe vrijednost, koje su činjenice upotrijebljene i odakle potječe svaka od njih, što je izračunato i kakav je rezultat. Član radničkog vijeća, auditor ili sam zaposlenik može provjeriti svaki korak a da ne čita kod. Objašnjenja su dostupna na svakom jeziku koji konzola nudi.
  - type: checklist
    eyebrow: "Zašto je zapisu moguće vjerovati"
    title: "Pravila kao podaci, činjenice s izvorima, ništa se ne prepisuje"
    items:
      - text: "Pravila su podaci, a ne kod"
        description: "Administratori biraju vrijednosti i opseg. Ne mogu pisati izraze, pa se svako pravilo može izlistati i pročitati."
      - text: "Svaka vrijednost ima razinu i izvor"
        description: "Zakon, kolektivni ugovor, društvo ili odjel, svaki s navodom izvora i razdobljem valjanosti."
      - text: "Svaka činjenica ima izvor"
        description: "Sustav i zapis iz kojeg potječe te vrijeme kada je zabilježena."
      - text: "Nedostajuće činjenice imenuju se"
        description: "Ako pravilu treba činjenica koje u zapisima nema, ishod je „neutvrđeno“, nikad „zadovoljeno“."
      - text: "Zapisi se samo dodaju"
        description: "Verzije pravila i zapisi o provjeri čuvaju se. Ispravak upućuje na ono što ispravlja."
  - type: split
    eyebrow: "Simulacija"
    title: "Isprobajte promjenu pravila na proteklim odlukama prije nego što se na ikoga primijeni"
    markdown: |
      Recimo da uprava i radničko vijeće raspravljaju o odredbi kolektivnog ugovora koja dopušta skraćivanje odmora na 10 sati dvaput mjesečno, uz zamjenski odmor kasnije tijekom tjedna. Prije nego što se dogovore, obje strane žele znati što bi se time promijenilo.

      Simulacija primjenjuje ista pravila na proteklo razdoblje s predloženim vrijednostima. Navodi svaku odluku čiji bi se ishod promijenio, po odjelu i smjeni, s objašnjenjem za svaku. Ništa iz simulacije ne postaje stvarni zapis i podaci nijednog zaposlenika ne napuštaju okruženje.

      Radničko vijeće vidi učinak odredbe na stvarnim rasporedima smjena, a ne na primjeru odabranom da ga uvjeri.
    aside:
      type: checklist
      title: "Što simulacija pokazuje"
      items:
        - { text: "Usporedbu vrijednosti", description: "Sadašnje i predložene, jedne uz druge." }
        - { text: "Svaku odluku koja se mijenja", description: "Iz blokirane u dopuštenu ili iz dopuštene u blokiranu." }
        - { text: "Gdje se mijenja", description: "Po odjelu, liniji i rasporedu smjena." }
        - { text: "Zašto, za svaku odluku", description: "Isto objašnjenje kao kod stvarnog zapisa." }
  - type: cta
    title: "Pogledajte objašnjenja vlastitih odluka"
    description: "Dijagnostika usklađenosti primjenjuje pravila na vašu povijest i daje vam svaki nalaz s objašnjenjem."
    primary_action: { text: "Zatražite dijagnostiku", url: "/diagnostic" }
    secondary_action: { text: "Pogledajte prikaz proizvoda", url: "/demo" }
---
