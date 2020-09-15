---
title: Synchronizacja profilu
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6b695be8-eaf5-44ff-b0ae-1e0d89e7ab36
ms.openlocfilehash: eee1080a95955332e205db3852381e39aaf5ae0e
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 09/15/2020
ms.locfileid: "47801779"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a><span data-ttu-id="c8d29-102">Kiedy zmiany w profilu są synchronizowane z aplikacją profilu użytkownika programu SharePoint?</span><span class="sxs-lookup"><span data-stu-id="c8d29-102">When do my profile changes sync to the SharePoint User Profile Application?</span></span>

<span data-ttu-id="c8d29-103">Usługa SharePoint Online używa zadania czasomierza importu usługi Active Directory (importu AD) do importowania użytkowników i grup do aplikacji profilu użytkownika.</span><span class="sxs-lookup"><span data-stu-id="c8d29-103">SharePoint Online uses the Active Directory Import timer job (AD Import) to import users and groups into the User Profile Application.</span></span> 
  
1. <span data-ttu-id="c8d29-104">Import usługi AD powoduje zsynchronizowanie zmian z magazynu katalogów usługi SharePoint Online w aplikacji profilu użytkownika.</span><span class="sxs-lookup"><span data-stu-id="c8d29-104">AD Import syncs changes from the SharePoint Online Directory Store to the User Profile Application.</span></span> <span data-ttu-id="c8d29-105">Te zmiany są przetwarzane w partiach.</span><span class="sxs-lookup"><span data-stu-id="c8d29-105">These changes are processed in batches.</span></span>
    
2. <span data-ttu-id="c8d29-106">Zadanie czasomierza zostanie uruchomione do momentu zsynchronizowania zmian.</span><span class="sxs-lookup"><span data-stu-id="c8d29-106">The timer job runs until the changes are synced.</span></span>
    
> [!NOTE]
> <span data-ttu-id="c8d29-107">Czas potrzebny na uruchomienie zadania zależy od liczby zmian, które należy przetworzyć.</span><span class="sxs-lookup"><span data-stu-id="c8d29-107">The time it takes the job to run depends on the number of changes to process.</span></span> <span data-ttu-id="c8d29-108">Duża liczba zmian trwa dłużej.</span><span class="sxs-lookup"><span data-stu-id="c8d29-108">A large number of changes takes longer.</span></span> <span data-ttu-id="c8d29-109">Umowa dotycząca poziomu usług (SLA) określa, że zmiana dotycząca użytkownika w katalogu usługi SharePoint Online będzie odzwierciedlana w aplikacji profilu użytkownika w ciągu 24 godzin.</span><span class="sxs-lookup"><span data-stu-id="c8d29-109">The Service Level Agreement (SLA) states that a change to a user in the SharePoint Online Directory will be reflected in the User Profile Application in 24 hours.</span></span> 
  
[<span data-ttu-id="c8d29-110">Więcej informacji na temat synchronizacji profilu użytkownika w usłudze SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="c8d29-110">More info about user profile sync in SharePoint Online</span></span>](https://go.microsoft.com/fwlink/?linkid=875671)
  

