---
title: Duplicarea înregistrărilor de dispozitiv în portal
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001495"
- "4386"
ms.openlocfilehash: 277afc59705e6040f0f9ae0c8cad965bd7d3ef65
ms.sourcegitcommit: 89ae9e8b36d1980f89f07b016fff0ec48f96b620
ms.translationtype: HT
ms.contentlocale: ro-RO
ms.lasthandoff: 04/23/2020
ms.locfileid: "43790169"
---
# <a name="duplicate-device-record-in-the-portal"></a><span data-ttu-id="808c5-102">Duplicarea înregistrărilor de dispozitiv în portal</span><span class="sxs-lookup"><span data-stu-id="808c5-102">Duplicate device record in the portal</span></span>

<span data-ttu-id="808c5-103">Este posibil să vedeți 2 înregistrări pentru un dispozitiv în portal dacă dispozitivul nu raportează corect starea de co-gestionare pe site-ul Manager de configurare.</span><span class="sxs-lookup"><span data-stu-id="808c5-103">You may see 2 records for a device in the portal if the device does not correctly report the co-management status to the Configuration Manager site.</span></span> <span data-ttu-id="808c5-104">Pentru a verifica starea de co-gestionare a unui dispozitiv, examinați coloana **Co-gestionat**pentru dispozitivul din consola Manager de configurare.</span><span class="sxs-lookup"><span data-stu-id="808c5-104">To check the co-management status of a device, review the **Co-managed** column for the device in the Configuration Manager console.</span></span> <span data-ttu-id="808c5-105">Dacă coloana nu este vizibilă, puteți să o adăugați făcând clic dreapta pe orice antet de coloană și selectându-o din listă.</span><span class="sxs-lookup"><span data-stu-id="808c5-105">If the column is not visible, you may add it by right-clicking any of the column headers, and selecting it from the list.</span></span>

<span data-ttu-id="808c5-106">Valoarea co-gestionată trebuie să fie **Da**.</span><span class="sxs-lookup"><span data-stu-id="808c5-106">The Co-managed value must be **Yes**.</span></span> <span data-ttu-id="808c5-107">Dacă valoarea este **Nu**, deschideți miniaplicația de client Manager de configurare pe dispozitivul clientului și verificați proprietatea **Co-gestionare** din fila General.</span><span class="sxs-lookup"><span data-stu-id="808c5-107">If the value is **No**, open the Configuration Manager client applet on the client device and check the **Co-management** property in the General tab.</span></span>

- <span data-ttu-id="808c5-108">Dacă valoarea este **Activat**, acest lucru indică probleme cu comunicarea de client cu Punctul de gestionare.</span><span class="sxs-lookup"><span data-stu-id="808c5-108">If the value is **Enabled**, this indicates problems with client communication with the Management Point.</span></span> <span data-ttu-id="808c5-109">Consultați\*\*CCmMessaging.log \*\* de pe dispozitiv pentru a investiga problemele potențiale de conectivitate.</span><span class="sxs-lookup"><span data-stu-id="808c5-109">Please review the **CcmMessaging.log** on the device to investigate potential connectivity issues.</span></span>

- <span data-ttu-id="808c5-110">Dacă valoarea este **Dezactivat** și dispozitivul este înscris în Intune, asigurați-vă că dispozitivul a primit Politica de co-gestionare, prin revizuirea **CoManagementHandler.log** de pe dispozitiv.</span><span class="sxs-lookup"><span data-stu-id="808c5-110">If the value is **Disabled** and the device is enrolled in Intune, please ensure that the device has received the Co-management policy by reviewing the **CoManagementHandler.log** on the device.</span></span>
