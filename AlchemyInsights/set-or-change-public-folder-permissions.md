---
title: Ustawianie lub zmienianie uprawnień do folderu publicznego
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 8/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cffdf9bf-34ce-40f6-a69e-d02f17d9caef
ms.openlocfilehash: d1554e8a63455f3549044e526183c0e8709f2631
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 04/23/2019
ms.locfileid: "32421826"
---
# <a name="permissions-and-public-folders"></a><span data-ttu-id="ecaba-102">Uprawnienia i folderów publicznych</span><span class="sxs-lookup"><span data-stu-id="ecaba-102">Permissions and Public Folders</span></span>

<span data-ttu-id="ecaba-103">Można zmienić uprawnienia na folderów publicznych za pomocą programu Outlook, Centrum administracyjnego programu Exchange (EAC) lub środowiska PowerShell:</span><span class="sxs-lookup"><span data-stu-id="ecaba-103">You can change the permissions on your Public Folders using Outlook, the Exchange admin center (EAC), or PowerShell:</span></span>
  
- <span data-ttu-id="ecaba-104">Aby uzyskać instrukcje programu Outlook, [kliknij tutaj](https://support.office.com/article/Set-or-change-permissions-for-a-public-folder-b2e0440c-7873-48ec-9ff2-b1a20b723005.aspx).</span><span class="sxs-lookup"><span data-stu-id="ecaba-104">For Outlook instructions, [click here](https://support.office.com/article/Set-or-change-permissions-for-a-public-folder-b2e0440c-7873-48ec-9ff2-b1a20b723005.aspx).</span></span>
    
- <span data-ttu-id="ecaba-105">SKK można znaleźć [w tym artykule](https://technet.microsoft.com/library/jj651147%28v=exchg.150%29.aspx.aspx#Anchor_1) , aby uzyskać instrukcje.</span><span class="sxs-lookup"><span data-stu-id="ecaba-105">For EAC, refer to [this article](https://technet.microsoft.com/library/jj651147%28v=exchg.150%29.aspx.aspx#Anchor_1) for instructions.</span></span> <span data-ttu-id="ecaba-106">Możesz kliknąć [tutaj](https://support.office.com/article/ https://outlook.office365.com/ecp/.aspx) , aby przejść do SKK.</span><span class="sxs-lookup"><span data-stu-id="ecaba-106">You can click [here](https://support.office.com/article/ https://outlook.office365.com/ecp/.aspx) to navigate to EAC.</span></span> 
    
- <span data-ttu-id="ecaba-107">Powershell można znaleźć w [tym artykule](https://technet.microsoft.com/library/bb124743%28v=exchg.160%29.aspx.aspx) instrukcje dotyczące używania apletu Dodaj-PublicFolderClientPermission.</span><span class="sxs-lookup"><span data-stu-id="ecaba-107">For Powershell, refer to [this article](https://technet.microsoft.com/library/bb124743%28v=exchg.160%29.aspx.aspx) for instructions on using the Add-PublicFolderClientPermission commandlet.</span></span> <span data-ttu-id="ecaba-108">Jeśli potrzebujesz instrukcji w celu połączenia do środowiska PowerShell programu Exchange, kliknij [tutaj](https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx.aspx).</span><span class="sxs-lookup"><span data-stu-id="ecaba-108">If you need instructions to connect to Exchange Powershell, click [here](https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx.aspx).</span></span>
    
<span data-ttu-id="ecaba-109">Jeśli **Użytkownicy zewnętrzni nie można wysłać wiadomości e-mail do folderu publicznego z włączoną obsługą poczty e-mail**, przyczyna może być zobowiązany że folder publiczny jest brak uprawnienia do dostarczania poczty zewnętrznej.</span><span class="sxs-lookup"><span data-stu-id="ecaba-109">If **external users can't send emails to a mail-enabled Public Folder**, the reason might be that the public folder is missing permissions required for external email delivery.</span></span> <span data-ttu-id="ecaba-110">Można to naprawić, zgodnie z instrukcjami programu Outlook [tutaj](https://technet.microsoft.com/library/aa997560%28v=exchg.150%29.aspx.aspx#Anchor_1)lub instrukcje programu PowerShell [w tym miejscu](https://support.microsoft.com/help/2984402/-5.7.1-smtp-550-5.7.1-resolver.rst.authrequired-nondelivery-report-when-external-users-try-to-send-mail-to-mail-enabled-public-folders-in-office-365.aspx).</span><span class="sxs-lookup"><span data-stu-id="ecaba-110">You can fix this using the Outlook instructions [here](https://technet.microsoft.com/library/aa997560%28v=exchg.150%29.aspx.aspx#Anchor_1), or the PowerShell instructions [here](https://support.microsoft.com/help/2984402/-5.7.1-smtp-550-5.7.1-resolver.rst.authrequired-nondelivery-report-when-external-users-try-to-send-mail-to-mail-enabled-public-folders-in-office-365.aspx).</span></span>
  

