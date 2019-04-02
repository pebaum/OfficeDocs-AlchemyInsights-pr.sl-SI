---
title: Napaka Winsock 1554 10061
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1554
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: f44ed42906b85e63f1f694813f54710906969904
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: sl-SI
ms.lasthandoff: 03/22/2019
ms.locfileid: "30772457"
---
# <a name="winsock-error-10061"></a><span data-ttu-id="c7005-102">Napaka Winsock 10061</span><span class="sxs-lookup"><span data-stu-id="c7005-102">Winsock error 10061</span></span>

<span data-ttu-id="c7005-103">Pomeni ta koda napake, da Office 365 ni mogel vzpostaviti vtičnico TCP (povezava) s ciljnega gostitelja.</span><span class="sxs-lookup"><span data-stu-id="c7005-103">This error code means that Office 365 couldn't establish a TCP socket (connection) with the target host.</span></span> <span data-ttu-id="c7005-104">Najverjetnejši vzrok te napake je problem s konfiguracijo požarnega zidu.</span><span class="sxs-lookup"><span data-stu-id="c7005-104">The most likely cause of this error is a problem with your firewall configuration.</span></span> <span data-ttu-id="c7005-105">Težavo, preverite te nastavitve:</span><span class="sxs-lookup"><span data-stu-id="c7005-105">To fix the problem, check these settings:</span></span>
  
- <span data-ttu-id="c7005-106">Preverite konfiguracijo požarnega zidu z informacijami v [Office 365 URL in IP naslov razponi](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span><span class="sxs-lookup"><span data-stu-id="c7005-106">Verify your firewall configuration with the information in [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span></span>
    
- <span data-ttu-id="c7005-107">Če napaka je specifična za Exchange Online varstvo (EOP), si mora prej vročenega spremembo v [Exchange Online zaščite IP naslove](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="c7005-107">If the error is specific to Exchange Online Protection (EOP), you should have been previously notified to a change to the [Exchange Online Protection IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>
    
- <span data-ttu-id="c7005-108">Preverite, da vaš Internet storitev ponudnik (ISP) ni blokira vrata.</span><span class="sxs-lookup"><span data-stu-id="c7005-108">Verify that your Internet Service Provider (ISP) isn't blocking the port.</span></span>
    
- <span data-ttu-id="c7005-109">Preverjanje pametnih in gostiteljskim ter ciljnim nastavitve strežnika v vaš priključki.</span><span class="sxs-lookup"><span data-stu-id="c7005-109">Verify the smart host and target server settings in your connectors.</span></span>
    
<span data-ttu-id="c7005-110">Upoštevajte, da Office 365 ne blokira *dohodne* povezave na ta način.</span><span class="sxs-lookup"><span data-stu-id="c7005-110">Note that Office 365 doesn't block  *incoming*  connections in this manner.</span></span> 
  
