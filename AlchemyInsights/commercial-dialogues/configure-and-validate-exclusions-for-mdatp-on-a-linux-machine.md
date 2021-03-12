---
title: Konfigurowanie i weryfikowanie wykluczeń MDATP na komputerze z systemem Linux
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000760"
- "7391"
ms.openlocfilehash: 4fad0a513f7c6d2f0337019488a4055c25e1650d
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 03/11/2021
ms.locfileid: "50749253"
---
# <a name="configure-and-validate-exclusions-for-mdatp-on-a-linux-machine"></a><span data-ttu-id="cba41-102">Konfigurowanie i weryfikowanie wykluczeń MDATP na komputerze z systemem Linux</span><span class="sxs-lookup"><span data-stu-id="cba41-102">Configure and validate exclusions for MDATP on a Linux machine</span></span>

<span data-ttu-id="cba41-103">W skanach MDATP możesz wykluczyć określone pliki, foldery, procesy oraz pliki otwarte w procesie.</span><span class="sxs-lookup"><span data-stu-id="cba41-103">You can exclude certain files, folders, processes, and process-opened files from MDATP scans.</span></span> <span data-ttu-id="cba41-104">Wykluczenia pomagają zapobiec niepoprawnemu wykrywaniu oprogramowania i plików unikatowych lub dostosowanych do potrzeb organizacji.</span><span class="sxs-lookup"><span data-stu-id="cba41-104">Exclusions help prevent incorrect detection of software and files unique or customized to your organization.</span></span> <span data-ttu-id="cba41-105">Wykluczenia ułatwiają również ograniczanie problemów z wydajnością spowodowanych przez usługę MDATP.</span><span class="sxs-lookup"><span data-stu-id="cba41-105">Exclusions also help mitigate performance problems caused by MDATP.</span></span>

<span data-ttu-id="cba41-106">Aby dowiedzieć się więcej, zobacz [Konfigurowanie i weryfikowanie wykluczeń usługi MDATP dla systemu Linux.](https://go.microsoft.com/fwlink/?linkid=2144517)</span><span class="sxs-lookup"><span data-stu-id="cba41-106">To learn more, see [Configure and validate exclusions for MDATP for Linux](https://go.microsoft.com/fwlink/?linkid=2144517).</span></span>

> [!IMPORTANT]
> <span data-ttu-id="cba41-107">Wykluczenia opisane w tym artykule nie dotyczą innych funkcji MDATP dla systemu Linux, w tym wykrywania punktu końcowego i odpowiedzi (EDR).</span><span class="sxs-lookup"><span data-stu-id="cba41-107">The exclusions described in this article don't apply to other capabilities of MDATP for Linux, including endpoint detection and response (EDR).</span></span> <span data-ttu-id="cba41-108">Pliki wykluczone przy użyciu metod opisanych w tym artykule nadal mogą wyzwalać alerty funkcji EDR i inne funkcje wykrywania.</span><span class="sxs-lookup"><span data-stu-id="cba41-108">Files that you exclude by using the methods described in this article can still trigger EDR alerts and other detection capabilities.</span></span>
