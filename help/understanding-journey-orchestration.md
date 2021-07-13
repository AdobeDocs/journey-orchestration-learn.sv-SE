---
title: Förstå Journey Orchestration
description: ”Förstå konceptet Journey Orchestration, de typer av användningsfall som det möjliggör och de viktigaste elementen i hur Journey Orchestration fungerar.”
feature: Översikt
topics: Introduction
kt: 2773
thumbnail: 29307.jpg
audience: user, developer
doc-type: video
activity: understand
role: User, Admin
source-git-commit: 6f3d3fcac73e5c770ae3171e2e14a22713f0d571
workflow-type: tm+mt
source-wordcount: '327'
ht-degree: 100%

---


# Förstå [!UICONTROL Journey Orchestration]

## Introduktion till [!UICONTROL Journey Orchestration]

Med [!UICONTROL Journey Orchestration] kan du skapa användningsfall för orkestrering i realtid med hjälp av kontextuella data som lagras i händelser eller i datakällor.

[!UICONTROL Journey Orchestration] är en programtjänst som är integrerad i Adobe Experience Platform. Tjänsten består av ett intelligent och öppet ekosystem som aktiverar alla relevanta data i realtid genom skalbar och händelsebaserad interaktion över alla kanaler som företaget behöver, från marknadsföring och drift till service. Med [!UICONTROL Journey Orchestration] kan alla data från Adobe Experience Platform och alla externa leveranssystem användas för att skapa och leverera tilltalande upplevelser.

I videon nedan introduceras

* Begreppet [!UICONTROL Journey Orchestration]
* De typer av användningsfall som kan användas
* De viktigaste elementen i hur [!UICONTROL Journey Orchestration] fungerar

>[!VIDEO](https://video.tv.adobe.com/v/29307?quality=12)

## Så här konfigurerar du en resa

De viktigaste förberedande stegen för att skapa resor är följande:

1. [Konfigurera direktuppspelningshändelser](/help/configuring-journey-orchestration/configure-streaming-events.md) – den här konfigurationen är obligatorisk eftersom [!UICONTROL Journey Orchestration] är designad för att läsa av händelser.
1. [Konfigurera datakällor](/help/configuring-journey-orchestration/configure-data-sources.md) – den här konfigurationen krävs inte om dina resor endast utnyttjar lokala data som kommer från en händelses nyttolast.
1. [Konfigurera anpassade åtgärder](/help/configuring-journey-orchestration/configure-actions.md): krävs om du vill använda en tjänst från en tredjepartsleverantör som kan anropas via ett [!DNL REST API] med en JSON-formaterad nyttolast

>[!NOTE]
>
>Dessa konfigurationssteg kräver teknisk kunskap. Du måste känna till [Upplevelsedatamodellen (XDM)](https://docs.adobe.com/content/help/sv-SE/platform-learn/tutorials/schemas/understanding-the-xdm-system-and-experience-data-model.html) och [hur du skapar XDM-upplevelsehändelser](https://docs.adobe.com/content/help/sv-SE/platform-learn/tutorials/schemas/create-your-first-schema-with-out-of-the-box-components.html).

## Skapa, publicera och analysera en resa

1. [Skapa en resa](/help/building-a-journey/creating-a-journey.md)
1. [Validera och publicera en resa](/help/validate-and-publish-a-journey.md)
1. [Analysera en resa med rapporteringsverktyg](/help/analyze-a-journey-via-reporting-tools.md)

## Ytterligare resurser

* [Help Center för Journey Orchestration](https://docs.adobe.com/content/help/sv-SE/journeys/using/journey-orchestration-home.html)
* [Självstudiekurser om Adobe Experience Platform](https://docs.adobe.com/content/help/sv-SE/platform-learn/tutorials/overview.html)
* [Så här hittar du hjälp med Journey Orchestration](/help/understanding-journey-orchestration.md)
* [Adobe Experience Platform Mobile SDK – börja använda](https://docs.adobe.com/content/help/sv-SE/core-services-learn/tutorials/launch-mobile/understanding-the-mobile-sdks.html)
* [Platstjänst i Adobe Experience Platform](https://docs.adobe.com/content/help/sv-SE/places/using/home.html)
