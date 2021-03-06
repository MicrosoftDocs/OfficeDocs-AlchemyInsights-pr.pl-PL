---
title: Narzędzie eksportu zbierania elektronicznych materiałów dowodowych
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
- "263"
- "928"
- "1100001"
- "3100022"
ms.assetid: b16d310d-1134-4959-be68-d1c0ad463930
ms.openlocfilehash: 67e59182a5053111a08f5fb2be814931a1aa815d
ms.sourcegitcommit: fbe6925797cab0b38172386f1b059dc122e452a4
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 09/25/2020
ms.locfileid: "48277919"
---
# <a name="cant-install-or-run-the-ediscovery-export-tool"></a>Nie można zainstalować lub uruchomić narzędzia eksportu zbierania elektronicznych materiałów dowodowych?

Jeśli nie możesz zainstalować lub uruchomić narzędzia eksportu zbierania elektronicznych materiałów dowodowych w celu pobrania wyników wyszukiwania, sprawdź następujące elementy:
  
- Komputer, z którego korzystasz, spełnia następujące wymagania wstępne:

  - 32-lub 64-bitowe wersje systemu Windows 7 i nowsze wersje

  - Microsoft .NET Framework 4.7

  - Obsługiwana przeglądarka:

  - Microsoft Edge

    Lub

  - Internet Explorer 10 i nowsze wersje

    Inne przeglądarki, takie jak Google Chrome i Mozilla Firefox, nie są obsługiwane.

- Twoja organizacja może nawiązać połączenie z punktem końcowym na platformie Azure, czyli ** \* BLOB.Core.Windows.NET** (symbol wieloznaczny reprezentuje unikatowy identyfikator zadania eksportu).

- Rola eksportowania jest przypisywana w centrum zgodności zabezpieczeń programu Microsoft 365 &amp; . Domyślnie ta rola jest przypisana tylko do grupy ról Menedżera zbierania elektronicznych materiałów dowodowych. Zobacz [przypisywanie uprawnień do zbierania elektronicznych materiałów dowodowych](https://docs.microsoft.com/microsoft-365/compliance/assign-ediscovery-permissions).

Aby uzyskać więcej informacji, zobacz [Eksportowanie wyników wyszukiwania zawartości](https://docs.microsoft.com/microsoft-365/compliance/export-search-results).

Jeśli eksportujesz więcej niż 100K skrzynek pocztowych, musisz użyć następującego programu PowerShell, aby pobrać wyniki eksportu:  [Eksportowanie wyników z ponad 100K skrzynek pocztowych](https://docs.microsoft.com/microsoft-365/compliance/export-search-results?view=o365-worldwide%23exporting-results-from-more-than-100000-mailboxes).