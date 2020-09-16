---
title: Uprawnienia do kalendarza
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3800009"
- "611"
ms.openlocfilehash: cfee520e26587c0a649c08084853c31232d027f8
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 09/14/2020
ms.locfileid: "47748803"
---
# <a name="calendar-permissions"></a>Uprawnienia do kalendarza

Użytkownicy mogą zmieniać swoje uprawnienia do kalendarza w programie Outlook w sieci Web lub innych klientach, ale jako administrator może być konieczne zbadanie również tych uprawnień.  
W przypadku polecenia cmdlet programu Exchange PowerShell są wyświetlane uprawnienia do kalendarza użytkownika:

`Get-MailboxFolderPermission <SMTPAddress>:\Calendar | FT -a`

Aby uzyskać więcej informacji, zobacz następujące tematy:

- [Get-MailboxFolderPermission](https://docs.microsoft.com/powershell/module/exchange/get-mailboxfolderpermission?view=exchange-ps)

- [Set-MailboxFolderPermission](https://docs.microsoft.com/powershell/module/exchange/set-mailboxfolderpermission?view=exchange-ps)

- [Dodaj-MailboxFolderPermission](https://office.visualstudio.com/DefaultCollection/MAX/_queries/query/Add-MailboxFolderPermission)

Uprawnienia do kalendarza są używane w przypadku udostępniania kalendarzy Aby uzyskać więcej informacji na temat udostępniania kalendarza programu Outlook, zobacz następujące artykuły:

- [Udostępnianie kalendarza programu Outlook innym osobom](https://support.office.com/article/353ed2c1-3ec5-449d-8c73-6931a0adab88)
- [Udostępnianie kalendarza w aplikacji Outlook w sieci Web dla firm](https://support.office.com/article/7ecef8ae-139c-40d9-bae2-a23977ee58d5)

Aby rozwiązać problem z uprawnieniem do kalendarza, możesz użyć narzędzia [Asystent odzyskiwania i pomocy technicznej](https://support.microsoft.com/office/e90bb691-c2a7-4697-a94f-88836856c72f) .