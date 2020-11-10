---
title: Błąd logowania do usługi OneDrive AADSTS50011
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003820"
- "6840"
ms.openlocfilehash: 1f906f82e99c322ed953800d54fba5a073eacd10
ms.sourcegitcommit: 534e9217d99336eb471166ff83231c7e408fb1d9
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 11/09/2020
ms.locfileid: "48982485"
---
# <a name="onedrive-login-error-aadsts50011"></a><span data-ttu-id="7a79e-102">Błąd logowania do usługi OneDrive AADSTS50011</span><span class="sxs-lookup"><span data-stu-id="7a79e-102">OneDrive login error AADSTS50011</span></span>

<span data-ttu-id="7a79e-103">Jeśli zostanie wyświetlony komunikat o błędzie "AADSTS50011: adres URL odpowiedzi określony w żądaniu jest niezgodny z odpowiedzią" podczas logowania się do aplikacji OneDrive, sprawdź następujące elementy:</span><span class="sxs-lookup"><span data-stu-id="7a79e-103">If you receive an error "AADSTS50011: The reply URL specified in the request does not match the reply" when signing into the OneDrive app, check for the following:</span></span>

<span data-ttu-id="7a79e-104">Wersja usługi OneDrive musi być równa lub większa niż wersja 20.052. XXXX. XX.</span><span class="sxs-lookup"><span data-stu-id="7a79e-104">Your OneDrive version needs to be equal to or greater than version 20.052.XXXX.XXXX.</span></span> <span data-ttu-id="7a79e-105">Aby sprawdzić wersję, kliknij niebieską ikonę usługi OneDrive w obszarze powiadomień, wybierz pozycję **pomoc & ustawienia > ustawienia > informacje**.</span><span class="sxs-lookup"><span data-stu-id="7a79e-105">To check your version, click on the blue OneDrive icon in the notification area, select **Help & Settings > Settings > About**.</span></span>

<span data-ttu-id="7a79e-106">Sieć może blokować ruch do **g.Live.com** i **oneclient.SFX.MS**.</span><span class="sxs-lookup"><span data-stu-id="7a79e-106">Your network might block traffic to **g.live.com** and **oneclient.sfx.ms**.</span></span> <span data-ttu-id="7a79e-107">Jeśli ten ruch jest zablokowany, usługa OneDrive nie może go zaktualizować.</span><span class="sxs-lookup"><span data-stu-id="7a79e-107">If that traffic is blocked, OneDrive cannot update itself.</span></span> <span data-ttu-id="7a79e-108">Skontaktuj się z administratorem sieci, aby upewnić się, że masz dostęp do tych adresów URL.</span><span class="sxs-lookup"><span data-stu-id="7a79e-108">Work with your network administrator to ensure you have access to those URLs.</span></span> <span data-ttu-id="7a79e-109">[Te punkty końcowe](https://docs.microsoft.com/microsoft-365/enterprise/urls-and-ip-address-ranges?view=o365-worldwide) powinny być dostępne dla klientów korzystających z planów Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="7a79e-109">[These endpoints](https://docs.microsoft.com/microsoft-365/enterprise/urls-and-ip-address-ranges?view=o365-worldwide) should be reachable for customers using Microsoft 365 plans.</span></span>

<span data-ttu-id="7a79e-110">Jeśli chcesz ręcznie uzyskać aktualną wersję usługi OneDrive, odwiedź stronę [https://aka.ms/getonedrive](https://aka.ms/getonedrive) .</span><span class="sxs-lookup"><span data-stu-id="7a79e-110">If you need to manually get a current version of OneDrive, visit [https://aka.ms/getonedrive](https://aka.ms/getonedrive).</span></span>
