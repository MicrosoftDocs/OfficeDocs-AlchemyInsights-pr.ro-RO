---
title: Depanarea problemelor de import PST
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1800027"
- "1225"
ms.openlocfilehash: 5065b9895954371e4298c98e8aadb67ba8f140fd
ms.sourcegitcommit: c977687a7dd03288a9ba396cf2a48ea384d72634
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 04/27/2021
ms.locfileid: "52059827"
---
# <a name="troubleshooting-pst-import-issues"></a><span data-ttu-id="72200-102">Depanarea problemelor de import PST</span><span class="sxs-lookup"><span data-stu-id="72200-102">Troubleshooting PST import issues</span></span>

- <span data-ttu-id="72200-103">Dacă importați în cadrul clientului Outlook propriu-zis, consultați [Remedierea problemelor cu importul unui fișier .pst Outlook.](https://support.office.com/article/Fix-problems-importing-an-Outlook-pst-file-2d2e50dc-5c36-4ab2-ab50-f1be733b3d6e)</span><span class="sxs-lookup"><span data-stu-id="72200-103">If you are importing within the Outlook client itself, see [Fix problems importing an Outlook .pst file](https://support.office.com/article/Fix-problems-importing-an-Outlook-pst-file-2d2e50dc-5c36-4ab2-ab50-f1be733b3d6e).</span></span>

- <span data-ttu-id="72200-104">Dacă utilizați Serviciul de import și s-a blocat, rețineți că fiecare fișier PST pe care îl încărcați în locația de stocare Azure nu trebuie să aibă mai mult de 20 GB.</span><span class="sxs-lookup"><span data-stu-id="72200-104">If you are using Import Service and it's stuck, note that each PST file that you upload to the Azure Storage location should be no larger than 20GB.</span></span> <span data-ttu-id="72200-105">Fișierele PST mai mari de 20 GB pot afecta performanța procesului de import PST.</span><span class="sxs-lookup"><span data-stu-id="72200-105">PST files larger than 20GB may impact the performance of the PST import process.</span></span> <span data-ttu-id="72200-106">Pentru mai multe informații despre depanarea problemelor blocate, consultați [Probleme care afectează activitățile de import PST.](https://docs.microsoft.com/office365/troubleshoot/pst-import-service/issues-with-pst-import-job)</span><span class="sxs-lookup"><span data-stu-id="72200-106">For more information troubleshooting stuck jobs, see [Issues that affect PST import jobs](https://docs.microsoft.com/office365/troubleshoot/pst-import-service/issues-with-pst-import-job).</span></span>

- <span data-ttu-id="72200-107">Dacă doriți să verificați starea unei anumite lucrări de Import, utilizați [Get-MailboxImportRequest -batchname](https://docs.microsoft.com/powershell/module/exchange/mailboxes/get-mailboximportrequest).</span><span class="sxs-lookup"><span data-stu-id="72200-107">If you want to verify the status of a specific Import job, use [Get-MailboxImportRequest -batchname](https://docs.microsoft.com/powershell/module/exchange/mailboxes/get-mailboximportrequest).</span></span>

- <span data-ttu-id="72200-108">Pentru detalii complete despre serviciul de import, consultați [Prezentare generală a importului fișierelor PST ale organizației dvs.](https://docs.microsoft.com/microsoft-365/compliance/importing-pst-files-to-office-365?view=o365-worldwide)</span><span class="sxs-lookup"><span data-stu-id="72200-108">For full details on the import service, see [Overview of importing your organization's PST files](https://docs.microsoft.com/microsoft-365/compliance/importing-pst-files-to-office-365?view=o365-worldwide).</span></span>
