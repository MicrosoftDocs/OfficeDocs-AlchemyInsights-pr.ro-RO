---
title: Depanarea protecției avansate a amenințărilor Office 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1039
ms.assetid: ''
ms.openlocfilehash: 5a13653ba08d8c6b822354ff70f6d276d31cd816
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 09/14/2020
ms.locfileid: "47658926"
---
# <a name="troubleshooting-office-365-advanced-threat-protection"></a><span data-ttu-id="9b1ec-102">Depanarea protecției avansate a amenințărilor Office 365</span><span class="sxs-lookup"><span data-stu-id="9b1ec-102">Troubleshooting Office 365 Advanced Threat Protection</span></span>

- <span data-ttu-id="9b1ec-103">Observați întârzieri în livrarea mesajelor?</span><span class="sxs-lookup"><span data-stu-id="9b1ec-103">Do you notice delays in message delivery?</span></span> <span data-ttu-id="9b1ec-104">Utilizați opțiunea de [livrare dinamică](https://docs.microsoft.com/microsoft-365/security/office-365-security/dynamic-delivery-and-previewing) din Politica de atașări sigure pentru ATP.</span><span class="sxs-lookup"><span data-stu-id="9b1ec-104">Use the [Dynamic Delivery](https://docs.microsoft.com/microsoft-365/security/office-365-security/dynamic-delivery-and-previewing) option in your ATP Safe Attachments policy.</span></span> <span data-ttu-id="9b1ec-105">Acest lucru vă va ajuta să evitați întârzierile mesajelor, protejând destinatarii din fișiere rău intenționate.</span><span class="sxs-lookup"><span data-stu-id="9b1ec-105">This will help avoid message delays while protecting recipients from malicious files.</span></span>

- <span data-ttu-id="9b1ec-106">Doriți să raportați pozitiv false sau negative false la Microsoft?</span><span class="sxs-lookup"><span data-stu-id="9b1ec-106">Do you want to report false positives or false negatives to Microsoft?</span></span> <span data-ttu-id="9b1ec-107">Utilizați acest [link](https://www.microsoft.com/wdsi/filesubmission/) pentru a remite fișiere pentru analiză.</span><span class="sxs-lookup"><span data-stu-id="9b1ec-107">Use this [link](https://www.microsoft.com/wdsi/filesubmission/) to submit files for analysis.</span></span>

- <span data-ttu-id="9b1ec-108">Știați că puteți să activați protecția Linkuri sigure pentru e-mailul intern trimis între destinatarii din cadrul Organizației?</span><span class="sxs-lookup"><span data-stu-id="9b1ec-108">Did you know that you can enable Safe Links protection for internal email sent between recipients within your organization?</span></span> <span data-ttu-id="9b1ec-109">Urmați acești pași:</span><span class="sxs-lookup"><span data-stu-id="9b1ec-109">Follow these steps:</span></span>

  1. <span data-ttu-id="9b1ec-110">Accesați [https://protection.office.com](https://protection.office.com) și conectați-vă cu un cont de administrator global sau de administrator de securitate.</span><span class="sxs-lookup"><span data-stu-id="9b1ec-110">Go to [https://protection.office.com](https://protection.office.com) and sign in with a global administrator or security administrator account.</span></span>

  2. <span data-ttu-id="9b1ec-111">În panoul de navigare din stânga, sub **gestionare amenințări**, alegeți **Policy** \> **linkuri sigure**pentru politică.</span><span class="sxs-lookup"><span data-stu-id="9b1ec-111">In the left navigation pane under **Threat management**, choose **Policy** \> **Safe Links**.</span></span>

  3. <span data-ttu-id="9b1ec-112">În **politicile care se aplică la întreaga** secțiune a Organizației, selectați politica și faceți clic pe **Editare**.</span><span class="sxs-lookup"><span data-stu-id="9b1ec-112">In the **Policies that apply to the entire organization** section, select the policy and click **Edit**.</span></span>

  4. <span data-ttu-id="9b1ec-113">Sub **Setări**, activați **aplicați Linkuri sigure la mesajele trimise în cadrul Organizației**.</span><span class="sxs-lookup"><span data-stu-id="9b1ec-113">Under **Settings**, enable **Apply safe links to messages sent within the organization**.</span></span>
