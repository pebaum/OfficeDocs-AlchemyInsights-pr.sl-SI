---
title: Odpravljanje težav z odprto Explorer
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 12/10/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: ed852342-e33f-4450-8400-63d30df09476
ms.openlocfilehash: 5be8a8f9f67939c7e2671855da259818269d9299
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: sl-SI
ms.lasthandoff: 01/15/2019
ms.locfileid: "28312767"
---
# <a name="fix-problems-with-open-with-explorer"></a>Odpravljanje težav z odprto s raziskovalec

Odpravite pogoste težave z odprtjem knjižnice dokumentov SharePoint ali OneDrive, uporabite ukaz **Odpri v Raziskovalcu** : 
  
- Z Internet Explorerjem 10 ali Internet Explorer 11. **Odpri v Raziskovalcu** ni združljiv z Microsoft Edge, Google Chrome, Firefox in drugi. **Odpri v Raziskovalcu** onemogočena v vseh brskalnikih razen Internet Explorer. 
    
- **Odpri v Raziskovalcu** ni na voljo v moderno izkušnjo za SharePointove knjižnice. Namesto tega uporabite **pogled v Raziskovalcu datoteke** . Izberite **možnosti pogleda** \> **pogled v Raziskovalcu datoteke**. Pogled v Raziskovalcu datoteke ni združljiva z Microsoft Edge, Google Chrome, Firefox in drugi. **Pogled v Raziskovalcu datoteke** na voljo le v Internet Explorerju. 
    
- Preverite, ali je zagnana storitev, od WebClient. V Windows iskalno polje, vnesite Zaženi, izberite prost dostop pult app, vnesite services.msc in pritisnite Enter. Se pomaknite navzdol do WebClient storitev in se prepričajte v stolpcu **stanje** prikaže "Teče". Če ne, dvokliknite storitve, kliknite **Start**in nato kliknite v **redu**. (Morda boste morali najprej omogočiti storitev tako, da izberete **ročno** ali **avtomatsko** v polje **Vrsta zagona** .) 
    
> [!NOTE]
> Otvoritev knjižnice v datoteko Explorer je priročno, če želite kopirati ali premakniti več datotek in map, ko, vendar če želite redno delo v knjižnici, priporočamo, da sinhronizirate. Odpravljanje težav v datoteko Explorer, glejte [plan v raziskovalec](https://go.microsoft.com/fwlink/?linkid=871665). Informacij o nastavitev sinhronizacije, glejte [Sinhroniziranje SharePointovih datotek z novo OneDrive sinhronizacijo odjemalca](https://go.microsoft.com/fwlink/?linkid=871666).
  
Prosimo, glejte članek [kako uporabite ukaz »Odpri z Explorer« težave v SharePoint Online](https://support.office.com/en-us/article/How-to-use-the-Open-with-Explorer-command-to-troubleshoot-issues-in-SharePoint-Online-87155331-0c92-4224-a4c1-da5c21c4ade4) za več informacij. 
  
