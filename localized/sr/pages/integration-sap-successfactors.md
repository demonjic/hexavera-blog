---
title: "Конектор за SAP SuccessFactors"
description: "Connect из SAP SuccessFactors у вашег закупца чита запослене, организацију, радна места, места трошкова и радно време, а евиденцију радног времена враћа."
url: "integrations/sap-successfactors"
slug: "integration-sap-successfactors"
locale: "sr"
localization_id: "page-integration-sap-successfactors"
published: true
layout: "page"
blocks:
  - type: hero
    eyebrow: "Конектор: HR систем"
    title: "SAP SuccessFactors остаје ваша HR евиденција"
    subtitle: "Connect ради са SAP SuccessFactors преко његовог OData API-ја. Ваши HR подаци тамо остају меродавни; Hexavera чита оно што је потребно за одлуке о радној снази."
    primary_action: { text: "Разговарајте са нама о свом окружењу", url: "/contact" }
    secondary_action: { text: "Све интеграције", url: "/integrations" }
  - type: split
    id: "what-flows"
    title: "Шта тече и у ком смеру"
    markdown: |
      **Из SuccessFactors у Hexavera**

      - Запослени и подаци о њиховом радном односу.
      - Организација: друштва, одељења и радна места.
      - Места трошкова.
      - Зараде, ако ваш уговор обухвата домен радног времена и зарада.
      - Евиденција радног времена која се води у SuccessFactors.

      **Из система Hexavera у SuccessFactors**

      - Евиденција радног времена, уписана назад као спољни записи о радном времену.

      Приступ, правила и одлуке не уписују се у SuccessFactors. Остају у систему Hexavera.
    aside:
      type: record
      title: "Конектор за SAP SuccessFactors"
      status: "У развоју"
      tone: info
      rows:
        - { label: "Ради", value: "У закупцу у облаку (Connect)" }
        - { label: "Интерфејс", value: "SuccessFactors OData API" }
        - { label: "Смер", value: "Претежно улаз; евиденција радног времена излаз" }
        - { label: "Етапа", value: "M2, прва испорука модула Connect" }
  - type: checklist
    id: "what-you-configure"
    title: "Шта подешавате"
    items:
      - text: "API сервер"
        description: "API адреса SuccessFactors за ваш центар података и идентификатор вашег предузећа."
      - text: "OAuth клијент"
        description: "OAuth 2.0 клијент који у SuccessFactors региструјете за Hexavera. Његови приступни подаци чувају се шифровани. Где ваша група захтева доделу на основу SAML потврде (SAML bearer grant), етапа M2 је додаје."
      - text: "Ваше друштво"
        description: "Чије запослене овај закупац прима. Од етапе M2 филтер се примењује на извору, па закупац никада не садржи редове другог друштва."
      - text: "Домени података"
        description: "Које домене синхронизујете: запослене и организацију, или уз то и радно време и зараде."
      - text: "Распоред"
        description: "Колико често се веза синхронизује. Сваки циклус се евидентира, са оним што се променило и оним што је одбијено."
  - type: section
    id: "groups"
    title: "Групе које деле један SuccessFactors"
    markdown: |
      Многе групе користе једну инстанцу SuccessFactors за више привредних друштава. У систему Hexavera свако привредно друштво је засебан закупац. Сваки закупац има сопствену везу, филтрирану на сопствено друштво, па HR подаци једног друштва никада не доспевају у закупца другог друштва.
  - type: section
    id: "status"
    title: "Статус"
    markdown: |
      Конектор је у развоју: читање и враћање евиденције радног времена су израђени. Продукциона испорука у плану је за етапу M2, са периодичним распоредом синхронизације, филтрирањем на извору, прегледом конфликата на екрану и историјом синхронизације на екрану.

      SAP и SuccessFactors наводе се само ради описа компатибилности. Hexavera нема партнерство са компанијом SAP.
  - type: cta
    title: "Користите SuccessFactors у целој групи?"
    description: "Опишите нам како су ваша друштва постављена у SuccessFactors. Показаћемо вам како би се мапирали закупци и везе."
    primary_action: { text: "Контактирајте нас", url: "/contact" }
    secondary_action: { text: "Закажите дијагностику", url: "/diagnostic" }
---
