---
title: 2419-imposibil de-la-enable-audit
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 2419
ms.assetid: ''
ms.openlocfilehash: 3af01c03711eed646f0009afb5bea685bc358196
ms.sourcegitcommit: 87153fec6f6468b57893abf4aac073ba4068e67b
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 06/19/2019
ms.locfileid: "35065689"
---
# <a name="unable-to-enable-unified-auditing"></a><span data-ttu-id="def29-102">Imposibilitatea de a permite unificate de audit</span><span class="sxs-lookup"><span data-stu-id="def29-102">Unable to enable unified auditing</span></span>

<span data-ttu-id="def29-103">Atunci când încercaţi să activaţi auditarea unificat pentru organizaţia Office 365, poate apărea o eroare similar cu următorul text:</span><span class="sxs-lookup"><span data-stu-id="def29-103">When you try to enable unified auditing for your Office 365 organization, you may receive an error similar the following:</span></span>

```
Request: /api/adminauditlogconfig/EnableUnifiedAuditLogIngestion Status code: 500 Exception message: {"Message":"The command you tried to run isn't currently allowed in your organization. To run this command, you first need to run the command: Enable-OrganizationCustomization."
```

<span data-ttu-id="def29-104">Pentru a rezolva această problemă, urmaţi aceşti paşi:</span><span class="sxs-lookup"><span data-stu-id="def29-104">To resolve this issue, follow these steps:</span></span>

1. <span data-ttu-id="def29-105">[Connect pentru a face schimb de Online Powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell).</span><span class="sxs-lookup"><span data-stu-id="def29-105">[Connect to Exchange Online Powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell).</span></span>

2. <span data-ttu-id="def29-106">Executaţi următoarele cmdlet-ului:</span><span class="sxs-lookup"><span data-stu-id="def29-106">Run the following cmdlet:</span></span>

   ```
   Enable-OrganizationCustomization
   ```

3. <span data-ttu-id="def29-107">Aşteptaţi pentru 60 de minute pentru setarea anterioară să aibă efect.</span><span class="sxs-lookup"><span data-stu-id="def29-107">Wait for 60 minutes for the previous setting to take effect.</span></span>

4. <span data-ttu-id="def29-108">Executaţi comanda următoare în Exchange Online PowerShell:</span><span class="sxs-lookup"><span data-stu-id="def29-108">Run the following command in Exchange Online PowerShell:</span></span>

   ```
   Set-AdminAuditLogConfig -UnifiedAuditLogIngestionEnabled $true
   ```

<span data-ttu-id="def29-109">Pentru informaţii suplimentare, consultaţi următoarele articole:</span><span class="sxs-lookup"><span data-stu-id="def29-109">For additional information, see the following articles:</span></span>

- [<span data-ttu-id="def29-110">Conecta la Exchange Online PowerShell utilizând autentificarea multi-factor</span><span class="sxs-lookup"><span data-stu-id="def29-110">Connect to Exchange Online PowerShell using multi-factor authentication</span></span>](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/mfa-connect-to-exchange-online-powershell)

-  [<span data-ttu-id="def29-111">Office 365 audit jurnal caută de activarea sau dezactivarea</span><span class="sxs-lookup"><span data-stu-id="def29-111">Turn Office 365 audit log search on or off</span></span>](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off)