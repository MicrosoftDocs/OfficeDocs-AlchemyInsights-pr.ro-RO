---
title: Creați un mesaj de e-mail pentru a vă prinde tot
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001524"
- "3732"
ms.openlocfilehash: 2b9131a620139a93ddb844fd49d8fa2ed68e52c2
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 04/15/2021
ms.locfileid: "51816212"
---
# <a name="create-an-email-catch-all"></a><span data-ttu-id="26a34-102">Creați un mesaj de e-mail pentru a vă prinde tot</span><span class="sxs-lookup"><span data-stu-id="26a34-102">Create an email catch all</span></span>

<span data-ttu-id="26a34-103">Utilizarea unei capturi este foarte puternică.</span><span class="sxs-lookup"><span data-stu-id="26a34-103">Use of a catch all is strongly discouraged.</span></span> <span data-ttu-id="26a34-104">Este mai bine să furnizați expeditorului o returnată, prin care expeditorii să știe că mesajul lor nu poate fi livrat ca adresat, astfel încât să poată lua măsuri.</span><span class="sxs-lookup"><span data-stu-id="26a34-104">It is better to provide a bounce back to the sender letting senders know their message could not be delivered as addressed so they can take action.</span></span> <span data-ttu-id="26a34-105">De asemenea, puteți limita cutia poștală monitorizată pentru a captura doar adresele de e-mail valide anterior.</span><span class="sxs-lookup"><span data-stu-id="26a34-105">You can also limit the monitored mailbox to only catch formerly valid email addresses.</span></span> 

<span data-ttu-id="26a34-106">Orice cutie poștală de tip catch will receive a good deal of spam (Spam) și poate completa în cele din urmă dacă nu este monitorizată îndeaproape.</span><span class="sxs-lookup"><span data-stu-id="26a34-106">Any catch all mailbox will receive a good deal of spam and may eventually fill if not closely monitored.</span></span> <span data-ttu-id="26a34-107">(Există limite pentru primirea de date.)</span><span class="sxs-lookup"><span data-stu-id="26a34-107">(There are receiving limits.)</span></span> 

<span data-ttu-id="26a34-108">Dacă decideți să continuați, urmați acești pași:</span><span class="sxs-lookup"><span data-stu-id="26a34-108">If you decide to proceed, follow these steps:</span></span>

1. <span data-ttu-id="26a34-109">Crearea unui grup de distribuire dinamic include & "Toate tipurile de destinatari".</span><span class="sxs-lookup"><span data-stu-id="26a34-109">Create a Dynamic Distribution Group & include "All Recipient Types."</span></span>

2. <span data-ttu-id="26a34-110">Creați o cutie poștală dedicată pentru a vă prinde mesajele de e-mail, de exemplu, catchall@domain.com.</span><span class="sxs-lookup"><span data-stu-id="26a34-110">Create a dedicated Mailbox to catch emails, for example, catchall@domain.com.</span></span>

3. <span data-ttu-id="26a34-111">Pentru domeniul specific, setați DomainType la "InternalRelay".</span><span class="sxs-lookup"><span data-stu-id="26a34-111">For the specific domain, set the DomainType to “InternalRelay”.</span></span> <span data-ttu-id="26a34-112">Dacă mai târziu eliminați toate capturile, asigurați-vă că setați domeniul înapoi la Autoritate.</span><span class="sxs-lookup"><span data-stu-id="26a34-112">If you later remove the catch all, be sure to set the domain back to Authoritative.</span></span>

4. <span data-ttu-id="26a34-113">Creați o regulă de transport de flux de corespondență după cum urmează:</span><span class="sxs-lookup"><span data-stu-id="26a34-113">Create a Mailflow Transport Rule as follows:</span></span>

    - <span data-ttu-id="26a34-114">Dacă expeditorul este "în afara organizației"</span><span class="sxs-lookup"><span data-stu-id="26a34-114">If the Sender is "Outside the Organization"</span></span>
    - <span data-ttu-id="26a34-115">Redirijați mesajul către Catchall@domain.com</span><span class="sxs-lookup"><span data-stu-id="26a34-115">Redirect the message to Catchall@domain.com</span></span>
    - <span data-ttu-id="26a34-116">Cu excepția cazului în care destinatarul este membru allusers@domain.com (Grupul de distribuire conține toți membrii)</span><span class="sxs-lookup"><span data-stu-id="26a34-116">Except if the recipient is a member of allusers@domain.com (Distribution Group contains all members)</span></span>
    - <span data-ttu-id="26a34-117">Asigurați-vă că validați faptul că noile cutii poștale sunt adăugate la grupul de distribuire dinamic</span><span class="sxs-lookup"><span data-stu-id="26a34-117">Ensure to validate that new mailboxes are added into the Dynamic Distribution Group</span></span>
