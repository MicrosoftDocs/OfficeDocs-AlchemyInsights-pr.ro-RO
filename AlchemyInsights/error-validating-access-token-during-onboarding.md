---
title: A apărut o eroare la validarea erorii tokenului de acces în timpul în care s-a făcut accesul la Desktop Analytics
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2536"
- "9000657"
ms.openlocfilehash: 12e5906ba8cbc76ba1fd99dde1cf76396c3a6942
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 04/15/2021
ms.locfileid: "51813700"
---
# <a name="there-was-an-error-validating-access-token-error-during-desktop-analytics-onboarding"></a>Eroarea "A apărut o eroare la validarea tokenului de acces" în timpul însamblarii Analizei desktop

Această eroare se observă în mod normal atunci când tokenul de autentificare expiră. De obicei, reîmprospătarea paginii reîmprospătează tokenul. Cu toate acestea, această problemă poate persista dacă există politici de acces condiționat aplicate la contul utilizat la analiza desktop de la nivel de utilizator. Puteți revizui jurnalele de conectare Azure AD în portalul Azure pentru a vedea dacă există erori de conectare pentru contul utilizat pentru desktop Analytics de înscriere.

Pentru mai multe informații despre accesul condiționat, vizitați [Planificarea implementării accesului condiționat.](https://docs.microsoft.com/azure/active-directory/conditional-access/plan-conditional-access)