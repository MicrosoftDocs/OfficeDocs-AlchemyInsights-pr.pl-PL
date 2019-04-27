---
title: Zapisz jako szablon witryny lub listy
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 368ff1fa-82cf-4a07-986e-140b212ffc5c
ms.openlocfilehash: 7930551c0938501d006f791491594f9d6d9ba260
ms.sourcegitcommit: 03258ec4f5476a1ea6dd3a31d17bda815bc5a18a
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 04/24/2019
ms.locfileid: "33243569"
---
# <a name="save-site-or-list-as-a-template"></a>Zapisz jako szablon witryny lub listy

Szablony witryn programu SharePoint są wbudowane definicje została zaprojektowana dla określonych potrzeb biznesowych. Aby uzyskać więcej informacji zobacz [Używanie szablonów do tworzenia różnego rodzaju witryny programu SharePoint](https://support.office.com/en-us/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).

Poniżej przedstawiono typowe problemy/rozwiązania dotyczące zapisywania witryny lub listy jako szablonu w dokumentacji Online programu SharePoint.

**Zapisz witrynę/lista przycisk Szablon nie jest dostępne lub brak**. 

- Administratorzy należy umożliwić niestandardowego skryptu do włączenia funkcji szablonu. Aby uzyskać szczegółowe instrukcje, przykłady i uwagi dotyczące zobacz [Zezwalaj lub zapobiegania niestandardowy skrypt](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script).


- Zapisz witrynę jako szablon, polecenie nie jest obsługiwane i może być przyczyną problemów w witrynach, które używają publikowania infrastruktury serwera programu SharePoint.


**Nie można utworzyć szablon witryny lub nie działa prawidłowo**

- Szablon może brakować [funkcji](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) i nie aktywuje. Jeśli funkcja nie jest dostępna uaktywnić w bieżącym zbiorze witryn, nie można użyć szablonu witryny do tworzenia witryny.


- Sprawdź, jeśli list ani bibliotek przekraczają [Próg Limit widoku listy](https://support.office.com/en-us/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) 5000 pozycji jak to zablokowanie tworzenia szablonu witryny.


- Witryny mogą używać zbyt wiele zasobów i w związku z tym szablon witryny przekracza limit 50 megabajtów (MB).


- Istnieją problemy z wyświetlaniem danych z listy, która jest używana kolumna odnośnika. Aby uzyskać więcej informacji zobacz temat [generowany szablon listy nie są wyświetlane dane z listy wyszukiwania poprawne w dokumentacji Online programu SharePoint](https://support.office.com/en-us/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a).


Aby uzyskać szczegółowe informacje na temat typowych problemów i rozwiązań prosimy o odniesienie, [tworzenia i stosowania szablonów witryn](https://support.office.com/en-us/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).
