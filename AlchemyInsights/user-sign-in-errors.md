---
title: Erori de conectare la utilizator
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 01/16/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "7790"
- "9004355"
ms.openlocfilehash: 05bd31cb4afecf1342e040eecd9e58cd38bd8d49
ms.sourcegitcommit: 6d02eb533fd74199af6b20f714b3720991da2c4a
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 01/18/2021
ms.locfileid: "49901256"
---
# <a name="user-sign-in-errors"></a><span data-ttu-id="b5c3d-102">Erori de conectare la utilizator</span><span class="sxs-lookup"><span data-stu-id="b5c3d-102">User sign-in errors</span></span>

<span data-ttu-id="b5c3d-103">**Rezolvarea problemelor cu diagnosticul de conectare**</span><span class="sxs-lookup"><span data-stu-id="b5c3d-103">**Resolve problems with the Sign-in Diagnostic**</span></span>

<span data-ttu-id="b5c3d-104">Pentru a detecta cauzele sau diagnosticarea problemelor legate de conectarea la utilizator, efectuați pașii următori:</span><span class="sxs-lookup"><span data-stu-id="b5c3d-104">To detect the cause or diagnose problems related to user sign-in, perform the following steps:</span></span>

1. <span data-ttu-id="b5c3d-105">Lansați [diagnosticul de conectare](https://ms.portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/diagnose/symptomId/ms_aad_dxp_signin_caDiagnoseAndSolveSummarySymptom).</span><span class="sxs-lookup"><span data-stu-id="b5c3d-105">Launch the [Sign-in Diagnostic](https://ms.portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/diagnose/symptomId/ms_aad_dxp_signin_caDiagnoseAndSolveSummarySymptom).</span></span>
2. <span data-ttu-id="b5c3d-106">Găsiți evenimentul de analizat introducând detaliile pe care le aveți despre utilizator, aplicație, ora conectării, ID-ul de solicitare sau ID-ul de corelare.</span><span class="sxs-lookup"><span data-stu-id="b5c3d-106">Find the event to analyze by entering the details you have about the user, application, time of sign in, request Id, or correlation Id.</span></span>
3. <span data-ttu-id="b5c3d-107">Revizuiți rezultatele de diagnosticare care afișează detaliile despre ce s-a întâmplat și ce acțiuni puteți efectua pentru a face modificări, dacă sunt necesare modificări.</span><span class="sxs-lookup"><span data-stu-id="b5c3d-107">Review the diagnostic results showing the details of what happened and what actions you can take to make changes, if any changes are needed.</span></span>

<span data-ttu-id="b5c3d-108">**Căutați informații despre codurile de eroare AADSTS care sunt returnate din serviciul token de securitate Azure Active Directory (Azure AD)?**</span><span class="sxs-lookup"><span data-stu-id="b5c3d-108">**Looking for information about the AADSTS error codes that are returned from the Azure Active Directory (Azure AD) security token service (STS)?**</span></span> <span data-ttu-id="b5c3d-109">Citiți [acest articol](https://docs.microsoft.com/azure/active-directory/develop/reference-aadsts-error-codes) pentru a găsi descrieri de erori AADSTS, remedieri și câteva soluții sugerate</span><span class="sxs-lookup"><span data-stu-id="b5c3d-109">Read [this article](https://docs.microsoft.com/azure/active-directory/develop/reference-aadsts-error-codes) to find AADSTS error descriptions, fixes, and some suggested workarounds</span></span>