---
title: Dodatek Dynamics 365 Forms — reguły biznesowe — reguła biznesowa nie jest wyzwalana dla formularza
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1926"
- "6200018"
ms.openlocfilehash: 7422b67973f93ce10c1639209cc50206a1016c10
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 09/14/2020
ms.locfileid: "47711501"
---
# <a name="onchange-event-does-not-occur-if-the-field-is-changed-programmatically"></a>Zdarzenie OnChange nie występuje, jeśli pole jest zmieniane programowo

Zdarzenie *OnChange* nie występuje, jeśli pole jest zmieniane programowo przy użyciu *atrybutu.* Metoda [SetValue](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) . Jeśli chcesz, aby w przypadku zdarzenia *OnChange* uruchamiane były uchwyty zdarzeń po ustawieniu wartości, należy użyć metody [fireOnchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) ( *formContext. Data. Entity* ) w kodzie.

[https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange)
