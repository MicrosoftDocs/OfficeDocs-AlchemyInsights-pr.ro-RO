---
title: Identifica Ştergere mesaj evenimente în jurnalele de auditare
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1370
ms.assetid: ''
ms.openlocfilehash: 93f8a192af6e689e2b2d04013f35b8da2b69e607
ms.sourcegitcommit: ffe2f489b1ac3aae62aa784c959da6a41c3261eb
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 04/17/2019
ms.locfileid: "31909481"
---
# <a name="audit-logs-for-deleted-email-messages"></a>Jurnalele de auditare pentru mesaje e-mail şterse

Începând din ianuarie 2019, Microsoft este de cotitură pe cutie poştală de audit logare în mod implicit. În caz contrar, pentru a revizui Ştergere mesaj evenimente pentru un anumit utilizator, trebuie să activaţi manual delete acţiunile de auditare. În cazul în care cutia poştală de audit logare deja este activată pentru organizaţie sau de utilizator specifice, urmaţi paşii de mai jos.

1. Conectaţi-vă la [Centrul de conformitatea Office 365 securitate &](https://protection.office.com/)

2. Faceţi clic pe **Căutare şi ancheta** şi selectaţi **Căutare de jurnalul de Audit**.

3. Selectaţi intervalul de date în câmpurile **data de început** şi **data de sfârşit** . Specificaţi numele de utilizator pentru utilizator pe care doriţi să investigheze (utilizatorul care elemente şterse). În câmpul de **activităţi** , selectaţi **mesajele şterse din folderul Elemente şterse** şi **mesaje de mutat în folderul Elemente şterse**.

4. Faceţi clic pe **Căutare**.

În rezultate, selectaţi o înregistrare de audit. În fișă de detalii, faceţi clic pe **Mai multe informaţii**. Informaţii suplimentare despre element şters (de exemplu, subiectul şi locaţia elementului atunci când a fost sters) este afişat în câmpul **AffectedItems** . Proprietatea **ClientInfoString** va arăta dacă ştergerea a avut loc în Outlook, Outlook web (cunoscut anterior ca Outlook Web App), sau orice alt dispozitiv.

Pentru informaţii suplimentare, consultaţi [determină care configurarea e-mail forwarding pentru o cutie poştală](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-deleted-email-items).

**Notă**: Imposibil de regăsit elementele şterse utilizând caracteristica de jurnalul de audit. Pentru a prelua mesajele şterse în Outlook pe web, a se vedea [a nota a şterge elemente din Outlook Web App](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).