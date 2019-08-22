---
title: Cod de eroare 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "919"
- "2000022"
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Dacă primiţi o eroare în timp ce activarea Office 2013 pe implementările de Remote Desktop Services (RDS), ia în considerare să permită ADAL editarea registry-ului.
ms.openlocfilehash: 4ef2943e5a529368fa2c614e4431cf180924fbb8
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 08/22/2019
ms.locfileid: "36527046"
---
# <a name="error-while-activation-office-2013-on-remote-desktop-services"></a><span data-ttu-id="58789-103">Eroare la activarea Office 2013 pe Remote Desktop servicii</span><span class="sxs-lookup"><span data-stu-id="58789-103">Error while activation Office 2013 on Remote Desktop Services</span></span>

<span data-ttu-id="58789-104">Dacă primiţi o eroare în timp ce activarea Office 2013 pe implementările de Remote Desktop Services (RDS), ia în considerare să permită ADAL editarea registry-ului.</span><span class="sxs-lookup"><span data-stu-id="58789-104">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span>
  
|<span data-ttu-id="58789-105">**Registru cheie**</span><span class="sxs-lookup"><span data-stu-id="58789-105">**Registry key**</span></span>|<span data-ttu-id="58789-106">**Tip**</span><span class="sxs-lookup"><span data-stu-id="58789-106">**Type**</span></span>|<span data-ttu-id="58789-107">**Valoarea**</span><span class="sxs-lookup"><span data-stu-id="58789-107">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="58789-108">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span><span class="sxs-lookup"><span data-stu-id="58789-108">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="58789-109">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="58789-109">REG_DWORD</span></span>  <br/> |<span data-ttu-id="58789-110">1</span><span class="sxs-lookup"><span data-stu-id="58789-110">1</span></span>  <br/> |

<span data-ttu-id="58789-111">Pentru informaţii suplimentare, consultaţi [Permite autentificarea moderne pentru Office 2013 pe Windows dispozitive](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span><span class="sxs-lookup"><span data-stu-id="58789-111">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="58789-112">Monica este activată în mod implicit în Office 365 ProPlus şi Office 2016.</span><span class="sxs-lookup"><span data-stu-id="58789-112">ADAL is enabled by default in Office 365 ProPlus and Office 2016.</span></span> <span data-ttu-id="58789-113">Remote Desktop servicii (RDS) a fost numit anterior Terminal Services.</span><span class="sxs-lookup"><span data-stu-id="58789-113">Remote Desktop Services (RDS) was previously named Terminal Services.</span></span>
  