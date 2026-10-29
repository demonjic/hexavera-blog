---
title: "Konektor za SAP SuccessFactors"
description: "Connect iz sustava SAP SuccessFactors u vaše okruženje Hexavera čita osobe, organizaciju, radna mjesta, mjesta troška i radno vrijeme te vraća evidenciju."
url: "integrations/sap-successfactors"
slug: "integration-sap-successfactors"
locale: "hr"
localization_id: "page-integration-sap-successfactors"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Konektor: kadrovski sustav"
    title: "SAP SuccessFactors ostaje vaša kadrovska evidencija"
    subtitle: "Connect radi sa sustavom SAP SuccessFactors putem njegova OData API-ja. Vaši kadrovski podaci ondje ostaju mjerodavni, a Hexavera čita ono što je potrebno za odluke o radnoj snazi."
    primary_action: { text: "Razgovarajte s nama o svojem okruženju sustava", url: "/contact" }
    secondary_action: { text: "Sve integracije", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "Što se prenosi i u kojem smjeru"
    markdown: |
      **Iz sustava SuccessFactors u Hexaveru**

      - Osobe i podaci o njihovu radnom odnosu.
      - Organizacija: društva, odjeli i radna mjesta.
      - Mjesta troška.
      - Primici, ako vaš ugovor uključuje područje radnog vremena i plaća.
      - Evidencija radnog vremena koja se vodi u sustavu SuccessFactors.

      **Iz Hexavere u SuccessFactors**

      - Evidencija radnog vremena, vraćena kao vanjski zapisi o radnom vremenu.

      Pristup, pravila i odluke ne zapisuju se u SuccessFactors. Ostaju u Hexaveri.
    aside:
      type: record
      title: "Konektor za SAP SuccessFactors"
      status: "U razvoju"
      tone: info
      rows:
        - { label: "Radi", value: "U okruženju u oblaku (Connect)" }
        - { label: "Sučelje", value: "SuccessFactors OData API" }
        - { label: "Smjer", value: "Uglavnom ulazni; evidencija radnog vremena izlazi" }
        - { label: "Etapa", value: "M2, prva isporuka modula Connect" }
  - type: checklist
    id: "what-you-configure"
    title: "Što konfigurirate"
    items:
      - text: "API poslužitelj"
        description: "Adresu API-ja sustava SuccessFactors za vaš podatkovni centar i identifikator vašeg društva."
      - text: "OAuth klijent"
        description: "Klijent OAuth 2.0 koji za Hexaveru registrirate u sustavu SuccessFactors. Njegove se vjerodajnice pohranjuju šifrirane. Ako vaša grupa zahtijeva SAML bearer grant, M2 ga dodaje."
      - text: "Vaše društvo"
        description: "Čije zaposlenike ovo okruženje prima. Od etape M2 filtar se primjenjuje u izvoru, pa okruženje nikad ne sadrži retke drugog društva."
      - text: "Područja podataka"
        description: "Koja područja sinkronizirate: osobe i organizaciju ili i radno vrijeme i plaće."
      - text: "Raspored"
        description: "Koliko se često veza sinkronizira. Svaka se sinkronizacija bilježi zajedno s onim što se promijenilo i što je odbijeno."
  - type: section
    id: "groups"
    title: "Grupe koje dijele jedan SuccessFactors"
    markdown: |
      Mnoge grupe koriste jednu instancu sustava SuccessFactors za više operativnih društava. U Hexaveri je svako operativno društvo zasebno okruženje. Svako okruženje ima vlastitu vezu, filtriranu na vlastito društvo, pa kadrovski podaci jednog društva nikad ne završe u okruženju drugog.
  - type: section
    id: "status"
    title: "Status"
    markdown: |
      Konektor je u razvoju: čitanje i vraćanje evidencije radnog vremena već su izrađeni. Produkcijska isporuka u planu je za etapu M2, s periodičnim rasporedom, filtriranjem u izvoru te pregledom sukoba i poviješću sinkronizacije na zaslonu.

      SAP i SuccessFactors navode se samo radi opisa kompatibilnosti. Hexavera nema partnerstvo sa SAP-om.
  - type: cta
    title: "Koristite SuccessFactors u cijeloj grupi?"
    description: "Opišite nam kako su vaša društva postavljena u sustavu SuccessFactors. Pokazat ćemo vam kako bi se povezala s okruženjima i vezama."
    primary_action: { text: "Kontaktirajte nas", url: "/contact" }
    secondary_action: { text: "Zatražite dijagnostiku", url: "/diagnostic" }
---
