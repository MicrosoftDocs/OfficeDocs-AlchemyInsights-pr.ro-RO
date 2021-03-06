---
title: Monitorizarea accesului condiționat
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "9003769"
- "6702"
ms.openlocfilehash: c3bf5dd9066685af2df7ba50f0eb3ba6e891c2a9
ms.sourcegitcommit: 0eb4f9bde53395b5fd4b5cd4ffc56ca96db91298
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 03/10/2021
ms.locfileid: "50708686"
---
# <a name="monitoring-conditional-access-for-exchange"></a>Monitorizarea accesului condiționat pentru Exchange

Utilizatorii vizați de Access condițional vor primi un e-mail de notificare dacă nu îndeplinesc cerințele de acces ale organizației dvs. Pentru a rezolva, vă recomandăm una sau mai multe dintre următoarele soluții:

- Dacă se presupune că dispozitivul este înscris, consiliați utilizatorul să meargă la aplicația portal a firmei și să verifice dacă apare în portalul firmei. Dacă nu, utilizatorul trebuie să înscrie dispozitivul.
- În portalul Azure, accesați Intune > conformitatea dispozitivelor. Sub monitor, faceți clic pe conformitate dispozitiv. Vizualizați raportul de conformitate al dispozitivului pentru a verifica dacă dispozitivul utilizatorului este marcat ca fiind conform.
- În portalul Azure, accesați Intune > conformitatea dispozitivelor. Sub gestionare, faceți clic pe politici. În lista de politici de conformitate, Verificați dacă un profil este atribuit dispozitivului utilizatorului. Dacă nu este atribuit niciun profil, atunci Intune nu va putea confirma starea de conformitate a dispozitivului.
- Editați atribuirea accesului condiționat al utilizatorului.

1. În portalul Azure, accesați Politica de   >  **acces condițională** Intune  >  .
2. Selectați o politică din listă.
3. Faceți clic pe utilizatori și grupuri.
4. Pentru a viza o anumită politică la o persoană, adăugați-o la lista includere. Pentru a vă asigura că o persoană este omisă din politică, adăugați-o la lista de excluderi.

Linkuri utile:

[Prezentare generală a conformității dispozitivelor](https://docs.microsoft.com/intune/device-compliance-get-started)

[Depanarea CA](https://docs.microsoft.com/intune/troubleshoot-conditional-access)

[Politica de depanare](https://docs.microsoft.com/troubleshoot/mem/intune/troubleshoot-policies-in-microsoft-intune)

[Monitorizarea conformității dispozitivelor Intune](https://docs.microsoft.com/intune/compliance-policy-monitor)

Notă: acești pași sunt utili doar în depanarea caracteristicii Azure Active Directory Access condiționale. De asemenea, este posibil să plasați în carantină un dispozitiv care blochează accesul la e-mail cu politica Exchange. Mai multe informații despre gestionarea dispozitivelor Exchange pot fi găsite [aici] ( https://docs.microsoft.com/previous-versions/office/exchange-server-2010/ff959225(v=exchg.141) .
