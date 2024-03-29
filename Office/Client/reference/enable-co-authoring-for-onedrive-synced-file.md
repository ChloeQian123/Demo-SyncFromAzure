---
title: Enable co-authoring for OneDrive-synced files
description: Explains how to enable co-authoring for OneDrive-synced files in Office 365 after a September 2019 change removes the feature.
author: lucciz
ms.author: v-zolu
manager: dcscontentpm
audience: ITPro 
ms.topic: article 
ms.prod: office 365
ms.custom: CSSTroubleshoot
localization_priority: Normal
search.appverid: 
- MET150
appliesto:
- OneDrive for Business
---

# How to enable co-authoring for OneDrive-synced files in Office 365

## Summary

Beginning in the September 2019 update for Microsoft Office 365, co-authoring capabilities will no longer be available for files that are synced to a local computer through the OneDrive for Business (Groove.exe) sync client. 

After this update is applied, you will see the following changes:  
 
- Locally synced Office files (such as Word documents, Excel spreadsheets, and PowerPoint presentations) that are synced by OneDrive for Business (Groove.exe) will no longer allow co-authoring between multiple users. This affects only locally synced files. It does not affect files that are opened directly from a SharePoint URL.     
- Files will have multiple entries for the Most Recently Used list in Office applications. This includes both the local and SharePoint-accessed file.    
- Files that are opened directly from a SharePoint URL while the computer is not connected to the internet will not open.

 
We are targeting this change to go into effect starting in the September 2019 monthly update (build 16.0.12129.xxxxx) Additionally, this change will be rolled into the next semi-annual channel release in the January 2020 update.   

## Workaround

If you are affected by this change, you can use one of the following workarounds (provided in recommended order).

### Workaround 1: Use the OneDrive sync client for SharePoint workloads

The OneDrive Sync Client (OneDrive.exe) is the recommended client for syncing SharePoint Online and SharePoint 2019 content. It will continue to allow co-authoring capabilities for synced files, together with features and improvements such as Files On-Demand. We recommend that all users and organizations move to the OneDrive sync client. 
For more information about how to deploy the OneDrive sync client, see [The OneDrive sync client](https://docs.microsoft.com/onedrive/one-drive-sync).

### Workaround 2: Open the file directly from SharePoint 

This change affects only local files that are synced by OneDrive for Business (Groove.exe). Users who open the Office file directly from SharePoint or OneDrive on the web will continue to be able to co-author.

### Workaround 3: Stay on a version of Office earlier than September 2019 (not recommended)

Versions of Office that are earlier than the September 2019 monthly update will continue to have co-authoring capabilities. However, we do not recommend this method. This is because the rest of the Office suite will no longer get the latest features, bugfixes, and improvements.
