---
title: Rozwiązywanie problemów z importowaniem pliku PST
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1800027"
- "1225"
ms.openlocfilehash: 58fdd509fae5e87bf5ae72db5d8926c4367cdd64
ms.sourcegitcommit: 87aa36e3ff4835efb120a320c5169bfa77199ec4
ms.translationtype: HT
ms.contentlocale: pl-PL
ms.lasthandoff: 05/01/2020
ms.locfileid: "43991375"
---
# <a name="troubleshooting-pst-import-issues"></a><span data-ttu-id="efcd5-102">Rozwiązywanie problemów z importowaniem pliku PST</span><span class="sxs-lookup"><span data-stu-id="efcd5-102">Troubleshooting PST import issues</span></span>

- <span data-ttu-id="efcd5-103">Jeśli importujesz bezpośrednio w kliencie programu Outlook, zobacz [Rozwiązywanie problemów z importowaniem pliku pst programu Outlook](https://support.office.com/article/Fix-problems-importing-an-Outlook-pst-file-2d2e50dc-5c36-4ab2-ab50-f1be733b3d6e).</span><span class="sxs-lookup"><span data-stu-id="efcd5-103">If you are importing within the Outlook client itself, please see [Fix problems importing an Outlook .pst file](https://support.office.com/article/Fix-problems-importing-an-Outlook-pst-file-2d2e50dc-5c36-4ab2-ab50-f1be733b3d6e).</span></span>

- <span data-ttu-id="efcd5-104">Jeśli używasz usługi importowania i usługa ta zatrzymuje się, pamiętaj, że rozmiar każdego pliku PST przekazywanego do lokalizacji usługi Azure Storage nie powinien być większy niż 20 GB.</span><span class="sxs-lookup"><span data-stu-id="efcd5-104">If you are using Import Service and it is stuck, please note that each PST file that you upload to the Azure Storage location should be no larger than 20 GB.</span></span> <span data-ttu-id="efcd5-105">Pliki PST, których rozmiar jest większy niż 20 GB mogą wpływać na poprawność działania procesu importowania pliku PST.</span><span class="sxs-lookup"><span data-stu-id="efcd5-105">PST files larger than 20 GB may impact the performance of the PST import process.</span></span>

- <span data-ttu-id="efcd5-106">Jeśli chcesz sprawdzić stan określonego zadania importu, możesz użyć [Get-MailboxImportRequest-batchname](https://docs.microsoft.com/powershell/module/exchange/mailboxes/get-mailboximportrequest).</span><span class="sxs-lookup"><span data-stu-id="efcd5-106">If you want to verify the status of a specific Import job, you can use [Get-MailboxImportRequest -batchname](https://docs.microsoft.com/powershell/module/exchange/mailboxes/get-mailboximportrequest).</span></span>

- <span data-ttu-id="efcd5-107">Aby uzyskać szczegółowe informacje o usłudze importowania, zobacz [Omówienie importowania plików PST organizacji](https://docs.microsoft.com/microsoft-365/compliance/importing-pst-files-to-office-365?view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="efcd5-107">For full details on the import service, please see [Overview of importing your organization's PST files](https://docs.microsoft.com/microsoft-365/compliance/importing-pst-files-to-office-365?view=o365-worldwide).</span></span>