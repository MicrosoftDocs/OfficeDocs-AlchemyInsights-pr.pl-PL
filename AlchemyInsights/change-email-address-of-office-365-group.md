---
title: Zmienianie adresu e-mail grupy usługi Microsoft 365
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "4704"
ms.openlocfilehash: 32968f085a4e9d49f60ef88e4e78bf6c67629556
ms.sourcegitcommit: f28dafa0f727870038f72bc904da926daf4ec07b
ms.translationtype: HT
ms.contentlocale: pl-PL
ms.lasthandoff: 06/05/2020
ms.locfileid: "44580667"
---
# <a name="change-email-address-of-a-microsoft-365-group"></a>Zmienianie adresu e-mail grupy usługi Microsoft 365

Adres e-mail grupy usługi Microsoft 365 można zmienić za pomocą centrum administracyjnego. Wystarczy wybrać grupę i wybrać @edit adres e-mail.

Można również użyć następującego polecenia EXO PowerShell, aby zmienić podstawowy adres SMTP grupy microsoft 365:

Set-UnifiedGroup <Group Name> -PrimarySmtpAddress<new SMTP Address>

Przykład:

```
    Set-UnifiedGroup Marketing -PrimarySmtpAddress marketing@contoso.com
```
