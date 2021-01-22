---
title: Activarea tehnologiei,
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
- "9004403"
- "7947"
ms.openlocfilehash: ea694898baffa50fca71957175eba3664dece44e
ms.sourcegitcommit: 112f18dce8257b98fab32d44910ee879efb44cb8
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 01/21/2021
ms.locfileid: "49935136"
---
# <a name="turn-on-ndi-technology"></a><span data-ttu-id="5c261-102">Activarea tehnologiei,</span><span class="sxs-lookup"><span data-stu-id="5c261-102">Turn on NDI technology</span></span>

<span data-ttu-id="5c261-103">Tehnologia, pentru un utilizator, trebuie să fie activate doi pași:</span><span class="sxs-lookup"><span data-stu-id="5c261-103">NDI technology requires two steps to be turned on for a user:</span></span>

1. <span data-ttu-id="5c261-104">Administratorul entității găzduite trebuie să activeze proprietatea ' AllowNDIStreaming ' în CsTeamsMeetingPolicy.</span><span class="sxs-lookup"><span data-stu-id="5c261-104">The tenant admin must enable the 'AllowNDIStreaming' property in CsTeamsMeetingPolicy.</span></span>

    `Set-CsTeamsMeetingPolicy -Identity MEETING_POLICY -AllowNDIStreaming $true`

2. <span data-ttu-id="5c261-105">După ce această modificare a fost populată, utilizatorul final trebuie să activeze tehnologia®, pentru clientul său specific, din **permisiunile > permisiuni**.</span><span class="sxs-lookup"><span data-stu-id="5c261-105">After this change has populated, the end user must turn on NDI® technology for their specific client from **Settings > Permissions**.</span></span>

<span data-ttu-id="5c261-106">Pentru mai multe informații, consultați [utilizarea tehnologiei, în Microsoft teams](https://docs.microsoft.com/microsoftteams/use-ndi-in-meetings).</span><span class="sxs-lookup"><span data-stu-id="5c261-106">For more information, see [Use NDI technology in Microsoft Teams](https://docs.microsoft.com/microsoftteams/use-ndi-in-meetings).</span></span>
