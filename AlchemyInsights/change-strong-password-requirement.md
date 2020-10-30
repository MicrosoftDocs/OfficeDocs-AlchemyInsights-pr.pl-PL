---
title: Zmienianie wymagania silnego hasła
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
- "9000105"
- "1600"
ms.openlocfilehash: 8ce331275e066b5a4f177ae27178ec726f90762f
ms.sourcegitcommit: aa35d2e1829f7d07f64fb891bf73b1fd80f0864c
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 10/30/2020
ms.locfileid: "48804433"
---
# <a name="change-strong-password-requirement"></a><span data-ttu-id="af3b3-102">Zmienianie wymagania silnego hasła</span><span class="sxs-lookup"><span data-stu-id="af3b3-102">Change strong password requirement</span></span>

<span data-ttu-id="af3b3-103">Firma Microsoft domyślnie wymaga silnych haseł.</span><span class="sxs-lookup"><span data-stu-id="af3b3-103">Microsoft requires strong passwords by default.</span></span>

<span data-ttu-id="af3b3-104">Za pomocą programu PowerShell możesz wyłączyć silne hasła dla określonych użytkowników za pomocą następujących poleceń:</span><span class="sxs-lookup"><span data-stu-id="af3b3-104">Using PowerShell, you can disable strong passwords for specific users with these commands:</span></span>

`Set-MsolUser –UserPrincipalName <UserPrincipalName> –StrongPasswordRequired  $false`

<span data-ttu-id="af3b3-105">Aby wyłączyć silne hasła dla wszystkich użytkowników, wykonaj następujące czynności:</span><span class="sxs-lookup"><span data-stu-id="af3b3-105">To disable strong passwords for all users, use:</span></span>

`Get-MsolUser | Set-MsolUser -StrongPasswordRequired $false`

- [<span data-ttu-id="af3b3-106">Więcej informacji na temat zasad haseł</span><span class="sxs-lookup"><span data-stu-id="af3b3-106">More information on password policy</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [<span data-ttu-id="af3b3-107">Jak nawiązać połączenie z programem Microsoft 365 za pomocą programu PowerShell</span><span class="sxs-lookup"><span data-stu-id="af3b3-107">How to connect to Microsoft 365 with PowerShell</span></span>](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [<span data-ttu-id="af3b3-108">Więcej informacji o poleceniach programu PowerShell MsolUser</span><span class="sxs-lookup"><span data-stu-id="af3b3-108">More information on PowerShell MsolUser commands</span></span>](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)
