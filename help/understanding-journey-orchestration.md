---
title: Förstå resesamordning
description: Förstå begreppet resesamordning, de typer av användningsområden som är möjliga och nyckelelementen i hur resesamordning fungerar.
feature: Journey Orchestration
topics: Introduction
kt: 2773
audience: user, developer
doc-type: video
activity: understand
translation-type: tm+mt
source-git-commit: 795b30fe984b7fe715789144e8c421028d7d32ac
workflow-type: tm+mt
source-wordcount: '326'
ht-degree: 0%

---


# Förstå [!UICONTROL Journey Orchestration]

## Introduktion till [!UICONTROL Journey Orchestration]

[!UICONTROL Journey Orchestration] gör att du kan skapa användningsfall för realtidssamordning med hjälp av kontextuella data som lagras i händelser eller datakällor.

[!UICONTROL Journey Orchestration] är en programtjänst som är integrerad med Adobe Experience Platform. Det ger ett intelligent och öppet ekosystem för att aktivera alla relevanta livedata genom skalbar, händelsebaserad interaktion i alla kanaler som företaget behöver, från marknadsföring till drift. [!UICONTROL Journey Orchestration] kan utnyttja alla data från Adobe Experience Platform och alla externa leveranssystem för att skapa och leverera övertygande upplevelser.

I videon nedan visas

* Begreppet [!UICONTROL Journey Orchestration]
* De typer av användningsfall som aktiveras
* Nyckelelementen i hur [!UICONTROL Journey Orchestration] fungerar

>[!VIDEO](https://video.tv.adobe.com/v/29307?quality=12)

## Konfigurera en resa

De viktigaste stegen för att förbereda byggresorna är följande:

1. [Konfigurera direktuppspelningshändelser](/help/configuring-journey-orchestration/configure-streaming-events.md) - Den här konfigurationen är obligatorisk, eftersom den [!UICONTROL Journey Orchestration] är utformad för att lyssna på händelser.
2. [Konfigurera datakällor](/help/configuring-journey-orchestration/configure-data-sources.md) - Den här konfigurationen krävs inte om dina resor endast utnyttjar lokala data som kommer från en händelsenyttolast.
3. [Konfigurera anpassade åtgärder](/help/configuring-journey-orchestration/configure-actions.md): Krävs om du vill använda en tjänst från en tredjepartsleverantör som kan anropas via en [!DNL REST API] med en JSON-formaterad nyttolast

>[!NOTE]
>Dessa konfigurationssteg kräver teknisk kunskap. Du måste känna till [Experience Data Model (XDM)](https://docs.adobe.com/content/help/en/platform-learn/tutorials/schemas/understanding-the-xdm-system-and-experience-data-model.html)och [hur du skapar XDM-händelsetyper](https://docs.adobe.com/content/help/en/platform-learn/tutorials/schemas/create-your-first-schema-with-out-of-the-box-components.html).

## Skapa, publicera och analysera en resa

1. [Skapa en resa](/help/create-a-journey.md)
2. [Validera och publicera en resa](/help/validate-and-publish-a-journey.md)
3. [Analysera en resa med rapportverktyg](/help/analyze-a-journey-via-reporting-tools.md)

## Ytterligare resurser

* [Hjälpcenter för resesamordning](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html)
* [Adobe Experience Platform - självstudiekurser](https://docs.adobe.com/content/help/en/platform-learn/tutorials/overview.html)
* [Hitta hjälp med Journey Orchestration](/help/understanding-journey-orchestration.md)
* [Adobe Experience Platform Mobile SDK - lansering](https://docs.adobe.com/content/help/en/core-services-learn/tutorials/launch-mobile/understanding-the-mobile-sdks.html)
* [Platstjänst för Adobe Experience Platform](https://docs.adobe.com/content/help/en/places/using/home.html)
