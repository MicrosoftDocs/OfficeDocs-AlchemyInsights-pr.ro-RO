---
title: Folder public trimitere ca E-mail activat în EXO
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1956"
- "3500007"
ms.openlocfilehash: ed62c6d7db0ae532f806ce4fdc48f42623bcd545
ms.sourcegitcommit: 1fb324fd156008e77b7e2008af4b3dc1c0d0ea3e
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 10/13/2020
ms.locfileid: "48461967"
---
# <a name="sendas-mail-enabled-public-folder"></a>Folder public SendAs mail activat

Următorul exemplu atribuie permisiuni "trimitere ca" pentru folderul public cu e-mail activat NewPF1 pentru utilizatorul Jason.

Add-RecipientPermission-Identity ' NewPF1 '-mandatar "Jason"-AccessRights ' SendAs '

Pentru informații detaliate despre sintaxă și parametri, consultați [atribuirea permisiunilor "trimitere ca" sau "trimitere în numele" pentru folderele publice activate pentru e-mail](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/assign-permissions-mail-enabled-pfs).

