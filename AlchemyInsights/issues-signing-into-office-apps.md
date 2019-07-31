---
title: Problemy z zalogowaniem się do aplikacji pakietu Office
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000571"
- "2559"
ms.openlocfilehash: 5f500ecf1f779fb1be4d257fd050a3ad054087dc
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938296"
---
# <a name="fixing-the-office-apps-your-computers-trusted-platform-module-is-not-functioning-properly-message"></a><span data-ttu-id="a2175-102">Ustalania komunikat "moduł zaufanej platformy komputera nie działa poprawnie" aplikacje pakietu Office</span><span class="sxs-lookup"><span data-stu-id="a2175-102">Fixing the Office apps "Your computer's Trusted Platform module is not functioning properly" message</span></span>

<span data-ttu-id="a2175-103">Aby naprawić ten błąd, spróbuj wykonać następujące czynności:</span><span class="sxs-lookup"><span data-stu-id="a2175-103">To fix this error, try the following:</span></span>

- <span data-ttu-id="a2175-104">Zainstaluj najnowsze aktualizacje dla [systemu Windows](https://support.microsoft.com/help/4027667/windows-10-update) i [pakietu Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span><span class="sxs-lookup"><span data-stu-id="a2175-104">Install the latest updates for [Windows](https://support.microsoft.com/help/4027667/windows-10-update) and [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span></span>
- <span data-ttu-id="a2175-105">[Wyczyść Office poświadczeń](https://docs.microsoft.com/eoffice/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) przy użyciu Menedżera poświadczeń systemu Windows.</span><span class="sxs-lookup"><span data-stu-id="a2175-105">[Clear Office credentials](https://docs.microsoft.com/eoffice/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="a2175-106">**Uwaga:** Ścieżki rejestru dla pakietu Office 2016 zostały zmienione na 16,0.</span><span class="sxs-lookup"><span data-stu-id="a2175-106">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="a2175-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span><span class="sxs-lookup"><span data-stu-id="a2175-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>
- <span data-ttu-id="a2175-108">Spróbuj [proces odzyskiwania użytkownika](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-2) do naprawienia błędów moduł zaufanej platformy (TPM).</span><span class="sxs-lookup"><span data-stu-id="a2175-108">Try the [user recovery process](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-2) to fix Trusted Platform Module (TPM) failures.</span></span>
- <span data-ttu-id="a2175-109">Ustaw EnableADAL = 0, wykonując następujące czynności:</span><span class="sxs-lookup"><span data-stu-id="a2175-109">Set the EnableADAL = 0 using the following steps:</span></span>  
    1. <span data-ttu-id="a2175-110">Kliknij prawym przyciskiem myszy przycisk Start systemu Windows, wybierz polecenie **Uruchom**, wpisz **polecenie regedit**, a następnie wybierz **OK**.</span><span class="sxs-lookup"><span data-stu-id="a2175-110">Right-click the Windows Start button, choose **Run**, type **regedit**, and then choose **OK**.</span></span>
    2. <span data-ttu-id="a2175-111">Wybierz opcję **Tak,** aby umożliwić Edytora rejestru, aby wprowadzić zmiany do urządzenia.</span><span class="sxs-lookup"><span data-stu-id="a2175-111">Select **Yes** to allow Registry Editor to make changes to your device.</span></span>
    3. <span data-ttu-id="a2175-112">W Edytorze rejestru dodać wartość DWORD **EnableADAL** z ustawieniem **0** w obszarze HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity.</span><span class="sxs-lookup"><span data-stu-id="a2175-112">In Registry Editor, add a DWORD value of **EnableADAL** with a setting of **0** under HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity.</span></span>

<span data-ttu-id="a2175-113">Aby uzyskać więcej informacji zobacz [w logowanie po aktualizacji do pakietu Office 2016 build 16.0.7967 w systemie Windows 10 problemy z połączeniem](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span><span class="sxs-lookup"><span data-stu-id="a2175-113">For more information, see [Connection issues in sign-in after update to Office 2016 build 16.0.7967 on Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span></span>