---
title: "Од модула Hexavera Access до модула Attendance"
description: "Hexavera Access објављује сваки пролаз са означеним празнинама. Attendance тај ток чита у погону и, уз смене, од њега израчунава радно време."
permalink: "/integrations/access-to-attendance"
slug: "integration-access-to-attendance"
lang: "sr"
id: "page-integration-access-to-attendance"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Конектор: производи Hexavera"
    title: "Од догађаја на вратима до радног времена, са празнинама на видном месту"
    subtitle: "Access и Attendance раде један поред другог у вашем погону. Access објављује шта се догодило на вратима, а Attendance то чита и утврђује шта то значи за радно време."
    primary_action: { text: "Закажите дијагностику", url: "/diagnostic" }
    secondary_action: { text: "Све интеграције", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "Шта тече и у ком смеру"
    markdown: |
      **Из модула Access у Attendance**

      - Сваки пролаз: особа, читач, врата, смер и време.
      - Покривеност: који читачи су били ван мреже, који догађаји су изгубљени и колико је сат сваког контролера одступао.

      **Из модула Attendance у Access**

      - Ништа. Исправке радног времена уносе се у Attendance и не мењају евиденцију приступа.

      Пошто ток сам означава своје празнине, Attendance никада не тумачи утихнули читач као особу која је остала код куће.
    aside:
      type: record
      title: "Од модула Access до модула Attendance"
      status: "У плану"
      tone: info
      rows:
        - { label: "Ради", value: "У погону" }
        - { label: "Смер", value: "Из модула Access у Attendance" }
        - { label: "Ток догађаја и извештај о квалитету података", value: "M1" }
        - { label: "Attendance чита ток", value: "M4" }
  - type: checklist
    id: "what-you-configure"
    title: "Шта подешавате"
    items:
      - text: "Који читачи се рачунају"
        description: "Читачи чији се пролази рачунају као почетак или крај рада, и у ком смеру."
      - text: "Смене"
        description: "Смене и ротације са којима Attendance упоређује пролазе."
      - text: "Правила"
        description: "Заокруживање, толеранција и правила о радном времену која важе за сваку локацију, одељење или групу."
  - type: section
    id: "status"
    title: "Статус"
    markdown: |
      Ток догађаја и извештај о квалитету података у плану су за етапу M1, заједно са модулом Hexavera Access у погону. Извештај о квалитету података по читачу и по дану показује шта ваши догађаји на вратима могу, а шта не могу да кажу обрачуну зарада. Attendance почиње да чита ток у етапи M4.
  - type: cta
    title: "Шта ваши догађаји на вратима данас говоре обрачуну зарада?"
    description: "Извештај о квалитету података на то одговара на основу ваших сопствених догађаја."
    primary_action: { text: "Контактирајте нас", url: "/contact" }
    secondary_action: { text: "Hexavera Attendance", url: "/products/attendance" }
---
