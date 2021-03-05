---
title: Informacje Exchange Server aktualizacji zabezpieczeń
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 03/04/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9005482"
- "9005483"
- "9413"
- "9412"
ms.openlocfilehash: 87a5cf1ac4dfb96a5406f6b1431adb6ead074fd6
ms.sourcegitcommit: 6741a997fff871d263f92d3ff7fb61e7755956a9
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 03/04/2021
ms.locfileid: "50481948"
---
# <a name="about-exchange-server-security-updates"></a><span data-ttu-id="defef-102">Informacje Exchange Server aktualizacji zabezpieczeń</span><span class="sxs-lookup"><span data-stu-id="defef-102">About Exchange Server Security updates</span></span>

<span data-ttu-id="defef-103">Firma Microsoft wydała serię krytycznych aktualizacji zabezpieczeń dla Exchange Server lokalnych.</span><span class="sxs-lookup"><span data-stu-id="defef-103">Microsoft has released a series of critical security updates for Exchange Server on-premises.</span></span> <span data-ttu-id="defef-104">Wersje serwerów, których dotyczy problem, to wszelkie poziomy aktualizacji Exchange Server 2010, 2013, 2016 i 2019.</span><span class="sxs-lookup"><span data-stu-id="defef-104">The affected server versions are any update levels of Exchange Server 2010, 2013, 2016 and 2019.</span></span> <span data-ttu-id="defef-105">Nie ma to wpływu na usługę Exchange Online, ale jeśli masz niektóre lokalne serwery programu Exchange z powodu konfiguracji hybrydowej, są one potencjalnie narażone.</span><span class="sxs-lookup"><span data-stu-id="defef-105">Exchange Online is NOT impacted, but if you have some on-premises Exchange servers due to Hybrid configuration, they are potentially vulnerable.</span></span>

<span data-ttu-id="defef-106">Aby zaktualizować serwery lokalne, muszą być uruchomione co najmniej następujące wersje programu Exchange:</span><span class="sxs-lookup"><span data-stu-id="defef-106">To update your on-premises servers will have to be running at least the following versions of Exchange:</span></span>

- <span data-ttu-id="defef-107">Exchange 2010 z dodatkiem Service Pack 3</span><span class="sxs-lookup"><span data-stu-id="defef-107">Exchange 2010 Service Pack 3</span></span>
- <span data-ttu-id="defef-108">Exchange Server 2013 CU 23</span><span class="sxs-lookup"><span data-stu-id="defef-108">Exchange Server 2013 CU 23</span></span>
- <span data-ttu-id="defef-109">Exchange Server 2016 CU 19 lub CU 18</span><span class="sxs-lookup"><span data-stu-id="defef-109">Exchange Server 2016 CU 19 or CU 18</span></span>
- <span data-ttu-id="defef-110">Exchange Server 2019 CU 8 lub CU 7</span><span class="sxs-lookup"><span data-stu-id="defef-110">Exchange Server 2019 CU 8 or CU 7</span></span>

<span data-ttu-id="defef-111">Zobacz poniższe ogłoszenie dotyczące lokalizacji poprawek: Wydano: marzec [2021](https://techcommunity.microsoft.com/t5/exchange-team-blog/released-march-2021-exchange-server-security-updates/ba-p/2175901) r. Exchange Server aktualizacji zabezpieczeń</span><span class="sxs-lookup"><span data-stu-id="defef-111">Please see the following announcement for location of fixes: [Released: March 2021 Exchange Server Security Updates](https://techcommunity.microsoft.com/t5/exchange-team-blog/released-march-2021-exchange-server-security-updates/ba-p/2175901)</span></span>

<span data-ttu-id="defef-112">**Ważne uwagi:**</span><span class="sxs-lookup"><span data-stu-id="defef-112">**Important notes:**</span></span>

<span data-ttu-id="defef-113">Instalacja aktualizacji nie będzie działać, jeśli na serwerach lokalnych nie są uruchomione wymagane wersje programu Exchange, zgodnie z listą powyżej.</span><span class="sxs-lookup"><span data-stu-id="defef-113">Installation of updates will not work if your on-premises servers are not running required Exchange versions, as per the above list.</span></span>

<span data-ttu-id="defef-114">W przypadku ręcznego instalowania aktualizacji zapoznaj się z sekcją "Znane problemy" artykułów z bazy wiedzy dotyczących aktualizacji, aby uzyskać ważne informacje.</span><span class="sxs-lookup"><span data-stu-id="defef-114">If installing updates manually, please read the "Known issues" section of update KB articles for important information.</span></span> <span data-ttu-id="defef-115">Aktualizacje zabezpieczeń MUSZĄ być uruchamiane z poziomu wiersza polecenia CMD/PowerShell z podwyższonym poziomem uprawnień!</span><span class="sxs-lookup"><span data-stu-id="defef-115">Security updates MUST be run from elevated CMD/PowerShell prompt!</span></span>
