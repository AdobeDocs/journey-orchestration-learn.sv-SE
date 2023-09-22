---
title: Förstå Journey Orchestration
description: Förstå konceptet Journey Orchestration, de typer av användningsfall som det möjliggör och de viktigaste elementen för hur Journey Orchestration fungerar.
feature: Overview
topics: Introduction
jira: KT-2773
thumbnail: 29307.jpg
audience: user, developer
doc-type: video
activity: understand
role: User, Admin
exl-id: db4f69bb-183c-4376-9791-eb6b1f78ab32
source-git-commit: 9db2765ee5e9520280711a6b1fe3c618963f6f87
workflow-type: tm+mt
source-wordcount: '325'
ht-degree: 99%

---

# Förstå [!UICONTROL Journey Orchestration]

Med [!UICONTROL Journey Orchestration] kan du skapa orkestrering i realtid med hjälp av kontextuella data som lagras i händelser eller i datakällor.

## Introduktion till [!UICONTROL Journey Orchestration]

[!UICONTROL Journey Orchestration] är en programtjänst som är integrerad i Adobe Experience Platform. Tjänsten består av ett intelligent och öppet ekosystem som aktiverar alla relevanta data i realtid genom skalbar och händelsebaserad interaktion över alla kanaler som företaget behöver, från marknadsföring och drift till service. [!UICONTROL Journey Orchestration] kan använda alla data från Adobe Experience Platform och andra externa leveranssystem för att skapa och leverera övertygande upplevelser.

I videon nedan introduceras

* Begreppet [!UICONTROL Journey Orchestration]
* De typer av användningsfall som kan användas
* De viktigaste elementen i hur [!UICONTROL Journey Orchestration] fungerar

>[!VIDEO](https://video.tv.adobe.com/v/29307?learn=on){trancript=true}

## Så här konfigurerar du en resa

De viktigaste förberedande stegen för att skapa resor är följande:

1. [Konfigurera direktuppspelningshändelser](/help/configuring-journey-orchestration/configure-streaming-events.md) – den här konfigurationen är obligatorisk eftersom [!UICONTROL Journey Orchestration] är designad för att läsa av händelser.
1. [Konfigurera datakällor](/help/configuring-journey-orchestration/configure-data-sources.md) – den här konfigurationen krävs inte om dina resor bara använder lokala data som kommer från en händelses nyttolast.
1. [Konfigurera anpassade åtgärder](/help/configuring-journey-orchestration/configure-actions.md): krävs om du vill använda en tjänst från en tredjepartsleverantör som kan anropas via ett [!DNL REST API] med en JSON-formaterad nyttolast

>[!NOTE]
>
>Dessa konfigurationssteg kräver teknisk kunskap. Du måste känna till [Experience Data Model (XDM)](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/schemas-and-experience-data-model.html?lang=sv) och [hur du skapar XDM-upplevelsescheman för händelser](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html?lang=sv).

## Skapa, publicera och analysera en resa

1. [Skapa en resa](/help/building-a-journey/creating-a-journey.md)
1. [Validera och publicera en resa](/help/validate-and-publish-a-journey.md)
1. [Analysera en resa med rapporteringsverktyg](/help/analyze-a-journey-via-reporting-tools.md)

## Ytterligare resurser

* [Help Center för Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=sv)
* [Självstudiekurser om Adobe Experience Platform](https://experienceleague.adobe.com/docs/platform-learn/tutorials/overview.html?lang=sv)
* [Så här hittar du hjälp med Journey Orchestration](/help/understanding-journey-orchestration.md)
* [Adobe Experience Platform Mobile SDK – börja använda](https://experienceleague.adobe.com/docs/platform-learn/data-collection/mobile-sdk/overview.html?lang=sv)
* [Platstjänst i Adobe Experience Platform](https://experienceleague.adobe.com/docs/places/using/home.html?lang=sv)
