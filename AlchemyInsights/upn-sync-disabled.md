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
# <a name="upn-sync-disabled"></a>Sincronizarea UPN este dezactivată

Dacă a început să se sincronizeze cu Azure AD înainte de 30 martie 2016, rulați următorul cmdlet Azure AD PowerShell pentru a activa potrivirea soft UPN doar pentru organizația dvs.:
  
 **Set-MsolDirSyncFeature -Caracteristică EnableSoftMatchOnUpn -Activați $True**
  
UpN soft match este activat automat pentru organizațiile care au început să se sincronizeze cu Azure AD la sau după 30 martie 2016.
  
Pentru a afla mai multe despre activarea potrivirii virtuale în UPN și alte caracteristici de sincronizare, consultați [Caracteristicile serviciului de sincronizare Azure AD Connect.](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features)
  

