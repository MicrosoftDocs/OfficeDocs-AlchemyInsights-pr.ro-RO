---
title: Echipele permit sau dezactivează IP video
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002537"
- "5617"
ms.openlocfilehash: cf2d67170f846db1d5d2f1ca8c8b50902e200e45
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 09/14/2020
ms.locfileid: "47670196"
---
# <a name="teams-allow-or-disable-ip-video"></a><span data-ttu-id="5848d-102">Echipele permit sau dezactivează IP video</span><span class="sxs-lookup"><span data-stu-id="5848d-102">Teams allow or disable IP video</span></span>

<span data-ttu-id="5848d-103">**Modificarea sau crearea unei politici de întâlnire**</span><span class="sxs-lookup"><span data-stu-id="5848d-103">**Change or create a meeting policy**</span></span>

<span data-ttu-id="5848d-104">Pentru a modifica sau a crea o politică de întâlnire, accesați **Centrul de administrare Microsoft teams > întâlniri > politicile de întâlnire**.</span><span class="sxs-lookup"><span data-stu-id="5848d-104">To change or create a meeting policy, go to the **Microsoft Teams admin center > Meetings > Meeting policies**.</span></span> <span data-ttu-id="5848d-105">Selectați o politică din listă sau selectați **Adăugare**.</span><span class="sxs-lookup"><span data-stu-id="5848d-105">Select a policy from the list or click **Add**.</span></span> <span data-ttu-id="5848d-106">Dacă creați o politică nouă, adăugați un nume și o descriere.</span><span class="sxs-lookup"><span data-stu-id="5848d-106">If you're creating a new policy, add a name and description.</span></span> <span data-ttu-id="5848d-107">Numele nu trebuie să conțină caractere speciale sau să fie mai mare de 64 de caractere.</span><span class="sxs-lookup"><span data-stu-id="5848d-107">The name can't contain special characters or be longer than 64 characters.</span></span> <span data-ttu-id="5848d-108">Alegeți setările, apoi faceți clic pe **Salvare**.</span><span class="sxs-lookup"><span data-stu-id="5848d-108">Choose your settings, and then click **Save**.</span></span>

<span data-ttu-id="5848d-109">De exemplu, să presupunem că aveți mulți utilizatori și doriți să limitați lățimea de bandă pe care ar necesita-o întâlnirea.</span><span class="sxs-lookup"><span data-stu-id="5848d-109">For example, say you have many users and you want to limit the amount of bandwidth that their meeting would require.</span></span> <span data-ttu-id="5848d-110">Ar trebui să creați o nouă politică particularizată numită: "lățime de bandă limitată" și să dezactivați următoarele setări:</span><span class="sxs-lookup"><span data-stu-id="5848d-110">You would create a new custom policy named "Limited bandwidth" and disable the following settings:</span></span>

<span data-ttu-id="5848d-111">Sub **Audio și video**:</span><span class="sxs-lookup"><span data-stu-id="5848d-111">Under **Audio & video**:</span></span>

- <span data-ttu-id="5848d-112">Dezactivați Permiteți înregistrarea în cloud.</span><span class="sxs-lookup"><span data-stu-id="5848d-112">Turn off Allow cloud recording.</span></span>
- <span data-ttu-id="5848d-113">Dezactivați Permiteți video prin IP.</span><span class="sxs-lookup"><span data-stu-id="5848d-113">Turn off Allow IP video.</span></span>

<span data-ttu-id="5848d-114">Apoi atribuiți politica utilizatorilor.</span><span class="sxs-lookup"><span data-stu-id="5848d-114">Then assign the policy to the users.</span></span>

<span data-ttu-id="5848d-115">**Atribuirea utilizatorilor a unei politici privind întâlnirile**</span><span class="sxs-lookup"><span data-stu-id="5848d-115">**Assign a meeting policy to users**</span></span>

1. <span data-ttu-id="5848d-116">În navigarea din stânga a centrului de administrare Microsoft Teams, accesați **Utilizatori**, apoi faceți clic pe utilizator.</span><span class="sxs-lookup"><span data-stu-id="5848d-116">In the left navigation of the Microsoft Teams admin center, go to **Users**, and then click the user.</span></span>
2. <span data-ttu-id="5848d-117">Selectați utilizatorul făcând clic pe stânga numelui de utilizator, apoi faceți clic pe **Editați setările**.</span><span class="sxs-lookup"><span data-stu-id="5848d-117">Select the user by clicking to the left of the user name, and then click **Edit settings**.</span></span>
3. <span data-ttu-id="5848d-118">Sub **Politica întâlnirii**, selectați politica pe care doriți să o atribuiți, apoi faceți clic pe **se aplică**.</span><span class="sxs-lookup"><span data-stu-id="5848d-118">Under **Meeting policy**, select the policy you want to assign and then click **Apply**.</span></span>

<span data-ttu-id="5848d-119">Pentru mai multe informații, consultați [gestionarea politicilor de întâlnire în teams](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams).</span><span class="sxs-lookup"><span data-stu-id="5848d-119">For more information, see [Manage meeting policies in Teams](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams).</span></span>