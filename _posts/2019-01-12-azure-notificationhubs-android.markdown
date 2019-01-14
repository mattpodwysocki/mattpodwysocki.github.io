---
layout: post
title:  "Azure Notification Hubs for Android Now Updated"
date:   2019-01-13 21:24:47 -0500
categories: azure notificationhubs push push-notifications android
---

Our team has been super busy over at [Microsoft App Center](https://azure.microsoft.com/en-us/services/app-center/) working on [Firebase Cloud Messaging](https://firebase.google.com/docs/cloud-messaging/) support for our Android SDKs while still supporting the now deprecated [Google Cloud Messaging]((https://developers.google.com/cloud-messaging/)) support.  In addition, we also updated the code to remove the Apache HttpClient in favor of HttpURLConnection.

You can find our Android SDK for Azure Notifications on [GitHub](https://github.com/Azure/azure-notificationhubs/tree/master/Android) which includes an end to end test application which allows you to receive push notifications using either GCM and FCM.  

We published two tutorials for getting started with the Android SDK:

- [Firebase Cloud Messaging](https://docs.microsoft.com/en-us/azure/notification-hubs/notification-hubs-android-push-notification-google-fcm-get-started)
- [Google Cloud Messaging](https://docs.microsoft.com/en-us/azure/notification-hubs/notification-hubs-android-push-notification-google-gcm-get-started)

Get started with our SDK and leave feedback on GitHub!