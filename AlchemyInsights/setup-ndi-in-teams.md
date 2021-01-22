---
title: Włączanie technologii NDI
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
- "9004403"
- "7947"
ms.openlocfilehash: ea694898baffa50fca71957175eba3664dece44e
ms.sourcegitcommit: 112f18dce8257b98fab32d44910ee879efb44cb8
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 01/21/2021
ms.locfileid: "49935134"
---
# <a name="turn-on-ndi-technology"></a><span data-ttu-id="55366-102">Włączanie technologii NDI</span><span class="sxs-lookup"><span data-stu-id="55366-102">Turn on NDI technology</span></span>

<span data-ttu-id="55366-103">Technologia NDI wymaga, aby użytkownik włączył dwie czynności:</span><span class="sxs-lookup"><span data-stu-id="55366-103">NDI technology requires two steps to be turned on for a user:</span></span>

1. <span data-ttu-id="55366-104">Administrator dzierżawy musi włączyć właściwość "AllowNDIStreaming" w u administratora usługi CsTeamsMeetingPolicy.</span><span class="sxs-lookup"><span data-stu-id="55366-104">The tenant admin must enable the 'AllowNDIStreaming' property in CsTeamsMeetingPolicy.</span></span>

    `Set-CsTeamsMeetingPolicy -Identity MEETING_POLICY -AllowNDIStreaming $true`

2. <span data-ttu-id="55366-105">Po wpełnieniu tej zmiany użytkownik końcowy musi włączyć technologię NDI® dla swojego konkretnego klienta z poziomu ustawień **> uprawnień.**</span><span class="sxs-lookup"><span data-stu-id="55366-105">After this change has populated, the end user must turn on NDI® technology for their specific client from **Settings > Permissions**.</span></span>

<span data-ttu-id="55366-106">Aby uzyskać więcej informacji, zobacz [Korzystanie z technologii NDI w aplikacji Microsoft Teams.](https://docs.microsoft.com/microsoftteams/use-ndi-in-meetings)</span><span class="sxs-lookup"><span data-stu-id="55366-106">For more information, see [Use NDI technology in Microsoft Teams](https://docs.microsoft.com/microsoftteams/use-ndi-in-meetings).</span></span>
