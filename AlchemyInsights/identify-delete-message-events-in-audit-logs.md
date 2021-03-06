---
title: Prepoznavanje dogodkov brisanja sporočil v dnevnikih revizij
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1370"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 641c0216491186aeb423a13854c6b39ee005e5df
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sl-SI
ms.lasthandoff: 06/02/2020
ms.locfileid: "44509004"
---
# <a name="audit-logs-for-deleted-email-messages"></a>Dnevniki revizij za izbrisana e-poštna sporočila

Od januarja 2019 se Microsoft samodejno obrača na beleženje dnevnika nadzora nabiralnika. V nasprotnem primeru, če želite pregledati brisanje dogodkov sporočila za določenega uporabnika, morate ročno omogočiti brisanje dejanj za nadzor. Če je beleženje revizij nabiralnika že omogočeno za vašo organizacijo ali za določenega uporabnika, sledite spodnjim korakom.

1. Prijavite se v [Microsoft 365 Security & center za skladnost](https://protection.office.com/)

2. Kliknite **iskanje in preiskovanje** ter izberite **iskanje dnevnika revizij**.

3. Izberite časovno območje v polji **Začetni datum** in **končni datum** . Določite uporabniško ime za uporabnika, ki ga želite raziskati (uporabnik, ki je izbrisal elemente). V polju **dejavnosti** izberite **izbrisana sporočila iz mape» izbrisani predmeti «** in **premaknjena sporočila v mapo» izbrisani predmeti «**.

4. Kliknite **Iskanje**.

V rezultatih Izberite zapis o reviziji. V meniju podrobnosti kliknite **več informacij**. Dodatne informacije o izbrisanem elementu (na primer vrstica z zadevo in mesto elementa, ko je bil izbrisan) so prikazane v polju» **Affecteditems** «. Lastnost **Clientinfostring** bo pokazala, ali je prišlo do brisanja v Outlooku, Outlooku v spletu (prej znan kot Outlook Web App) ali kateri koli drugi napravi.

Če želite več informacij, glejte [določanje, kdo je nastavil posredovanje e-pošte za nabiralnik](https://docs.microsoft.com/microsoft-365/compliance/auditing-troubleshooting-scenarios#determine-if-a-user-deleted-email-items).

**Opomba**: izbrisanih elementov ni mogoče pridobiti z uporabo funkcije dnevnika revizij. Če želite pridobiti izbrisana sporočila v Outlooku v spletu, glejte [obnovitev izbrisanih elementov v storitvi Outlook Web App](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).
