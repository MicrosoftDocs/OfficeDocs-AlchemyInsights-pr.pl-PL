---
title: Rozwiązywanie problemów z wiadomościami odmowa dostępu
ms.author: kaarins
author: kaarins
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: f1a4803838b6511ef4fe7f03cafa4aa13b3c9734
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 02/12/2019
ms.locfileid: "29916462"
---
# <a name="troubleshoot-access-denied-messages"></a><span data-ttu-id="a25b6-102">Rozwiązywanie problemów z wiadomościami odmowa dostępu</span><span class="sxs-lookup"><span data-stu-id="a25b6-102">Troubleshoot Access Denied messages</span></span>

<span data-ttu-id="a25b6-p101">Jeśli ktoś ma komunikat "Odmowa dostępu" w folderze udostępnionym, administrator zbioru witryn może mieć aktywny "dostęp ograniczony uprawnienie blokowania tryb użytkownika." Aby wyłączyć tę funkcję:</span><span class="sxs-lookup"><span data-stu-id="a25b6-p101">If someone got an "Access Denied" message to a shared folder, the site collection administrator might have enabled "Limited-access user permission lockdown mode." To turn this off:</span></span> 
  
1. <span data-ttu-id="a25b6-105">Przejdź do witryny, kliknij przycisk Ustawienia, a następnie kliknij **Ustawienia witryny**.</span><span class="sxs-lookup"><span data-stu-id="a25b6-105">Browse to the site, click the Settings icon, and then click **Site Settings**.</span></span>
    
2. <span data-ttu-id="a25b6-106">W obszarze **Administracja zbioru witryn**kliknij przycisk **Funkcje zbioru witryn**.</span><span class="sxs-lookup"><span data-stu-id="a25b6-106">Under **Site Collection Administration**, click **Site collection features**.</span></span>
    
3. <span data-ttu-id="a25b6-107">Obok **Tryb blokowania uprawnień ograniczony dostęp użytkownika**kliknij przycisk **Dezaktywuj**.</span><span class="sxs-lookup"><span data-stu-id="a25b6-107">Next to **Limited-access user permission lockdown mode**, click **Deactivate**.</span></span>
    
<span data-ttu-id="a25b6-p102">Komunikat Odmowa dostępu może również wystąpić w udostępnionych folderach, jeśli witryna jest witryną publikowania. Aby uzyskać informacje zobacz [Odmowa dostępu, gdy dostęp do folderu udostępnionego](https://go.microsoft.com/fwlink/?linkid=2004317).</span><span class="sxs-lookup"><span data-stu-id="a25b6-p102">An Access Denied message can also occur for shared folders if the site is a publishing site. For info, see [Access Denied when accessing a shared folder](https://go.microsoft.com/fwlink/?linkid=2004317).</span></span>
  
<span data-ttu-id="a25b6-p103">Jeśli ktoś ma komunikat "Odmowa dostępu" przy próbie wyświetlenia żądania dostępu, użytkownik musi zostać dodany jako administrator zbioru witryn lub członkiem grupy Właściciele witryny. Aby uzyskać więcej informacji zobacz temat [Odmowa dostępu do listy żądań dostępu](https://go.microsoft.com/fwlink/?linkid=2004220).</span><span class="sxs-lookup"><span data-stu-id="a25b6-p103">If a someone got an "Access Denied" message when trying to view access requests, the user needs to be added as either a site collection administrator or a member of the Owners group for the site. For more info, see [Access Denied to Access Requests list](https://go.microsoft.com/fwlink/?linkid=2004220).</span></span>
  
<span data-ttu-id="a25b6-112">Jeśli użytkownik ma komunikat "Odmowa dostępu" po zostały usunięte z lokalnej usługi Active Directory, a następnie dodane ponownie, zobacz [Odmowa dostępu, gdy konto użytkownika jest zsynchronizowane z programem Office 365](https://go.microsoft.com/fwlink/?linkid=2004318).</span><span class="sxs-lookup"><span data-stu-id="a25b6-112">If a user got an "Access Denied" message after they were removed from Active Directory on-premises and then added back, see [Access Denied when a user account is synced to Office 365](https://go.microsoft.com/fwlink/?linkid=2004318).</span></span>
  

