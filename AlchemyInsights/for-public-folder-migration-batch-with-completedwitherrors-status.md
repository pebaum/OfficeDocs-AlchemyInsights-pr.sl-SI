---
title: Za selitev javnih map s stanjem» CompletedWithErrors «
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3532"
ms.openlocfilehash: 739e9d91f90e4c0374814d199e4372eb5625553a
ms.sourcegitcommit: 2a9d059262c07c33f9a740b3da4e6e3366b2f925
ms.translationtype: MT
ms.contentlocale: sl-SI
ms.lasthandoff: 02/20/2020
ms.locfileid: "42158637"
---
# <a name="for-public-folder-migration-batch-with-completedwitherrors-status"></a>Za selitev javnih map s stanjem» CompletedWithErrors «

Uporabite naslednje korake za dokončanje serije, preskoči velike/slabe elemente: 
1. Odobrite izpuščene elemente v selitvenem paketu:

    `Set-MigrationBatch \<batchname> -ApproveSkippedItems` 
2. S tem ukazom odobrite izpuščene elemente v zahtevah za selitev, ki so» sinhronizirani «, vendar niso končani:

    `$pf=Get-PublicFolderMailboxMigrationRequest | Get-PublicFolderMailboxMigrationRequestStatistics -IncludeReport; ForEach ($i in $pf) {if ($i.LargeItemsEncountered -gt 0 -or $i.BadItemsEncountered -gt 0) {Set-PublicFolderMailboxMigrationRequest $i.Identity.IdentifyingGuid -SkippedItemApprovalTime $([DateTime]::UtcNow)}}`
3. Selitveni paket in zahteve se morajo nadaljevati in dokončati v nekaj minutah.

