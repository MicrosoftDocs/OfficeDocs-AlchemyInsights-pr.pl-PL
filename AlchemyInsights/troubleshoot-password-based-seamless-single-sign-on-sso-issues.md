---
title: Rozwiązywanie problemów z bezproblemowym logowaniem jednokrotnym opartym na hasłach
ms.author: v-jmathew
author: v-jmathew
manager: scotv
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004357"
- "9374"
ms.openlocfilehash: 4a9163f199a505df9b2de4f02b7c37a5f5677022
ms.sourcegitcommit: 0eb4f9bde53395b5fd4b5cd4ffc56ca96db91298
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 03/10/2021
ms.locfileid: "50714882"
---
# <a name="troubleshoot-password-based-seamless-single-sign-on-sso-issues"></a>Rozwiązywanie problemów z bezproblemowym logowaniem jednokrotnym opartym na hasłach

Aby poznać podstawy logowania jednokrotnego opartego na hasłach, zobacz uwierzytelnianie oparte na hasłach za [pomocą usługi Azure Active Directory.](https://docs.microsoft.com/azure/active-directory/fundamentals/auth-password-based-sso)

**Konfigurowanie logowania jednokrotnego opartego na hasłach**

1. [Konfigurowanie logowania jednokrotnego opartego](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-password-single-sign-on-non-gallery-applications) na hasłach — w tym artykule opisano szczegółowo opcję logowania jednokrotnego opartą na hasłach. Jeśli dodawania aplikacji wymaga konfiguracji niestandardowej i musisz używać logowania jednokrotnego opartego na hasłach, ten artykuł jest dla Ciebie.
2. [Konfigurowanie logowania pojedynczego opartego](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-single-sign-on-password-vaulting) na hasłach w aplikacjach wykonuj — serwer proxy aplikacji obsługuje kilka trybów logowania pojedynczego. Logowanie oparte na hasłach jest przeznaczone dla aplikacji, które używają kombinacji nazwy użytkownika i hasła do uwierzytelniania. Podczas konfigurowania logowania opartego na hasłach dla aplikacji użytkownicy muszą zalogować się do aplikacji lokalnej jeden raz. Następnie usługa Azure Active Directory przechowuje informacje logowania i automatycznie udostępnia je aplikacji, gdy użytkownicy uzyskają do nich dostęp zdalnie.
    - Aplikacja powinna już zostać opublikowana i przetestowana przy użyciu serwera proxy aplikacji. Jeśli nie, wykonaj czynności opisane w tece Publikowanie aplikacji przy użyciu serwera proxy aplikacji usługi [Azure AD,](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-add-on-premises-application) a następnie kontynuuj konfigurację logowania jednokrotnego opartego na hasłach dla aplikacji w wersji wstępnej.

Aby rozwiązać problemy z logowaniem jednokrotnym opartym na hasłach, zobacz Rozwiązywanie problemów z logowaniem jednokrotnym opartym [na hasłach w usłudze Azure AD](https://docs.microsoft.com/azure/active-directory/manage-apps/troubleshoot-password-based-sso)
