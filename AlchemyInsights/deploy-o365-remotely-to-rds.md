---
title: Implementarea aplicațiilor Microsoft 365 pentru întreprinderi pentru utilizare partajată pe RDS, Terminal Server sau VDI
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: ''
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001419"
- "3411"
ms.openlocfilehash: a57be7fcf9d8236a51dc4b38e33ad1c2ac717f11
ms.sourcegitcommit: 2eab0980268e08a58014459d44a08a1cc34a17d4
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 03/25/2021
ms.locfileid: "51200685"
---
# <a name="deploying-microsoft-365-apps-for-enterprise-for-shared-use-on-rds-terminal-server-or-vdi"></a>Implementarea aplicațiilor Microsoft 365 pentru întreprinderi pentru utilizare partajată pe RDS, Terminal Server sau VDI

Pentru a implementa aplicații Microsoft 365 pentru întreprinderi utilizând Remote Desktop Services (RDS), denumit anterior Terminal Services:

- Trebuie să aveți un plan Microsoft 365 pentru firme sau un plan Office 365 care include aplicațiile Microsoft 365 pentru întreprinderi, cum ar fi Office 365 Enterprise E3 sau Enterprise E5.
   > [!NOTE]
   > Planurile Microsoft 365 pentru aplicații pentru firme și Microsoft 365 Business standard nu includ aplicații Microsoft 365 pentru întreprinderi.
- Trebuie să activați [Activarea pentru computere partajate](https://docs.microsoft.com/DeployOffice/overview-shared-computer-activation).

> [!NOTE]
> De asemenea, puteți să descărcați și să difuzați [Asistentul Microsoft pentru recuperare și asistență](https://aka.ms/SaRA_OfficeSCA_M365Portal) pentru a instala aplicații Microsoft 365 pentru întreprinderi în modul de activare a computerului partajat.

Pentru mai multe informații despre cerințe preliminare, instrucțiuni de configurare și instrucțiuni despre instalările particularizate, utilizând instrumentul de implementare Office, consultați [implementarea aplicațiilor Microsoft 365 pentru întreprinderi utilizând servicii Desktop la distanță](https://docs.microsoft.com/DeployOffice/deploy-microsoft-365-apps-remote-desktop-services).

Pentru a remedia erorile legate de activarea computerului partajat:

- Consultați [Depanarea problemelor cu activarea computerului partajat pentru aplicațiile Microsoft 365 pentru întreprinderi](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation).
- Consultați [Resetarea aplicațiilor Microsoft 365 pentru starea de activare pentru întreprinderi](https://go.microsoft.com/fwlink/?linkid=2109218).

Dacă doriți să instalați aplicații Microsoft 365 pentru Enterprise pe RDS din centrul de administrare Microsoft 365, ***care utilizează setările implicite de instalare***, utilizați pașii următori:

1. Verificați ce abonament aveți. [Aflați cum](https://docs.microsoft.com/microsoft-365/admin/admin-overview/what-subscription-do-i-have).
2. Dacă este necesar, comutați la un alt abonament. [Aflați cum](https://docs.microsoft.com/microsoft-365/commerce/subscriptions/switch-to-a-different-plan).
3. Dacă Office este deja instalat pe serverul RDS utilizând orice alte abonamente Microsoft, dezinstalați-l. De exemplu, accesând **panoul de control**  >  **Dezinstalați un program**. Dezinstalați utilizând [Asistentul de recuperare și asistență Microsoft](https://aka.ms/SARA-OfficeUninstall-Alchemy) dacă întâmpinați probleme.
4. Pe serverul RDS, conectați-vă la centrul de administrare Microsoft 365 cu contul de administrator și [Instalați aplicațiile Microsoft 365 pentru întreprinderi](https://portal.office.com/OLS/MySoftware.aspx).
5. După ce este instalat Office, ***nu deschideți sau nu vă conectați*** la nicio aplicație Office.
6. Pe serverul RDS, activați activarea computerului partajat editând registry urmând acești pași:
   1. Faceți clic dreapta pe butonul Windows din colțul din stânga jos al ecranului și selectați **rulare**. În caseta Deschidere, tastați **regedit**, apoi selectați **OK**.
   2. Selectați **Da** atunci când vi se solicită să permiteți Registry Editor să efectueze modificări pe dispozitivul dvs.
   3. În Registry Editor, adăugați o valoare șir de **SharedComputerLicensing** cu o setare de 1 sub HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.
   4. Pe serverul RDS, ***Conectați-vă ca utilizator final*** și [Verificați dacă activarea pentru computere partajate este activată pentru aplicațiile Microsoft 365 pentru întreprinderi](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation#verify-that-activation-for-microsoft-365-apps-succeeded).
