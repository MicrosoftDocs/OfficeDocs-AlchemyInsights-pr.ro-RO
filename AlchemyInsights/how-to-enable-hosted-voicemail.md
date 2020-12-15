---
title: Cum se activează mesageria vocală găzduită
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 12/09/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9002347"
- "7563"
ms.openlocfilehash: 26eb22054d246a6ca5a2491c68a5d9e4ed90d45b
ms.sourcegitcommit: 523098560e54a50184a99c974809dfbfffadacb5
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 12/09/2020
ms.locfileid: "49679168"
---
# <a name="how-to-enable-hosted-voicemail"></a><span data-ttu-id="b341d-102">Cum se activează mesageria vocală găzduită</span><span class="sxs-lookup"><span data-stu-id="b341d-102">How to enable Hosted Voicemail</span></span>

<span data-ttu-id="b341d-103">Pentru a activa mesageria vocală, **HostedVoicemail** trebuie setată la $True.</span><span class="sxs-lookup"><span data-stu-id="b341d-103">To enable Voicemail, **HostedVoicemail** must be set to $true.</span></span>

<span data-ttu-id="b341d-104">Proprietatea **HostedVoicemail** a utilizatorului utilizând Remote POWERSHELL (RPS).</span><span class="sxs-lookup"><span data-stu-id="b341d-104">The **HostedVoicemail** property on the user using Remote PowerShell (RPS).</span></span>

<span data-ttu-id="b341d-105">Pentru mai multe informații despre conectarea la RPS, consultați [prezentarea generală Microsoft teams PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview) pentru mai multe informații despre conectarea la RPS.</span><span class="sxs-lookup"><span data-stu-id="b341d-105">For more information on connecting to RPS, see [Microsoft Teams PowerShell Overview](https://docs.microsoft.com/microsoftteams/teams-powershell-overview) for more information on connecting to RPS.</span></span>

1. <span data-ttu-id="b341d-106">Administratorul teams trebuie să fie conectat la Remote PowerShell pentru teams.</span><span class="sxs-lookup"><span data-stu-id="b341d-106">The Teams Admin should be logged into Remote PowerShell for Teams.</span></span>
1. <span data-ttu-id="b341d-107">Din PowerShell prompt, administratorul teams poate executa **set-csuser user@contoso.com-HostedVoiceMail $True** în care SIP uri este al utilizatorului în cauză.</span><span class="sxs-lookup"><span data-stu-id="b341d-107">From PowerShell prompt the Teams Admin can run **set-csuser user@contoso.com -HostedVoiceMail $true** where the sip uri is of the user in question.</span></span>

> [!NOTE]
> <span data-ttu-id="b341d-108">Modificările aduse politicilor pot dura până la 24 de ore pentru reproducere.</span><span class="sxs-lookup"><span data-stu-id="b341d-108">Changes to policies can take up to 24 hours to replicate.</span></span>