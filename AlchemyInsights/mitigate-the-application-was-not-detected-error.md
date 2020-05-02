---
title: Diminuarea erorii Aplicația nu a fost detectată
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000171"
- "1712"
ms.openlocfilehash: e07c6b128a39f1fb1c998d051aafe72205d8cbee
ms.sourcegitcommit: 82155846ce771c18050e6113d6c199b34a1504ff
ms.translationtype: HT
ms.contentlocale: ro-RO
ms.lasthandoff: 04/24/2020
ms.locfileid: "43810495"
---
# <a name="mitigate-the-application-was-not-detected-error"></a><span data-ttu-id="74138-102">Diminuarea erorii „Aplicația nu a fost detectată”</span><span class="sxs-lookup"><span data-stu-id="74138-102">Mitigate "The application was not detected" error</span></span>

<span data-ttu-id="74138-103">Eroarea de instalare a aplicației, „Aplicația nu a fost detectată după ce instalarea s-a finalizat cu succes”, raportată de Intune, poate apărea pe toate platformele de operare majore (Windows, iOS și Android).</span><span class="sxs-lookup"><span data-stu-id="74138-103">The app installation error, “The application was not detected after installation completed successfully,” reported by Intune, may occur on all major OS platforms (Windows, iOS and Android).</span></span>

<span data-ttu-id="74138-104">Printre scenariile cele mai obișnuite care generează această eroare se numără:</span><span class="sxs-lookup"><span data-stu-id="74138-104">The most common scenarios that generate this error include:</span></span>

- <span data-ttu-id="74138-105">Aplicația a fost actualizată în afara Intune (de la un magazin de aplicații de la terți) după implementarea inițială.</span><span class="sxs-lookup"><span data-stu-id="74138-105">The app has been updated outside of Intune (from a third-party app store) after the initial deployment.</span></span> <span data-ttu-id="74138-106">De exemplu, unele aplicații, cum ar fi Google Chrome, pot efectua actualizări automate.</span><span class="sxs-lookup"><span data-stu-id="74138-106">For example some applications such as Google Chrome may perform auto updates.</span></span>
- <span data-ttu-id="74138-107">Un utilizator a dezinstalat aplicația după instalarea inițială.</span><span class="sxs-lookup"><span data-stu-id="74138-107">A user has uninstalled the app after the initial install.</span></span>

<span data-ttu-id="74138-108">Pentru a diminua această problemă, efectuați mai întâi o revizuire a dispozitivelor afectate pentru a determina scenariul în care apare eroarea.</span><span class="sxs-lookup"><span data-stu-id="74138-108">To mitigate this issue, first perform a review of the affected devices to determine the scenario in which the error occurs.</span></span>

- <span data-ttu-id="74138-109">Dacă aplicația a fost actualizată în afara Intune, implementarea aplicației poate fi setată pentru a ignora versiunea aplicației.</span><span class="sxs-lookup"><span data-stu-id="74138-109">If the app has been updated outside of Intune, the app deployment can be set to ignore the application version.</span></span> <span data-ttu-id="74138-110">Pentru a face acest lucru, sub **Configurare aplicații > Informații despre aplicații**, setați **Ignorați versiunea aplicației** la **Da**.</span><span class="sxs-lookup"><span data-stu-id="74138-110">To do so, under **App Configuration > App Information**, set **Ignore App** version to **Yes**.</span></span>
- <span data-ttu-id="74138-111">Atunci când țintește clientul, poate fi potrivit să implementați aplicația ca „obligatori” și să vă asigurați că este implementată cea mai recentă versiune.</span><span class="sxs-lookup"><span data-stu-id="74138-111">When targeting the client, it may be appropriate to deploy the application as “required,” and to ensure that the latest version is deployed.</span></span>
- <span data-ttu-id="74138-112">Ca alternativă, pe platforma iOS, puteți utiliza funcționalitatea **actualizare automată** asociată cu programul de achiziționare în volum Apple, care poate fi configurată să actualizeze automat la noile versiuni ale aplicației, pe măsură ce devin disponibile.</span><span class="sxs-lookup"><span data-stu-id="74138-112">Alternatively, on the iOS platform, it is possible to use the **autoupdate** functionality associated with the Apple Volume Purchase Program, which can be configured to automatically update to new application versions as they become available.</span></span>

<span data-ttu-id="74138-113">Pentru mai multe informații despre depanarea problemelor de instalare a aplicațiilor, consultați [Depanarea problemelor de instalare a aplicațiilor](https://docs.microsoft.com/intune/troubleshoot-app-install).</span><span class="sxs-lookup"><span data-stu-id="74138-113">For more information about troubleshooting app installation issues, please see [Troubleshoot app installation issues](https://docs.microsoft.com/intune/troubleshoot-app-install).</span></span>