---
title: Dostęp do abonamentu
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
ms.contentlocale: pl-PL
ms.lasthandoff: 10/27/2020
ms.locfileid: "48807717"
---
# <a name="unable-to-sign-in-azure-due-to-browser-issues-browser-hangs-keeps-spinning-does-not-load-etc"></a><span data-ttu-id="b3463-102">Nie można zalogować się na platformie Azure ze względu na problemy z przeglądarką (przeglądarka zawiesza się, nie ładuje, itd.)</span><span class="sxs-lookup"><span data-stu-id="b3463-102">Unable to Sign-in Azure due to browser issues (Browser hangs, keeps spinning, does not load, etc.)</span></span>

<span data-ttu-id="b3463-103">Może to mieć wpływ na awarię.</span><span class="sxs-lookup"><span data-stu-id="b3463-103">You might be impacted by an outage.</span></span> <span data-ttu-id="b3463-104">Sprawdź, czy są stale dostępne awarie: [stan kondycji Azure](https://status.azure.com/status/history/).</span><span class="sxs-lookup"><span data-stu-id="b3463-104">Please check to see if there is an ongoing outage: [Azure Health Status](https://status.azure.com/status/history/).</span></span>

<span data-ttu-id="b3463-105">Wyloguj się ze wszystkich aktywnych sesji platformy Azure.</span><span class="sxs-lookup"><span data-stu-id="b3463-105">Please log out of all the active Azure sessions.</span></span> <span data-ttu-id="b3463-106">Uruchom w przeglądarce sieci Web tryb in-prywatny lub incognito.</span><span class="sxs-lookup"><span data-stu-id="b3463-106">Start a in-private or incognito mode of your web browser.</span></span>

<span data-ttu-id="b3463-107">Możesz również spróbować odświeżyć przeglądarkę, użyć innej przeglądarki, usunąć pliki cookie z pamięci podręcznej, jeśli nie działają.</span><span class="sxs-lookup"><span data-stu-id="b3463-107">You could also try to Refresh browser, use another browser, delete cache cookies if above doesn't work.</span></span>

<span data-ttu-id="b3463-108">Dowiedz się więcej: [Rozwiązywanie problemów z logowaniem](https://support.microsoft.com/help/4042961/troubleshoot-why-you-can-t-sign-in-to-manage-your-azure-subscription)</span><span class="sxs-lookup"><span data-stu-id="b3463-108">Learn more: [Troubleshoot Sign-in Issues](https://support.microsoft.com/help/4042961/troubleshoot-why-you-can-t-sign-in-to-manage-your-azure-subscription)</span></span>

<span data-ttu-id="b3463-109">**Nie można uzyskać dostępu do subskrypcji**</span><span class="sxs-lookup"><span data-stu-id="b3463-109">**Unable to access subscriptions**</span></span>

<span data-ttu-id="b3463-110">W [portalu Azure](https://portal.azure.com/)upewnij się, że w obszarze konto u ¿prawego prawej strony wybrano właściwy katalog Azure.</span><span class="sxs-lookup"><span data-stu-id="b3463-110">In the [Azure portal](https://portal.azure.com/), make sure that the correct Azure directory is selected from the account at the top right.</span></span>

<span data-ttu-id="b3463-111">Upewnij się, że w [centrum konta platformy Azure](https://account.windowsazure.com/Subscriptions)jest używane konto administratora konta.</span><span class="sxs-lookup"><span data-stu-id="b3463-111">In the [Azure Account center](https://account.windowsazure.com/Subscriptions), make sure if the account used is the account admin.</span></span>

<span data-ttu-id="b3463-112">Dowiedz się więcej: [Rozwiązywanie problemów z nie odnalezionymi subskrypcjami](https://docs.microsoft.com/azure/billing/billing-no-subscriptions-found?WT.mc_id=Portal-Microsoft_Azure_Support)</span><span class="sxs-lookup"><span data-stu-id="b3463-112">Learn more: [Troubleshoot No Subscriptions found](https://docs.microsoft.com/azure/billing/billing-no-subscriptions-found?WT.mc_id=Portal-Microsoft_Azure_Support)</span></span>

<span data-ttu-id="b3463-113">**Nie można uzyskać dostępu do historii rozliczeń**</span><span class="sxs-lookup"><span data-stu-id="b3463-113">**Unable to access billing history**</span></span>

<span data-ttu-id="b3463-114">Administrator konta musi upewnić się, że użytkownik uzyskujący dostęp do informacji o rozliczeniach jest dodawany w usłudze Azure Active Directory jako użytkownik Gość: [Dodawanie lub usuwanie nowego użytkownika](https://docs.microsoft.com/azure/active-directory/fundamentals/add-users-azure-active-directory?WT.mc_id=Portal-Microsoft_Azure_Support).</span><span class="sxs-lookup"><span data-stu-id="b3463-114">The account admin needs to make sure the user accessing the billing information is added in the Azure Active directory as a guest user: [Add or delete a new user](https://docs.microsoft.com/azure/active-directory/fundamentals/add-users-azure-active-directory?WT.mc_id=Portal-Microsoft_Azure_Support).</span></span>

<span data-ttu-id="b3463-115">Użytkownik musi być następnie członkiem roli administratora globalnego: [Przypisywanie roli użytkownikom](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-users-assign-role-azure-portal?WT.mc_id=Portal-Microsoft_Azure_Support).</span><span class="sxs-lookup"><span data-stu-id="b3463-115">The user then needs to be given a Global admin role: [Assign role to users](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-users-assign-role-azure-portal?WT.mc_id=Portal-Microsoft_Azure_Support).</span></span>

<span data-ttu-id="b3463-116">Opublikuj, użytkownik może otrzymać dostęp do rozliczeń za pomocą zasad RBAC: [udzielanie dostępu do rozliczeń](https://docs.microsoft.com/azure/billing/billing-manage-access?WT.mc_id=Portal-Microsoft_Azure_Support).</span><span class="sxs-lookup"><span data-stu-id="b3463-116">Post this, the user can be given billing access using RBAC policies: [Grant access to billing](https://docs.microsoft.com/azure/billing/billing-manage-access?WT.mc_id=Portal-Microsoft_Azure_Support).</span></span>

<span data-ttu-id="b3463-117">**Polecane dokumenty**</span><span class="sxs-lookup"><span data-stu-id="b3463-117">**Recommended Documents**</span></span>

-   [<span data-ttu-id="b3463-118">Nie mogę się zalogować, aby zarządzać subskrypcją platformy Azure</span><span class="sxs-lookup"><span data-stu-id="b3463-118">I can't sign in to manage my Azure subscription</span></span>](https://docs.microsoft.com/azure/billing-cannot-login-subscription?WT.mc_id=Portal-Microsoft_Azure_Support)