---
title: Solutions for the game development industry 
titleSuffix: Azure Architecture Center
description: Architectures and ideas for using Azure services to build solutions in the game development industry.
author: martinekuan
ms.author: architectures
ms.date: 07/26/2022
ms.topic: conceptual
ms.service: architecture-center
ms.subservice: azure-guide
ms.custom: fcp 
keywords:
  - Azure
products:
- azure-speech-text
- azure-speech-translation
- azure-functions
- azure-cache-redis
- azure-kubernetes-service
categories:
- ai-machine-learning
- containers
- databases
---

# Solutions for the gaming industry

In the exciting world of game development, the call for innovation, engagement, and seamless experiences echoes louder than ever. In this highly competitive industry, creating experiences that stand out in a crowded marketplace of 2 billion gamers is no small mission. 
Azure is your key ally in this race, offering an all-inclusive platform on a global scale for end-to-end game development. It's more than a cloud service; it's your strategic partner in a journey that takes your gaming ideas from initial spark to full-blown reality, efficiently and innovatively.


<br>

> [!VIDEO https://www.youtube.com/embed/mPJUsxRBF4o]

With Azure, your game development process is transformed. It's a one-stop-shop where you leverage a custom Virtual Machine tailored for game development, manage source code securely, and handle builds efficiently for an optimized workflow. As you enhance your gaming toolkit with upcoming versatile cloud DevKits, AI-powered testing tools, and robust game server hosting, Azure equips you with powerful analytics to monitor game performance and user engagement. This empowers you to make data-driven decisions, allowing for continuous refinement of your gaming experiences. Azure isn't just a tool for game development; it's a strategic partner in your journey to create immersive experiences. 

For a video about building AI in gaming, see [Azure Cognitive Services for game development](https://youtu.be/dG57AYkWFB0).

## Architectures for game development

The following articles provide detailed analysis of architectures created and recommended for the game development industry.

| Architecture | Summary | Technology Focus |
| ------------ | ------- | ---------------- |
| [Content moderation](https://docs.microsoft.com/gaming/azure/reference-architectures/cognitive-content-moderation) | Learn how to moderate content to maintain a civil, welcoming, and pleasurable experience among players. | AI in games |
| [Customer service bot for gaming](https://docs.microsoft.com/gaming/azure/reference-architectures/cognitive-css-bot) | Create a conversational assistant that's tailored to your game and that understands natural language. | AI in games |
| [Image classification](https://docs.microsoft.com/azure/architecture/example-scenario/ai/intelligent-apps-image-processing) | Use Azure services like the Computer Vision API and Azure Functions to process images. For example, you could classify telemetry data from game screenshots. | AI in games |
| [In-editor debugging telemetry](https://docs.microsoft.com/gaming/azure/reference-architectures/analytics-in-editor-debugging) | Gather data from gameplay sessions and display it directly within the game engine. | Analytics in games |
| [Non-real time analytics dashboard](https://docs.microsoft.com/gaming/azure/reference-architectures/analytics-non-real-time-dashboard) | Create a game analytics pipeline to use when you track data that doesn't require real-time analysis. | Analytics in games |
| [Gaming using Azure MySQL](https://docs.microsoft.com/azure/architecture/solution-ideas/articles/gaming-using-azure-database-for-mysql) | Elastically scale your Azure Database for MySQL database to accommodate unpredictable bursts of traffic and deliver low-latency multiplayer experiences on a global scale. | Databases for gaming |
| [Gaming using Azure Cosmos DB](https://docs.microsoft.com/azure/architecture/solution-ideas/articles/gaming-using-cosmos-db) | Elastically scale your Azure Cosmos DB database to accommodate unpredictable bursts of traffic and deliver low-latency multiplayer experiences on a global scale. | Databases for gaming |
| [Unreal Pixel Streaming](https://docs.microsoft.com/gaming/azure/reference-architectures/unreal-pixel-streaming-in-azure) | Deploy Unreal Engine's Pixel Streaming technology on Azure. You can use this Epic Games technology to stream remotely deployed interactive 3D applications through a browser. | Game streaming |
| [Deploy Unreal Pixel Streaming](https://docs.microsoft.com/gaming/azure/reference-architectures/unreal-pixel-streaming-deploying) | Deploy the Unreal Pixel Streaming package on an Azure GPU virtual machine or on multiple virtual machines. | Game streaming |
| [Unreal Pixel Streaming at scale](https://docs.microsoft.com/gaming/azure/reference-architectures/unreal-pixel-streaming-at-scale) | Deploy Unreal Engine's Pixel Streaming technology at scale on Azure. | Game streaming |
| [Leaderboard basics](https://docs.microsoft.com/gaming/azure/reference-architectures/leaderboard) | Implement a leaderboard that suits your game design. | Leaderboards |
| [Non-relational leaderboard](https://docs.microsoft.com/gaming/azure/reference-architectures/leaderboard-non-relational) | Implement a gaming leaderboard that uses Azure Cache for Redis together with another database to improve data throughput and reduce database load. | Leaderboards |
| [Relational leaderboard](https://docs.microsoft.com/gaming/azure/reference-architectures/leaderboard-relational) | Enable a leaderboard in your large-scale game by using a relational database. | Leaderboards |
| [Multiplayer matchmaker](https://docs.microsoft.com/gaming/azure/reference-architectures/multiplayer-matchmaker) | Build a multiplayer matchmaker that uses the PlayFab matchmaking feature. | Matchmaking |
| [Skill-based matchmaker](https://docs.microsoft.com/gaming/azure/reference-architectures/multiplayer-matchmaker-skill) | Use Azure Cognitive Services Personalizer to build a matchmaker that pairs players based on skill. | Matchmaking |
| [Tournament matchmaker](https://docs.microsoft.com/gaming/azure/reference-architectures/multiplayer-matchmaker-tournament) | Build a tournament matchmaker that supports group or tournament play. | Matchmaking |
| [Serverless matchmaker](https://docs.microsoft.com/gaming/azure/reference-architectures/multiplayer-matchmaker-serverless) | Build a serverless multiplayer matchmaker that uses Azure Traffic Manager, Azure Functions, and Azure Event Hubs. | Matchmaking |
| [3D video rendering](https://docs.microsoft.com/azure/architecture/example-scenario/infrastructure/video-rendering) | Use Azure Batch to run large-scale 3D video rendering jobs. | Rendering |
| [Digital image-based modeling](https://docs.microsoft.com/azure/architecture/example-scenario/infrastructure/image-modeling) | Perform image-based modeling for your game's visual effects. | Rendering |
| [Asynchronous multiplayer](https://docs.microsoft.com/gaming/azure/reference-architectures/multiplayer-asynchronous) | Build an asynchronous multiplayer by saving game state to a persistent database. | Scalable gaming servers |
| [Custom game server scaling](https://docs.microsoft.com/gaming/azure/reference-architectures/multiplayer-custom-server-scaling) | Containerize your game server with Docker and build a reliable, automated deployment process for servers by using Azure Resource Manager templates, Azure Functions, and DevOps practices. | Scalable gaming servers |
| [Multiplayer backend reference architectures](https://docs.microsoft.com/gaming/azure/reference-architectures/multiplayer) | Learn about a variety of multiplayer backend use cases and implementations that can help you create a cloud solution that works for your game. | Scalable gaming servers |
| [Multiplayer hosting with Azure Batch](https://docs.microsoft.com/gaming/azure/reference-architectures/multiplayer-synchronous-batch) | Build a scalable game server that's hosted on Azure Batch. | Scalable gaming servers |
| [Multiplayer hosting with Service Fabric](https://docs.microsoft.com/gaming/azure/reference-architectures/multiplayer-synchronous) | Build a scalable game server that's hosted on Azure Service Fabric. | Scalable gaming servers |
| [Multiplayer with Azure Container Instances](https://docs.microsoft.com/gaming/azure/reference-architectures/multiplayer-synchronous-aci) | Learn about a multiplayer solution that automatically scales on demand and is billed per seconds of usage. | Scalable gaming servers |
| [Multiplayer with Azure Kubernetes Service](https://docs.microsoft.com/gaming/azure/reference-architectures/multiplayer-synchronous-aks) | Manage containerized, dedicated game servers by using the Kubernetes orchestrator on Azure. | Scalable gaming servers |
| [Serverless asynchronous multiplayer](https://docs.microsoft.com/gaming/azure/reference-architectures/multiplayer-asynchronous-serverless) | Build a serverless asynchronous multiplayer game on Azure. | Scalable gaming servers |
| [Basic game server hosting](https://docs.microsoft.com/gaming/azure/reference-architectures/multiplayer-basic-game-server-hosting) | Set up a basic Azure back end that hosts a game server on either Windows or Linux. | Server hosting |
| [LAMP architectures for gaming](https://docs.microsoft.com/gaming/azure/reference-architectures/general-purpose-lamp) | Learn how to  effectively and efficiently deploy an existing LAMP architecture on Azure. | Server hosting |


## Related resources

- [Browse all our game development architectures](/azure/architecture/browse/?terms=game)
