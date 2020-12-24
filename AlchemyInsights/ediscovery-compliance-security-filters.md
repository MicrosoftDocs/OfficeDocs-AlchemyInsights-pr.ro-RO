---
title: Nu a fost returnat niciun rezultat în timpul căutării de conținut/export
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3200003"
- "7463"
ms.openlocfilehash: 8786f11f170edb151879235e19caa38b50f3f06e
ms.sourcegitcommit: 3d662e1a1440ba74b5347896347d03bb8c8f3af5
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 12/22/2020
ms.locfileid: "49727235"
---
# <a name="no-results-returned-during-content-searchexport"></a><span data-ttu-id="5a877-102">Nu a fost returnat niciun rezultat în timpul căutării de conținut/export</span><span class="sxs-lookup"><span data-stu-id="5a877-102">No results returned during Content Search/Export</span></span>

<span data-ttu-id="5a877-103">Dacă întâmpinați probleme cu următoarele scenarii eDiscovery:</span><span class="sxs-lookup"><span data-stu-id="5a877-103">If you are experiencing issues with the following eDiscovery scenarios:</span></span>

- <span data-ttu-id="5a877-104">Căutarea de conținut/exportul nu returnează date sau date neașteptate</span><span class="sxs-lookup"><span data-stu-id="5a877-104">Content Search/Export returns no data or unexpected data</span></span>
- <span data-ttu-id="5a877-105">Căutarea sau exportul eDiscovery nu reușește</span><span class="sxs-lookup"><span data-stu-id="5a877-105">eDiscovery Search or Export fails</span></span>

<span data-ttu-id="5a877-106">Acest lucru se poate datora anumitor filtre de securitate conformității care au fost de configurare de către un anumit administrator și nu au fost comunicate către toți administratorii.</span><span class="sxs-lookup"><span data-stu-id="5a877-106">This may be due to certain Compliance Security Filters that were setup by a specific Admin and not been communicated to all Admins.</span></span>

<span data-ttu-id="5a877-107">Pentru a rezolva acest lucru, Verificați dacă există filtre de securitate conformității care pot provoca aceste probleme:</span><span class="sxs-lookup"><span data-stu-id="5a877-107">To resolve this, check if there are any Compliance Security Filters that may be causing these issues:</span></span>

1. <span data-ttu-id="5a877-108">Conectarea la centrul de securitate și conformitate PowerShell</span><span class="sxs-lookup"><span data-stu-id="5a877-108">Connect to Security and Compliance Center Powershell</span></span>
2. <span data-ttu-id="5a877-109">Rulează următorul commandlet:</span><span class="sxs-lookup"><span data-stu-id="5a877-109">Run the following commandlets:</span></span>

    `$org = “yourdomain.com”`

    `Get-ComplianceSecurityFilter -Organization $org`

<span data-ttu-id="5a877-110">Pentru informații suplimentare despre filtrele de securitate de conformitate, consultați [Filtrarea permisiunilor pentru căutarea de conținut](https://docs.microsoft.com/microsoft-365/compliance/permissions-filtering-for-content-search)</span><span class="sxs-lookup"><span data-stu-id="5a877-110">For additional information on Compliance Security Filters, see [Permissions Filtering for Content Search](https://docs.microsoft.com/microsoft-365/compliance/permissions-filtering-for-content-search)</span></span>