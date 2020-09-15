---
title: Regulile firmei Dynamics 365 Forms-reguli pentru firme nu se lansează pentru un formular
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1926"
- "6200018"
ms.openlocfilehash: 7422b67973f93ce10c1639209cc50206a1016c10
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 09/14/2020
ms.locfileid: "47711503"
---
# <a name="onchange-event-does-not-occur-if-the-field-is-changed-programmatically"></a>Evenimentul OnChange nu se produce dacă acest câmp este modificat prin programare

Evenimentul *onChange* nu se produce dacă acest câmp este modificat prin programare utilizând *atributul.* metoda [SetareValoare](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) . Dacă doriți rutine de tratare a evenimentului pentru ca evenimentul *onChange* să ruleze după ce setați valoarea, trebuie să utilizați metoda [FireOnchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) *atributului formContext. data. entității* în cod.

[https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange)
