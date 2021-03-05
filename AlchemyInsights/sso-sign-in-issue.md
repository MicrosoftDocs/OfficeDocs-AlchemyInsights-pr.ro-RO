---
title: Probleme de conectare pentru utilizatorul SSO fără sudură
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
- "9004357"
- "7811"
ms.openlocfilehash: 347ef8f8176583f2a7c15fa82435eeb118b58c39
ms.sourcegitcommit: 67c873fa6e23ec39a826d60ac830969073bf79e1
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 01/21/2021
ms.locfileid: "49935179"
---
# <a name="seamless-sso-user-sign-in-issues"></a><span data-ttu-id="1aa6d-102">Probleme de conectare pentru utilizatorul SSO fără sudură</span><span class="sxs-lookup"><span data-stu-id="1aa6d-102">Seamless SSO user sign-in issues</span></span>

<span data-ttu-id="1aa6d-103">După autentificarea utilizatorului, browserul va memora acreditările utilizatorului, astfel încât, în același browser, aplicația să se conecteze automat la același cont.</span><span class="sxs-lookup"><span data-stu-id="1aa6d-103">After the user is authenticated, the browser will cache the user's credentials, so that on the same browser, the application will automatically sign-in with the same account.</span></span> <span data-ttu-id="1aa6d-104">Acest lucru poate îngreuna faptul ca un alt utilizator sau un singur utilizator să se conecteze la mai multe conturi pe un singur dispozitiv.</span><span class="sxs-lookup"><span data-stu-id="1aa6d-104">This may make it difficult for another user or a single user to log into multiple accounts on one device.</span></span> <span data-ttu-id="1aa6d-105">Pentru a rezolva această problemă: 1.</span><span class="sxs-lookup"><span data-stu-id="1aa6d-105">To solve this: 1.</span></span> <span data-ttu-id="1aa6d-106">Încercați să vă conectați la alt browser.</span><span class="sxs-lookup"><span data-stu-id="1aa6d-106">Try signing in on another browser.</span></span> <span data-ttu-id="1aa6d-107">2.</span><span class="sxs-lookup"><span data-stu-id="1aa6d-107">2.</span></span> <span data-ttu-id="1aa6d-108">Debifați memoria cache a browserului și/sau modulele cookie și încercați din nou să vă conectați.</span><span class="sxs-lookup"><span data-stu-id="1aa6d-108">Clear the browser's cache and/or cookies and try signing in again.</span></span>

<span data-ttu-id="1aa6d-109">Dacă încă întâmpinați probleme de conectare, vă recomandăm următoarele pentru a diagnostica și a automatiza pașii de rezolvare:</span><span class="sxs-lookup"><span data-stu-id="1aa6d-109">If you are still experiencing sign-in issues, we recommend the following to diagnose and automate the resolution steps:</span></span>

1. <span data-ttu-id="1aa6d-110">Instalați [extinderea aplicațiilor mele sigure pentru browser](https://docs.microsoft.com/azure/active-directory/manage-apps/access-panel-extension-problem-installing) pentru a ajuta Azure Active Directory (Azure AD) să ofere un diagnostic și rezoluții mai bune atunci când utilizați experiența de testare din portalul Azure.</span><span class="sxs-lookup"><span data-stu-id="1aa6d-110">Install the [My Apps Secure Browser Extension](https://docs.microsoft.com/azure/active-directory/manage-apps/access-panel-extension-problem-installing) to help Azure Active Directory (Azure AD) to provide better diagnosis and resolutions when using the testing experience in the Azure portal.</span></span>
2. <span data-ttu-id="1aa6d-111">Reproducerea erorii utilizând experiența de testare din pagina de configurare a aplicației din portalul Azure.</span><span class="sxs-lookup"><span data-stu-id="1aa6d-111">Reproduce the error using the testing experience in the app configuration page in the Azure portal.</span></span> <span data-ttu-id="1aa6d-112">Pentru a afla mai multe, consultați [Depanarea aplicațiilor de sign-on unice bazate pe SAML](https://docs.microsoft.com/azure/active-directory/azuread-dev/howto-v1-debug-saml-sso-issues).</span><span class="sxs-lookup"><span data-stu-id="1aa6d-112">To learn more, see [Debug SAML-based single sign-on applications](https://docs.microsoft.com/azure/active-directory/azuread-dev/howto-v1-debug-saml-sso-issues).</span></span>
3. <span data-ttu-id="1aa6d-113">Dacă utilizați experiența de testare din portalul Azure cu extensia de browser securizată a aplicațiilor mele, puteți **ignora pasul 4**.</span><span class="sxs-lookup"><span data-stu-id="1aa6d-113">If you use the testing experience in the Azure portal with the My Apps Secure Browser Extension, you can **skip step 4**.</span></span>
4. <span data-ttu-id="1aa6d-114">Pentru a deschide pagina de configurare pentru sign-on unic bazat pe SAML:</span><span class="sxs-lookup"><span data-stu-id="1aa6d-114">To open the SAML-based single sign-on configuration page:</span></span>
    - <span data-ttu-id="1aa6d-115">Deschideți [portalul Azure](https://portal.azure.com/) și conectați-vă ca **administrator global** sau **coadministrator**.</span><span class="sxs-lookup"><span data-stu-id="1aa6d-115">Open the [Azure portal](https://portal.azure.com/) and sign in as a **Global Administrator** or **Coadmin**.</span></span>
    - <span data-ttu-id="1aa6d-116">Deschideți **extensia Azure Active Directory** selectând **toate serviciile** în partea de sus a meniului de navigare principal din partea stângă.</span><span class="sxs-lookup"><span data-stu-id="1aa6d-116">Open the **Azure Active Directory Extension** by selecting **All services** at the top of the main left-side navigation menu.</span></span>
    - <span data-ttu-id="1aa6d-117">Tastați "Azure Active Directory" în caseta de căutare filtrare și selectați elementul **Azure Active Directory** .</span><span class="sxs-lookup"><span data-stu-id="1aa6d-117">Type "Azure Active Directory" in the filter search box and select the **Azure Active Directory** item.</span></span>
    - <span data-ttu-id="1aa6d-118">Selectați **aplicații de întreprindere** din meniul de navigare din stânga-dreapta Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="1aa6d-118">Select **Enterprise Applications** from the Azure Active Directory left-hand navigation menu.</span></span>
    - <span data-ttu-id="1aa6d-119">Selectați **toate aplicațiile** pentru a vizualiza o listă cu toate aplicațiile dvs.</span><span class="sxs-lookup"><span data-stu-id="1aa6d-119">Select **All Applications** to view a list of all your applications.</span></span> <span data-ttu-id="1aa6d-120">Dacă nu vedeți aplicația pe care doriți să o Afișați aici, utilizați controlul de **Filtrare** din partea de sus a **listei toate aplicațiile** și setați opțiunea **Afișare** pentru **toate aplicațiile**.</span><span class="sxs-lookup"><span data-stu-id="1aa6d-120">If you do not see the application you want show up here, use the **Filter** control at the top of the **All Applications List** and set the **Show** option to **All Applications**.</span></span>
    - <span data-ttu-id="1aa6d-121">Selectați aplicația pe care doriți să o configurați pentru sign-on unic.</span><span class="sxs-lookup"><span data-stu-id="1aa6d-121">Select the application you want to configure for single sign-on.</span></span>
    - <span data-ttu-id="1aa6d-122">După ce se încarcă aplicația, selectați **Sign-on unic** din meniul de navigare din partea stângă a aplicației.</span><span class="sxs-lookup"><span data-stu-id="1aa6d-122">After the application loads, select **Single sign-on** from the application’s left-hand navigation menu.</span></span>
    - <span data-ttu-id="1aa6d-123">Selectați **SSO bazat pe SAML**.</span><span class="sxs-lookup"><span data-stu-id="1aa6d-123">Select **SAML-based SSO**.</span></span>
5. <span data-ttu-id="1aa6d-124">Pe baza erorii, pentru a afla mai multe despre pașii recomandați de urmărit, consultați [probleme la conectarea la aplicații configurate pentru sign-on unic bazat pe SAML](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-problem-federated-sso-gallery#application-not-found-in-directory).</span><span class="sxs-lookup"><span data-stu-id="1aa6d-124">Based on the error, to learn more about the recommended steps to follow, see [Problems signing in to SAML-based single sign-on configured apps](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-problem-federated-sso-gallery#application-not-found-in-directory).</span></span>
6. <span data-ttu-id="1aa6d-125">Pentru a depana alte probleme de sign-in de utilizator, consultați următoarele instrucțiuni:</span><span class="sxs-lookup"><span data-stu-id="1aa6d-125">To troubleshoot other user sign-issues refer to the following guidance:</span></span>
    - [<span data-ttu-id="1aa6d-126">Protocolul single Sign-On SAML</span><span class="sxs-lookup"><span data-stu-id="1aa6d-126">Single Sign-On SAML protocol</span></span>](https://docs.microsoft.com/azure/active-directory/develop/single-sign-on-saml-protocol)
    - [<span data-ttu-id="1aa6d-127">Instrucțiuni: Depanarea erorilor de conectare utilizând rapoartele Azure Active Directory</span><span class="sxs-lookup"><span data-stu-id="1aa6d-127">How to: Troubleshoot sign-in errors using Azure Active Directory reports</span></span>](https://docs.microsoft.com/azure/active-directory/reports-monitoring/howto-troubleshoot-sign-in-errors)
    - [<span data-ttu-id="1aa6d-128">Solicitare de consimțământ neașteptată</span><span class="sxs-lookup"><span data-stu-id="1aa6d-128">Unexpected consent prompt</span></span>](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-unexpected-user-consent-prompt)
    - [<span data-ttu-id="1aa6d-129">Eroare de consimțământ pentru utilizator</span><span class="sxs-lookup"><span data-stu-id="1aa6d-129">User consent error</span></span>](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-unexpected-user-consent-error)
    - [<span data-ttu-id="1aa6d-130">Probleme la conectare din aplicațiile mele</span><span class="sxs-lookup"><span data-stu-id="1aa6d-130">Problems signing in from My Apps</span></span>](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-other-problem-access-panel)
    - [<span data-ttu-id="1aa6d-131">Eroare la pagina de conectare la aplicație</span><span class="sxs-lookup"><span data-stu-id="1aa6d-131">Error on application sign-in page</span></span>](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-problem-application-error)
    - [<span data-ttu-id="1aa6d-132">Problemă la conectarea la o aplicație Microsoft</span><span class="sxs-lookup"><span data-stu-id="1aa6d-132">Problem signing into a Microsoft App</span></span>](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-problem-first-party-microsoft)