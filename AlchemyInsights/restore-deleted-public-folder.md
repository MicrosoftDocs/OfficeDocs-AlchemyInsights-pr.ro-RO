---
title: Restaurarea unui folder public șters
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3488"
ms.openlocfilehash: bb7fe248714e9a7e7f4c48913b159b5c23132192
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 09/15/2020
ms.locfileid: "47774543"
---
# <a name="restore-a-deleted-public-folder"></a><span data-ttu-id="7d448-102">Restaurarea unui folder public șters</span><span class="sxs-lookup"><span data-stu-id="7d448-102">Restore a deleted public folder</span></span>

<span data-ttu-id="7d448-103">**Pentru a restaura elementele șterse dintr-un folder public**:</span><span class="sxs-lookup"><span data-stu-id="7d448-103">**To restore deleted items from a public folder**:</span></span>

- <span data-ttu-id="7d448-104">Consultați [nu puteți recupera elementele șterse dintr-un folder public non-corespondență din Outlook 2016](https://aka.ms/pfrec).</span><span class="sxs-lookup"><span data-stu-id="7d448-104">See [You can't recover deleted items from a non-mail public folder in Outlook 2016](https://aka.ms/pfrec).</span></span>
 
<span data-ttu-id="7d448-105">**Pentru a restaura un folder public șters (de orice tip)**:</span><span class="sxs-lookup"><span data-stu-id="7d448-105">**To restore a deleted public folder (of any type)**:</span></span> 

- <span data-ttu-id="7d448-106">Vă rugăm să utilizați următoarea comandă EXO PowerShell:</span><span class="sxs-lookup"><span data-stu-id="7d448-106">Please use following EXO PowerShell command:</span></span>

    <span data-ttu-id="7d448-107">Sintaxa</span><span class="sxs-lookup"><span data-stu-id="7d448-107">Syntax:</span></span>

     `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse  | ?{$_.Name -eq "\<name_of_deleted_public_Folder"};Set-PublicFolder $pf.identity -Path \<path where the folder will be restored>`

    <span data-ttu-id="7d448-108">Exemplu: următoarea comandă va restabili Subfolder1 și o plasează sub \Parent1:</span><span class="sxs-lookup"><span data-stu-id="7d448-108">Example: The following command will restore Subfolder1 and place it under \Parent1:</span></span>

    `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse | ?{$_.Name -eq "Subfolder1"};Set-PublicFolder $pf.identity -Path \Parent1`

<span data-ttu-id="7d448-109">Consultați [restaurarea unui folder public șters](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) pentru mai multe detalii.</span><span class="sxs-lookup"><span data-stu-id="7d448-109">See [Restore a deleted public folder](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) for more details.</span></span>
