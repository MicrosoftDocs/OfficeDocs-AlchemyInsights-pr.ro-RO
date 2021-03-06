---
title: Problemă cu grupurile de securitate
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/09/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "8252"
- "9004397"
ms.openlocfilehash: 1198b79c3301bd2752a7385a6ba6746c8f0c2b5b
ms.sourcegitcommit: 22eaf0a151ab95414476f596db8d318b6540ff31
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 02/09/2021
ms.locfileid: "50177630"
---
# <a name="issue-with-security-groups"></a>Problemă cu grupurile de securitate

**Dacă primiți o eroare de rețea AADDS104**

Regulile de grup de securitate din rețea nevalide sunt cauza cea mai frecventă a erorilor de rețea pentru serviciile de domeniu Azure Active Directory (AD DS). Grupul securitate rețea pentru rețeaua virtuală trebuie să permită accesul la anumite porturi și protocoale. Dacă aceste porturi sunt blocate, platforma Azure nu poate monitoriza sau actualiza domeniul gestionat. Sincronizarea dintre Azure AD și Azure AD DS este, de asemenea, afectată. Asigurați-vă că ați păstrat porturile implicite deschise pentru a evita întreruperea serviciului.

Pentru a înțelege și a rezolva avertizări comune pentru problemele de configurare a grupurilor de securitate în rețea, consultați [adăugarea și verificarea grupurilor de securitate](https://docs.microsoft.com/azure/active-directory-domain-services/alert-nsg#verify-and-edit-existing-security-rules).
