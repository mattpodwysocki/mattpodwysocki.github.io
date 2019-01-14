---
layout: post
title:  "Azure Notification Hubs for .NET Now Open Source"
date:   2019-01-13 21:24:47 -0500
categories: azure notificationhubs push push-notifications
---

Recently, my team at Microsoft, App Center, has open source our .NET SDK for Azure Notification Hubs which is now available on [GitHub]((https://github.com/azure/azure-notificationhubs-dotnet)) and [NuGet](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs/).  The latest release includes support for [.NET Standard 2.0](https://docs.microsoft.com/en-us/dotnet/standard/net-standard) as well as support for [Firebase Cloud Messaging](https://firebase.google.com/docs/cloud-messaging/) in addition to the support for the deprecated [Google Cloud Messaging](https://developers.google.com/cloud-messaging/) APIs.

We include a number of samples to get you started with Azure Notification Hubs.  To get started, check the [Azure Notification Hubs Documentation](https://docs.microsoft.com/en-us/azure/notification-hubs/) which helps you get started on your platform and language of choice, such as iOS, Android and Windows.  The [samples](https://github.com/Azure/azure-notificationhubs-dotnet/tree/master/Samples) listed are as follows:

- CreateHubSample: a command line interface to create an Azure Notification Hub
- SendPushSample: a command line interface to send push notifications and receive PNS feedback
- ParseFeedbackSample: a command line interface to send push notifications and parse per message telemetry
- RegistrationSample: a command line interface to add and delete registrations and installations
- UWPSample: A UWP application for sending push notifications

Get started with the Azure Notification Hubs SDK today and give us feedback via the GitHub repository!