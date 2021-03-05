---
title: Ziua de lucru pentru asigurarea accesului utilizatorilor AD intră în starea de carantină
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/19/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "8471"
- "9004687"
ms.openlocfilehash: 0fc519c8170de498c9bcb1fc41a76116bda48b1f
ms.sourcegitcommit: 379e132c4d21ecf703d5506484ec96a767fdda39
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 03/04/2021
ms.locfileid: "50482901"
---
# <a name="workday-to-ad-user-provisioning-goes-into-quarantine-state"></a><span data-ttu-id="b4103-102">Ziua de lucru pentru asigurarea accesului utilizatorilor AD intră în starea de carantină</span><span class="sxs-lookup"><span data-stu-id="b4103-102">Workday to AD User Provisioning goes into quarantine state</span></span>

<span data-ttu-id="b4103-103">**Ziua de lucru pentru asigurarea accesului utilizatorilor AD intră în starea de carantină și nu se creează niciun utilizator în AD**</span><span class="sxs-lookup"><span data-stu-id="b4103-103">**Workday to AD User Provisioning goes into quarantine state and no users are created in AD**</span></span>

<span data-ttu-id="b4103-104">Lucrarea de lucru pentru asigurarea accesului utilizatorilor de zile lucrătoare a intrat în starea de carantină și jurnalele de audit afișează evenimentele nereușite de export cu eroarea mesajului de eroare **: OperationsError-SvcErr: a apărut o eroare de operațiune. Nicio referință superioară nu a fost configurată pentru serviciul director. Prin urmare, serviciul director nu poate emite referințe la obiectele din afara acestei păduri**.</span><span class="sxs-lookup"><span data-stu-id="b4103-104">The Workday to AD User Provisioning job has gone into quarantine state and the audit logs show export failure events with the error message **Error: OperationsError-SvcErr: An operation error occurred. No superior reference has been configured for the directory service. The directory service is therefore unable to issue referrals to objects outside this forest**.</span></span> <span data-ttu-id="b4103-105">Această eroare apare de obicei dacă containerul Active Directory nu este setat corect sau dacă există probleme cu maparea de expresie utilizată pentru **parentDistinguishedName**.</span><span class="sxs-lookup"><span data-stu-id="b4103-105">This error usually shows up if the Active Directory Container OU is not set correctly or if there are issues with the Expression Mapping used for **parentDistinguishedName**.</span></span>

<span data-ttu-id="b4103-106">Verificați parametrul implicit OU pentru **utilizatori noi** pentru greșeli de ortografie.</span><span class="sxs-lookup"><span data-stu-id="b4103-106">Check the Default OU for **New Users** parameter for typos.</span></span> <span data-ttu-id="b4103-107">Asigurați-vă că există deja un OU specificat în reclama dvs.</span><span class="sxs-lookup"><span data-stu-id="b4103-107">Ensure that the specified OU already exists in your AD.</span></span> <span data-ttu-id="b4103-108">Dacă utilizați **parentDistinguishedName** în maparea atributului, asigurați-vă că acesta se evaluează întotdeauna la un container cunoscut din domeniul de publicitate.</span><span class="sxs-lookup"><span data-stu-id="b4103-108">If you are using **parentDistinguishedName** in the attribute mapping, ensure that it always evaluates to a known container within the AD domain.</span></span> <span data-ttu-id="b4103-109">Verificați evenimentul de export din jurnalele de audit pentru a vedea valoarea generată.</span><span class="sxs-lookup"><span data-stu-id="b4103-109">Check the Export event in the audit logs to see the generated value.</span></span>

<span data-ttu-id="b4103-110">Pentru mai multe detalii despre configurarea zilei de lucru pentru asigurarea accesului automat, consultați [Tutorial: Configurarea zilei de lucru pentru asigurarea accesului automat la utilizatori](https://docs.microsoft.com/azure/active-directory/saas-apps/workday-inbound-tutorial).</span><span class="sxs-lookup"><span data-stu-id="b4103-110">For more details on configuring workday for automated provisioning, see [Tutorial: Configure Workday for automatic user provisioning](https://docs.microsoft.com/azure/active-directory/saas-apps/workday-inbound-tutorial).</span></span>
