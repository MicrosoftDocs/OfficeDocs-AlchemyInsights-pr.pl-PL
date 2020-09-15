---
title: Kod błędu 0x15
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "919"
- "2000022"
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Jeśli podczas aktywowania pakietu Office 2013 na wdrożeniach usług pulpitu zdalnego (RDS) jest wyświetlany komunikat o błędzie, warto włączyć bibliotekę ADAL, edytując rejestr.
ms.openlocfilehash: deb2ac4b0fb6a7b2e0045ff1b0ba95ad6e5e4a3a
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 09/14/2020
ms.locfileid: "47709197"
---
# <a name="error-while-activation-office-2013-on-remote-desktop-services"></a>Błąd podczas aktywowania pakietu Office 2013 w usługach pulpitu zdalnego

Jeśli podczas aktywowania pakietu Office 2013 na wdrożeniach usług pulpitu zdalnego (RDS) jest wyświetlany komunikat o błędzie, warto włączyć bibliotekę ADAL, edytując rejestr.
  
|**Klucz rejestru**|**Type**|**Wartość**|
|:-----|:-----|:-----|
|HKEY_CURRENT_USER \Software\Microsoft\Office\15.0\Common\Identity\EnableADAL  <br/> |REG_DWORD  <br/> |jedno  <br/> |

Aby uzyskać więcej informacji, zobacz [Włączanie nowoczesnego uwierzytelniania dla pakietu Office 2013 na urządzeniach z systemem Windows](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).
  
> [!NOTE]
>  Wartość ADAL jest domyślnie włączona w aplikacjach Microsoft 365 dla przedsiębiorstw i pakietu Office 2016. Usługi pulpitu zdalnego (RDS) były wcześniej nazwane usługami terminalowymi.
  