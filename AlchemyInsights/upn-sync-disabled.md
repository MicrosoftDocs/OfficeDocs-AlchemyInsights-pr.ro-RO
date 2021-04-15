---
title: Sincronizarea UPN este dezactivată
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 2a3489fe-c2a8-4e43-96c2-be4b3c5e978c
ms.openlocfilehash: 2b1ba772459091ce1a796884997fe2516d0407eb
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 04/15/2021
ms.locfileid: "51782163"
---
# <a name="upn-sync-disabled"></a><span data-ttu-id="ead05-102">Sincronizarea UPN este dezactivată</span><span class="sxs-lookup"><span data-stu-id="ead05-102">UPN sync disabled</span></span>

<span data-ttu-id="ead05-103">Dacă a început să se sincronizeze cu Azure AD înainte de 30 martie 2016, rulați următorul cmdlet Azure AD PowerShell pentru a activa potrivirea soft UPN doar pentru organizația dvs.:</span><span class="sxs-lookup"><span data-stu-id="ead05-103">If you started syncing to Azure AD before March 30, 2016, run the following Azure AD PowerShell cmdlet to enable UPN soft match for your organization only:</span></span>
  
 <span data-ttu-id="ead05-104">**Set-MsolDirSyncFeature -Caracteristică EnableSoftMatchOnUpn -Activați $True**</span><span class="sxs-lookup"><span data-stu-id="ead05-104">**Set-MsolDirSyncFeature -Feature EnableSoftMatchOnUpn -Enable $True**</span></span>
  
<span data-ttu-id="ead05-105">UpN soft match este activat automat pentru organizațiile care au început să se sincronizeze cu Azure AD la sau după 30 martie 2016.</span><span class="sxs-lookup"><span data-stu-id="ead05-105">UPN soft match is automatically turned on for organizations that started syncing to Azure AD on or after March 30, 2016.</span></span>
  
<span data-ttu-id="ead05-106">Pentru a afla mai multe despre activarea potrivirii virtuale în UPN și alte caracteristici de sincronizare, consultați [Caracteristicile serviciului de sincronizare Azure AD Connect.](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features)</span><span class="sxs-lookup"><span data-stu-id="ead05-106">To learn more about enabling soft match on UPN and other sync features, please see [Azure AD Connect sync service features](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).</span></span>
  

