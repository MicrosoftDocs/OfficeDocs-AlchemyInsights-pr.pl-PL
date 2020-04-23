---
title: Duże listy programu SharePoint
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "407"
- "530001"
ms.assetid: ee07bf74-7aeb-4c47-8f5d-f496d6c09d79
ms.openlocfilehash: e85686788c60d365a00970e9ffe58e97512894a3
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 04/22/2020
ms.locfileid: "43767295"
---
# <a name="work-with-large-lists-and-libraries-in-sharepoint"></a><span data-ttu-id="6de42-102">Praca z dużymi listami i bibliotekami w programie SharePoint</span><span class="sxs-lookup"><span data-stu-id="6de42-102">Work with large lists and libraries in SharePoint</span></span>

<span data-ttu-id="6de42-103">Listy i biblioteki programu SharePoint mogą zawierać do 30 milionów elementów, ale gdy mają więcej niż 5000 elementów, podczas próby pracy z nimi może zostać wyświetlony błąd progu widoku listy.</span><span class="sxs-lookup"><span data-stu-id="6de42-103">SharePoint lists and libraries can contain up to 30 million items, but when they have more than 5,000 items, you might see a List View Threshold error when you try to work with them.</span></span> <span data-ttu-id="6de42-104">Zadaniem tego progu jest utrzymanie wydajności usługi.</span><span class="sxs-lookup"><span data-stu-id="6de42-104">This threshold is in place to maintain performance of the service.</span></span> <span data-ttu-id="6de42-105">Nie można go zmienić.</span><span class="sxs-lookup"><span data-stu-id="6de42-105">It can't be changed.</span></span> <span data-ttu-id="6de42-106">Aby uniknąć osiągnięcia tego progu:</span><span class="sxs-lookup"><span data-stu-id="6de42-106">To avoid hitting this threshold:</span></span>

<span data-ttu-id="6de42-107">**Korzystaj z nowoczesnych**</span><span class="sxs-lookup"><span data-stu-id="6de42-107">**Use modern**</span></span>

<span data-ttu-id="6de42-108">Widoki pokazujące wiele elementów działa najlepiej w nowoczesnym doświadczeniu.</span><span class="sxs-lookup"><span data-stu-id="6de42-108">Views showing many items work best in the modern experience.</span></span> <span data-ttu-id="6de42-109">[Użyj nowoczesnego środowiska,](https://support.office.com/article/66dac24b-4177-4775-bf50-3d267318caa9) aby uniknąć błędów, które można zobaczyć w klasycznym doświadczeniu.</span><span class="sxs-lookup"><span data-stu-id="6de42-109">[Use the modern experience](https://support.office.com/article/66dac24b-4177-4775-bf50-3d267318caa9) to avoid errors you might see in the classic experience.</span></span>

<span data-ttu-id="6de42-110">**Dodawanie indeksów**</span><span class="sxs-lookup"><span data-stu-id="6de42-110">**Add indexes**</span></span>

<span data-ttu-id="6de42-111">Podczas filtrowania lub sortowania według kolumny, która nie ma indeksu, może zostać wyświetlony komunikat o błędzie.</span><span class="sxs-lookup"><span data-stu-id="6de42-111">When you filter or sort by a column that doesn't have an index, you might see an error message.</span></span> <span data-ttu-id="6de42-112">[Dodaj indeks](https://support.office.com/article/f3f00554-b7dc-44d1-a2ed-d477eac463b0) ręcznie z **pozycji Ustawienia listy** w menu ustawień, a następnie kolumny **indeksowane**.</span><span class="sxs-lookup"><span data-stu-id="6de42-112">[Add an index](https://support.office.com/article/f3f00554-b7dc-44d1-a2ed-d477eac463b0) manually from **List Settings** in the settings menu, then **Indexed Columns**.</span></span>

<span data-ttu-id="6de42-113">**Edytowanie widoku listy**</span><span class="sxs-lookup"><span data-stu-id="6de42-113">**Edit the list view**</span></span>

<span data-ttu-id="6de42-114">Jeśli podczas pracy z dużą listą wystąpi błąd, [edytuj widok listy](https://support.office.com/article/15916903-e79a-423f-b4e2-02d37e1ff372).</span><span class="sxs-lookup"><span data-stu-id="6de42-114">If an error occurs when working with a large list, [edit your list view](https://support.office.com/article/15916903-e79a-423f-b4e2-02d37e1ff372).</span></span>

<span data-ttu-id="6de42-115">Następujące cztery zmiany usunie błędy progowe widoku listy.</span><span class="sxs-lookup"><span data-stu-id="6de42-115">The following four changes will remove list view threshold errors.</span></span> <span data-ttu-id="6de42-116">Wykonuj wszystkie cztery zmiany, aby usunąć wszystkie błędy.</span><span class="sxs-lookup"><span data-stu-id="6de42-116">Make all four changes to remove all errors.</span></span> <span data-ttu-id="6de42-117">Jeśli nadal występują błędy, sprawdź [Zarządzanie dużymi listami i bibliotekami](https://support.office.com/article/B8588DAE-9387-48C2-9248-C24122F07C59).</span><span class="sxs-lookup"><span data-stu-id="6de42-117">If you are still getting errors, check [Manage large lists and libraries](https://support.office.com/article/B8588DAE-9387-48C2-9248-C24122F07C59).</span></span>

1. <span data-ttu-id="6de42-118">Wybierz **opcję Brak** z obu Pierwszego **sortowania według kolumny,** **a następnie posortuj według kolumny**.</span><span class="sxs-lookup"><span data-stu-id="6de42-118">Select **None** from both **First sort by the column** and **Then sort by the column**.</span></span>
2. <span data-ttu-id="6de42-119">Wybierz **opcję Brak** z pierwszej grupy według **kolumny,** **a następnie grupuj według kolumny**.</span><span class="sxs-lookup"><span data-stu-id="6de42-119">Select **None** from both **First group by the column** and **Then group by the column**.</span></span>
3. <span data-ttu-id="6de42-120">Wybierz **opcję Brak** dla wszystkich kolumn w sekcji **Sumy.**</span><span class="sxs-lookup"><span data-stu-id="6de42-120">Select **None** for all columns in the **Totals** section.</span></span>
4. <span data-ttu-id="6de42-121">Usuń zaznaczenie wszystkich kolumn z wyjątkiem jednej do wyświetlenia z sekcji **Kolumny.**</span><span class="sxs-lookup"><span data-stu-id="6de42-121">Deselect all but one column for display from the **Columns** section.</span></span>

