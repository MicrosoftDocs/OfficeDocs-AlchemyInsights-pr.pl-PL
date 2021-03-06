---
title: Włączanie usługi Microsoft Defender dla usługi Office 365 dla usług SharePoint Online, OneDrive i Microsoft Teams
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000760"
- "7391"
ms.openlocfilehash: 1c29afdcc52e7032fea22d698371677918665fa9
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 03/11/2021
ms.locfileid: "50747745"
---
# <a name="enable-microsoft-defender-for-office-365-for-sharepoint-online-onedrive-and-microsoft-teams"></a>Włączanie usługi Microsoft Defender dla usługi Office 365 dla usług SharePoint Online, OneDrive i Microsoft Teams

1. Korzystając z poświadczeń administratora globalnego lub administratora zabezpieczeń, zaloguj się do Centrum zabezpieczeń i zgodności usługi [Office 365.](https://protection.office.com/)
2. Wybierz **pozycję Zarządzanie zagrożeniami** w okienku po lewej stronie, a następnie wybierz pozycję   >  [Załączniki do sejfu zasad.](https://protection.office.com/safeattachment)
3. Wybierz **pozycję Włącz usługę Microsoft Defender dla usługi Office 365 dla usług SharePoint, OneDrive** i Microsoft Teams, a następnie wybierz pozycję **Zapisz.**
    > [!TIP]
    >
    > - Jako administrator globalny lub administrator usługi SharePoint Online uruchom następujące polecenie cmdlet programu PowerShell z parametrem **DisallowInfectedFileDownload** ustawionym na *wartość true:* [Set-SPOTenant](https://go.microsoft.com/fwlink/?linkid=2092301)
    > - [Konfigurowanie alertów dotyczących wykrytych plików](https://go.microsoft.com/fwlink/?linkid=2092110)

Aby uzyskać więcej informacji, zobacz [Program Microsoft Defender dla usługi Office 365 w przypadku programu SharePoint, usługi OneDrive i aplikacji Microsoft Teams.](https://go.microsoft.com/fwlink/?linkid=2092041)
