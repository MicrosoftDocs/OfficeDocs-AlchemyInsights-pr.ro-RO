---
title: Eroare AttributeValueMustBeUnique
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: bf8ac830-6f0c-4616-827d-987616700e59
ms.openlocfilehash: 7b98b68fabff6c048f1bab6cf506355114d18658
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 02/12/2019
ms.locfileid: "29916536"
---
# <a name="error-attributevaluemustbeunique"></a>Eroare: AttributeValueMustBeUnique

Cel mai frecvent motiv pentru erori de AttributeValueMustBeUnique este două obiecte cu diferite SourceAnchor (immutableId) au aceeaşi valoare pentru atributele ProxyAddresses şi/sau UserPrincipalName. Pentru a remedia eroarea AttributeValueMustBeUnique:
  
1. Identifica proxyAddresses duplicat, userPrincipalName sau altă valoare de atribut care provoacă eroarea. De asemenea, identifica care două (sau mai multe) obiecte sunt implicate în conflict. Raportul generat de sănătate Azure AD Connect pentru sincronizare vă pot ajuta să identifice două obiecte.
    
2. Identificarea obiectului care ar trebui să continue să aibă valoarea duplicat şi obiect care ar trebui să nu.
    
3. Elimina valoarea duplicat la obiect pe care ar trebui să aibă această valoare. Reţineţi că ar trebui să facă schimbare în directorul în care obiectul este provin din. În unele cazuri, trebuie să ştergeţi unul dintre obiectele în conflict.
    
4. În cazul în care aţi făcut schimbarea în incinta pe AD, să Azure AD conecta sincronizare schimbarea de eroare pentru a obţine stabilite.
    
