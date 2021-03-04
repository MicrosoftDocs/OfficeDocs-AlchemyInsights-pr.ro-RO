---
title: Implementare GPO
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 02/24/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004400"
- "8602"
ms.openlocfilehash: d31f77e70e8456a4076a8146025f1f8ada977a06
ms.sourcegitcommit: 969219d6dff18d86d679d4d8741d1e39e4ce9539
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 03/03/2021
ms.locfileid: "50427562"
---
# <a name="gpo-deployment"></a><span data-ttu-id="fa2b5-102">Implementare GPO</span><span class="sxs-lookup"><span data-stu-id="fa2b5-102">GPO Deployment</span></span>

<span data-ttu-id="fa2b5-103">Setările pentru obiectele utilizator și computer din Azure Active Directory Domain Services (Azure AD DS) sunt deseori gestionate utilizând obiecte politică de grup (GPO).</span><span class="sxs-lookup"><span data-stu-id="fa2b5-103">Settings for user and computer objects in Azure Active Directory Domain Services (Azure AD DS) are often managed using Group Policy Objects (GPOs).</span></span> <span data-ttu-id="fa2b5-104">Azure AD DS include GPO-ul încorporat pentru AADDC utilizatori și containere pentru computere AADDC.</span><span class="sxs-lookup"><span data-stu-id="fa2b5-104">Azure AD DS includes built-in GPOs for the AADDC Users and AADDC Computers containers.</span></span> <span data-ttu-id="fa2b5-105">Puteți să particularizați aceste GPO-ul încorporat pentru a configura politica de grup, după cum este necesar pentru mediul dvs.</span><span class="sxs-lookup"><span data-stu-id="fa2b5-105">You can customize these built-in GPOs to configure group policy as needed for your environment.</span></span> <span data-ttu-id="fa2b5-106">Membrii grupului Azure AD DC administratorii au privilegii de administrare a politicilor de grup în domeniul Azure AD DS și pot crea, de asemenea, GPO-ul particularizat și unitățile organizaționale (ou).</span><span class="sxs-lookup"><span data-stu-id="fa2b5-106">Members of the Azure AD DC administrators group have group policy administration privileges in the Azure AD DS domain, and can also create custom GPOs and organizational units (OUs).</span></span> <span data-ttu-id="fa2b5-107">Pentru mai multe informații despre politica de grup și cum funcționează, consultați [prezentarea generală a politicii de grup](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/hh831791(v=ws.11)).</span><span class="sxs-lookup"><span data-stu-id="fa2b5-107">For more information on what group policy is and how it works, see [Group Policy Overview](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/hh831791(v=ws.11)).</span></span>

<span data-ttu-id="fa2b5-108">Într-un mediu hibrid, politicile de grup configurate într-un mediu AD DS local nu sunt sincronizate cu Azure AD DS.</span><span class="sxs-lookup"><span data-stu-id="fa2b5-108">In a hybrid environment, group policies configured in an on-premises AD DS environment aren't synchronized to Azure AD DS.</span></span> <span data-ttu-id="fa2b5-109">Pentru a defini setările de configurare pentru utilizatori sau computere în Azure AD DS, editați unul dintre GPO-ul implicit sau creați un GPO particularizat.</span><span class="sxs-lookup"><span data-stu-id="fa2b5-109">To define configuration settings for users or computers in Azure AD DS, edit one of the default GPOs or create a custom GPO.</span></span>

<span data-ttu-id="fa2b5-110">Acest articol [gestionarea politicii de grup](https://docs.microsoft.com/azure/active-directory-domain-services/manage-group-policy) vă arată cum să instalați instrumentele de gestionare a politicilor de grup, cum să editați tona în GPO-ul încorporat și cum să creați GPO particularizat.</span><span class="sxs-lookup"><span data-stu-id="fa2b5-110">This article [Manage Group Policy](https://docs.microsoft.com/azure/active-directory-domain-services/manage-group-policy) shows you how to install the Group Policy Management tools, how ton edit the built-in GPOs, and how to create custom GPOs.</span></span>
