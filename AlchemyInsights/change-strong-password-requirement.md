---
title: Wymaganie silnego hasła zmiany
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000105"
- "1600"
ms.openlocfilehash: 53affd2a347c004e7b21b353c2b3df98bc30a585
ms.sourcegitcommit: a7e5ca472000dfec471950bafd12eee8d7144f74
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 07/16/2019
ms.locfileid: "35701593"
---
# <a name="change-strong-password-requirement"></a>Wymaganie silnego hasła zmiany

Silne hasła są domyślnie wymagane. 

Przy użyciu programu PowerShell można wyłączyć silnych haseł dla określonych użytkowników, przy użyciu tego polecenia:<br>
*Cmdlettogether — UserPrincipalName <UserPrincipalName> -StrongPasswordRequired $false*

- [Więcej informacji na temat zasad haseł](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [Jak połączyć się O365 przy użyciu programu PowerShell](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [Więcej informacji na temat poleceń programu PowerShell MsolUser](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)