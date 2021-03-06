---
title: Težave s povezavo za SharePoint Designer
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 01ccc6bc28148f397fb6cd2b7a0eaaeb5b51973f
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sl-SI
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511560"
---
# <a name="sharepoint-designer-connection-issues"></a>Težave s povezavo za SharePoint Designer 

Če SharePoint Designer doživlja težave s povezavo s SharePointovimi mesti, poskusite z naslednjimi skupnimi rešitvami.

Korak 1: Preverite, ali je SharePoint Designer 2013 posodobljen s [servisnim paketom SharePoint Designer 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) in [avgustom 2, 2016 posodobitev za SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).



2. korak: počistite lokalne datoteke predpomnilnika:

1. Zaprite SharePoint Designer 2013.

2. V lokalnem računalniku odstranite vse datoteke, najdene v vsaki od teh map.

    - %AppData%\microsoft\spletni strežnik Extensions\Cache
    - %APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache
    - %USERPROFILE%\AppData\Local\Microsoft\WebsiteCache

3. Odprite SharePoint Designer 2013 in znova vnesite račun, da preverite, ali deluje.

Korak 3: [omogočite sodobno preverjanje pristnosti za Office 2013 v napravah s sistemom Windows](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).

Korak 4: skrbniki bodo morali **dovoliti skript po meri** v nastavitvah SharePoint skrbniško središče, da se omogoči povezava SharePointovega oblikovalca. Če želite več informacij, glejte [Omogočanje ali preprečevanje skripta po meri](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) .


