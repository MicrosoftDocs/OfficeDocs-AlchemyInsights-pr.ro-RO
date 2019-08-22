---
title: Creaţi un site SharePoint
ms.author: efrene
author: efrene
ms.date: 1/16/2019
ms.audience: ITPro
ms.topic: article
ms.collection: Adm_O365
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "5200004"
- "1386"
- "2303"
ms.assetid: e62b9f80-b017-42dc-9464-f4e32c19d6c9
ms.openlocfilehash: 96780bd2f4182c1385406ec2a31cd62745137985
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 08/22/2019
ms.locfileid: "36515819"
---
# <a name="create-a-sharepoint-site"></a><span data-ttu-id="b3255-102">Creaţi un site SharePoint</span><span class="sxs-lookup"><span data-stu-id="b3255-102">Create a SharePoint site</span></span>

<span data-ttu-id="b3255-103">Puteţi vedea următoarele pentru informaţii despre crearea de site-ul SharePoint:</span><span class="sxs-lookup"><span data-stu-id="b3255-103">You can see the following for information about SharePoint site creation:</span></span>
- <span data-ttu-id="b3255-104">[Administrare site-uri în noul centru de administrare SharePoint](https://docs.microsoft.com/sharepoint/manage-site-creation): Aflaţi mai multe despre site-ul crearea de opţiuni, inclusiv cum să creaţi un site clasic sau un site de echipe, care nu include un grup de Office 365.</span><span class="sxs-lookup"><span data-stu-id="b3255-104">[Manage sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/manage-site-creation): Learn about site creation options, including how to create a classic site or a teams site that doesn't include an Office 365 group.</span></span>
- <span data-ttu-id="b3255-105">[Creaţi un site de echipă în SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d?ui=en-US&amp;rs=en-US&amp;ad=US): Aflaţi cum să creaţi un site de echipă.</span><span class="sxs-lookup"><span data-stu-id="b3255-105">[Create a team site in SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d?ui=en-US&amp;rs=en-US&amp;ad=US): Learn how to create a team site.</span></span>
- <span data-ttu-id="b3255-106">[Creaţi un site de comunicare în SharePoint Online](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb): Aflaţi cum să creaţi un site de comunicaţii.</span><span class="sxs-lookup"><span data-stu-id="b3255-106">[Create a communication site in SharePoint Online](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb): Learn how to create a communications site.</span></span>
- <span data-ttu-id="b3255-107">[Administrare site-uri în noul centru de administrare SharePoint](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site): Aflaţi cum să creaţi un site clasic sau un site de echipă, care nu include un grup de Office 365.</span><span class="sxs-lookup"><span data-stu-id="b3255-107">[Manage sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site):  Learn how to create a classic site or a team site that doesn't include an Office 365 group.</span></span>


  
> [! Sfaturi]
> - <span data-ttu-id="b3255-109">Nu puteţi crea un site cu aceeaşi adresă URL de un site existent.</span><span class="sxs-lookup"><span data-stu-id="b3255-109">You cannot create a site with the same URL of an existing site.</span></span> <span data-ttu-id="b3255-110">Dacă aţi şters un site şi sunt care doresc să re-utilizarea URL-ul, este posibil site-ul şterse încă există în **site-uri şterse**.</span><span class="sxs-lookup"><span data-stu-id="b3255-110">If you deleted a site and are wishing to re-use the URL, it's possible the deleted site still exists under **Deleted sites**.</span></span> <span data-ttu-id="b3255-111">Pentru a gestiona elimină a se vedea site-uri, [ştergeţi un Site](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site).</span><span class="sxs-lookup"><span data-stu-id="b3255-111">To manage deleted sites see, [Delete a Site](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site).</span></span> <span data-ttu-id="b3255-112">Pentru a elimina complet un site cu Powershell, a se vedea exemplul de cmdlet-ul [Remove-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) .</span><span class="sxs-lookup"><span data-stu-id="b3255-112">To completely remove a site with Powershell, see the [Remove-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) cmdlet example.</span></span>
> - <span data-ttu-id="b3255-113">Unii utilizatori nu poate fi capabil de a crea un site.</span><span class="sxs-lookup"><span data-stu-id="b3255-113">Some users may not be able to create a site.</span></span> <span data-ttu-id="b3255-114">Consultaţi [crearea de site-ul administrare în SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation).</span><span class="sxs-lookup"><span data-stu-id="b3255-114">See [Manage site creation in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation).</span></span>
> - <span data-ttu-id="b3255-115">Este posibil site-ul pare blocat la **crearea** mai mult decât se aştepta.</span><span class="sxs-lookup"><span data-stu-id="b3255-115">It's possible the site appears stuck at **Creating** longer than expected.</span></span> <span data-ttu-id="b3255-116">În cazul în care mai mult de 24 de ore au trecut de când aţi văzut prima dată această problemă, vă rugăm să vă un bilet de sprijin.</span><span class="sxs-lookup"><span data-stu-id="b3255-116">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="b3255-117">În multe cazuri, lucrăm deja la o soluţie.</span><span class="sxs-lookup"><span data-stu-id="b3255-117">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="b3255-118">Vă rugăm să ne dea cel puţin 24 de ore pentru a finaliza o soluţie.</span><span class="sxs-lookup"><span data-stu-id="b3255-118">Please give us at least 24 hours to complete a solution.</span></span>
> - <span data-ttu-id="b3255-119">În cazul în care aveţi nevoie pentru a crea un nou site de echipa care nu include un grup de Office 365,</span><span class="sxs-lookup"><span data-stu-id="b3255-119">If you need to create a new team site that doesn't include an Office 365 group,</span></span> 


