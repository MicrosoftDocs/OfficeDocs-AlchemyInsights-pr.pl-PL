---
title: Problemy z tokenami
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 01/15/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "7774"
- "9004351"
ms.openlocfilehash: 14a9681c08920094813497e7a75eb87bb0733cbc
ms.sourcegitcommit: e378232f4c9ef4e962208100db752221e7bd2dd6
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 01/20/2021
ms.locfileid: "49917038"
---
# <a name="issues-with-tokens"></a><span data-ttu-id="a0239-102">Problemy z tokenami</span><span class="sxs-lookup"><span data-stu-id="a0239-102">Issues with tokens</span></span>

<span data-ttu-id="a0239-103">Aby zarządzać problemami związanymi z tokenami, można wykonać następujące czynności:</span><span class="sxs-lookup"><span data-stu-id="a0239-103">To manage issues related to tokens, you can perform the following steps:</span></span>

1. <span data-ttu-id="a0239-104">Możesz określić okres istnienia, jaki ma mieć dostęp, identyfikator lub token SAML wystawiony przez platformę Microsoft Identity.</span><span class="sxs-lookup"><span data-stu-id="a0239-104">You can specify the lifetime of an access, ID, or SAML token issued by Microsoft identity platform.</span></span> <span data-ttu-id="a0239-105">Możesz ustawić okresy ważności tokenów dla wszystkich aplikacji w organizacji, dla aplikacji z wieloma dzierżawami (wielu organizacji) lub dla określonego podmiotu zabezpieczeń usługi w organizacji.</span><span class="sxs-lookup"><span data-stu-id="a0239-105">You can set token lifetimes for all apps in your organization, for a multi-tenant (multi-organization) application, or for a specific service principal in your organization.</span></span> <span data-ttu-id="a0239-106">Aby uzyskać więcej informacji, zobacz [konfigurowalne okresy ważności tokenów w usłudze Microsoft Identity platform (wersja Preview)](https://docs.microsoft.com/azure/active-directory/develop/active-directory-configurable-token-lifetimes).</span><span class="sxs-lookup"><span data-stu-id="a0239-106">For more information, see [Configurable token lifetimes in Microsoft identity platform (preview)](https://docs.microsoft.com/azure/active-directory/develop/active-directory-configurable-token-lifetimes).</span></span>
2. <span data-ttu-id="a0239-107">Tokeny dostępu umożliwiają klientom bezpieczne nawiązywanie połączeń za pomocą interfejsów API sieci Web oraz uwierzytelnianie i autoryzację przy użyciu interfejsów API sieci Web.</span><span class="sxs-lookup"><span data-stu-id="a0239-107">Access tokens enable clients to securely call protected web APIs, and are used by web APIs to perform authentication and authorization.</span></span> <span data-ttu-id="a0239-108">Zgodnie z specyfikacją OAuth tokeny dostępu są nieprzezroczystymi ciągami bez zestawu, a u innych dostawców tożsamości (IDPs) używają identyfikatorów GUID, inne używają zaszyfrowanych obiektów BLOB.</span><span class="sxs-lookup"><span data-stu-id="a0239-108">As per the OAuth specification, access tokens are opaque strings without a set format - some identity providers (IDPs) use GUIDs, others use encrypted blobs.</span></span> <span data-ttu-id="a0239-109">Platforma tożsamości firmy Microsoft korzysta z różnych formatów tokenów dostępu, w zależności od konfiguracji interfejsu API, który akceptuje token.</span><span class="sxs-lookup"><span data-stu-id="a0239-109">The Microsoft identity platform uses a variety of access token formats, depending on the configuration of the API that accepts the token.</span></span> <span data-ttu-id="a0239-110">Aby dowiedzieć się, jak interfejs API może sprawdzać i stosować oświadczenia w tokenie dostępu, zobacz [tokeny dostępu platformy Microsoft Identity platform](https://docs.microsoft.com/azure/active-directory/develop/userinfo#calling-the-userinfo-endpoint).</span><span class="sxs-lookup"><span data-stu-id="a0239-110">To learn how your API can validate and use the claims inside an access token, see [Microsoft identity platform access tokens](https://docs.microsoft.com/azure/active-directory/develop/userinfo#calling-the-userinfo-endpoint).</span></span>
3. <span data-ttu-id="a0239-111">Biblioteka uwierzytelniania firmy Microsoft (MSAL) obsługuje kilka przepływów uwierzytelniania, które można wykorzystać w różnych scenariuszach aplikacji.</span><span class="sxs-lookup"><span data-stu-id="a0239-111">The Microsoft Authentication Library (MSAL) supports several authentication flows for use in different application scenarios.</span></span> <span data-ttu-id="a0239-112">Aby uzyskać więcej informacji, zobacz [przepływy uwierzytelniania](https://docs.microsoft.com/azure/active-directory/develop/msal-authentication-flows#how-each-flow-emits-tokens-and-codes).</span><span class="sxs-lookup"><span data-stu-id="a0239-112">For more information, see [Authentication flows](https://docs.microsoft.com/azure/active-directory/develop/msal-authentication-flows#how-each-flow-emits-tokens-and-codes).</span></span>
4. <span data-ttu-id="a0239-113">Za pomocą kodu autoryzacji OAuth 2,0 można korzystać w aplikacjach zainstalowanych na urządzeniu w celu uzyskania dostępu do chronionych zasobów, takich jak internetowe interfejsy API.</span><span class="sxs-lookup"><span data-stu-id="a0239-113">The OAuth 2.0 authorization code grant can be used in apps that are installed on a device to gain access to protected resources, such as web APIs.</span></span> <span data-ttu-id="a0239-114">Korzystając z implementacji platformy Microsoft Identity platform uwierzytelniania OAuth 2,0, możesz dodać funkcję logowania i korzystania z interfejsu API do aplikacji mobilnych i klasycznych.</span><span class="sxs-lookup"><span data-stu-id="a0239-114">Using the Microsoft identity platform implementation of OAuth 2.0, you can add sign-in and API access to your mobile and desktop apps.</span></span> <span data-ttu-id="a0239-115">Zobacz [przepływ kodu autoryzacji Microsoft Identity platform i OAuth 2,0](https://docs.microsoft.com/azure/active-directory/develop/v2-oauth2-auth-code-flow#refresh-the-access-token) , aby korzystać bezpośrednio z protokołu w aplikacji, korzystając z dowolnego języka.</span><span class="sxs-lookup"><span data-stu-id="a0239-115">See [Microsoft identity platform and OAuth 2.0 authorization code flow](https://docs.microsoft.com/azure/active-directory/develop/v2-oauth2-auth-code-flow#refresh-the-access-token) for how to program directly against the protocol in your application, using any language.</span></span>
5. <span data-ttu-id="a0239-116">OpenID Connect (OIDC) jest protokołem uwierzytelniania opartym na 2,0 OAuth, za pomocą którego można bezpiecznie zalogować użytkownika do aplikacji.</span><span class="sxs-lookup"><span data-stu-id="a0239-116">OpenID Connect (OIDC) is an authentication protocol built on OAuth 2.0 that you can use to securely sign in a user to an application.</span></span> <span data-ttu-id="a0239-117">Gdy korzystasz z implementacji programu OpenID Connect w punkcie końcowym Microsoft Identity platform, możesz dodać do aplikacji uprawnienia do logowania i korzystania z interfejsu API.</span><span class="sxs-lookup"><span data-stu-id="a0239-117">When you use the Microsoft identity platform endpoint's implementation of OpenID Connect, you can add sign-in and API access to your apps.</span></span> <span data-ttu-id="a0239-118">W [protokole Microsoft Identity platform i OpenID Connect Protocol](https://docs.microsoft.com/azure/active-directory/develop/v2-protocols-oidc#send-the-sign-in-request) jest wyświetlana Metoda niezależna od języka oraz opis sposobu wysyłania i odbierania wiadomości HTTP bez użycia bibliotek Microsoft Open Source.</span><span class="sxs-lookup"><span data-stu-id="a0239-118">[Microsoft identity platform and OpenID Connect protocol](https://docs.microsoft.com/azure/active-directory/develop/v2-protocols-oidc#send-the-sign-in-request) shows how to do this independent of language and describes how to send and receive HTTP messages without using any Microsoft open-source libraries.</span></span>
    - <span data-ttu-id="a0239-119">Punkt końcowy UserInfo jest częścią standardu OIDC, który umożliwia zwracanie oświadczeń dotyczących użytkownika, który został uwierzytelniony.</span><span class="sxs-lookup"><span data-stu-id="a0239-119">The UserInfo endpoint is part of the OIDC standard, designed to return claims about the user that authenticated.</span></span> <span data-ttu-id="a0239-120">Aby uzyskać więcej informacji, zobacz [punkt końcowy informacji o firmie Microsoft Identity platform](https://docs.microsoft.com/azure/active-directory/develop/userinfo#consider-use-an-id-token-instead).</span><span class="sxs-lookup"><span data-stu-id="a0239-120">For more information, see [Microsoft identity platform UserInfo endpoint](https://docs.microsoft.com/azure/active-directory/develop/userinfo#consider-use-an-id-token-instead).</span></span>
    - <span data-ttu-id="a0239-121">[Wywołanie internetowego interfejsu API w aplikacji sieci Web przy użyciu przykładu usługi Azure AD i OpenID Connect](https://docs.microsoft.com/samples/azure-samples/active-directory-dotnet-webapp-webapi-openidconnect/active-directory-dotnet-webapp-webapi-openidconnect/) przykładowe pokazuje, jak utworzyć aplikację sieci Web MVC korzystającą z usługi Azure AD do logowania przy użyciu protokołu OpenID Connect, a następnie zadzwonić do internetowego interfejsu API pod tożsamością zalogowanego użytkownika przy użyciu tokenów uzyskanych za pośrednictwem uwierzytelniania OAuth 2,0.</span><span class="sxs-lookup"><span data-stu-id="a0239-121">The [Calling a web API in a web app using Azure AD and OpenID Connect](https://docs.microsoft.com/samples/azure-samples/active-directory-dotnet-webapp-webapi-openidconnect/active-directory-dotnet-webapp-webapi-openidconnect/) sample shows how to build an MVC web application that uses Azure AD for sign-in using the OpenID Connect protocol, and then call a web API under the signed-in user's identity using tokens obtained via OAuth 2.0.</span></span> <span data-ttu-id="a0239-122">W tym przykładzie użyto oprogramowania OpenID Connect ASP .NET OWIN i ADAL .NET.</span><span class="sxs-lookup"><span data-stu-id="a0239-122">This sample uses the OpenID Connect ASP .Net OWIN middleware and ADAL .Net.</span></span>
6. <span data-ttu-id="a0239-123">[Skonfiguruj aplikację w celu udostępnienia internetowego interfejsu API](https://docs.microsoft.com/azure/active-directory/develop/quickstart-configure-app-expose-web-apis) -w tym szybkim połączeniu możesz zarejestrować internetowy interfejs API za pomocą platformy tożsamości Microsoft i uwidocznić go aplikacjom klienckim, dodając przykładowy zakres.</span><span class="sxs-lookup"><span data-stu-id="a0239-123">[Configure an application to expose a web API](https://docs.microsoft.com/azure/active-directory/develop/quickstart-configure-app-expose-web-apis) - In this quickstart, you register a web API with the Microsoft identity platform and expose it to client apps by adding an example scope.</span></span> <span data-ttu-id="a0239-124">Rejestrując interfejs API sieci Web i uwidaczniając go za pośrednictwem zakresów, można udostępnić swoim zasobom dostęp do zasobów autoryzowanym użytkownikom i aplikacjom klienckim, które uzyskają dostęp do interfejsu API.</span><span class="sxs-lookup"><span data-stu-id="a0239-124">By registering your web API and exposing it through scopes, you can provide permissions-based access to its resources to authorized users and client apps that access your API.</span></span>
7. <span data-ttu-id="a0239-125">W usłudze Azure Active Directory B2C (Azure AD B2C) przepływ poświadczeń hasła właściciela zasobów (ROPC) jest przepływem standardowego uwierzytelniania OAuth.</span><span class="sxs-lookup"><span data-stu-id="a0239-125">In Azure Active Directory B2C (Azure AD B2C), the resource owner password credentials (ROPC) flow is an OAuth standard authentication flow.</span></span> <span data-ttu-id="a0239-126">W tym przepływie aplikacja, nazywana również jednostką uzależnioną, wymienia prawidłowe poświadczenia dla tokenów.</span><span class="sxs-lookup"><span data-stu-id="a0239-126">In this flow, an application, also known as the relying party, exchanges valid credentials for tokens.</span></span> <span data-ttu-id="a0239-127">Poświadczenia zawierają identyfikator użytkownika i hasło.</span><span class="sxs-lookup"><span data-stu-id="a0239-127">The credentials include a user ID and password.</span></span> <span data-ttu-id="a0239-128">Zwrócone tokeny to token identyfikatora, token dostępu i token odświeżania.</span><span class="sxs-lookup"><span data-stu-id="a0239-128">The tokens returned are an ID token, access token, and a refresh token.</span></span> <span data-ttu-id="a0239-129">Aby uzyskać więcej informacji, zobacz [Konfigurowanie przepływu poświadczeń hasła właściciela zasobów w usłudze Azure Active Directory B2C](https://docs.microsoft.com/azure/active-directory-b2c/add-ropc-policy?tabs=app-reg-ga&pivots=b2c-user-flow).</span><span class="sxs-lookup"><span data-stu-id="a0239-129">For more information, see [Set up a resource owner password credentials flow in Azure Active Directory B2C](https://docs.microsoft.com/azure/active-directory-b2c/add-ropc-policy?tabs=app-reg-ga&pivots=b2c-user-flow).</span></span> 
