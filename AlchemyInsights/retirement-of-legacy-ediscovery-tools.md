---
title: Upokojitev Legacy orodja e-odkrivanja
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001487"
- "3523"
ms.openlocfilehash: c4632b52dde579b7d5b2e6e15f1583300a0bd136
ms.sourcegitcommit: a7c17217c170ead24571421baaf5a14f1525b1a6
ms.translationtype: MT
ms.contentlocale: sl-SI
ms.lasthandoff: 02/20/2020
ms.locfileid: "42157716"
---
# <a name="retirement-of-legacy-ediscovery-tools"></a><span data-ttu-id="fc54d-102">Upokojitev Legacy orodja e-odkrivanja</span><span class="sxs-lookup"><span data-stu-id="fc54d-102">Retirement of Legacy eDiscovery Tools</span></span>

<span data-ttu-id="fc54d-103">Zaradi nove in izboljšane funkcionalnosti e-odkrivanja v Microsoftovem 365 centru za skladnost bodo v naslednjih mesecih upokojeni naslednji podedovani orodji e-discovery in Commandlets:</span><span class="sxs-lookup"><span data-stu-id="fc54d-103">As a result of the new and improved eDiscovery functionality in Microsoft 365 Compliance center, the following legacy eDiscovery tools and commandlets will be retired in the coming months:</span></span>

- <span data-ttu-id="fc54d-104">In [-Place eDiscovery](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery) in [v mestu ima](https://docs.microsoft.com/exchange/security-and-compliance/create-or-remove-in-place-holds) v skrbniškem središču Exchange.</span><span class="sxs-lookup"><span data-stu-id="fc54d-104">[In-Place eDiscovery](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery) and [In-Place Holds](https://docs.microsoft.com/exchange/security-and-compliance/create-or-remove-in-place-holds) in the Exchange admin center.</span></span>

- <span data-ttu-id="fc54d-105">Cmdlets za Exchange Online PowerShell, ki podpirajo e-odkrivanje in-Place v mestu.</span><span class="sxs-lookup"><span data-stu-id="fc54d-105">The Exchange Online PowerShell cmdlets that support In-Place eDiscovery and In-Place Holds.</span></span> <span data-ttu-id="fc54d-106">(Ti ukazi» cmdlet «so skupno označeni kot» cmdlet «-MailboxSearch.) To vključuje naslednje ukaze» cmdlet «:</span><span class="sxs-lookup"><span data-stu-id="fc54d-106">(These cmdlets are collectively identified as \*-MailboxSearch cmdlets.) This includes the following cmdlets:</span></span>

    - [<span data-ttu-id="fc54d-107">Novo-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="fc54d-107">New-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/new-mailboxsearch)
    - [<span data-ttu-id="fc54d-108">Start-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="fc54d-108">Start-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/start-mailboxsearch)
    - [<span data-ttu-id="fc54d-109">Zaustavitev-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="fc54d-109">Stop-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/stop-mailboxsearch)
    - [<span data-ttu-id="fc54d-110">Set-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="fc54d-110">Set-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/set-mailboxsearch)

- <span data-ttu-id="fc54d-111">Ukaz» cmdlet «za [Iskanje-nabiralnik](https://docs.microsoft.com/powershell/module/exchange/mailboxes/search-mailbox?view=exchange-ps) v PowerShell Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="fc54d-111">The [Search-Mailbox](https://docs.microsoft.com/powershell/module/exchange/mailboxes/search-mailbox?view=exchange-ps) cmdlet in Exchange Online PowerShell.</span></span>
- <span data-ttu-id="fc54d-112">Naslednje operacije v API-ju storitve Exchange Web Services:</span><span class="sxs-lookup"><span data-stu-id="fc54d-112">The following operations in the Exchange Web Services API:</span></span>
    - [<span data-ttu-id="fc54d-113">Getsearchablenabiralniki</span><span class="sxs-lookup"><span data-stu-id="fc54d-113">GetSearchableMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getsearchablemailboxes-operation)
    - [<span data-ttu-id="fc54d-114">Setholdonnabiralniki</span><span class="sxs-lookup"><span data-stu-id="fc54d-114">SetHoldOnMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/setholdonmailboxes-operation)
    - [<span data-ttu-id="fc54d-115">Getholdonnabiralniki</span><span class="sxs-lookup"><span data-stu-id="fc54d-115">GetHoldOnMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getholdonmailboxes-operation)

- [<span data-ttu-id="fc54d-116">Urad 365 napreden eDiscovery v 1.0</span><span class="sxs-lookup"><span data-stu-id="fc54d-116">Office 365 Advanced eDiscovery v1.0</span></span>](https://docs.microsoft.com/en-us/microsoft-365/compliance/office-365-advanced-ediscovery)

<span data-ttu-id="fc54d-117">**Časovna premica za upokojitev**:</span><span class="sxs-lookup"><span data-stu-id="fc54d-117">**Timeline for retirement**:</span></span>
- <span data-ttu-id="fc54d-118">1. april 2020: ne boste mogli ustvariti novih iskanj in zadržanj, vendar lahko še vedno zaženete, urejate in izbrišete obstoječa iskanja na lastno odgovornost.</span><span class="sxs-lookup"><span data-stu-id="fc54d-118">April 1, 2020: You won't be able to create new searches and holds, but you can still run, edit, and delete existing searches at your own risk.</span></span> <span data-ttu-id="fc54d-119">Microsoftova podpora ne bo več podpirala in-Place eDiscovery & zadržki v EAC.</span><span class="sxs-lookup"><span data-stu-id="fc54d-119">Microsoft Support will no longer support In-Place eDiscovery & Holds in the EAC.</span></span>

- <span data-ttu-id="fc54d-120">1. julij 2020: funkcija eDiscovery & na mestu delovanja v EAC bo postavljena v način samo za branje.</span><span class="sxs-lookup"><span data-stu-id="fc54d-120">July 1, 2020: The In-Place eDiscovery & Holds functionality in the EAC will be placed in a read-only mode.</span></span> <span data-ttu-id="fc54d-121">To pomeni, da boste lahko odstranili obstoječa iskanja in zadržki.</span><span class="sxs-lookup"><span data-stu-id="fc54d-121">This means you'll only be able to remove existing searches and holds.</span></span>

<span data-ttu-id="fc54d-122">**Za več informacij glejte**:</span><span class="sxs-lookup"><span data-stu-id="fc54d-122">**For more information, see**:</span></span>

 - [<span data-ttu-id="fc54d-123">Selitev podedovanih iskanj e-odkrivanja in skladišč v središče za skladnost z Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="fc54d-123">Migrate legacy eDiscovery searches and holds to the Microsoft 365 compliance center</span></span>](https://docs.microsoft.com/en-us/microsoft-365/compliance/migrate-legacy-ediscovery-searches-and-holds)
 - [<span data-ttu-id="fc54d-124">Upokojitev starejših orodij e-odkrivanja</span><span class="sxs-lookup"><span data-stu-id="fc54d-124">Retirement of legacy eDiscovery tools</span></span>](https://docs.microsoft.com/en-us/microsoft-365/compliance/legacy-ediscovery-retirement)
 - [<span data-ttu-id="fc54d-125">Pogosta vprašanja o eDiscovery v mestu in kraju</span><span class="sxs-lookup"><span data-stu-id="fc54d-125">FAQs about In-Place eDiscovery and In-Place Holds</span></span>](https://docs.microsoft.com/en-us/microsoft-365/compliance/legacy-ediscovery-retirement#faqs-about-in-place-ediscovery-and-in-place-holds)


