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
ms.openlocfilehash: 2bcfb7cc174cd58b21e1bb0c82f0d7cdb25e2fdd
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506964"
---
# <a name="enable-mailbox-auditing"></a><span data-ttu-id="0da5d-102">Włączanie inspekcji skrzynek pocztowych</span><span class="sxs-lookup"><span data-stu-id="0da5d-102">Enable mailbox auditing</span></span>

<span data-ttu-id="0da5d-103">Aby włączyć inspekcję skrzynek pocztowych dla pojedynczego użytkownika lub całej organizacji, należy uruchomić następujące polecenia cmdlet z powłoki zdalnej zasilania:</span><span class="sxs-lookup"><span data-stu-id="0da5d-103">To enable Mailbox Auditing for either a single user or an entire organization the following cmdlets must be run from Remote Power Shell:</span></span>
  
 <span data-ttu-id="0da5d-104">**Pojedynczy użytkownik**</span><span class="sxs-lookup"><span data-stu-id="0da5d-104">**Single User**</span></span>
  
<span data-ttu-id="0da5d-105">Set-Mailbox -Tożsamość "Jane Dow" -AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="0da5d-105">Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true</span></span>
  
 <span data-ttu-id="0da5d-106">**Organizacji**</span><span class="sxs-lookup"><span data-stu-id="0da5d-106">**Organization**</span></span>
  
<span data-ttu-id="0da5d-107">Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Skrzynka pocztowa -AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="0da5d-107">Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span></span>
  
[<span data-ttu-id="0da5d-108">Dowiedz się więcej</span><span class="sxs-lookup"><span data-stu-id="0da5d-108">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/enable-mailbox-auditing)
  

