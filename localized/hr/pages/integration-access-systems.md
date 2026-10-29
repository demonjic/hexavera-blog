---
title: "Drugi sustavi kontrole pristupa"
description: "Već imate sustav kontrole pristupa? On ostaje. Connect iz njega čita osobe, identifikatore i događaje pristupa, a redoslijed novih sustava određuje potražnja."
permalink: "/integrations/access-systems"
slug: "integration-access-systems"
lang: "hr"
id: "page-integration-access-systems"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Konektor: sustavi kontrole pristupa"
    title: "Zadržite sustav kontrole pristupa koji imate"
    subtitle: "Ako u vašem pogonu već radi kontrola pristupa, Hexavera ne traži da je zamijenite. Connect čita podatke iz nje, pa njezini događaji ulaze u iste odluke."
    primary_action: { text: "Recite nam što koristite", url: "/contact" }
    secondary_action: { text: "Sve integracije", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "Što se prenosi i u kojem smjeru"
    markdown: |
      **Iz vašeg sustava kontrole pristupa u Hexaveru**

      - Osobe i njihovi identifikatori, kako bi se prolaz pripisao pravoj osobi.
      - Događaji pristupa: prolazi, odbijanja i alarmi, s čitačem i smjerom.
      - Stanje čitača i kontrolera, kako bi se znalo da je čitač izvan mreže kad to i jest.

      **Iz Hexavere u vaš sustav kontrole pristupa**

      - Dogovara se za svaki sustav posebno. Vaš sustav kontrole pristupa i dalje određuje tko smije otvoriti koja vrata.
    aside:
      type: record
      title: "Drugi sustavi kontrole pristupa"
      status: "Redoslijed prema potražnji"
      tone: neutral
      rows:
        - { label: "Radi", value: "U okruženju u oblaku (Connect)" }
        - { label: "Smjer", value: "Ulazni; zapisuje samo ondje gdje je dogovoreno" }
        - { label: "Redoslijed", value: "Određuju ga zahtjevi kupaca" }
  - type: checklist
    id: "what-you-configure"
    title: "Što konfigurirate"
    items:
      - text: "Izvor"
        description: "Poslužitelj vašeg sustava kontrole pristupa i račun za Hexaveru, pohranjen šifriran."
      - text: "Čitači i vrata"
        description: "Koji čitač služi kojim vratima i kojem smjeru."
      - text: "Povezivanje osoba"
        description: "Kako se nositelj kartice u vašem sustavu povezuje s osobom u Hexaveri."
  - type: section
    id: "status"
    title: "Status"
    markdown: |
      Svaki konektor za kontrolu pristupa izrađen je na istom ugovornom sučelju: što sustav pojedinog proizvođača može učiniti, navedeno za svaku mogućnost posebno, s tipiziranim rezultatima. Hikvision je prvi. Daljnji proizvođač dodaje se kad ga kupac treba i prije isporuke mora proći iste testove sukladnosti.

      Ako želite da kontrolu pristupa isporuči Hexavera, to je Hexavera Access.
  - type: cta
    title: "Koji sustav kontrole pristupa koristite?"
    description: "Navedite nam sustav, njegovu verziju i u koliko ga pogona koristite."
    primary_action: { text: "Kontaktirajte nas", url: "/contact" }
    secondary_action: { text: "Hexavera Access", url: "/products/access" }
---
