---
title: A apărut o eroare la validarea erorii tokenului de acces în timpul în care s-a făcut accesul la Desktop Analytics
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
- "2536"
- "9000657"
ms.openlocfilehash: 12e5906ba8cbc76ba1fd99dde1cf76396c3a6942
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 04/15/2021
ms.locfileid: "51813700"
---
# <a name="there-was-an-error-validating-access-token-error-during-desktop-analytics-onboarding"></a><span data-ttu-id="a6524-102">Eroarea "A apărut o eroare la validarea tokenului de acces" în timpul însamblarii Analizei desktop</span><span class="sxs-lookup"><span data-stu-id="a6524-102">"There was an error validating access token" error during Desktop Analytics onboarding</span></span>

<span data-ttu-id="a6524-103">Această eroare se observă în mod normal atunci când tokenul de autentificare expiră.</span><span class="sxs-lookup"><span data-stu-id="a6524-103">This error is normally observed when the authentication token expires.</span></span> <span data-ttu-id="a6524-104">De obicei, reîmprospătarea paginii reîmprospătează tokenul.</span><span class="sxs-lookup"><span data-stu-id="a6524-104">Usually, refreshing the page refreshes the token.</span></span> <span data-ttu-id="a6524-105">Cu toate acestea, această problemă poate persista dacă există politici de acces condiționat aplicate la contul utilizat la analiza desktop de la nivel de utilizator.</span><span class="sxs-lookup"><span data-stu-id="a6524-105">However, this issue can persist if there are any Conditional Access policies applied to the account being used to on-board Desktop Analytics.</span></span> <span data-ttu-id="a6524-106">Puteți revizui jurnalele de conectare Azure AD în portalul Azure pentru a vedea dacă există erori de conectare pentru contul utilizat pentru desktop Analytics de înscriere.</span><span class="sxs-lookup"><span data-stu-id="a6524-106">You can review the Azure AD Sign In logs in the Azure Portal to see if there are any sign-in failures for the account being used for Desktop Analytics onboarding.</span></span>

<span data-ttu-id="a6524-107">Pentru mai multe informații despre accesul condiționat, vizitați [Planificarea implementării accesului condiționat.](https://docs.microsoft.com/azure/active-directory/conditional-access/plan-conditional-access)</span><span class="sxs-lookup"><span data-stu-id="a6524-107">For more information about Conditional Access, visit [Plan your Conditional Access deployment](https://docs.microsoft.com/azure/active-directory/conditional-access/plan-conditional-access).</span></span>