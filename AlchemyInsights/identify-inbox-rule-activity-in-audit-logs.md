---
title: Określenie działania reguł skrzynki odbiorczej w dziennikach inspekcji
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1368
ms.assetid: ''
ms.openlocfilehash: 9339d9c58056f568dc994b75bffe39f2c8bbdd34
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 04/23/2019
ms.locfileid: "32417256"
---
# <a name="identify-inbox-rule-activity-in-audit-logs"></a><span data-ttu-id="8099f-102">Określenie działania reguł skrzynki odbiorczej w dziennikach inspekcji</span><span class="sxs-lookup"><span data-stu-id="8099f-102">Identify inbox rule activity in audit logs</span></span>

<span data-ttu-id="8099f-103">Przeszukiwanie dziennika inspekcji w & zabezpieczeń Centrum zgodności służy do przeglądania zdarzeń reguły skrzynki odbiorczej (Tworzenie, modyfikowanie i usuwanie reguł skrzynki odbiorczej).</span><span class="sxs-lookup"><span data-stu-id="8099f-103">You can use audit log search in the Security & Compliance Center to view inbox rule events (creating, modifying, and deleting inbox rules).</span></span>

1. <span data-ttu-id="8099f-104">Zaloguj się do [Centrum zgodności Office 365 zabezpieczeń &](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="8099f-104">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="8099f-105">Kliknij przycisk **Wyszukaj i dochodzenia** i wybierz **Przeszukiwania dzienników inspekcji**.</span><span class="sxs-lookup"><span data-stu-id="8099f-105">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

3. <span data-ttu-id="8099f-106">Wybierz zakres dat w polach **Data początkowa** i **Data końcowa** .</span><span class="sxs-lookup"><span data-stu-id="8099f-106">Select the date range in the **Start date** and **End date** fields.</span></span>

4. <span data-ttu-id="8099f-107">W obszarze **Działania skrzynki pocztowej programu Exchange**, sprawdź pole **działania** jest ustawiona na **Create New-InboxRule/Modyfikuj/Włącz/Wyłącz reguły skrzynki odbiorczej**.</span><span class="sxs-lookup"><span data-stu-id="8099f-107">Under **Exchange Mailbox Activities**, verify the **Activities** field is set to **New-InboxRule Create/modify/enable/disable inbox rule**.</span></span>

5. <span data-ttu-id="8099f-108">Kliknij przycisk **Wyszukaj**.</span><span class="sxs-lookup"><span data-stu-id="8099f-108">Click **Search**.</span></span>

<span data-ttu-id="8099f-109">W wynikach wybierz rekord audytu.</span><span class="sxs-lookup"><span data-stu-id="8099f-109">In the results, select an audit record.</span></span> <span data-ttu-id="8099f-110">W menu wysuwane Szczegóły kliknij przycisk **Więcej informacji**.</span><span class="sxs-lookup"><span data-stu-id="8099f-110">In the details flyout, click **More Information**.</span></span> <span data-ttu-id="8099f-111">Informacje o ustawieniach reguł skrzynki odbiorczej jest wyświetlana w polu **Parametry** .</span><span class="sxs-lookup"><span data-stu-id="8099f-111">Information about the inbox rule settings is displayed in the **Parameters** field.</span></span>

<span data-ttu-id="8099f-112">Aby uzyskać więcej informacji zobacz [Określanie, czy użytkownik utworzył regułę skrzynki odbiorczej](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)</span><span class="sxs-lookup"><span data-stu-id="8099f-112">For more information, see [Determining if a user created an inbox rule](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)</span></span>