---
title: Wychodząca wiadomość e-mail do folderu wiadomości-śmieci
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2697"
ms.assetid: ''
ms.openlocfilehash: 7e6f8d1a161d3eee398230750cc98a46579a56b1
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 09/15/2020
ms.locfileid: "47769193"
---
# <a name="outbound-email-to-junk-email-folder"></a><span data-ttu-id="cb6ad-102">Wychodząca wiadomość e-mail do folderu wiadomości-śmieci</span><span class="sxs-lookup"><span data-stu-id="cb6ad-102">Outbound email to Junk Email folder</span></span>

<span data-ttu-id="cb6ad-103">Jeśli widzisz wiadomości wychodzące oznaczone jako wiadomości-śmieci, wykonaj następujące czynności:</span><span class="sxs-lookup"><span data-stu-id="cb6ad-103">If you're seeing outbound messages being marked as Junk, do the following steps:</span></span>

- <span data-ttu-id="cb6ad-104">Jeśli jeszcze tego nie zrobiono, możesz [skonfigurować powiadomienia o zasadach dla wychodzących spamu](https://docs.microsoft.com/microsoft-365/security/office-365-security/configure-the-outbound-spam-policy).</span><span class="sxs-lookup"><span data-stu-id="cb6ad-104">If you haven't already, consider [configuring outbound spam policy notifications](https://docs.microsoft.com/microsoft-365/security/office-365-security/configure-the-outbound-spam-policy).</span></span>

- <span data-ttu-id="cb6ad-105">Użyj [funkcji śledzenia wiadomości](https://docs.microsoft.com/microsoft-365/security/office-365-security/message-trace-scc) , aby sprawdzić, czy wiadomość wychodząca zawiera wartość **spamu** z dodatkowymi szczegółami: **Użyj puli wysokiego ryzyka**.</span><span class="sxs-lookup"><span data-stu-id="cb6ad-105">Use [message trace](https://docs.microsoft.com/microsoft-365/security/office-365-security/message-trace-scc) to see if the outbound message has the event value **Spam** with the additional detail: **Use high risk delivery pool**.</span></span>

  <span data-ttu-id="cb6ad-106">W przypadku tych wiadomości sprawdź zawartość wiadomości, aby zobaczyć, co można uznać za spam.</span><span class="sxs-lookup"><span data-stu-id="cb6ad-106">For these messages, check the message content to see what might be considered spam.</span></span> <span data-ttu-id="cb6ad-107">Na przykład podpisy mogą czasami powodować problemy dla wielu użytkowników.</span><span class="sxs-lookup"><span data-stu-id="cb6ad-107">For example, signatures can sometimes cause problems for many users.</span></span>

  <span data-ttu-id="cb6ad-108">Jeśli masz wiele przykładów legalnych wiadomości wychodzących oznaczonych jako wiadomości-śmieci, Otwórz bilet pomocy technicznej i poproś o pomoc agenta pomocy technicznej o przesłanie wiadomości jako fałszywych wyników do analityków spamu.</span><span class="sxs-lookup"><span data-stu-id="cb6ad-108">If you have multiple examples of legitimate outbound messages that are being marked as Junk, open a support ticket and ask the support agent to submit your messages as false positives to our spam analysts.</span></span> <span data-ttu-id="cb6ad-109">Przygotuj się na dostarczenie przykładowych wiadomości zawierających wszystkie nagłówki wiadomości.</span><span class="sxs-lookup"><span data-stu-id="cb6ad-109">Be prepared to provide sample messages that include all message headers.</span></span>
