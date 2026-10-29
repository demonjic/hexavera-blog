---
title: "Пријава преко Microsoft Entra ID"
description: "Оператери и запослени пријављују се пословним налозима из Microsoft Entra ID. Улоге остају у систему Hexavera, који никада не уписује у ваш директоријум."
permalink: "/integrations/microsoft-entra-id"
slug: "integration-microsoft-entra-id"
lang: "sr"
id: "page-integration-microsoft-entra-id"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Конектор: идентитет"
    title: "Пријава пословним налозима којима већ управљате"
    subtitle: "Сервис за идентитет система Hexavera ради са Microsoft Entra ID као пружаоцем пријаве. Запослени користе свој пословни налог, а ваш директоријум остаје место где се налози отварају и затварају."
    primary_action: { text: "Разговарајте са нама о пријави", url: "/contact" }
    secondary_action: { text: "Безбедност", url: "/security" }
  - type: split
    id: "what-flows"
    title: "Шта тече и у ком смеру"
    markdown: |
      **Из Entra ID у Hexavera**

      - Сама пријава: Entra ID потврђује ко је особа.
      - Тврдње које су систему Hexavera потребне да налог упари са особом у вашем закупцу.

      **Из система Hexavera у Entra ID**

      - Ништа. Hexavera не отвара, не мења и не брише налоге ни групе у вашем директоријуму.

      Улоге и овлашћења воде се у систему Hexavera, па се о томе шта особа сме да ради одлучује на једном месту и тамо се и евидентира.
    aside:
      type: record
      title: "Microsoft Entra ID"
      status: "У плану"
      tone: info
      rows:
        - { label: "Ради", value: "Сервис за идентитет система Hexavera" }
        - { label: "Протокол", value: "OpenID Connect" }
        - { label: "Смер", value: "Само пријава" }
        - { label: "Етапа", value: "M2, прва испорука модула Connect" }
  - type: checklist
    id: "what-you-configure"
    title: "Шта подешавате"
    items:
      - text: "Регистрација апликације"
        description: "Региструје се у вашем Entra закупцу, за Hexavera."
      - text: "Ваш директоријум"
        description: "Идентификатор вашег Entra закупца. Hexavera прихвата пријаве искључиво из тог директоријума."
      - text: "Ваши домени"
        description: "Имејл домени за које докажете да су ваши, да би се пријаве за њих усмеравале на ваш директоријум."
      - text: "Ко сме да се пријави"
        description: "Које особе у вашем закупцу у систему Hexavera се пријављују преко Entra ID и које улоге имају у систему Hexavera."
  - type: section
    id: "status"
    title: "Статус"
    markdown: |
      Пријава преко Entra ID у плану је за етапу M2. До тада се сваки налог пријављује на сопствени сервис за идентитет система Hexavera, уз други фактор или приступни кључ.

      Упис у ваш директоријум, на пример отварање налога за новозапослене, назива се провизионисање. То је изван овог конектора и посебно се договара ако вам је потребно.

      Microsoft и Entra наводе се само ради описа компатибилности. Hexavera нема партнерство са компанијом Microsoft.
  - type: cta
    title: "Испланирајте пријаву са својим тимом за идентитет"
    description: "Са вашим руководиоцем за идентитет проћи ћемо кроз регистрацију, домене и улоге пре него што се било шта укључи."
    primary_action: { text: "Контактирајте нас", url: "/contact" }
    secondary_action: { text: "Све интеграције", url: "/integrations" }
---
