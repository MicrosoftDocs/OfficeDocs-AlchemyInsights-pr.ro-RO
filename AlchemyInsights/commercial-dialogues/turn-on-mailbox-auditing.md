---
title: Activarea auditării cutiei poștale
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 02/26/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3100005"
- "7327"
ms.openlocfilehash: aa0ff925ae891d28e31394ec66eb17c2d9710008
ms.sourcegitcommit: 251e2e82571fb3bb1fbe3dbf7bfca30e004b3373
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 03/05/2021
ms.locfileid: "50483541"
---
# <a name="turn-on-mailbox-auditing"></a>Activarea auditării cutiei poștale

Pentru a activa auditarea cutiei poștale pentru un singur utilizator sau pentru o întreagă organizație, derulează următoarele cmdleturi de la Remote PowerShell:

- **Utilizator unic**: Set-Mailbox-identitatea "Jane Dow"-AuditEnabled $True
- **Organizație**: Get-Mailbox-ResultSize Nelimitat-Filter {RecipientTypeDetails-EQ "UserMailbox"} | Set-Mailbox-AuditEnabled $true

Pentru a afla mai multe, consultați [gestionarea auditării cutiei poștale](https://go.microsoft.com/fwlink/?linkid=2103668).