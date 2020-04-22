---
title: 2491 Mesaje de poștă electronică de alertă din politica "Phish livrate din cauza chiriaș sau user suprascrie" politica
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 2491
ms.assetid: ''
ms.openlocfilehash: 2e4efd504304da757687e697ff23374aeea31851
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 04/22/2020
ms.locfileid: "43758942"
---
# <a name="alert-email-messages-from-the-phish-delivered-due-to-tenant-or-user-override-policy"></a><span data-ttu-id="eac0f-102">Alertați mesajele de e-mail din politica "Phish livrate din cauza entității găzduite sau a utilizatorului suprascrie"</span><span class="sxs-lookup"><span data-stu-id="eac0f-102">Alert email messages from the 'Phish Delivered due to tenant or user override' policy</span></span>

<span data-ttu-id="eac0f-103">O politică de alertă implicită denumită "Phish livrate din cauza entității găzduite sau a înlocuirii utilizatorilor" a fost lansată pentru entitățile găzduite cu licențe Office 365 ATP P1 și P2.</span><span class="sxs-lookup"><span data-stu-id="eac0f-103">A default alert policy named "Phish Delivered due to tenant or user override" has been rolled out to tenants with Office 365 ATP P1 and P2 licenses.</span></span> <span data-ttu-id="eac0f-104">Dacă ați primit această alertă, iată pașii de investigare:</span><span class="sxs-lookup"><span data-stu-id="eac0f-104">If you received this alert, here are the steps to investigate:</span></span>

1. <span data-ttu-id="eac0f-105">Din mesajul de avertizare, faceți clic pe **Vizualizare avertizare** pentru a accesați pagina **Alerte** din Centrul de securitate & conformitate.</span><span class="sxs-lookup"><span data-stu-id="eac0f-105">From the alert message, click **View Alert** to go to the **Alerts** page in the Security & Compliance Center.</span></span>

2. <span data-ttu-id="eac0f-106">Selectați alerta pentru a vedea opțiunea de vizualizare listă **de mesaje** sau Vizualizare mesaje **în Explorer**.</span><span class="sxs-lookup"><span data-stu-id="eac0f-106">Select the alert to see the option to **View message list** or **View messages in Explorer**.</span></span> <span data-ttu-id="eac0f-107">Ambele opțiuni vă duc la detaliile mesajului, care include ID-ul mesajului.</span><span class="sxs-lookup"><span data-stu-id="eac0f-107">Both of these options take you to the details of the message, which includes the Message ID.</span></span> <span data-ttu-id="eac0f-108">Rețineți că linkul Explorator amenințări va filtra automat mesajele care corespund criteriilor de alertă.</span><span class="sxs-lookup"><span data-stu-id="eac0f-108">Note that the Threat Explorer link will automatically filter the messages that match the alert criteria.</span></span> <span data-ttu-id="eac0f-109">Poate fi necesar să ajustați filtrul de dată în Exploratorul de amenințări.</span><span class="sxs-lookup"><span data-stu-id="eac0f-109">You might need to adjust the date filter in Threat Explorer.</span></span>

<span data-ttu-id="eac0f-110">Mesajul de phishing a fost livrat din cauza unei înlocuiri configurate manual:</span><span class="sxs-lookup"><span data-stu-id="eac0f-110">The phishing message was delivered because of a manually configured override:</span></span>

- <span data-ttu-id="eac0f-111">Un expeditor sau un domeniu autorizat setat de utilizator.</span><span class="sxs-lookup"><span data-stu-id="eac0f-111">An allowed sender or domain set by the user.</span></span>

- <span data-ttu-id="eac0f-112">Un expeditor sau un domeniu autorizat setat de administrator într-o politică anti-spam.</span><span class="sxs-lookup"><span data-stu-id="eac0f-112">An allowed sender or domain set by the admin in an anti-spam policy.</span></span>

- <span data-ttu-id="eac0f-113">O adresă IP permisă într-o politică de filtrare a conexiunii.</span><span class="sxs-lookup"><span data-stu-id="eac0f-113">An allowed IP address in a connection filter policy.</span></span>

- <span data-ttu-id="eac0f-114">O regulă de flux de corespondență (cunoscută și ca regulă de transport) care este configurată pentru a permite mesajele.</span><span class="sxs-lookup"><span data-stu-id="eac0f-114">A mail flow rule (also known as a transport rule) that's configured to allow messages in.</span></span>

<span data-ttu-id="eac0f-115">Dacă credeți că mesajul a fost marcat incorect ca phish, utilizați [programul de completare Mesaj raport](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) Outlook pentru a remite mostre de mesaj la Microsoft.</span><span class="sxs-lookup"><span data-stu-id="eac0f-115">If you believe the message was incorrectly marked as phish, use the Outlook [Report Message add-in](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) to submit message samples to Microsoft.</span></span>
