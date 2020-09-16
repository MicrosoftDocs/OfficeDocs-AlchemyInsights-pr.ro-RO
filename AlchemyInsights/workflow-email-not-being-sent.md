---
title: E-mailul fluxului de lucru nu este trimis
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1586"
ms.openlocfilehash: 7efb8895ac7e2816a2c6055ec3c08d6f7029d39d
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 09/14/2020
ms.locfileid: "47749001"
---
# <a name="workflow-email-is-not-being-sent-for-a-sharepoint-list-or-library"></a><span data-ttu-id="c091d-102">E-mailul fluxului de lucru nu este trimis pentru o listă sau o bibliotecă SharePoint</span><span class="sxs-lookup"><span data-stu-id="c091d-102">Workflow email is not being sent for a SharePoint list or library</span></span>

1. <span data-ttu-id="c091d-103">E-mailul de la fluxurile de lucru nu este trimis tuturor utilizatorilor sau doar anumitor utilizatori sau vedeți eroarea **mesajul de e-mail nu poate fi trimis. Asigurați-vă că e-mailul are un destinatar valid**.</span><span class="sxs-lookup"><span data-stu-id="c091d-103">Email from workflows are not sent to all users or only specific users, or you see the error **The e-mail message cannot be sent. Make sure the e-mail has a valid recipient**.</span></span>

    <span data-ttu-id="c091d-104">Verificați dacă utilizatorul există în grupul permisiuni pentru **toate persoanele** (lista de informații utilizator) pentru acea colecție de site-uri.</span><span class="sxs-lookup"><span data-stu-id="c091d-104">Check if the user exist in the **All People** permissions group (user information list) for that site collection.</span></span>  <span data-ttu-id="c091d-105">Exemplu de URL direct: https:// <tenant> . SharePoint.com/sites/ <sitename> /_layouts/15/People.aspx? MembershipGroupId = 0</span><span class="sxs-lookup"><span data-stu-id="c091d-105">Sample direct URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx?MembershipGroupId=0</span></span>

    - <span data-ttu-id="c091d-106">Dacă utilizatorul nu există, asigurați-vă că utilizatorul este conectat la pagină.</span><span class="sxs-lookup"><span data-stu-id="c091d-106">If the user does not exist, make sure the user is signed into the page.</span></span> 
    - <span data-ttu-id="c091d-107">Dacă este un utilizator extern, asigurați-vă că invitația a fost acceptată.</span><span class="sxs-lookup"><span data-stu-id="c091d-107">If it is an external user, make sure that their invitation has been accepted.</span></span>
    - <span data-ttu-id="c091d-108">Dacă utilizatorul există în grupul permisiuni, asigurați-vă că adresa de e-mail este corectă.</span><span class="sxs-lookup"><span data-stu-id="c091d-108">If the user does exist in the permissions group, make sure the email address is correct.</span></span>
    - <span data-ttu-id="c091d-109">Dacă adresa de e-mail a utilizatorilor nu este setată aici, creați o avertizare eșantion pentru acel utilizator care forțează sincronizarea acelui cont de utilizator de profilurile de utilizator din SharePoint în această colecție de site-uri.</span><span class="sxs-lookup"><span data-stu-id="c091d-109">If the users email address is not set here, then create a sample alert for that user which forces the sync of that user account from User Profiles of SharePoint to this site collection.</span></span>
 
2. <span data-ttu-id="c091d-110">E-mailul de la fluxurile de lucru este trimis administratorilor colecției de site-uri, dar nu și altor utilizatori și vedeți eroarea **http interzisă <span>https:</span>//URL/_vti_bin/client.XVC.SP.Utilities.Utility.SendEmail**.</span><span class="sxs-lookup"><span data-stu-id="c091d-110">Email from workflows are sent to the site collection administrators but not to other users and see the error **HTTP Forbidden to <span>https:</span>//URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**.</span></span>
 

    <span data-ttu-id="c091d-111">Consultați [Access Denied atunci când trimiteți un mesaj de e-mail la un grup SharePoint](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).</span><span class="sxs-lookup"><span data-stu-id="c091d-111">See [Access Denied when you send an email to a SharePoint group](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).</span></span>

    <span data-ttu-id="c091d-112">De asemenea, Verificați dacă caracteristica de colecție de site-uri cu **acces limitat la permisiune utilizator** nu este activă.</span><span class="sxs-lookup"><span data-stu-id="c091d-112">Also, verify that the **Limited-access user permission lockdown mode** site collection feature is not active.</span></span>


## <a name="related-topics"></a><span data-ttu-id="c091d-113">Subiecte asociate</span><span class="sxs-lookup"><span data-stu-id="c091d-113">Related topics</span></span>
<span data-ttu-id="c091d-114">Doriți să încercați Microsoft Flow în SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="c091d-114">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="c091d-115">Crearea fluxului</span><span class="sxs-lookup"><span data-stu-id="c091d-115">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="c091d-116">SharePoint și fluxul</span><span class="sxs-lookup"><span data-stu-id="c091d-116">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


