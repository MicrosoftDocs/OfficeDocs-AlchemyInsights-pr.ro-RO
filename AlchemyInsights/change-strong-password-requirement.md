---
title: Modificare cerință parolă puternică
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000105"
- "1600"
ms.openlocfilehash: 21f80a7cc8b00ac56acdb05add1e1bfdfac9d827
ms.sourcegitcommit: c061f1dfa6f557a9ec083dd030b73b121d9864ea
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 04/14/2020
ms.locfileid: "43286290"
---
# <a name="change-strong-password-requirement"></a><span data-ttu-id="d353e-102">Modificarea cerinței de parolă puternică</span><span class="sxs-lookup"><span data-stu-id="d353e-102">Change strong password requirement</span></span>

<span data-ttu-id="d353e-103">Microsoft necesită parole puternice în mod implicit.</span><span class="sxs-lookup"><span data-stu-id="d353e-103">Microsoft requires strong passwords by default.</span></span> 

<span data-ttu-id="d353e-104">Folosind PowerShell, poți dezactiva parolele puternice pentru anumiți utilizatori cu această comandă:</span><span class="sxs-lookup"><span data-stu-id="d353e-104">Using PowerShell, you can disable strong passwords for specific users with this command:</span></span><br>
<span data-ttu-id="d353e-105">*Set-MsolUser –UserPrincipalName <UserPrincipalName> –StrongPasswordRequired $false*</span><span class="sxs-lookup"><span data-stu-id="d353e-105">*Set-MsolUser –UserPrincipalName <UserPrincipalName> –StrongPasswordRequired  $false*</span></span>

- [<span data-ttu-id="d353e-106">Mai multe informații despre politica privind parolele</span><span class="sxs-lookup"><span data-stu-id="d353e-106">More information on password policy</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [<span data-ttu-id="d353e-107">să vă conectați la Office 365 cu PowerShell</span><span class="sxs-lookup"><span data-stu-id="d353e-107">How to connect to Office 365 with PowerShell</span></span>](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [<span data-ttu-id="d353e-108">Mai multe informații despre comenzile PowerShell MsolUser</span><span class="sxs-lookup"><span data-stu-id="d353e-108">More information on PowerShell MsolUser commands</span></span>](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)
- [<span data-ttu-id="d353e-109">Setarea parolei unui utilizator individual să nu expire niciodată</span><span class="sxs-lookup"><span data-stu-id="d353e-109">Set an individual user's password to never expire</span></span>](https://docs.microsoft.com/microsoft-365/admin/add-users/set-password-to-never-expire)
