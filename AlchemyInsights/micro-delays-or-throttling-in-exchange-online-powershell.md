---
title: Mikroopóźnienia lub ograniczanie w programie PowerShell dla usługi Exchange Online
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3500011"
- "5106"
ms.openlocfilehash: 7ab4e7f18b7b8edf08098af8fe9674f66b1b81f4
ms.sourcegitcommit: fbaa2ce2cfb4d56d8c4cf2fa2d95489bdfcb7ff0
ms.translationtype: HT
ms.contentlocale: pl-PL
ms.lasthandoff: 04/30/2020
ms.locfileid: "43947904"
---
# <a name="micro-delays-or-throttling-in-exchange-online-powershell"></a>Mikroopóźnienia lub ograniczanie w programie PowerShell dla usługi Exchange Online

Podczas uruchamiania skryptów i poleceń cmdlet w usłudze Exchange Online mogą zostać wyświetlone ostrzeżenia „Zastosowano mikroopóźnienie” lub wystąpić opóźnienia. Oto dwie sugestie dotyczące tej kwestii:

- Być może zechcesz spróbować skorzystać z modułu [Exchange Online v2 PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps), który obsługuje polecenia CMDlet oparte na interfejsie API REST i znacznie bardziej wydajniej. Może to być dobre rozwiązanie w przypadku wielu często używanych poleceń CMDlet Get-.
- Jeśli musisz używać poleceń CMDlet, które nie są objęte modułem w wersji 2, zobacz [Uruchamianie poleceń cmdlet programu PowerShell dla dużej liczby użytkowników w usłudze Office 365](https://techcommunity.microsoft.com/t5/exchange-team-blog/updated-running-powershell-cmdlets-for-large-numbers-of-users-in/ba-p/1000628#), który zawiera informacje o tym, jak obejść oczekiwane limity ograniczania programu PowerShell dla usługi Exchange Online.
