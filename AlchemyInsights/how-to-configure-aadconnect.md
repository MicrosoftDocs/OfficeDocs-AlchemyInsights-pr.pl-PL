---
title: 646 jak skonfigurować AADConnect
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "646"
- "1300023"
ms.assetid: 599698ac-6709-477a-a66f-169b3165064e
ms.openlocfilehash: 6327e42b74283d732247c9a847c68db72082c56a
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 09/14/2020
ms.locfileid: "47704499"
---
# <a name="configure-sync-features"></a><span data-ttu-id="809e5-102">Konfigurowanie funkcji synchronizacji</span><span class="sxs-lookup"><span data-stu-id="809e5-102">Configure sync features</span></span>

<span data-ttu-id="809e5-103">Usługa Azure AD Connect zawiera kilka funkcji, które są domyślnie włączone lub można je włączyć później.</span><span class="sxs-lookup"><span data-stu-id="809e5-103">Azure AD Connect includes several features that are enabled by default, or that you can enable later.</span></span> <span data-ttu-id="809e5-104">Niektóre funkcje wymagają dodatkowej konfiguracji w określonych środowiskach.</span><span class="sxs-lookup"><span data-stu-id="809e5-104">Some features require additional configuration in specific environments.</span></span>

- <span data-ttu-id="809e5-105">Ograniczenia [filtrowania](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) obiekty są synchronizowane z usługą Azure AD.</span><span class="sxs-lookup"><span data-stu-id="809e5-105">[Filtering](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) limits the objects are synchronized to Azure AD.</span></span> <span data-ttu-id="809e5-106">Domyślnie synchronizowane są wszyscy użytkownicy, kontakty, grupy i konta komputerów z systemem Windows 10.</span><span class="sxs-lookup"><span data-stu-id="809e5-106">By default, all users, contacts, groups, and Windows 10 computer accounts are synchronized.</span></span> <span data-ttu-id="809e5-107">Możesz uwzględnić lub wykluczyć obiekty na podstawie domen, jednostek organizacyjnych lub innych atrybutów.</span><span class="sxs-lookup"><span data-stu-id="809e5-107">You can include or exclude objects based on domains, OUs, or other attributes.</span></span>

- <span data-ttu-id="809e5-108">[Synchronizacja skrótu hasła](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) synchronizuje skrót hasła z lokalnej usługi Active Directory z usługą Azure AD.</span><span class="sxs-lookup"><span data-stu-id="809e5-108">[Password hash synchronization](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) synchronizes the password hash from the on-premises Active Directory to Azure AD.</span></span> <span data-ttu-id="809e5-109">Umożliwia to zarządzanie hasłami w jednym miejscu, ale używanie tego samego hasła w środowiskach lokalnych i w chmurze.</span><span class="sxs-lookup"><span data-stu-id="809e5-109">This allows password management in one location, but use of the same password in both on-premises and cloud environments.</span></span> <span data-ttu-id="809e5-110">Usługa Active Directory jest źródłem autorytatywnym, ale można korzystać z własnych zasad haseł.</span><span class="sxs-lookup"><span data-stu-id="809e5-110">Because Active Directory is the authoritative source, you can use your own password policies.</span></span>

- <span data-ttu-id="809e5-111">Samoobsługowe [Resetowanie hasła (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) umożliwia użytkownikom Resetowanie własnych haseł w chmurze przy jednoczesnym stosowaniu lokalnych zasad haseł.</span><span class="sxs-lookup"><span data-stu-id="809e5-111">[Self-service password reset (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) allows users to reset their own passwords in the cloud while still applying your on-premises password policy.</span></span>

- <span data-ttu-id="809e5-112">[Zapisanie urządzenia](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) umożliwia zapisanie zarejestrowanych urządzeń w usłudze Azure AD z powrotem do lokalnej usługi Active Directory, aby można było ich użyć na potrzeby dostępu warunkowego.</span><span class="sxs-lookup"><span data-stu-id="809e5-112">[Device writeback](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) allows registered devices in Azure AD to be written back to the on-premises Active Directory so they can be used for conditional access.</span></span>

- <span data-ttu-id="809e5-113">[Zapobieganie przypadkowemu usuwaniu](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) jest domyślnie włączone, co zapobiega zbyt wielu jednoczesnym usuwaniem obiektów (ponad 500 obiektów na synchronizację).</span><span class="sxs-lookup"><span data-stu-id="809e5-113">[Prevent accidental deletes](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) is enabled by default to help prevent too many simultaneous object deletions (more than 500 objects per synchronization).</span></span> <span data-ttu-id="809e5-114">Możesz zmienić to ustawienie, aby zaspokoić potrzeby Twojej organizacji.</span><span class="sxs-lookup"><span data-stu-id="809e5-114">You can change this setting to meet the needs of your organization.</span></span>

- <span data-ttu-id="809e5-115">[Automatyczne uaktualnienie](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) jest domyślnie włączone dla instalacji ekspresowych i zapewnia, że Twoja wersja usługi Azure AD Connect jest zawsze aktualna.</span><span class="sxs-lookup"><span data-stu-id="809e5-115">[Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) is enabled by default for express installations and helps ensure your version of Azure AD Connect is always current.</span></span>
