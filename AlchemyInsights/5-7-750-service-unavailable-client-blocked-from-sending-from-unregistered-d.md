---
title: 1048 5.7.750 usługa jest niedostępna. Klient zablokowaną możliwość wysyłania z niezarejestrowanych domen
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 9/28/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 8cf6d70b-9a78-4f04-ac59-7ffcf44ffd22
ms.custom: 1048
ms.openlocfilehash: 9417fef2584e9b81a2ca71cbcc5e23ce093d94e8
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 06/07/2019
ms.locfileid: "34751713"
---
# <a name="57750-client-blocked-from-sending-from-unregistered-domain"></a><span data-ttu-id="4c2a2-103">5.7.750 klienta zablokowaną możliwość wysyłania z niezarejestrowanych domena</span><span class="sxs-lookup"><span data-stu-id="4c2a2-103">5.7.750 Client blocked from sending from unregistered domain</span></span>

<span data-ttu-id="4c2a2-104">Ten błąd występuje w przypadku dużej liczby wiadomości są wysyłane z domen, które nie są obsługiwane w usłudze Office 365 (dodawane jako zaakceptowane domeny i sprawdzone).</span><span class="sxs-lookup"><span data-stu-id="4c2a2-104">The error occurs when a large volume of messages are sent from domains that aren't provisioned in Office 365 (added as accepted domains and validated).</span></span>

<span data-ttu-id="4c2a2-105">Aby uniknąć tego błędu, można użyć łącznika przepływu poczty opartego na certyfikatach gdzie certyfikatu domena jest domeną obsługiwaną lub umożliwia obsługę wszystkich domen wysyłającego.</span><span class="sxs-lookup"><span data-stu-id="4c2a2-105">To avoid this error, you can use a certificate-based mail flow connector where the certificate's domain is a provisioned domain, or you can provision all sending domains.</span></span>
