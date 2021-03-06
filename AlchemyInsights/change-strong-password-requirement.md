---
title: Modificați cerința puternică de parolă
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
- "9000105"
- "1600"
ms.openlocfilehash: cf5cab9a1c2dd4226997d93417dc7104347f8a6e
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 04/15/2021
ms.locfileid: "51818480"
---
# <a name="change-strong-password-requirement"></a>Modificați cerința puternică de parolă

Microsoft necesită parole puternice în mod implicit.

Cu ajutorul PowerShell, puteți dezactiva parole puternice pentru utilizatori cu aceste comenzi:

`Set-MsolUser –UserPrincipalName <UserPrincipalName> –StrongPasswordRequired  $false`

Pentru a dezactiva parolele puternice pentru toți utilizatorii, utilizați:

`Get-MsolUser | Set-MsolUser -StrongPasswordRequired $false`

- [Mai multe informații despre politica pentru parole](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [Conectarea la Microsoft 365 cu PowerShell](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [Mai multe informații despre comenzile MsolUser PowerShell](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)
