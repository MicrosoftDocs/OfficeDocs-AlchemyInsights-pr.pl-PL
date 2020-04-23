---
title: Nie jest wysyłana wiadomość e-mail z przepływem pracy
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1586"
ms.openlocfilehash: 391d3a2dcc2676a405065115f375c802d2492119
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766143"
---
# <a name="workflow-email-is-not-being-sent-for-a-sharepoint-list-or-library"></a><span data-ttu-id="485ab-102">Poczta e-mail przepływu pracy nie jest wysyłana dla listy lub biblioteki programu SharePoint</span><span class="sxs-lookup"><span data-stu-id="485ab-102">Workflow email is not being sent for a SharePoint list or library</span></span>

1. <span data-ttu-id="485ab-103">Wiadomości e-mail z przepływów pracy nie są wysyłane do wszystkich użytkowników lub tylko do określonych użytkowników lub pojawia się błąd **Nie można wysłać wiadomości e-mail. Upewnij się, że wiadomość e-mail ma prawidłowego adresata**.</span><span class="sxs-lookup"><span data-stu-id="485ab-103">Email from workflows are not sent to all users or only specific users, or you see the error **The e-mail message cannot be sent. Make sure the e-mail has a valid recipient**.</span></span>

    <span data-ttu-id="485ab-104">Sprawdź, czy użytkownik istnieje w grupie Uprawnienia **Wszystkie osoby** (lista informacji o użytkowniku) dla tego zbioru witryn.</span><span class="sxs-lookup"><span data-stu-id="485ab-104">Check if the user exist in the **All People** permissions group (user information list) for that site collection.</span></span>  <span data-ttu-id="485ab-105">Przykładowy bezpośredni adres URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx? Udział w członkostwie=0</span><span class="sxs-lookup"><span data-stu-id="485ab-105">Sample direct URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx?MembershipGroupId=0</span></span>

    - <span data-ttu-id="485ab-106">Jeśli użytkownik nie istnieje, upewnij się, że użytkownik jest zalogowany do strony.</span><span class="sxs-lookup"><span data-stu-id="485ab-106">If the user does not exist, make sure the user is signed into the page.</span></span> 
    - <span data-ttu-id="485ab-107">Jeśli jest to użytkownik zewnętrzny, upewnij się, że jego zaproszenie zostało zaakceptowane.</span><span class="sxs-lookup"><span data-stu-id="485ab-107">If it is an external user, make sure that their invitation has been accepted.</span></span>
    - <span data-ttu-id="485ab-108">Jeśli użytkownik istnieje w grupie uprawnień, upewnij się, że adres e-mail jest poprawny.</span><span class="sxs-lookup"><span data-stu-id="485ab-108">If the user does exist in the permissions group, make sure the email address is correct.</span></span>
    - <span data-ttu-id="485ab-109">Jeśli adres e-mail użytkowników nie jest w tym miejscu ustawiony, utwórz przykładowy alert dla tego użytkownika, który wymusza synchronizację tego konta użytkownika z profili użytkowników programu SharePoint do tego zbioru witryn.</span><span class="sxs-lookup"><span data-stu-id="485ab-109">If the users email address is not set here, then create a sample alert for that user which forces the sync of that user account from User Profiles of SharePoint to this site collection.</span></span>
 
2. <span data-ttu-id="485ab-110">Wiadomości e-mail z przepływów pracy są wysyłane do administratorów zbioru witryn, ale nie do innych użytkowników i zobacz błąd **HTTP zabronione <span>https:</span>//URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**.</span><span class="sxs-lookup"><span data-stu-id="485ab-110">Email from workflows are sent to the site collection administrators but not to other users and see the error **HTTP Forbidden to <span>https:</span>//URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**.</span></span>
 

    <span data-ttu-id="485ab-111">Zobacz [Odmowa dostępu podczas wysyłania wiadomości e-mail do grupy programu SharePoint](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).</span><span class="sxs-lookup"><span data-stu-id="485ab-111">See [Access Denied when you send an email to a SharePoint group](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).</span></span>

    <span data-ttu-id="485ab-112">Sprawdź również, czy funkcja zbierania witryn **w trybie blokady uprawnień użytkownika o ograniczonym dostępie** nie jest aktywna.</span><span class="sxs-lookup"><span data-stu-id="485ab-112">Also, verify that the **Limited-access user permission lockdown mode** site collection feature is not active.</span></span>


## <a name="related-topics"></a><span data-ttu-id="485ab-113">Tematy pokrewne</span><span class="sxs-lookup"><span data-stu-id="485ab-113">Related topics</span></span>
<span data-ttu-id="485ab-114">Chcesz wypróbować usługę Microsoft Flow w usłudze SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="485ab-114">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="485ab-115">Utwórz przepływ</span><span class="sxs-lookup"><span data-stu-id="485ab-115">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="485ab-116">Program SharePoint i przepływ</span><span class="sxs-lookup"><span data-stu-id="485ab-116">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


