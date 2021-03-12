---
title: Przywracanie usuniętego pliku lub folderu
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: ba1573a5-9f44-482b-8082-6f648f169449
ms.openlocfilehash: 8c7ce48f50b5c933ea15c23a486b99ad7a7f4d79
ms.sourcegitcommit: 0eb4f9bde53395b5fd4b5cd4ffc56ca96db91298
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 03/10/2021
ms.locfileid: "50707532"
---
# <a name="restore-a-deleted-file-or-folder"></a><span data-ttu-id="17942-102">Przywracanie usuniętego pliku lub folderu</span><span class="sxs-lookup"><span data-stu-id="17942-102">Restore a deleted file or folder</span></span>

<span data-ttu-id="17942-103">W usłudze SharePoint Online kopie zapasowe wszystkich treści są przechowywane przez 14 dni po ich usunięciu.</span><span class="sxs-lookup"><span data-stu-id="17942-103">SharePoint Online retains backups of all content for 14 additional days beyond actual deletion.</span></span> <span data-ttu-id="17942-104">Jeśli nie można przywrócić zawartości za pośrednictwem Kosza lub przywracania plików, administrator może skontaktować się z pomocą techniczną firmy Microsoft w celu zażądania przywrócenia w dowolnym momencie w oknie 14-dniowym.</span><span class="sxs-lookup"><span data-stu-id="17942-104">If content cannot be restored via the Recycle Bin or Files Restore, an administrator can contact Microsoft Support to request a restore any time inside the 14 day window.</span></span> <span data-ttu-id="17942-105">Przywrócenie z kopii zapasowych można wykonać tylko w przypadku zbiorów witryn lub podwitryn, a nie w przypadku konkretnych plików, list i bibliotek.</span><span class="sxs-lookup"><span data-stu-id="17942-105">Restorations from backups can only be completed for site collections or sub-sites, not for specific files, lists, or libraries.</span></span>

<span data-ttu-id="17942-106">Usunięcie elementu lub witryny z programu SharePoint nie powoduje jego natychmiastowego usunięcia.</span><span class="sxs-lookup"><span data-stu-id="17942-106">When you delete an item or site from Sharepoint, it isn't immediately removed.</span></span> <span data-ttu-id="17942-107">Usunięte elementy znajdują się przez pewien czas w koszu.</span><span class="sxs-lookup"><span data-stu-id="17942-107">Deleted items go into the recycle bin for a period of time.</span></span> <span data-ttu-id="17942-108">Podczas tego okresu można przywrócić usunięte elementy do ich pierwotnych lokalizacji.</span><span class="sxs-lookup"><span data-stu-id="17942-108">During that time, you can restore the items you deleted to their original location.</span></span> <span data-ttu-id="17942-109">Aby uzyskać więcej informacji, skorzystaj z poniższych linków.</span><span class="sxs-lookup"><span data-stu-id="17942-109">For more information, please visit the links below.</span></span>

<span data-ttu-id="17942-110">[Przywracanie elementów z Kosza witryny programu SharePoint.](https://support.microsoft.com/office/restore-items-in-the-recycle-bin-that-were-deleted-from-sharepoint-or-teams-6df466b6-55f2-4898-8d6e-c0dff851a0be)</span><span class="sxs-lookup"><span data-stu-id="17942-110">[Restore items in the Recycle Bin of a SharePoint site](https://support.microsoft.com/office/restore-items-in-the-recycle-bin-that-were-deleted-from-sharepoint-or-teams-6df466b6-55f2-4898-8d6e-c0dff851a0be).</span></span>

[<span data-ttu-id="17942-111">Przywracanie usuniętych plików lub folderów w usłudze OneDrive</span><span class="sxs-lookup"><span data-stu-id="17942-111">Restore deleted files or folders in OneDrive</span></span>](https://support.office.com/article/Restore-deleted-files-or-folders-in-OneDrive-949ada80-0026-4db3-a953-c99083e6a84f)

[<span data-ttu-id="17942-112">Przywracanie usuniętego zbioru witryn (w tym grupy, komunikacji i innych witryn)</span><span class="sxs-lookup"><span data-stu-id="17942-112">Restore a deleted site collection (Including group, communication and other sites)</span></span>](https://docs.microsoft.com/sharepoint/restore-deleted-site-collection)

[<span data-ttu-id="17942-113">Przywracanie usuniętej witryny usługi OneDrive</span><span class="sxs-lookup"><span data-stu-id="17942-113">Restore a deleted OneDrive site</span></span>](https://docs.microsoft.com/onedrive/restore-deleted-onedrive)

<span data-ttu-id="17942-114">W przypadku akcji kosza zbiorczego administratorzy mogą rozważyć użycie usługi [SharePoint Online PNP.](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps)</span><span class="sxs-lookup"><span data-stu-id="17942-114">For bulk recycle bin actions, admins may consider using [Sharepoint Online PNP](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps).</span></span>

<span data-ttu-id="17942-115">**Funkcja przywracania plików**</span><span class="sxs-lookup"><span data-stu-id="17942-115">**Files Restore feature**</span></span>

<span data-ttu-id="17942-116">Jeśli wiele Twoich plików w usłudze OneDrive lub programie SharePoint zostało usuniętych, nadpisanych, uszkodzonych lub zainfekowanych złośliwym oprogramowaniem, możesz przywrócić całą bibliotekę usługi OneDrive lub programu SharePoint do poprzedniego czasu przy użyciu funkcji przywracania plików.</span><span class="sxs-lookup"><span data-stu-id="17942-116">If lots of your OneDrive or SharePoint files get deleted, overwritten, corrupted, or infected by malware, you can restore your entire OneDrive or SharePoint library to a previous time using the files restore feature.</span></span>

[<span data-ttu-id="17942-117">Przywracanie biblioteki usługi OneDrive</span><span class="sxs-lookup"><span data-stu-id="17942-117">Restore a OneDrive library</span></span>](https://support.office.com/article/restore-your-onedrive-fa231298-759d-41cf-bcd0-25ac53eb8a15)

[<span data-ttu-id="17942-118">Przywracanie biblioteki dokumentów</span><span class="sxs-lookup"><span data-stu-id="17942-118">Restore a Document library</span></span>](https://support.office.com/article/restore-a-document-library-317791c3-8bd0-4dfd-8254-3ca90883d39a)

