---
title: 1336 RecoverableItems mapa je polna
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1336
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: a048949d5284d018303d03aad26cdf26eee2fb5c
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: sl-SI
ms.lasthandoff: 03/22/2019
ms.locfileid: "30776412"
---
# <a name="the-recoverable-items-folder-is-full"></a><span data-ttu-id="c8471-102">«Mapa »Obnovljivo «je poln</span><span class="sxs-lookup"><span data-stu-id="c8471-102">The Recoverable Items folder is full</span></span>

<span data-ttu-id="c8471-103">Za nabiralnikov Exchange Online v Office 365, privzeto omejitev velikosti shrambe za mapo »Obnovljivo« je 30 GB.</span><span class="sxs-lookup"><span data-stu-id="c8471-103">For Exchange Online mailboxes in Office 365, the default storage limit for the Recoverable Items folder is 30 GB.</span></span> <span data-ttu-id="c8471-104">Omejitev velikosti shrambe za mapo »Obnovljivo« se samodejno poveča na 100 GB, če nabiralnik je postavljena na čakanje, eDiscovery drži, ali je dodeljen pravilnik o hranjenju z Office 365.</span><span class="sxs-lookup"><span data-stu-id="c8471-104">The storage limit for the Recoverable Items folder is automatically increased to 100 GB if the mailbox is placed on Litigation Hold, eDiscovery hold, or is assigned to an Office 365 retention policy.</span></span>
  
<span data-ttu-id="c8471-105">Ko mapo »Obnovljivo «doseže omejitev velikosti shrambe, nabiralnik funkcionalnost vpliva na naslednje načine:</span><span class="sxs-lookup"><span data-stu-id="c8471-105">When the Recoverable Items folder reaches the storage limit, mailbox functionality is affected in the following ways:</span></span>
  
- <span data-ttu-id="c8471-106">Uporabnik ne more izbrisati elemente iz nabiralnika.</span><span class="sxs-lookup"><span data-stu-id="c8471-106">The user can't delete items from the mailbox.</span></span>
    
- <span data-ttu-id="c8471-107">Pomočnik za upravljane mape ne morete izbrisati elementov glede na oznako za hranjenje ali nastavitve za upravljane mape.</span><span class="sxs-lookup"><span data-stu-id="c8471-107">The Managed Folder Assistant can't delete items based on retention tag or managed folder settings.</span></span>
    
- <span data-ttu-id="c8471-108">Za nabiralnike, ki imajo omogočeno obnovitvijo posamezen element ali so postavljena na čakanje, kopijo na napišite strani zaščitnega postopka ne more vzdrževati različice elementov, ki jih bo uporabnik.</span><span class="sxs-lookup"><span data-stu-id="c8471-108">For mailboxes that have Single Item Recovery enabled or are placed on hold, the copy-on-write page protection process can't maintain versions of items edited by the user.</span></span>
    
- <span data-ttu-id="c8471-109">Za nabiralnike, ki so nabiralnik revizijo omogočenim pisanjem dnevnika, vnose v dnevnik nadzora ni nabiralnik lahko shranite v revizije podmapo v mapi »obnovljivo« .</span><span class="sxs-lookup"><span data-stu-id="c8471-109">For mailboxes that have mailbox audit logging enabled, no mailbox audit log entries can be saved in the Audits subfolder in the Recoverable Items folder.</span></span>
    
<span data-ttu-id="c8471-110">Za nabiralnike, ki niso na čakanju, administratorji lahko uporabite na `Search-Mailbox -SearchDumpsterOnly -DeleteContent` v Exchange Online PowerShell za brisanje elementov v mapi »obnovljivo« .</span><span class="sxs-lookup"><span data-stu-id="c8471-110">For mailboxes that aren't on hold, admins can use the  `Search-Mailbox -SearchDumpsterOnly -DeleteContent` command in Exchange Online PowerShell to delete items in the Recoverable Items folder.</span></span> <span data-ttu-id="c8471-111">Če želite več informacij, glejte te teme:</span><span class="sxs-lookup"><span data-stu-id="c8471-111">For more information, see the following topics:</span></span> 
  
- [<span data-ttu-id="c8471-112">Iskanje in brisanje sporočil</span><span class="sxs-lookup"><span data-stu-id="c8471-112">Search for and delete messages</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-for-and-delete-messagesadmin-help)
    
- [<span data-ttu-id="c8471-113">Search-Mailbox</span><span class="sxs-lookup"><span data-stu-id="c8471-113">Search-Mailbox</span></span>](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)
    
<span data-ttu-id="c8471-114">Za nabiralnike, ki so na čakanju, administratorji morali odstraniti zadržanja, preden se lahko izbrisano iz mape »Obnovljivo« .</span><span class="sxs-lookup"><span data-stu-id="c8471-114">For mailboxes that are on hold, admins have to remove the hold before they can deleted items from the Recoverable Items folder.</span></span> <span data-ttu-id="c8471-115">Če želite več informacij, glejte [brisanje elementov v obnovljivo mapo oblaku nabiralnikov na imajo](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="c8471-115">For more information, see [Delete items in the Recoverable Items folder of cloud-based mailboxes on hold](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span></span>
  
<span data-ttu-id="c8471-116">Da bi preprečili mape »Obnovljivo« od postane poln, lahko administratorji poveča omejitev velikosti shrambe za obnovljivo mapo za nabiralnike v strežniku imajo in nastavite pravilnika o hranjenju za nabiralnik, ki premakne elemente iz mape »Obnovljivo« v uporabnikovem Arhiv nabiralnik.</span><span class="sxs-lookup"><span data-stu-id="c8471-116">To help prevent the Recoverable Items folder from becoming full, admins can increase the storage limit of the Recoverable Items folder for mailboxes on hold and set up a mailbox retention policy that moves items from the Recoverable Items folder to the user's archive mailbox.</span></span> <span data-ttu-id="c8471-117">Glej, [povečanje obnovljivo imajo količinske omejitve za nabiralnike v strežniku](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="c8471-117">See [Increase the Recoverable Items quota for mailboxes on hold](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span></span>
  
