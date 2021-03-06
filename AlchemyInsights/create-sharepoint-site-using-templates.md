---
title: Ustvarjanje spletnega mesta v SharePointu online
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 84f2b70e-2b23-4039-8305-85783798feed
ms.openlocfilehash: b9009fdbdc2a5e7443151446daade1685d2f5d45
ms.sourcegitcommit: 317eeed39c7777a922442992d67733726c41d9e1
ms.translationtype: MT
ms.contentlocale: sl-SI
ms.lasthandoff: 02/04/2020
ms.locfileid: "41770439"
---
# <a name="create-sharepoint-sites-using-templates"></a>Ustvarjanje SharePointovih mest s predlogami

Zmožnost shranjevanja spletnega mesta kot predloge ni podprta s sodobnimi komunikacijskimi ali skupinskega mesta. Če želite več informacij o uporabi predlog [, glejte shranjevanje, prenos in nalaganje SharePointovega mesta kot predloge](https://docs.microsoft.com/sharepoint/dev/general-development/save-download-and-upload-a-sharepoint-site-as-a-template).

Tukaj je nekaj pogostih težav/rešitev v zvezi s shranjevanjem mesta ali seznama kot predloge v programu SharePoint online. 

**Gumb» Shrani predlogo mesta/seznama «ni na voljo ali manjka**

Skrbniki bodo morali dovoliti skript po meri za omogočanje funkcij predloge. Za podrobnejše korake, primere in premisleke glej 

- [Omogočanje ali preprečevanje skripta po meri](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)

- Ukaz» Shrani mesto kot predlogo «ni podprt in lahko povzroči težave na spletnih mestih, ki uporabljajo infrastrukturo za objavljanje strežnika SharePoint Server.

**Predloge mesta ni mogoče ustvariti ali pa ne deluje pravilno**

Predloga morda manjka [funkcija](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) in se ne bo aktivirala. Če funkcija ni na voljo za aktiviranje v trenutni zbirki mest, ne morete uporabiti predloge mesta za ustvarjanje mesta.

- Preverite, ali seznami ali knjižnice presegajo [prag pogleda seznama](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) za 5000 elementov, saj lahko to blokira ustvarjanje predloge mesta.

- Spletna stran lahko uporablja preveč sredstev in zato predlogo mesta presega 50 MB omejitev.


- Na seznamu so težave s prikazom podatkov s seznama, ki uporablja stolpec za iskanje. Če želite več informacij, glejte [predloge-ustvarjeni seznam ne prikaže podatkov s pravilnega seznama za iskanje v SharePoint online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).

Za podrobnejše informacije o pogostih problemih in rešitvah preverite [Ustvarjanje in uporabo predlog mesta](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).



