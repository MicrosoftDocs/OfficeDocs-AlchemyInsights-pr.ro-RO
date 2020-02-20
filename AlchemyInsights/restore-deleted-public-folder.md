---
title: Restaurarea unui folder public șters
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
- "3488"
ms.openlocfilehash: cd85dd3c0eb14f6e02ac4f912e733468403387aa
ms.sourcegitcommit: 2a9d059262c07c33f9a740b3da4e6e3366b2f925
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 02/20/2020
ms.locfileid: "42158534"
---
# <a name="restore-a-deleted-public-folder"></a>Restaurarea unui folder public șters

**Pentru a restaura elementele șterse dintr-un folder public**:

- Consultați [Nu puteți recupera elementele șterse dintr-un folder public non-mail în Outlook 2016](https://aka.ms/pfrec).
 
**Pentru a restaura un folder public șters (de orice tip)**: 

- Utilizați următoarea comandă EXO PowerShell:

    Sintaxa:

     `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse  | ?{$_.Name -eq "\<name_of_deleted_public_Folder"};Set-PublicFolder $pf.identity -Path \<path where the folder will be restored>`

    Exemplu: Următoarea comandă va restaura Subfolder1 și o va plasa sub \Parent1:

    `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse | ?{$_.Name -eq "Subfolder1"};Set-PublicFolder $pf.identity -Path \Parent1`

Consultați [Restaurarea unui folder public șters](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) pentru mai multe detalii.
