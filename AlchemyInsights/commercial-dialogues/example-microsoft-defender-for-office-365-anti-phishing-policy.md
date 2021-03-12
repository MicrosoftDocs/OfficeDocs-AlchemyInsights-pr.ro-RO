---
title: Exemplu de politică anti-phishing Microsoft Defender pentru Office 365
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000760"
- "7391"
ms.openlocfilehash: eabff70c22b641627d3ab6c0b2f8846a0be2f49e
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: ro-RO
ms.lasthandoff: 03/11/2021
ms.locfileid: "50750794"
---
# <a name="example-microsoft-defender-for-office-365-anti-phishing-policy"></a><span data-ttu-id="3f3ec-102">Exemplu de politică anti-phishing Microsoft Defender pentru Office 365</span><span class="sxs-lookup"><span data-stu-id="3f3ec-102">Example Microsoft Defender for Office 365 anti-phishing policy</span></span>

<span data-ttu-id="3f3ec-103">Aceste setări permit o politică denumită *Domain și CEO*.</span><span class="sxs-lookup"><span data-stu-id="3f3ec-103">These settings enable a policy called *Domain and CEO*.</span></span> <span data-ttu-id="3f3ec-104">Această politică oferă protecție pentru utilizator și domeniu de la personificare, apoi aplică politica pentru toate mesajele de e-mail primite de utilizatorii din domeniu.</span><span class="sxs-lookup"><span data-stu-id="3f3ec-104">This policy provides both user and domain protection from impersonation and then applies the policy to all email received by users within the domain.</span></span> <span data-ttu-id="3f3ec-105">Mai întâi, adăugați următoarele informații pentru a crea politica:</span><span class="sxs-lookup"><span data-stu-id="3f3ec-105">First, add the following information to create the policy:</span></span>

- <span data-ttu-id="3f3ec-106">**Nume**: Domain and CEO **Description**: asigură faptul că directorul general și domeniul dumneavoastră nu sunt imitate.</span><span class="sxs-lookup"><span data-stu-id="3f3ec-106">**Name**: Domain and CEO **Description**: Ensures that the CEO and your domain are not being impersonated.</span></span>
  <span data-ttu-id="3f3ec-107">**Aplicată la**: selectați **domeniul destinatarului este**.</span><span class="sxs-lookup"><span data-stu-id="3f3ec-107">**Applied to**: Select **The recipient domain is**.</span></span> <span data-ttu-id="3f3ec-108">Sub **oricare dintre acestea**, selectați **alegere**, apoi selectați un domeniu.</span><span class="sxs-lookup"><span data-stu-id="3f3ec-108">Under **Any of these**, select **Choose**, and then select a domain.</span></span> <span data-ttu-id="3f3ec-109">Selectați **+ Adăugare**.</span><span class="sxs-lookup"><span data-stu-id="3f3ec-109">Select **+ Add**.</span></span> <span data-ttu-id="3f3ec-110">Bifați caseta de selectare de lângă numele domeniului din listă (de exemplu, *contoso.com*), apoi selectați **Adăugare**.</span><span class="sxs-lookup"><span data-stu-id="3f3ec-110">Select the check box next to the name of the domain in the list (for example, *contoso.com*), and then select **Add**.</span></span> <span data-ttu-id="3f3ec-111">Selectați **gata**.</span><span class="sxs-lookup"><span data-stu-id="3f3ec-111">Select **Done**.</span></span>
- <span data-ttu-id="3f3ec-112">După ce se creează politica, puteți ajusta politica utilizând următoarele opțiuni:</span><span class="sxs-lookup"><span data-stu-id="3f3ec-112">After the policy is created, you can fine-tune the policy by using the following options:</span></span>
  - <span data-ttu-id="3f3ec-113">**Adăugați utilizatori pentru a proteja:** Pentru acest exemplu, adăugați adresa de e-mail a CEO-ului, cel puțin.</span><span class="sxs-lookup"><span data-stu-id="3f3ec-113">**Add users to protect:** For this example, add the CEO's email address, at a minimum.</span></span>
  - <span data-ttu-id="3f3ec-114">**Adăugați domenii de protejat**: adăugați domeniul organizațional care include Office pentru CEO.</span><span class="sxs-lookup"><span data-stu-id="3f3ec-114">**Add domains to protect**: Add the organizational domain that includes the office of the CEO.</span></span>
  - <span data-ttu-id="3f3ec-115">**Alegeți acțiuni**: pentru **dacă e-mailul este trimis de un utilizator pretins**, selectați **redirecționați mesajul către altă adresă de e-mail**, apoi introduceți adresa de e-mail a administratorului de securitate (de exemplu, *securityadmin@contoso.com*).</span><span class="sxs-lookup"><span data-stu-id="3f3ec-115">**Choose actions**: For **If email is sent by an impersonated user**, select **Redirect message to another email address**, and then enter the email address of the security administrator (for example, *securityadmin@contoso.com*).</span></span> <span data-ttu-id="3f3ec-116">**Dacă e-mailul este trimis de un domeniu pretins**, selectați **carantină mesaj**.</span><span class="sxs-lookup"><span data-stu-id="3f3ec-116">For **If email is sent by an impersonated domain**, select **Quarantine the message**.</span></span>
  - <span data-ttu-id="3f3ec-117">**Serviciul de informații pentru cutia poștală**: în mod implicit, această opțiune este selectată atunci când creați o nouă politică anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="3f3ec-117">**Mailbox intelligence**: By default, this option is selected when you create a new anti-phishing policy.</span></span> <span data-ttu-id="3f3ec-118">Lăsați această setare **la** cele mai bune rezultate.</span><span class="sxs-lookup"><span data-stu-id="3f3ec-118">Leave this setting **On** for best results.</span></span>
  - <span data-ttu-id="3f3ec-119">**Adăugați expeditori și domenii de încredere:** Pentru acest exemplu, nu definiți nicio suprascrie.</span><span class="sxs-lookup"><span data-stu-id="3f3ec-119">**Add trusted senders and domains:** For this example, don't define any overrides.</span></span>
- <span data-ttu-id="3f3ec-120">După ce ați revizuit setările, selectați **Creați această politică** sau **Salvați**, după cum este cazul.</span><span class="sxs-lookup"><span data-stu-id="3f3ec-120">Once you've reviewed your settings, select **Create this policy** or **Save**, as appropriate.</span></span>

<span data-ttu-id="3f3ec-121">Pentru a afla mai multe, consultați [politici anti-phishing în Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2092235).</span><span class="sxs-lookup"><span data-stu-id="3f3ec-121">To learn more, see [Anti-phishing policies in Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2092235).</span></span>
