---
title: Rozwiązywanie problemów z aplikacjami Microsoft 365 Twoje konto jest w nieprawidłowym stanie
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
- "2558"
- "9000571"
ms.openlocfilehash: ec529291ec9406eba9dc2b0f2cc7a93c77fa3456
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 09/14/2020
ms.locfileid: "47744555"
---
# <a name="fixing-the-microsoft-365-apps-your-account-is-in-a-bad-state-error"></a>Błąd podczas rozwiązywania problemów z aplikacjami Microsoft 365 "Twoje konto jest w nieprawidłowym stanie"

Aby rozwiązać ten problem, wypróbuj następujące opcje na komputerze, którego dotyczy problem:

- Otwórz aplikację pakietu Office, wybierz **File**pozycję  >  **konto**plików  >  **Wyloguj się z wszystkich kont**. Zaloguj się ponownie przy użyciu konta użytkownika z ważną licencją. Aby uzyskać szczegółowe informacje, zobacz [Konta w pakiecie Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).
- [Wyczyść poświadczenia pakietu Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) przy użyciu Menedżera poświadczeń systemu Windows.<br>
  **Uwaga:** Ścieżki rejestru dla pakietu Office 2016 zostały zmienione na 16,0. Na przykład \Software\Microsoft\Office\16.0\Common\Identity\
- Jeśli podczas nawiązywania połączenia z pakietem Office 365 przy użyciu pakietu Office 2013 wystąpi błąd, [Włącz nowoczesne uwierzytelnianie](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication) dla klienta pakietu Office.

Aby uzyskać więcej informacji, zobacz [Rozwiązywanie problemów z aplikacjami nieobsługującymi przeglądarki, które nie mogą zalogować się do aplikacji Microsoft 365, Azure lub Intune](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1).

