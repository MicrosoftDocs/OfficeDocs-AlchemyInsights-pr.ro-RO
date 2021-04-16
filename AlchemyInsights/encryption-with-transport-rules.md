---
title: Criptarea cu regulile de transport
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
- "9002635"
- "5154"
ms.openlocfilehash: dfd77bc83b4b278e3630858f54fdfb109ade2a14
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: ro-RO
ms.lasthandoff: 04/15/2021
ms.locfileid: "51813880"
---
# <a name="encryption-with-transport-rules"></a>Criptarea cu regulile de transport

În [Centrul de administrare Exchange](https://go.microsoft.com/fwlink/p/?linkid=834822) (EAC) puteți utiliza capacitățile Office Message Encryption (OME) în regulile de flux de corespondență pentru a declanșa criptarea mesajelor. Alegeți opțiunea **Aplicați Office 365 Message Encryption și protejarea drepturilor** din condiția Regulă de transport.

- Pentru mai multe informații, consultați [Definirea regulii de flux de corespondență pentru criptare](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email).

- În PowerShell, utilizați cmdletul [New-TransportRule](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email?view=o365-worldwide#use-exchange-online-powershell-to-create-a-mail-flow-rule-for-encrypting-email-messages-without-the-new-ome-capabilities) și setați parametrul *ApplyOME* la $true.
