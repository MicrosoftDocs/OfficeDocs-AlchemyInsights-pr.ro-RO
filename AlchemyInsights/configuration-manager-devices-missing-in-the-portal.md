---
title: Dispozitivele Manager de configurare lipsesc din portal
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001495"
- "4384"
ms.openlocfilehash: 7a11ad3c6970be2c52a7cf0696bd3810b9bd665a
ms.sourcegitcommit: 89ae9e8b36d1980f89f07b016fff0ec48f96b620
ms.translationtype: HT
ms.contentlocale: ro-RO
ms.lasthandoff: 04/23/2020
ms.locfileid: "43790229"
---
# <a name="configuration-manager-devices-missing-in-the-portal"></a><span data-ttu-id="572c1-102">Dispozitivele Manager de configurare lipsesc din portal</span><span class="sxs-lookup"><span data-stu-id="572c1-102">Configuration Manager devices missing in the portal</span></span>

<span data-ttu-id="572c1-103">Pentru ca sincronizarea dispozitivelor să funcționeze, [Parametri necesare de internet](https://docs.microsoft.com/configmgr/tenant-attach/device-sync-actions#internet-endpoints) trebuie să fie accesibile de pe serverul local care găzduiește rolul de Punct de conexiune la serviciu.</span><span class="sxs-lookup"><span data-stu-id="572c1-103">For device sync to work, [required internet endpoints](https://docs.microsoft.com/configmgr/tenant-attach/device-sync-actions#internet-endpoints) must be reachable from the on-premise server hosting the Service Connection Point role.</span></span> <span data-ttu-id="572c1-104">Pentru a depana sincronizarea dispozitivelor, revizuiți**CMGatewaySyncUploadWorker.log** din punctul de conexiune la serviciu.</span><span class="sxs-lookup"><span data-stu-id="572c1-104">To troubleshoot device sync, please review the **CMGatewaySyncUploadWorker.log** located on the service connection point.</span></span>

<span data-ttu-id="572c1-105">Aflați mai multe despre [Entitatea găzduită atașată în Microsoft Endpoint Manager](https://docs.microsoft.com/configmgr/tenant-attach/).</span><span class="sxs-lookup"><span data-stu-id="572c1-105">Learn more about [Tenant attach in Microsoft Endpoint Manager](https://docs.microsoft.com/configmgr/tenant-attach/).</span></span>
