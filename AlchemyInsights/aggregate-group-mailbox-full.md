---
title: AggregateGroupMailbox pełny raport NDR odebrany w przypadku wiadomości e-mail wysyłanych do grupy Microsoft 365
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 12/18/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004286"
- "7656"
ms.openlocfilehash: 9de09ab4cbd2f09648305b11da6273ed990907cf
ms.sourcegitcommit: 2ffdf6096de5608b117c6677d3cd7dd4c23ea024
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 12/18/2020
ms.locfileid: "49722085"
---
# <a name="aggregategroupmailbox-full-ndr-received-for-email-sent-to-microsoft-365-group"></a>AggregateGroupMailbox pełny raport NDR odebrany w przypadku wiadomości e-mail wysyłanych do grupy Microsoft 365

Użyj następującego polecenia powłoki EXO, aby utworzyć regułę transportu programu Exchange w celu cichego porzucania wiadomości e-mail wysyłanych do grupowej skrzynki pocztowej grupy:

`New-TransportRule -SentTo @("AggregateGroupMailbox.A.201708181918@contoso.onmicrosoft.com") -DeleteMessage:$true -Name 'Agg1' -StopRuleProcessing:$false -Mode 'Enforce' -Comments '' -RuleErrorAction 'Ignore' -SenderAddressLocation 'Header'`

> [!NOTE]
> Zamień adres SMTP in **-SentTo** na adres SMTP zagregowanej skrzynki pocztowej grupy w dzierżawie. Możesz uzyskać adres SMTP zagregowanej skrzynki pocztowej grupy z otrzymanego raportu o niedostarczeniu.



