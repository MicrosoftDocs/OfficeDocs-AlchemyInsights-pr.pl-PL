---
title: 1491-Search-not-Returning-expected-Results
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: ''
ms.openlocfilehash: 881a579d7098578452c994b7ac66fe22a1d90dc2
ms.sourcegitcommit: 5182c9a73641079be59740e4524434b2e8be613a
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 02/12/2019
ms.locfileid: "29964929"
---
# <a name="content-search-not-returning-expected-results"></a>Przeszukiwanie zawartości nie zwraca wyników oczekiwanych

Podczas uruchamiania wyszukiwania zawartości z & zabezpieczeń usługi Office 365 Centrum zgodności, może pojawić się nieoczekiwanych wyników. Należy wziąć pod uwagę następujące rzeczy, które mogą wpływać na wyniki wyszukiwania:

- **Lokalizacje zawartości i warunki wyszukiwania**: Upewnij się, wybraniu odpowiedniej lokalizacji zawartości i warunki wyszukiwania. Jeśli uruchomiono dużych wyszukiwania (z wielu lokalizacji), należy rozważyć rozdzielenie go na wielu wyszukiwań.

- **Częściowo indeksowanych elementów**: [częściowo indeksowanych elementów](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) ze skrzynek pocztowych są uwzględniane w wynikach wyszukiwania szacowany. Jednak częściowo indeksowane elementy z witryn programu SharePoint i OneDrive nie są uwzględniane podczas szacowania wyszukiwania.

- **Wyszukiwanie błędów**: podczas wyszukiwania dużą liczbę skrzynek pocztowych (ponad 100 000 skrzynek pocztowych), mogą wystąpić błędy wyszukiwania, z kodami błędów, takich jak CS008-009 i CS012-002). W takim przypadku ponów próbę wyszukiwania tylko dla lokalizacji zawartości nie powiodło się. Zobacz [Ten artykuł](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) , aby uzyskać więcej informacji.