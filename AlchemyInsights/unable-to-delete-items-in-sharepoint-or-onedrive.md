---
title: Imposibil de șters elemente în SharePoint sau OneDrive
ms.author: pebaum
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1851"
- "2377"
- "9000255"
ms.assetid: ''
ms.openlocfilehash: 3cc168846999c6880b95edfaedb2df8cf6e843a6
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 10/18/2019
ms.locfileid: "36748588"
---
# <a name="unable-to-delete-items"></a>Imposibil de șters elemente

Probleme la ștergerea elementelor SharePoint?

- Asigurați-vă întotdeauna că aveți [permisiunile corespunzătoare](https://docs.microsoft.com/sharepoint/default-sharepoint-groups) pentru a șterge elementul sau aveți un [administrator de colecție de site-ul](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) încearcă să eliminați elementul.

- Asigurați-vă că nu există o setare de [politică de retenție](https://docs.microsoft.com/office365/securitycompliance/retention-policies) pe element.

- Asigurați-vă că elementul nu este [verificat](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) la un alt utilizator.

- În cele din urmă, administratorii pot utiliza [modele și practici SharePoint](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PNP) care conține o bibliotecă de comenzi PowerShell care vă permit să efectuați acțiuni complexe de gestionare, ar fi forța ștergerea elemente încăpățânate.
- [Eliminare fișier PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [Eliminare folder PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [Eliminare element listă PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [Eliminare listă PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [Eliminare câmp PNP (coloană)](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)