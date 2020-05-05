---
title: Activarea auditării cutiilor poștale
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: ae11d6be0789a5662d202b85268480a3d42922c4
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 04/22/2020
ms.locfileid: "43703583"
---
# <a name="enable-mailbox-auditing"></a>Activarea auditării cutiilor poștale

Pentru a activa Mailbox Auditing pentru un singur utilizator sau o întreagă organizație, următoarele cmdlet-uri trebuie executate din Remote Power Shell:
  
 **Utilizator unic**
  
Set-Mailbox -Identitate "Jane Dow" -AuditEnabled $true
  
 **Organizaţie**
  
Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true
  
[Aflați mai multe](https://docs.microsoft.com/office365/securitycompliance/enable-mailbox-auditing)
  

