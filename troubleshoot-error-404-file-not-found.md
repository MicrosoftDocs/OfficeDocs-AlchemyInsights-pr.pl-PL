---
title: Rozwiązywanie błędu 404 Nie znaleziono pliku
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 1b15444c-367b-4523-8e08-1c77bbea7524
ms.openlocfilehash: 2b0f6d84c53b812fe0552fc05473eebdfcc8d71a
ms.sourcegitcommit: 56c52c73e752414d66785f175c3a0e2925ad41c1
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 04/02/2019
ms.locfileid: "31044049"
---
# <a name="troubleshoot-error-404-file-not-found"></a><span data-ttu-id="2d4f2-102">Rozwiązywanie błędu 404 Nie znaleziono pliku</span><span class="sxs-lookup"><span data-stu-id="2d4f2-102">Troubleshoot Error 404, File not found</span></span>

<span data-ttu-id="2d4f2-103">Odebrano błąd 404, gdy użytkownicy próbują uzyskać dostęp do strony lub pliku w programie SharePoint lub OneDrive.</span><span class="sxs-lookup"><span data-stu-id="2d4f2-103">An Error 404 is received when users are attempting to access a site or file in SharePoint or OneDrive.</span></span> <span data-ttu-id="2d4f2-104">Jest to często spowodowane przez witryny lub pliku lub grupy coraz, zmieniono jego nazwę, przeniesiony lub usunięty.</span><span class="sxs-lookup"><span data-stu-id="2d4f2-104">This is often caused by a site or file or group getting renamed, moved or deleted.</span></span> <span data-ttu-id="2d4f2-105">Na przykład: użytkownicy napotkają błąd 404 próby dostępu głównego zbioru witryn i został usunięty.</span><span class="sxs-lookup"><span data-stu-id="2d4f2-105">For example: Users will experience a 404 Error attempting to access the Root Site Collection and it has been deleted.</span></span>

<span data-ttu-id="2d4f2-106">Aby rozwiązać błąd 404 dla strony, która została zmieniona, przeniesiony lub usunięty:</span><span class="sxs-lookup"><span data-stu-id="2d4f2-106">To resolve Error 404 for a Site that has been renamed, moved or deleted:</span></span>

<span data-ttu-id="2d4f2-107">Dla klasycznych stron, które występują w Centrum administracyjnego Classic zobacz [Przywracanie usuniętych zaufany](https://docs.microsoft.com/en-us/sharepoint/restore-deleted-site-collection).</span><span class="sxs-lookup"><span data-stu-id="2d4f2-107">For classic sites that exist in the Classic Admin Center, see [Restore a deleted site collection](https://docs.microsoft.com/en-us/sharepoint/restore-deleted-site-collection).</span></span>


<span data-ttu-id="2d4f2-108">Dla nowoczesnych witryn (komunikacji, podłączone do grupy, lub innych witryn) istniejące w podglądzie Centrum admin zobacz [View i przywracanie usunięte witryny w Centrum administracyjnego programu SharePoint](https://docs.microsoft.com/en-us/sharepoint/restore-deleted-site-collection).</span><span class="sxs-lookup"><span data-stu-id="2d4f2-108">For modern sites (communication, group-connected, or other sites) that exist in the new admin center preview, see [View and restore deleted sites in the new SharePoint admin center](https://docs.microsoft.com/en-us/sharepoint/restore-deleted-site-collection).</span></span>

<span data-ttu-id="2d4f2-109">Aby rozwiązać błąd 404 dla pliku (lub inny element), który został przeniesiony, przeniesiony lub usunięty:</span><span class="sxs-lookup"><span data-stu-id="2d4f2-109">To resolve Error 404 for a File (or other item) that has been renamed, moved or deleted:</span></span>

<span data-ttu-id="2d4f2-110">Przejdź do witryny programu SharePoint lub OneDrive i wyświetlić Kosz z zawartości witryny.</span><span class="sxs-lookup"><span data-stu-id="2d4f2-110">Go to the SharePoint or OneDrive site and view the Recycle Bin from the Site contents.</span></span> <span data-ttu-id="2d4f2-111">Zobacz, [Przywracanie elementów z Kosza witryny programu SharePoint](https://support.office.com/en-us/article/Restore-items-in-the-Recycle-Bin-of-a-SharePoint-site-6df466b6-55f2-4898-8d6e-c0dff851a0be#ID0EAADAAA=Online).</span><span class="sxs-lookup"><span data-stu-id="2d4f2-111">See, [Restore items in the Recycle Bin of a SharePoint site](https://support.office.com/en-us/article/Restore-items-in-the-Recycle-Bin-of-a-SharePoint-site-6df466b6-55f2-4898-8d6e-c0dff851a0be#ID0EAADAAA=Online).</span></span>

<span data-ttu-id="2d4f2-112">Jeśli nadal nie można znaleźć elementu można przeszukiwać dziennik inspekcji, jeśli rejestrowanie jest włączone zobacz [wyszukiwania dziennika inspekcji w & zabezpieczeń usługi Office 365 Centrum zgodności](https://docs.microsoft.com/en-us/office365/securitycompliance/search-the-audit-log-in-security-and-compliance?redirectSourcePath=%252fclient%252fsearch-the-audit-log-in-the-office-365-security-compliance-center-0d4d0f35-390b-4518-800e-0c7ec95e946c).</span><span class="sxs-lookup"><span data-stu-id="2d4f2-112">If you are still unable to find the item you can search the audit log if logging is enabled see, [Search the audit log in the Office 365 Security & Compliance Center](https://docs.microsoft.com/en-us/office365/securitycompliance/search-the-audit-log-in-security-and-compliance?redirectSourcePath=%252fclient%252fsearch-the-audit-log-in-the-office-365-security-compliance-center-0d4d0f35-390b-4518-800e-0c7ec95e946c).</span></span>