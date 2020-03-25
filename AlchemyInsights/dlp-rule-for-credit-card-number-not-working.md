---
title: Reguła DLP dla numeru karty kredytowej nie działa
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1270"
- "3200001"
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: 6b28534d072c024a98a9b05f6cb55bfdc3435db6
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932453"
---
# <a name="dlp-issues-with-credit-card-numbers"></a><span data-ttu-id="1c18b-102">Problemy z DLP z numerami kart kredytowych</span><span class="sxs-lookup"><span data-stu-id="1c18b-102">DLP issues with credit card numbers</span></span>

<span data-ttu-id="1c18b-103">**Ważne:** Wielu klientów korzystających z usługi SharePoint Online i OneDrive uruchamia aplikacje o znaczeniu krytycznym dla firmy w stosunku do usługi działającej w tle.</span><span class="sxs-lookup"><span data-stu-id="1c18b-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="1c18b-104">Należą do nich migracja zawartości, zapobieganie utracie danych (DLP) i rozwiązania do tworzenia kopii zapasowych.</span><span class="sxs-lookup"><span data-stu-id="1c18b-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="1c18b-105">W tych bezprecedensowych czasach podejmujemy kroki w celu zapewnienia, że usługi SharePoint Online i OneDrive pozostają wysoce dostępne i niezawodne dla użytkowników, którzy są bardziej niż kiedykolwiek zależni od usługi w scenariuszach pracy zdalnej.</span><span class="sxs-lookup"><span data-stu-id="1c18b-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="1c18b-106">W celu wsparcia tego celu wprowadziliśmy ściślejsze limity ograniczania przepustowości w aplikacjach w tle (migracja, DLP i rozwiązania do tworzenia kopii zapasowych) w dni powszednie w ciągu dnia.</span><span class="sxs-lookup"><span data-stu-id="1c18b-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="1c18b-107">Należy się spodziewać, że te aplikacje osiągną bardzo ograniczoną przepływność w tych czasach.</span><span class="sxs-lookup"><span data-stu-id="1c18b-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="1c18b-108">Jednak w godzinach wieczornych i weekendowych dla regionu usługa będzie gotowa do przetwarzania znacznie większej liczby żądań z aplikacji w tle.</span><span class="sxs-lookup"><span data-stu-id="1c18b-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="1c18b-109">**Problemy z DLP z numerami kart kredytowych**</span><span class="sxs-lookup"><span data-stu-id="1c18b-109">**DLP issues with credit card numbers**</span></span>

<span data-ttu-id="1c18b-110">Czy masz problemy z **zapobieganiem utracie danych (DLP)** nie działa dla zawartości zawierającej **numer karty kredytowej** podczas korzystania z typu poufnych informacji DLP w UO365?</span><span class="sxs-lookup"><span data-stu-id="1c18b-110">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Credit Card Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="1c18b-111">Jeśli tak, upewnij się, że zawartość zawiera informacje potrzebne do wyzwolenia zasad DLP, gdy jest oceniana.</span><span class="sxs-lookup"><span data-stu-id="1c18b-111">If so, make sure your content contains the needed information to trigger the the DLP policy when it is evaluated.</span></span> <span data-ttu-id="1c18b-112">Na przykład dla **zasad kart kredytowych** skonfigurowanych z poziomem zaufania równym 85%, aby reguła wyzwoliła, należy wykryć następujące zasady:</span><span class="sxs-lookup"><span data-stu-id="1c18b-112">For example, for a **Credit Card policy** configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="1c18b-113">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 cyfr, które mogą być sformatowane lub niesformatowane (ddddddddddddddd) i muszą przejść test Luhna.</span><span class="sxs-lookup"><span data-stu-id="1c18b-113">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 digits which can be formatted or unformatted (dddddddddddddddd) and must pass the Luhn test.</span></span>

- <span data-ttu-id="1c18b-114">**[Wzór:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Bardzo złożony i solidny wzór, który wykrywa karty wszystkich głównych marek na całym świecie, w tym Visa, MasterCard, Discover Card, JCB, American Express, karty upominkowe i karty do kolacji.</span><span class="sxs-lookup"><span data-stu-id="1c18b-114">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Very complex and robust pattern that detects cards from all major brands worldwide, including Visa, MasterCard, Discover Card, JCB, American Express, gift cards, and diner cards.</span></span>

- <span data-ttu-id="1c18b-115">**[Suma kontrolna:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Tak, suma kontrolna Luhna</span><span class="sxs-lookup"><span data-stu-id="1c18b-115">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Yes, the Luhn checksum</span></span>

- <span data-ttu-id="1c18b-116">**[Definicja:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** Zasady DLP są w 85% pewne, że wykryto tego typu poufne informacje, jeśli w pobliżu 300 znaków:</span><span class="sxs-lookup"><span data-stu-id="1c18b-116">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="1c18b-117">Funkcja Func_credit_card znajduje zawartość, która pasuje do wzorca.</span><span class="sxs-lookup"><span data-stu-id="1c18b-117">The function Func_credit_card finds content that matches the pattern.</span></span>

  - <span data-ttu-id="1c18b-118">Jedna z następujących elementów jest prawdziwa:</span><span class="sxs-lookup"><span data-stu-id="1c18b-118">One of the following is true:</span></span>

  - <span data-ttu-id="1c18b-119">Zostanie znalezione słowo kluczowe z Keyword_cc_verification.</span><span class="sxs-lookup"><span data-stu-id="1c18b-119">A keyword from Keyword_cc_verification is found.</span></span>

  - <span data-ttu-id="1c18b-120">Znaleziono słowo kluczowe z Keyword_cc_name</span><span class="sxs-lookup"><span data-stu-id="1c18b-120">A keyword from Keyword_cc_name is found</span></span>

  - <span data-ttu-id="1c18b-121">Funkcja Func_expiration_date znajduje datę w odpowiednim formacie daty.</span><span class="sxs-lookup"><span data-stu-id="1c18b-121">The function Func_expiration_date finds a date in the right date format.</span></span>

  - <span data-ttu-id="1c18b-122">Suma kontrolna przechodzi</span><span class="sxs-lookup"><span data-stu-id="1c18b-122">The checksum passes</span></span>

    <span data-ttu-id="1c18b-123">Na przykład następujący przykład może wyzwolić zasady numeru karty kredytowej DLP:</span><span class="sxs-lookup"><span data-stu-id="1c18b-123">For example, the following sample would trigger for a DLP Credit Card Number Policy:</span></span>

  - <span data-ttu-id="1c18b-124">Wiza: 4485 3647 3952 7352</span><span class="sxs-lookup"><span data-stu-id="1c18b-124">Visa: 4485 3647 3952 7352</span></span>
  
  - <span data-ttu-id="1c18b-125">Wygasa: 2/2009</span><span class="sxs-lookup"><span data-stu-id="1c18b-125">Expires: 2/2009</span></span>

<span data-ttu-id="1c18b-126">Aby uzyskać więcej informacji na temat tego, co jest wymagane do wykrycia **numeru karty kredytowej** dla twojej zawartości, zobacz następującą sekcję w tym artykule: Jakie [typy poufnych informacji szukają dla karty kredytowej#](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span><span class="sxs-lookup"><span data-stu-id="1c18b-126">For more information on what is required for a **Credit Card Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for Credit Card#](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span></span>
  
<span data-ttu-id="1c18b-127">Przy użyciu innego wbudowanego typu poufnych informacji, zobacz następujący artykuł, aby uzyskać informacje na temat tego, co jest wymagane dla innych typów: [Czego szukają typy poufnych informacji](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="1c18b-127">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  