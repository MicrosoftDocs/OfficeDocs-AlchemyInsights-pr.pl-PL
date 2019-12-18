---
title: Wdrażanie pakietu Office 365 ProPlus do użytku udostępnionego na RDS, Terminal Server lub VDI
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 12/9/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001419"
- "3411"
ms.openlocfilehash: 2312cca9ebf5dad1322bc98335cef6a6bc81f03e
ms.sourcegitcommit: cbbd46fa9a32873c5446d9fd5a532cea0300b795
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 12/10/2019
ms.locfileid: "39959469"
---
# <a name="deploying-office-365-proplus-for-shared-use-on-rds-terminal-server-or-vdi"></a><span data-ttu-id="35fc2-102">Wdrażanie pakietu Office 365 ProPlus do użytku udostępnionego na RDS, Terminal Server lub VDI</span><span class="sxs-lookup"><span data-stu-id="35fc2-102">Deploying Office 365 ProPlus for shared use on RDS, Terminal Server, or VDI</span></span>

<span data-ttu-id="35fc2-103">Aby wdrożyć pakiet Office 365 ProPlus przy użyciu usług pulpitu zdalnego (RDS), dawniej nazwanych usług terminalowych:</span><span class="sxs-lookup"><span data-stu-id="35fc2-103">To deploy Office 365 ProPlus using Remote Desktop Services (RDS), formerly named Terminal Services:</span></span>
- <span data-ttu-id="35fc2-104">Musi mieć Microsoft 365 dla biznesplanu lub Office 365 plan, który zawiera Office 365 ProPlus, takich jak Office 365 Enterprise E3 lub Enterprise E5.</span><span class="sxs-lookup"><span data-stu-id="35fc2-104">You must have a Microsoft 365 For Business plan or an Office 365 plan that includes Office 365 ProPlus, such as Office 365 Enterprise E3 or Enterprise E5.</span></span>
   > [!NOTE] 
   > <span data-ttu-id="35fc2-105">Plany Office 365 Business i Office 365 Business Premium nie zawierają pakietu Office 365 ProPlus.</span><span class="sxs-lookup"><span data-stu-id="35fc2-105">The Office 365 Business and Office 365 Business Premium plans do not include Office 365 ProPlus.</span></span>
- <span data-ttu-id="35fc2-106">Należy włączyć [aktywację udostępnionego komputera](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span><span class="sxs-lookup"><span data-stu-id="35fc2-106">You must enable [shared computer activation](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span></span>

> [!NOTE]
> <span data-ttu-id="35fc2-107">Można również pobrać i uruchomić [Microsoft Support i Recovery Assistant](https://aka.ms/SaRA_OfficeSCA_M365Portal) do zainstalowania pakietu Office 365 ProPlus w trybie aktywacji komputera udostępnionego.</span><span class="sxs-lookup"><span data-stu-id="35fc2-107">You can also download and run the [Microsoft Support and Recovery Assistant](https://aka.ms/SaRA_OfficeSCA_M365Portal) to install Office 365 ProPlus in shared computer activation mode.</span></span>

<span data-ttu-id="35fc2-108">Aby uzyskać więcej informacji na temat wymagań wstępnych, instrukcje dotyczące instalacji i wskazówki dotyczące instalacji dostosowanych za pomocą narzędzia wdrażania pakietu Office, zobacz [wdrażanie pakietu office 365 ProPlus przy użyciu usług pulpitu zdalnego](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span><span class="sxs-lookup"><span data-stu-id="35fc2-108">For more information on prerequisites, setup instructions, and guidance on customized installations by using the Office Deployment Tool, see [Deploy Office 365 ProPlus by using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span></span>

<span data-ttu-id="35fc2-109">Aby naprawić błędy związane z aktywacją komputera udostępnionego:</span><span class="sxs-lookup"><span data-stu-id="35fc2-109">To fix errors related to shared computer activation:</span></span>
- <span data-ttu-id="35fc2-110">Zobacz [Rozwiązywanie problemów z aktywacją komputera udostępnionego dla pakietu Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span><span class="sxs-lookup"><span data-stu-id="35fc2-110">See [Troubleshoot issues with shared computer activation for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span></span>
- <span data-ttu-id="35fc2-111">Zobacz [resetowanie stanu aktywacji pakietu Office 365 ProPlus](https://go.microsoft.com/fwlink/?linkid=2109218).</span><span class="sxs-lookup"><span data-stu-id="35fc2-111">See [Reset Office 365 ProPlus activation state](https://go.microsoft.com/fwlink/?linkid=2109218).</span></span>

<span data-ttu-id="35fc2-112">Jeśli chcesz zainstalować pakiet Office 365 ProPlus na RDS z centrum administracyjnego Microsoft 365, ***które używa domyślnych ustawień instalacji***, wykonaj następujące czynności:</span><span class="sxs-lookup"><span data-stu-id="35fc2-112">If you want to install Office 365 ProPlus on RDS from the Microsoft 365 admin center, ***which uses default installation settings***, use the following steps:</span></span>

1.  <span data-ttu-id="35fc2-113">Sprawdź, co masz plan 365 Office.</span><span class="sxs-lookup"><span data-stu-id="35fc2-113">Check what Office 365 plan you have.</span></span> <span data-ttu-id="35fc2-114">[Dowiedz się, jak to zrobić](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have).</span><span class="sxs-lookup"><span data-stu-id="35fc2-114">[Learn how](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have).</span></span>
2.  <span data-ttu-id="35fc2-115">Jeśli to konieczne, przełącz się do innego pakietu Office 365 plan.</span><span class="sxs-lookup"><span data-stu-id="35fc2-115">If necessary, switch to a different Office 365 plan.</span></span> <span data-ttu-id="35fc2-116">[Dowiedz się, jak to zrobić](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan).</span><span class="sxs-lookup"><span data-stu-id="35fc2-116">[Learn how](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan).</span></span>
3.  <span data-ttu-id="35fc2-117">Jeśli pakiet Office jest już zainstalowany na serwerze usług pulpitu zdalnego przy użyciu innych planów pakietu Office 365, odinstaluj go.</span><span class="sxs-lookup"><span data-stu-id="35fc2-117">If Office is already installed on the RDS server using any other Office 365 plans, uninstall it.</span></span> <span data-ttu-id="35fc2-118">Na przykład, przechodząc do **panelu** > sterowania**Odinstaluj program**.</span><span class="sxs-lookup"><span data-stu-id="35fc2-118">For example, by going to **Control Panel** > **Uninstall a program**.</span></span> <span data-ttu-id="35fc2-119">Odinstaluj, korzystając z [pomocy technicznej firmy Microsoft i asystenta odzyskiwania](https://aka.ms/SARA-OfficeUninstall-Alchemy) , jeśli masz problemy z uruchamianiem.</span><span class="sxs-lookup"><span data-stu-id="35fc2-119">Uninstall using [Microsoft Support and Recovery Assistant](https://aka.ms/SARA-OfficeUninstall-Alchemy) if you're running into issues.</span></span>
4.  <span data-ttu-id="35fc2-120">Na serwerze RDS Zaloguj się do centrum administracyjnego Microsoft 365 z kontem administratora i [Zainstaluj pakiet Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span><span class="sxs-lookup"><span data-stu-id="35fc2-120">On the RDS server, sign in to the Microsoft 365 admin center with your administrator account and [install Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span></span>
5.  <span data-ttu-id="35fc2-121">Po zainstalowaniu pakietu Office ***nie otwieraj ani nie logujesz*** się do żadnych aplikacji pakietu Office.</span><span class="sxs-lookup"><span data-stu-id="35fc2-121">After Office is installed, ***don't open or sign in*** to any Office applications.</span></span>
6.  <span data-ttu-id="35fc2-122">Na serwerze usług pulpitu zdalnego Włącz aktywację udostępnionego komputera, edytując rejestr, wykonując następujące kroki:</span><span class="sxs-lookup"><span data-stu-id="35fc2-122">On the RDS server, enable shared computer activation by editing the registry by following these steps:</span></span>
   1. <span data-ttu-id="35fc2-123">Kliknij prawym przyciskiem myszy przycisk Windows znajdujący się w lewym dolnym rogu ekranu i wybierz polecenie **Uruchom**.</span><span class="sxs-lookup"><span data-stu-id="35fc2-123">Right-click the Windows button in the lower left-corner of your screen and select **Run**.</span></span> <span data-ttu-id="35fc2-124">W polu Otwórz wpisz **polecenie regedit**, a następnie wybierz **przycisk OK**.</span><span class="sxs-lookup"><span data-stu-id="35fc2-124">In the Open box, type **regedit**, and then select **OK**.</span></span>
   2. <span data-ttu-id="35fc2-125">Wybierz opcję **tak** po wyświetleniu monitu, aby zezwolić edytorowi rejestru na wprowadzanie zmian w urządzeniu.</span><span class="sxs-lookup"><span data-stu-id="35fc2-125">Select **Yes** when prompted to allow Registry Editor to make changes to your device.</span></span>
   3. <span data-ttu-id="35fc2-126">W Edytorze rejestru Dodaj wartość ciągu **Sharedcomputerlicensing** z ustawieniem 1 w obszarze HKEY_LOCAL_MACHINE \SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span><span class="sxs-lookup"><span data-stu-id="35fc2-126">In the Registry Editor, add a string value of **SharedComputerLicensing** with a setting of 1 under HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span></span>
   4. <span data-ttu-id="35fc2-127">Na serwerze usług pulpitu zdalnego ***Zaloguj się jako użytkownik końcowy*** i [Sprawdź, czy aktywacja udostępnionego komputera jest włączona dla pakietu Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span><span class="sxs-lookup"><span data-stu-id="35fc2-127">On the RDS server, ***sign in as an end user*** and [verify that shared computer activation is enabled for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span></span>
