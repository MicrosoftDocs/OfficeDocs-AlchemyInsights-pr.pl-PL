---
title: Rozwiązywanie problemów z zgodą użytkownika
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 01/18/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004353"
- "7785"
ms.openlocfilehash: 7249bafe1b047c66d9351a79f1782cfcc1a936a1
ms.sourcegitcommit: 7b213fd5e8a3fdb5c602673dc194d576d372ac96
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 01/18/2021
ms.locfileid: "49901634"
---
# <a name="troubleshoot-user-consent"></a><span data-ttu-id="60193-102">Rozwiązywanie problemów z zgodą użytkownika</span><span class="sxs-lookup"><span data-stu-id="60193-102">Troubleshoot user consent</span></span>

1. <span data-ttu-id="60193-103">Możesz skonfigurować sposób udzielania użytkownikom końcowym zgody na aplikacje za pośrednictwem witryny Azure Portal lub programu PowerShell.</span><span class="sxs-lookup"><span data-stu-id="60193-103">You can configure how end-users consent to applications through the Azure Portal or PowerShell.</span></span> <span data-ttu-id="60193-104">Aby uzyskać więcej informacji, zobacz [Ustawienia zgody użytkownika](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-user-consent?tabs=azure-portal#user-consent-settings) .</span><span class="sxs-lookup"><span data-stu-id="60193-104">See [User consent settings](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-user-consent?tabs=azure-portal#user-consent-settings) for more information.</span></span>
1. <span data-ttu-id="60193-105">Administrator może również skorzystać z [interfejsu API programu Microsoft Graph](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-user-consent?tabs=azure-portal#user-consent-settings) , aby udzielić zgody na delegowane uprawnienia w imieniu jednego użytkownika.</span><span class="sxs-lookup"><span data-stu-id="60193-105">An administrator can also use the [Microsoft Graph API](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-user-consent?tabs=azure-portal#user-consent-settings) to grant consent to delegated permissions on behalf of a single user.</span></span> <span data-ttu-id="60193-106">Aby uzyskać więcej informacji, zobacz [Uzyskiwanie dostępu do programu Access w imieniu użytkownika](https://docs.microsoft.com/graph/auth-v2-user).</span><span class="sxs-lookup"><span data-stu-id="60193-106">For more information, see [Get access on behalf of a user](https://docs.microsoft.com/graph/auth-v2-user).</span></span>
1. <span data-ttu-id="60193-107">[Błędy zgody użytkownika](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-unexpected-user-consent-error): w tym artykule omówiono błędy, które mogą wystąpić podczas procesu wyrażania zgody na aplikację.</span><span class="sxs-lookup"><span data-stu-id="60193-107">[User Consent Errors](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-unexpected-user-consent-error): this article discusses errors that can occur during the process of consenting to an application.</span></span> <span data-ttu-id="60193-108">W przypadku rozwiązywania problemów z nieoczekiwanymi monitami o zgodzie, które nie zawierają żadnych komunikatów o błędach, zobacz [scenariusze uwierzytelniania usługi Azure AD](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-unexpected-user-consent-error).</span><span class="sxs-lookup"><span data-stu-id="60193-108">If you are troubleshooting unexpected consent prompts that do not contain any error messages, see [Authentication Scenarios for Azure AD](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-unexpected-user-consent-error).</span></span>