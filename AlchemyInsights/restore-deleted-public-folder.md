---
title: Przywracanie usuniętego folderu publicznego
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3488"
ms.openlocfilehash: cd85dd3c0eb14f6e02ac4f912e733468403387aa
ms.sourcegitcommit: 2a9d059262c07c33f9a740b3da4e6e3366b2f925
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 02/20/2020
ms.locfileid: "42158529"
---
# <a name="restore-a-deleted-public-folder"></a>Przywracanie usuniętego folderu publicznego

**Aby przywrócić usunięte elementy z folderu publicznego:**

- Zobacz [Nie można odzyskać usuniętych elementów z folderu publicznego niebędącego pocztą w programie Outlook 2016](https://aka.ms/pfrec).
 
**Aby przywrócić usunięty folder publiczny (dowolnego typu):** 

- Użyj następującego polecenia EXO PowerShell:

    Składni:

     `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse  | ?{$_.Name -eq "\<name_of_deleted_public_Folder"};Set-PublicFolder $pf.identity -Path \<path where the folder will be restored>`

    Przykład: Następujące polecenie przywróci podfolder1 i umieści go w obszarze \Parent1:

    `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse | ?{$_.Name -eq "Subfolder1"};Set-PublicFolder $pf.identity -Path \Parent1`

Aby uzyskać więcej informacji, zobacz [Przywracanie usuniętego folderu publicznego.](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder)
