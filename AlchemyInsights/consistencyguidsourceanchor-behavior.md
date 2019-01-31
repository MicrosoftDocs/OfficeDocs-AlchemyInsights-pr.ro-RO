---
title: ConsistencyGuid / sourceAnchor de comportament
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 6a44f797-acc7-4cbe-aa5a-47e2581fabf5
ms.openlocfilehash: 010474bcc4cc6f97bcaafef9dfe6f4accfed4247
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 01/30/2019
ms.locfileid: "29659603"
---
# <a name="consistencyguid--sourceanchor-behavior"></a><span data-ttu-id="5fd65-102">ConsistencyGuid / sourceAnchor de comportament</span><span class="sxs-lookup"><span data-stu-id="5fd65-102">ConsistencyGuid / sourceAnchor behavior</span></span>

<span data-ttu-id="5fd65-p101">Azur AD Connect (versiunea 1.1.524.0 şi după) acum facilitează utilizarea ConsistencyGuid AMS ca atributul sourceAnchor. Atunci când se utilizează această caracteristică, Azure AD conecta configurează automat regulile sincronizare:</span><span class="sxs-lookup"><span data-stu-id="5fd65-p101">Azure AD Connect (version 1.1.524.0 and after) now facilitates the use of msDS-ConsistencyGuid as sourceAnchor attribute. When using this feature, Azure AD Connect automatically configures the synchronization rules to:</span></span>
  
- <span data-ttu-id="5fd65-p102">Utilizarea ConsistencyGuid AMS ca atributul sourceAnchor pentru obiectele utilizator. ObjectGUID este utilizat pentru alte tipuri de obiecte.</span><span class="sxs-lookup"><span data-stu-id="5fd65-p102">Use msDS-ConsistencyGuid as the sourceAnchor attribute for User objects. ObjectGUID is used for other object types.</span></span>
    
- <span data-ttu-id="5fd65-p103">Pentru orice dat local AD utilizator obiect a cărui atribut de AMS-ConsistencyGuid nu este populat, Azure AD conecta scrie valoarea objectGUID înapoi la atributul de AMS-ConsistencyGuid în Active Directory local. După atributul AMS-ConsistencyGuid este populat, Azure AD conecta apoi exportă obiectul azuriu AD.</span><span class="sxs-lookup"><span data-stu-id="5fd65-p103">For any given on-premises AD User object whose msDS-ConsistencyGuid attribute isn't populated, Azure AD Connect writes its objectGUID value back to the msDS-ConsistencyGuid attribute in on-premises Active Directory. After the msDS-ConsistencyGuid attribute is populated, Azure AD Connect then exports the object to Azure AD.</span></span>
    
 <span data-ttu-id="5fd65-p104">**Notă:** O dată un local AD obiect este importat în Azure AD conecta (adică, importate în spaţiul conector AD şi proiectat în Metaverse), nu se poate modifica valoarea sa sourceAnchor mai. Pentru a preciza valoarea sourceAnchor o dat local AD obiect, configuraţi atributul lui AMS-ConsistencyGuid înainte de a acesta este importat în Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="5fd65-p104">**Note:** Once an on-premises AD object is imported into Azure AD Connect (that is, imported into the AD Connector Space and projected into the Metaverse), you cannot change its sourceAnchor value anymore. To specify the sourceAnchor value for a given on-premises AD object, configure its msDS-ConsistencyGuid attribute before it is imported into Azure AD Connect.</span></span> 
  
<span data-ttu-id="5fd65-111">Pentru mai multe informaţii despre SourceAnchor şi ConsistencyGuid, se referă la următoarele: [Azure AD conecta: concepte de Design](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span><span class="sxs-lookup"><span data-stu-id="5fd65-111">For more information on SourceAnchor and ConsistencyGuid, refer to the following: [Azure AD Connect: Design concepts](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span></span>
  

