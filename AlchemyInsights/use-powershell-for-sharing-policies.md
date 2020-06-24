---
title: Utilizarea PowerShell pentru partajarea politicilor și relațiilor de organizație
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3800014"
- "898"
ms.openlocfilehash: 717cdd6827e243ac6bf375209a911937c97088d2
ms.sourcegitcommit: 722e9a0ed058cb1eab2dd053be2418b60f7d4aac
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 06/23/2020
ms.locfileid: "44862153"
---
# <a name="use-powershell-for-sharing-policies-and-organization-relationships"></a><span data-ttu-id="42964-102">Utilizarea PowerShell pentru partajarea politicilor și relațiilor de organizație</span><span class="sxs-lookup"><span data-stu-id="42964-102">Use PowerShell for Sharing policies and Organization relationships</span></span>


<span data-ttu-id="42964-103">Pentru relațiile de organizație vă rugăm să consultați sintaxa detaliată și informațiile despre parametri pentru : [Get-FederationInformation](https://docs.microsoft.com/powershell/module/exchange/get-federationinformation), [New-OrganizationRelationship](https://docs.microsoft.com/powershell/module/exchange/new-organizationrelationship), [Set-OrganizationRelationship](https://docs.microsoft.com/powershell/module/exchange/set-organizationrelationship) AND [Remove-OrganizationRelationship](https://docs.microsoft.com/powershell/module/exchange/remove-organizationrelationship).</span><span class="sxs-lookup"><span data-stu-id="42964-103">For Organization relationships please review the detailed syntax and parameter information for : [Get-FederationInformation](https://docs.microsoft.com/powershell/module/exchange/get-federationinformation), [New-OrganizationRelationship](https://docs.microsoft.com/powershell/module/exchange/new-organizationrelationship), [Set-OrganizationRelationship](https://docs.microsoft.com/powershell/module/exchange/set-organizationrelationship)  AND  [Remove-OrganizationRelationship](https://docs.microsoft.com/powershell/module/exchange/remove-organizationrelationship).</span></span>

<span data-ttu-id="42964-104">Pentru a crea politica de partajare, utilizați [New-SharingPolicy](https://docs.microsoft.com/powershell/module/exchange/new-sharingpolicy).</span><span class="sxs-lookup"><span data-stu-id="42964-104">To create sharing policy use [New-SharingPolicy](https://docs.microsoft.com/powershell/module/exchange/new-sharingpolicy).</span></span> <span data-ttu-id="42964-105">Pentru a aplica o politică de [partajare unei cutii poștale sau unui utilizator,](https://docs.microsoft.com/exchange/sharing/sharing-policies/apply-a-sharing-policy%23use-exchange-online-powershell-to-apply-a-sharing-policy-to-one-or-more-mailboxes) trebuie să utilizați o combinație de [Set-Cutie poștală](https://docs.microsoft.com/powershell/module/exchange/set-mailbox) și [Get-Mailbox](https://docs.microsoft.com/powershell/module/exchange/get-mailbox) cu politica nou creată.</span><span class="sxs-lookup"><span data-stu-id="42964-105">To  [apply a sharing policy to a mailbox or user](https://docs.microsoft.com/exchange/sharing/sharing-policies/apply-a-sharing-policy%23use-exchange-online-powershell-to-apply-a-sharing-policy-to-one-or-more-mailboxes)  you need to use a combination of  [Set-Mailbox](https://docs.microsoft.com/powershell/module/exchange/set-mailbox) and [Get-Mailbox](https://docs.microsoft.com/powershell/module/exchange/get-mailbox) with the newly created policy.</span></span> <span data-ttu-id="42964-106">Pentru a [modifica, dezactiva sau elimina o politică de partajare](https://docs.microsoft.com/exchange/sharing/sharing-policies/modify-a-sharing-policy) trebuie să utilizați [Politica de partajare și](https://docs.microsoft.com/powershell/module/exchange/set-sharingpolicy) [Politică eliminare-partajare](https://docs.microsoft.com/powershell/module/exchange/remove-sharingpolicy).</span><span class="sxs-lookup"><span data-stu-id="42964-106">To  [modify, disable or remove a sharing policy](https://docs.microsoft.com/exchange/sharing/sharing-policies/modify-a-sharing-policy)  you need to use  [Set-SharingPolicy](https://docs.microsoft.com/powershell/module/exchange/set-sharingpolicy) and [Remove-SharingPolicy](https://docs.microsoft.com/powershell/module/exchange/remove-sharingpolicy).</span></span>

<span data-ttu-id="42964-107">**Pentru o înțelegere completă a acestui subiect vă rugăm să citiți:**</span><span class="sxs-lookup"><span data-stu-id="42964-107">**For full understanding of this topic please read:**</span></span>

[<span data-ttu-id="42964-108">Partajarea în Exchange Online</span><span class="sxs-lookup"><span data-stu-id="42964-108">Sharing in Exchange Online</span></span>](https://docs.microsoft.com/exchange/sharing/sharing)