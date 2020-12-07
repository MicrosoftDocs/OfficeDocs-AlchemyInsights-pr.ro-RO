---
title: Ce se poate face dacă caracteristicile Azure nu funcționează corect în Microsoft Edge
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
- "9004128"
- "7206"
ms.openlocfilehash: 463236bcd9ff480471604c992aa1ed1ed4ac2987
ms.sourcegitcommit: 2e4a5153e530bf15744a52e982eeb0d99757e9d2
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 12/04/2020
ms.locfileid: "49583785"
---
# <a name="what-to-do-if-azure-features-dont-work-properly-in-microsoft-edge"></a><span data-ttu-id="d3406-102">Ce se poate face dacă caracteristicile Azure nu funcționează corect în Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="d3406-102">What to do if Azure features don't work properly in Microsoft Edge</span></span>

<span data-ttu-id="d3406-103">Microsoft Edge are [probleme cunoscute](https://go.microsoft.com/fwlink/?linkid=2140608) legate de zonele de securitate și pot afecta modul în care utilizatorii Azure se conectează la centrul de administrare Windows.</span><span class="sxs-lookup"><span data-stu-id="d3406-103">Microsoft Edge has [known issues](https://go.microsoft.com/fwlink/?linkid=2140608) that are related to security zones and might affect how Azure users log in to Windows Admin Center.</span></span> <span data-ttu-id="d3406-104">Dacă întâmpinați probleme la utilizarea caracteristicilor Azure cu Microsoft Edge, încercați următorii pași:</span><span class="sxs-lookup"><span data-stu-id="d3406-104">If you're having trouble using Azure features with Microsoft Edge, try the following steps:</span></span>

1. <span data-ttu-id="d3406-105">În meniul **Start** , căutați **Opțiuni Internet** și selectați-l.</span><span class="sxs-lookup"><span data-stu-id="d3406-105">In the **Start** menu, search for **Internet Options** and select it.</span></span>
2. <span data-ttu-id="d3406-106">În caseta de dialog **Proprietăți Internet** , accesați fila **Securitate** .</span><span class="sxs-lookup"><span data-stu-id="d3406-106">In the **Internet Properties** dialog box, go to the **Security** tab.</span></span>
3. <span data-ttu-id="d3406-107">Selectați zona **site-uri de încredere** , apoi selectați butonul **site-uri** .</span><span class="sxs-lookup"><span data-stu-id="d3406-107">Select the **Trusted sites** zone and then select the **Sites** button.</span></span>
4. <span data-ttu-id="d3406-108">În caseta de dialog **site-uri de încredere** , adăugați adresa URL a gateway-ului, precum [https://login.microsoftonline.com](https://login.microsoftonline.com) și [https://login.live.com](https://login.live.com) , apoi selectați **Închidere**.</span><span class="sxs-lookup"><span data-stu-id="d3406-108">In the **Trusted sites** dialog box, add your gateway URL as well as [https://login.microsoftonline.com](https://login.microsoftonline.com) and [https://login.live.com](https://login.live.com), and then select **Close**.</span></span>
5. <span data-ttu-id="d3406-109">În caseta de dialog **Proprietăți Internet** , accesați fila **confidențialitate** .</span><span class="sxs-lookup"><span data-stu-id="d3406-109">In the **Internet Properties** dialog box, go to the **Privacy** tab.</span></span>
6. <span data-ttu-id="d3406-110">În secțiunea **Blocare ferestre pop-up** , selectați **Setări**.</span><span class="sxs-lookup"><span data-stu-id="d3406-110">In the **Pop-up Blocker** section, select **Settings**.</span></span> <span data-ttu-id="d3406-111">În caseta de dialog care se deschide, adăugați adresa URL a gateway-ului, precum [https://login.microsoftonline.com](https://login.microsoftonline.com) și [https://login.live.com](https://login.live.com) , apoi selectați **Închidere**.</span><span class="sxs-lookup"><span data-stu-id="d3406-111">In the dialog box that opens, add your gateway URL as well as [https://login.microsoftonline.com](https://login.microsoftonline.com) and [https://login.live.com](https://login.live.com), and then select **Close**.</span></span>
