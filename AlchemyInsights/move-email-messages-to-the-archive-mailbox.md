---
title: Premikanje e-poštnih sporočil v arhivski nabiralnik
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1083"
- "3100008"
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: 35c11f1bfb7c61b28a64f0128c29ddf7b4fce939
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sl-SI
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511056"
---
# <a name="move-email-to-the-archive-mailbox"></a>Premakni e-poštno sporočilo v arhivski nabiralnik

1. Potrdite, da je bil omogočen **arhivski nabiralnik** . Če ne, uporabite korake v [tem članku](https://docs.microsoft.com/microsoft-365/compliance/enable-archive-mailboxes) , da omogočite arhivski nabiralnik.

2. Če želite samodejno arhivirati sporočila v arhivski nabiralnik, mora biti oznaka za hranjenje z dejanjem **Premakni v arhiviranje** nastavljena tako, da se **samodejno uporabi za celoten nabiralnik (privzeta) oznaka**. Uporabite korake tukaj za ustvarjanje oznake: [Arhiv privzeta oznaka](https://docs.microsoft.com/microsoft-365/compliance/set-up-an-archive-and-deletion-policy-for-mailboxes#create-a-custom-archive-default-policy-tag).

3. Nato dodajte **arhivsko** oznako v pravilnik o hranjenju. V skrbniškem središču za Exchange izberite **Pravilniki o hranjenju** > dodajte **oznako Premakni v arhiv** v pravilnik > **Shrani**.

4. Zdaj [dodelite pravilnik o hranjenju](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) za nabiralnik določenega uporabnika. Ista politika bo uporabljena za **primarni** in **arhivski** nabiralnik.

Morda bo potrebno prisiliti pomočnika za upravljane mape (MFA), da zažene in uporabi nove nastavitve v nabiralniku uporabnika. Zaženite ta ukaz, medtem ko je [povezan z lupino EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) , da zaženete pomočnika za upravljane mape za določen nabiralnik:
  
Start-ManagedFolderAssistant-identiteta<name of the mailbox>

Če želite več informacij o nastavitvi pravilnika arhiva, glejte [nastavitev pravilnika o arhiviranju in brisanju nabiralnikov](https://docs.microsoft.com/microsoft-365/compliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).
  