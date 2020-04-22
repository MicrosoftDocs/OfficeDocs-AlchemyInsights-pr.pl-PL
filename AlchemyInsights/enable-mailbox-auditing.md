---
title: Włączanie inspekcji skrzynek pocztowych
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: ae11d6be0789a5662d202b85268480a3d42922c4
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 04/22/2020
ms.locfileid: "43703581"
---
# <a name="enable-mailbox-auditing"></a><span data-ttu-id="75c32-102">Włączanie inspekcji skrzynek pocztowych</span><span class="sxs-lookup"><span data-stu-id="75c32-102">Enable mailbox auditing</span></span>

<span data-ttu-id="75c32-103">Aby włączyć inspekcję skrzynek pocztowych dla pojedynczego użytkownika lub całej organizacji, należy uruchomić następujące polecenia cmdlet z powłoki zdalnej zasilania:</span><span class="sxs-lookup"><span data-stu-id="75c32-103">To enable Mailbox Auditing for either a single user or an entire organization the following cmdlets must be run from Remote Power Shell:</span></span>
  
 <span data-ttu-id="75c32-104">**Pojedynczy użytkownik**</span><span class="sxs-lookup"><span data-stu-id="75c32-104">**Single User**</span></span>
  
<span data-ttu-id="75c32-105">Set-Mailbox -Tożsamość "Jane Dow" -AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="75c32-105">Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true</span></span>
  
 <span data-ttu-id="75c32-106">**Organizacji**</span><span class="sxs-lookup"><span data-stu-id="75c32-106">**Organization**</span></span>
  
<span data-ttu-id="75c32-107">Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Skrzynka pocztowa -AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="75c32-107">Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span></span>
  
[<span data-ttu-id="75c32-108">Dowiedz się więcej</span><span class="sxs-lookup"><span data-stu-id="75c32-108">Learn more</span></span>](https://docs.microsoft.com/office365/securitycompliance/enable-mailbox-auditing)
  

