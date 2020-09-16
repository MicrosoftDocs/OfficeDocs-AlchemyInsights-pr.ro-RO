---
title: Activarea auditării cutiei poștale
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 404ef9ecd824541f98471bb8797f5f6e025012b7
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 09/15/2020
ms.locfileid: "47806303"
---
# <a name="enable-mailbox-auditing"></a>Activarea auditării cutiei poștale

Pentru a activa auditarea cutiei poștale pentru un singur utilizator sau pentru o întreagă organizație, trebuie să ruleze următoarele cmdleturi de la Remote Power Shell:
  
 **Utilizator unic**
  
Set-cutia poștală-identitatea "Jane Dow"-AuditEnabled $true
  
 **Organizația**
  
Get-Mailbox-ResultSize Nelimitat-Filter {RecipientTypeDetails-EQ "UserMailbox"} | Set-Mailbox-AuditEnabled $true
  
[află mai multe](https://docs.microsoft.com/microsoft-365/compliance/enable-mailbox-auditing)
  

