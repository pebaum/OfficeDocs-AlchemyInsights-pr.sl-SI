---
title: Sodobna stran kot korensko mesto
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.date: 04/21/2020
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000265"
- "1874"
ms.openlocfilehash: 0388f95e2b7815dcbbb6aca200f44e55e9c5724f
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sl-SI
ms.lasthandoff: 04/22/2020
ms.locfileid: "43713807"
---
# <a name="modern-site-as-root-site"></a>Sodobna stran kot root stran

Začeli smo, da uvajanje nove funkcije, ki vam bo omogočilo, da [swap vaše klasično stran root stran s sodobno spletno stran](https://docs.microsoft.com/sharepoint/modern-root-site). Uporaba [sklicevati-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) zamenjati lokacijo mesta z drugo spletno stran, medtem ko arhiviranje izvirno mesto. Na voljo za obe strani skupine (ni povezan s skupino) in mesto za komunikacijo.

>[!Important]
> Ne izbrišite klasične korenske strani, da ustvarite sodobno komunikacijsko mesto. Microsoft tega ne podpira. Če izbrišete korensko mesto, bodo vsa SharePointova mesta v vaši organizaciji nedostopna vsem uporabnikom, dokler ne obnovite mesta ali ustvarite novega mesta na istem URL-ju. To funkcijo bomo komunicirali prek centra za sporočila. Pričakovati je, da bo funkcija v kratkem vklopljena v najemniku.

## <a name="known-issues-with-swapping-sites"></a>Znane težave s zamenjavo strani
- Ciljna stran lahko za kratek čas vrne napako» ni mogoče najti «(HTTP 404).
- Vsebino bo treba ponovno prejeti, da posodobite indeks iskanja. Tu ni ročnega koraka, ki je zahtevan tukaj, to se bo samodejno zgodilo.
- Vse odvisno od "statičnih" povezav (kot so file Sync in OneNote datoteke) bo treba ročno popraviti.
- Mesta strežnika Project Server je morda treba potrditi, da se zagotovi, da so še vedno pravilno povezani. 
