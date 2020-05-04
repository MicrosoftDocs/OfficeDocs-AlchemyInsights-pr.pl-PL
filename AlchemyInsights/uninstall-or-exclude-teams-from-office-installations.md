---
title: Odinstalowywanie lub wykluczanie aplikacji Teams z instalacji pakietu Office
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2662"
- "9000660"
ms.openlocfilehash: b6613733e743e08a9b18b1ada70fde164b0d5dc3
ms.sourcegitcommit: 7e06d9ec1dd462cbd882f088c997d012a032f04d
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 05/04/2020
ms.locfileid: "44010309"
---
# <a name="uninstall-or-exclude-teams-from-new-or-existing-office-installations"></a><span data-ttu-id="ab0a9-102">Odinstalowywanie lub wykluczanie aplikacji Teams z nowych lub istniejących instalacji pakietu Office</span><span class="sxs-lookup"><span data-stu-id="ab0a9-102">Uninstall or exclude Teams from new or existing Office installations</span></span>

<span data-ttu-id="ab0a9-103">Usługa Microsoft Teams jest częścią usługi Microsoft 365 Apps dla przedsiębiorstw, aplikacji Microsoft 365 dla firm i pakietu Office dla komputerów Mac.</span><span class="sxs-lookup"><span data-stu-id="ab0a9-103">Microsoft Teams is included as part of Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and Office for Mac.</span></span>

- <span data-ttu-id="ab0a9-104">Narzędzie [wdrażania pakietu Office](https://docs.microsoft.com/deployoffice/teams-install#how-to-exclude-microsoft-teams-from-new-installations-of-microsoft-365-apps) umożliwia wykluczenie zespołów z nowych instalacji pakietu Office.</span><span class="sxs-lookup"><span data-stu-id="ab0a9-104">Use the [Office Deployment Tool](https://docs.microsoft.com/deployoffice/teams-install#how-to-exclude-microsoft-teams-from-new-installations-of-microsoft-365-apps) to exclude Teams from new installations of Office.</span></span>
- <span data-ttu-id="ab0a9-105">Aby *odinstalować* usługi Teams z urządzenia z systemem Windows, zobacz [Odinstalowywanie usługi Microsoft Teams](https://support.office.com/article/3b159754-3c26-4952-abe7-57d27f5f4c81).</span><span class="sxs-lookup"><span data-stu-id="ab0a9-105">To *uninstall* Teams from a device running Windows, see [Uninstall Microsoft Teams](https://support.office.com/article/3b159754-3c26-4952-abe7-57d27f5f4c81).</span></span> <span data-ttu-id="ab0a9-106">Aby oczyścić usługę Microsoft Teams z wielu komputerów docelowych lub użytkowników, zobacz [Oczyszczanie wdrażania usługi Microsoft Teams](https://docs.microsoft.com/microsoftteams/scripts/powershell-script-teams-deployment-clean-up).</span><span class="sxs-lookup"><span data-stu-id="ab0a9-106">To clean up Microsoft Teams from multiple target machines or users, see [Microsoft Teams deployment clean up](https://docs.microsoft.com/microsoftteams/scripts/powershell-script-teams-deployment-clean-up).</span></span>
- <span data-ttu-id="ab0a9-107">Użyj opcji [PreventTeamsInstall,](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-control-the-installation-of-microsoft-teams
) aby uniemożliwić automatyczne instalowanie usługi Microsoft Teams za pomocą pakietu Office.</span><span class="sxs-lookup"><span data-stu-id="ab0a9-107">Use the [PreventTeamsInstall](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-control-the-installation-of-microsoft-teams
) option to prevent Microsoft Teams from installing automatically with Office.</span></span>
- <span data-ttu-id="ab0a9-108">Użyj opcji [PreventFirstLaunchAfterInstall](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-prevent-microsoft-teams-from-starting-automatically-after-installation) *przed zainstalowaniem programu Teams,* aby zapobiec automatycznemu uruchamianiu usługi Microsoft Teams po instalacji.</span><span class="sxs-lookup"><span data-stu-id="ab0a9-108">Use the [PreventFirstLaunchAfterInstall](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-prevent-microsoft-teams-from-starting-automatically-after-installation) option, *before Teams is installed*, to prevent Microsoft Teams from starting automatically after installation.</span></span>

<span data-ttu-id="ab0a9-109">Jeśli korzystasz z pakietu Office dla komputerów Mac, zobacz [Instalacje usługi Microsoft Teams na komputerze Mac](https://docs.microsoft.com/deployoffice/teams-install#microsoft-teams-installations-on-a-mac).</span><span class="sxs-lookup"><span data-stu-id="ab0a9-109">If you're using Office for Mac, see [Microsoft Teams installations on a Mac](https://docs.microsoft.com/deployoffice/teams-install#microsoft-teams-installations-on-a-mac).</span></span>