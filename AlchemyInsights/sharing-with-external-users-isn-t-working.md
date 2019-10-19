---
title: Udostępnianie użytkownikom zewnętrznym nie działa
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 5/18/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: d4c8fc75ff8db2319b88a20bea9b3ee661f2e36e
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 10/18/2019
ms.locfileid: "36502241"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a><span data-ttu-id="9e063-102">Rozwiązywanie problemów z udostępnianiem zawartości programu SharePoint użytkownikom zewnętrznym</span><span class="sxs-lookup"><span data-stu-id="9e063-102">Fix problems sharing SharePoint content with external users</span></span>

<span data-ttu-id="9e063-103">Upewnij się, że w organizacji jest włączone udostępnianie zewnętrzne:</span><span class="sxs-lookup"><span data-stu-id="9e063-103">Make sure external sharing is turned on for your organization:</span></span>
  
1. <span data-ttu-id="9e063-104">Przejdź do [strony dodatków &amp; usług w centrum administracyjnym Microsoft 365](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns)i kliknij przycisk **witryny**.</span><span class="sxs-lookup"><span data-stu-id="9e063-104">Go to the [Services &amp; add-ins page in the Microsoft 365 admin center](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), and click **Sites**.</span></span>
    
2. <span data-ttu-id="9e063-105">Upewnij się, że ustawienie jest włączone.</span><span class="sxs-lookup"><span data-stu-id="9e063-105">Make sure the setting is turned to "On."</span></span> <span data-ttu-id="9e063-106">Jeśli wybrano "tylko istniejący użytkownicy zewnętrzni", upewnij się, że użytkownik zewnętrzny jest wymieniony w centrum administracyjnym Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="9e063-106">If "Only existing external users" is selected, make sure the external user is listed in the Microsoft 365 admin center.</span></span>
    
<span data-ttu-id="9e063-107">Upewnij się, że udostępnianie zewnętrzne jest włączone dla witryny.</span><span class="sxs-lookup"><span data-stu-id="9e063-107">Make sure external sharing it turned on for the site.</span></span> <span data-ttu-id="9e063-108">Dla klasycznego zbioru witryn:</span><span class="sxs-lookup"><span data-stu-id="9e063-108">For a classic site collection:</span></span>
  
1. <span data-ttu-id="9e063-109">W nowym centrum administracyjnym programu SharePoint w lewym okienku kliknij pozycję **witryny**.</span><span class="sxs-lookup"><span data-stu-id="9e063-109">In the new SharePoint admin center, in the left pane, click **sites**.</span></span>
    
2. <span data-ttu-id="9e063-110">Wybierz witrynę lub witryny, a na wstążce kliknij przycisk **udostępnianie**.</span><span class="sxs-lookup"><span data-stu-id="9e063-110">Select the site or sites, and on the ribbon, click **Sharing**.</span></span>
    
<span data-ttu-id="9e063-111">W przypadku witryny zespołu należącej do grupy 365 pakietu Office lub witryny komunikacyjnej:</span><span class="sxs-lookup"><span data-stu-id="9e063-111">For a team site that belongs to an Office 365 group, or a communication site:</span></span>
  
- <span data-ttu-id="9e063-112">Te nowe typy witryn mają takie samo ustawienie udostępniania jak ustawienia dla całej organizacji, chyba że ustawienie dla całej organizacji umożliwia udostępnianie plików za pomocą łączy, które nie wymagają logowania.</span><span class="sxs-lookup"><span data-stu-id="9e063-112">These new site types have the same sharing setting as your organization-wide setting, unless the organization-wide setting allows sharing files using links that don't require sign-in.</span></span> <span data-ttu-id="9e063-113">W takim przypadku witryny umożliwiają udostępnianie nowym i istniejącym użytkownikom zewnętrznym, którzy się zalogują.</span><span class="sxs-lookup"><span data-stu-id="9e063-113">In this case, the sites allow sharing with new and existing external users who sign in.</span></span> <span data-ttu-id="9e063-114">Aby zmienić ustawienie dla określonych witryn, należy użyć nowego centrum administracyjnego programu SharePoint lub programu PowerShell.</span><span class="sxs-lookup"><span data-stu-id="9e063-114">To change the setting for specific sites, use the new SharePoint admin center or PowerShell.</span></span> <span data-ttu-id="9e063-115">[Dowiedz się więcej](https://go.microsoft.com/fwlink/?linkid=871863).</span><span class="sxs-lookup"><span data-stu-id="9e063-115">[Learn more](https://go.microsoft.com/fwlink/?linkid=871863).</span></span>
    
> [!NOTE]
> <span data-ttu-id="9e063-116">Ustawienie udostępniania zewnętrznego dla dowolnej witryny może być bardziej restrykcyjne niż ustawienie dla całej organizacji, ale nie jest to więcej niż ustawienie dla całej organizacji.</span><span class="sxs-lookup"><span data-stu-id="9e063-116">The external sharing setting for any site can be more restrictive than your organization-wide setting, but not more permissive than the organization-wide setting.</span></span> 
  

