---
title: Gestiona Căutaţi dicţionare în SharePoint Online
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fe00f4c0-44d5-49d4-9db0-a62698bcd1d1
ms.openlocfilehash: c2960093bb1cfb649c26528c9f671e6d720ff237
ms.sourcegitcommit: 241e21b6da226563bf70bdb1f5bad3d91c38cd2c
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 06/05/2019
ms.locfileid: "34736064"
---
# <a name="search-in-sharepoint-online"></a><span data-ttu-id="5be5d-102">Căutare în SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="5be5d-102">Search in SharePoint Online</span></span>

<span data-ttu-id="5be5d-103">Conţinutul trebuie să fie indexat şi adăugate la indexul de căutare pentru utilizatorilor să găsească ceea ce ei caută în SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="5be5d-103">Content must be crawled and added to the search index for users to find what they're searching for in SharePoint Online.</span></span> <span data-ttu-id="5be5d-104">Conţinutul este scotocit automat bazat pe un program de accesare cu crawlere pre-definite (programul de scotocire nu poate fi schimbat).</span><span class="sxs-lookup"><span data-stu-id="5be5d-104">Content is automatically crawled based on a pre-defined crawl schedule (the crawl schedule cannot be changed).</span></span> <span data-ttu-id="5be5d-105">Crawler-ul preia conţinutul pe care s-a schimbat ultima scotocire şi actualizează indexul.</span><span class="sxs-lookup"><span data-stu-id="5be5d-105">The crawler picks up content that has changed since the last crawl and updates the index.</span></span> <span data-ttu-id="5be5d-106">Pentru a se asigura de conţinut este indexat şi Indexul este actualizat, urmaţi paşii de mai jos.</span><span class="sxs-lookup"><span data-stu-id="5be5d-106">To ensure content is crawled and the index is updated, follow the steps below.</span></span>

<span data-ttu-id="5be5d-107">Asiguraţi-vă că de conţinut pot fi găsite făcând conţinutul site-ului poate fi căutat.</span><span class="sxs-lookup"><span data-stu-id="5be5d-107">Make sure content can be found by making site content searchable.</span></span> <span data-ttu-id="5be5d-108">Pentru mai multe informaţii, consultaţi [Enable conţinutul de pe un site să fie căutate](https://docs.microsoft.com/en-us/sharepoint/make-site-content-searchable).</span><span class="sxs-lookup"><span data-stu-id="5be5d-108">For more info, see [Enable content on a site to be searchable](https://docs.microsoft.com/en-us/sharepoint/make-site-content-searchable).</span></span>

<span data-ttu-id="5be5d-109">Aţi modificat o proprietate gestionată, sau atunci când aţi schimbat cartografierea accesate şi gestionate proprietăţi, site-ul trebuie să fie re-scotocite înainte de modificările vor fi reflectate în indexul de căutare.</span><span class="sxs-lookup"><span data-stu-id="5be5d-109">When you have changed a managed property, or when you have changed the mapping of crawled and managed properties, the site must be re-crawled before your changes will be reflected in the search index.</span></span> 

<span data-ttu-id="5be5d-110">Deoarece modificările sunt făcute în schemă de căutare, şi nu la site-ul real, crawlerul va automat re-indexa site-ul.</span><span class="sxs-lookup"><span data-stu-id="5be5d-110">Because your changes are made in the search schema, and not to the actual site, the crawler will not automatically re-index the site.</span></span> 

<span data-ttu-id="5be5d-111">Pentru mai multe informaţii, consultaţi [manual solicita accesarea cu crawlere şi re-indexarea unui site, o listă sau o bibliotecă](https://docs.microsoft.com/en-us/sharepoint/crawl-site-conten).</span><span class="sxs-lookup"><span data-stu-id="5be5d-111">For more info, see [Manually request crawling and re-indexing of a site, a library or a list](https://docs.microsoft.com/en-us/sharepoint/crawl-site-conten).</span></span>

 <span data-ttu-id="5be5d-112">Aşteptaţi cel puţin 24 de ore după manual solicită o accesare cu crawlere şi complet re-index pentru a vedea dacă vă confruntaţi în continuare o problemă.</span><span class="sxs-lookup"><span data-stu-id="5be5d-112">Wait at least 24 hours after manually requesting a crawl and full re-index to see if you're still experiencing an issue.</span></span> 

<span data-ttu-id="5be5d-113">În cazul în care mai mult de 24 de ore au trecut de cand ai initiat de accesare cu crawlere şi complet re-indexa, vă rugăm să vă un caz de suport.</span><span class="sxs-lookup"><span data-stu-id="5be5d-113">If more than 24 hours have passed since you initiated the crawl and full re-index, please log a support case.</span></span> <span data-ttu-id="5be5d-114">În multe cazuri, lucrăm deja la o soluţie.</span><span class="sxs-lookup"><span data-stu-id="5be5d-114">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="5be5d-115">Vă rugăm să ne dea cel puţin 24 de ore pentru a finaliza o soluţie.</span><span class="sxs-lookup"><span data-stu-id="5be5d-115">Please give us at least 24 hours to complete a solution.</span></span>

<span data-ttu-id="5be5d-116">**Important**: dacă un site, documentul (biblioteca) sau o listă a fost şterse şi încă arată în rezultatele de căutare, utilizatorii ar trebui să primească o eroare 404 Fişier negăsit atunci când încearcă să acceseze.</span><span class="sxs-lookup"><span data-stu-id="5be5d-116">**Important**: If a site, document (library), or a list was deleted and still shows in the search results, users should receive an Error 404 File Not Found when trying to access.</span></span> <span data-ttu-id="5be5d-117">Această problemă trebuie să fiţi conectat ca un caz de suport pentru o analiza ulterioara.</span><span class="sxs-lookup"><span data-stu-id="5be5d-117">This issue should be logged as a support case for further investigation.</span></span> 


