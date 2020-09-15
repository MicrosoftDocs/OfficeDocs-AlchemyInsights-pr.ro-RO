---
title: Instrucțiuni pentru a ascunde/reafișa grupul din lista de adrese
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
- "1200024"
- "3161"
ms.openlocfilehash: 1ad9ab294d46ca0fc88a454e3503ddcf80398896
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 09/14/2020
ms.locfileid: "47663021"
---
# <a name="hide-microsoft-365-group-from-address-list-gal"></a><span data-ttu-id="abe56-102">Ascunderea grupului Microsoft 365 din lista de adrese (GAL)</span><span class="sxs-lookup"><span data-stu-id="abe56-102">Hide Microsoft 365 group from address list (GAL)</span></span>

<span data-ttu-id="abe56-103">Pentru a ascunde un grup Microsoft 365 din listele de adrese (GAL) ale clienților Exchange (cum ar fi Outlook sau OWA), utilizați următoarea comandă în EXO Shell:</span><span class="sxs-lookup"><span data-stu-id="abe56-103">To hide a Microsoft 365 group from address lists (GAL) of Exchange clients (such as Outlook or OWA), use the following command in EXO shell:</span></span>

`Set-UnifiedGroup -Identity GroupName -HiddenFromAddressListsEnabled:$true`

<span data-ttu-id="abe56-104">Pentru a ascunde grupul Microsoft 365 ca fiind vizibil pentru clienții Exchange, utilizați următoarea comandă în EXO Shell:</span><span class="sxs-lookup"><span data-stu-id="abe56-104">To hide the Microsoft 365 group from being visible to Exchange clients, use the following command in EXO shell:</span></span>

`Set-unifiedGroup -Identity GroupName -HiddenFromExchangeClientsEnabled:$true
Check this article for detailed instructions`

