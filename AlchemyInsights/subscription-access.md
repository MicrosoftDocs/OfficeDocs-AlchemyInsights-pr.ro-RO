---
title: Acces la abonament
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003799"
- "6805"
ms.openlocfilehash: 166380cff09f2a2bd9b7e8914d5db4071b6c3f12
ms.sourcegitcommit: bec3554bf061ef28a009f460fb9d0a661b4fc008
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 10/27/2020
ms.locfileid: "48807719"
---
# <a name="unable-to-sign-in-azure-due-to-browser-issues-browser-hangs-keeps-spinning-does-not-load-etc"></a><span data-ttu-id="71af4-102">Nu puteți să vă conectați la Azure din cauza problemelor de browser (browser-ul se blochează, continuă să se rotească, nu se încarcă etc.)</span><span class="sxs-lookup"><span data-stu-id="71af4-102">Unable to Sign-in Azure due to browser issues (Browser hangs, keeps spinning, does not load, etc.)</span></span>

<span data-ttu-id="71af4-103">Este posibil să fiți afectat de o pană.</span><span class="sxs-lookup"><span data-stu-id="71af4-103">You might be impacted by an outage.</span></span> <span data-ttu-id="71af4-104">Vă rugăm să verificați dacă există o pană în curs: [starea de sănătate Azure](https://status.azure.com/status/history/).</span><span class="sxs-lookup"><span data-stu-id="71af4-104">Please check to see if there is an ongoing outage: [Azure Health Status](https://status.azure.com/status/history/).</span></span>

<span data-ttu-id="71af4-105">Vă rugăm să vă deconectați de la toate sesiunile Active Azure.</span><span class="sxs-lookup"><span data-stu-id="71af4-105">Please log out of all the active Azure sessions.</span></span> <span data-ttu-id="71af4-106">Porniți un modul în mod privat sau incognito al browserului web.</span><span class="sxs-lookup"><span data-stu-id="71af4-106">Start a in-private or incognito mode of your web browser.</span></span>

<span data-ttu-id="71af4-107">De asemenea, puteți încerca să reîmprospătați browserul, să utilizați alt browser, să ștergeți modulele cookie din cache dacă nu funcționează mai sus.</span><span class="sxs-lookup"><span data-stu-id="71af4-107">You could also try to Refresh browser, use another browser, delete cache cookies if above doesn't work.</span></span>

<span data-ttu-id="71af4-108">Aflați mai multe: [Depanarea problemelor de conectare](https://support.microsoft.com/help/4042961/troubleshoot-why-you-can-t-sign-in-to-manage-your-azure-subscription)</span><span class="sxs-lookup"><span data-stu-id="71af4-108">Learn more: [Troubleshoot Sign-in Issues](https://support.microsoft.com/help/4042961/troubleshoot-why-you-can-t-sign-in-to-manage-your-azure-subscription)</span></span>

<span data-ttu-id="71af4-109">**Nu puteți accesa abonamente**</span><span class="sxs-lookup"><span data-stu-id="71af4-109">**Unable to access subscriptions**</span></span>

<span data-ttu-id="71af4-110">În [portalul Azure](https://portal.azure.com/), asigurați-vă că este selectat directorul Azure corect din contul din partea dreaptă sus.</span><span class="sxs-lookup"><span data-stu-id="71af4-110">In the [Azure portal](https://portal.azure.com/), make sure that the correct Azure directory is selected from the account at the top right.</span></span>

<span data-ttu-id="71af4-111">În [Centrul de cont Azure](https://account.windowsazure.com/Subscriptions), asigurați-vă că contul utilizat este administratorul de cont.</span><span class="sxs-lookup"><span data-stu-id="71af4-111">In the [Azure Account center](https://account.windowsazure.com/Subscriptions), make sure if the account used is the account admin.</span></span>

<span data-ttu-id="71af4-112">Aflați mai multe: [Depanarea negăsită a abonamentelor](https://docs.microsoft.com/azure/billing/billing-no-subscriptions-found?WT.mc_id=Portal-Microsoft_Azure_Support)</span><span class="sxs-lookup"><span data-stu-id="71af4-112">Learn more: [Troubleshoot No Subscriptions found](https://docs.microsoft.com/azure/billing/billing-no-subscriptions-found?WT.mc_id=Portal-Microsoft_Azure_Support)</span></span>

<span data-ttu-id="71af4-113">**Nu puteți accesa istoricul de facturare**</span><span class="sxs-lookup"><span data-stu-id="71af4-113">**Unable to access billing history**</span></span>

<span data-ttu-id="71af4-114">Administratorul de cont trebuie să se asigure că utilizatorul care accesează informațiile de facturare este adăugat în Azure Active Directory ca utilizator invitat: [adăugarea sau ștergerea unui utilizator nou](https://docs.microsoft.com/azure/active-directory/fundamentals/add-users-azure-active-directory?WT.mc_id=Portal-Microsoft_Azure_Support).</span><span class="sxs-lookup"><span data-stu-id="71af4-114">The account admin needs to make sure the user accessing the billing information is added in the Azure Active directory as a guest user: [Add or delete a new user](https://docs.microsoft.com/azure/active-directory/fundamentals/add-users-azure-active-directory?WT.mc_id=Portal-Microsoft_Azure_Support).</span></span>

<span data-ttu-id="71af4-115">Utilizatorului i se va acorda un rol de administrator global: [atribuirea rolului pentru utilizatori](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-users-assign-role-azure-portal?WT.mc_id=Portal-Microsoft_Azure_Support).</span><span class="sxs-lookup"><span data-stu-id="71af4-115">The user then needs to be given a Global admin role: [Assign role to users](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-users-assign-role-azure-portal?WT.mc_id=Portal-Microsoft_Azure_Support).</span></span>

<span data-ttu-id="71af4-116">Postați aceasta, utilizatorului i se poate acorda acces de facturare utilizând politicile RBAC: [acordarea accesului la facturare](https://docs.microsoft.com/azure/billing/billing-manage-access?WT.mc_id=Portal-Microsoft_Azure_Support).</span><span class="sxs-lookup"><span data-stu-id="71af4-116">Post this, the user can be given billing access using RBAC policies: [Grant access to billing](https://docs.microsoft.com/azure/billing/billing-manage-access?WT.mc_id=Portal-Microsoft_Azure_Support).</span></span>

<span data-ttu-id="71af4-117">**Documente recomandate**</span><span class="sxs-lookup"><span data-stu-id="71af4-117">**Recommended Documents**</span></span>

-   [<span data-ttu-id="71af4-118">Nu mă pot conecta pentru a gestiona abonamentul meu Azure</span><span class="sxs-lookup"><span data-stu-id="71af4-118">I can't sign in to manage my Azure subscription</span></span>](https://docs.microsoft.com/azure/billing-cannot-login-subscription?WT.mc_id=Portal-Microsoft_Azure_Support)