---
title: Folder public trimitere ca E-mail activat în EXO
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1956"
- "3500007"
ms.openlocfilehash: ed62c6d7db0ae532f806ce4fdc48f42623bcd545
ms.sourcegitcommit: 1fb324fd156008e77b7e2008af4b3dc1c0d0ea3e
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 10/13/2020
ms.locfileid: "48461967"
---
# <a name="sendas-mail-enabled-public-folder"></a><span data-ttu-id="61b1a-102">Folder public SendAs mail activat</span><span class="sxs-lookup"><span data-stu-id="61b1a-102">SendAs Mail Enabled Public Folder</span></span>

<span data-ttu-id="61b1a-103">Următorul exemplu atribuie permisiuni "trimitere ca" pentru folderul public cu e-mail activat NewPF1 pentru utilizatorul Jason.</span><span class="sxs-lookup"><span data-stu-id="61b1a-103">The following example assigns "Send As" permissions for the mail-enabled public folder NewPF1 to the user Jason.</span></span>

<span data-ttu-id="61b1a-104">Add-RecipientPermission-Identity ' NewPF1 '-mandatar "Jason"-AccessRights ' SendAs '</span><span class="sxs-lookup"><span data-stu-id="61b1a-104">Add-RecipientPermission -Identity 'NewPF1' -Trustee "Jason" -AccessRights 'SendAs'</span></span>

<span data-ttu-id="61b1a-105">Pentru informații detaliate despre sintaxă și parametri, consultați [atribuirea permisiunilor "trimitere ca" sau "trimitere în numele" pentru folderele publice activate pentru e-mail](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/assign-permissions-mail-enabled-pfs).</span><span class="sxs-lookup"><span data-stu-id="61b1a-105">For detailed syntax and parameter information see [Assign "Send As" or "Send on Behalf" permissions for mail-enabled public folders](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/assign-permissions-mail-enabled-pfs).</span></span>

