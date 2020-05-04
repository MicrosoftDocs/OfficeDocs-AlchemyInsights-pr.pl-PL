---
title: Pytania dotyczące korzystania z narzędzia wdrażania pakietu Office (ODT)
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: 4aef42df4dde17d15863fca67e41f0ff23e506dc
ms.sourcegitcommit: 7e06d9ec1dd462cbd882f088c997d012a032f04d
ms.translationtype: MT
ms.contentlocale: pl-PL
ms.lasthandoff: 05/04/2020
ms.locfileid: "44010761"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a><span data-ttu-id="a116d-102">Pytania dotyczące korzystania z narzędzia wdrażania pakietu Office (ODT)</span><span class="sxs-lookup"><span data-stu-id="a116d-102">Questions about how to use the Office Deployment Tool (ODT)</span></span>

<span data-ttu-id="a116d-103">Pobierz narzędzie wdrażania pakietu Office z [Centrum pobierania Firmy Microsoft](https://go.microsoft.com/fwlink/p/?LinkID=626065).</span><span class="sxs-lookup"><span data-stu-id="a116d-103">Download the Office Deployment Tool from the [Microsoft Download Center](https://go.microsoft.com/fwlink/p/?LinkID=626065).</span></span>
  
<span data-ttu-id="a116d-104">Po pobraniu pliku uruchom samodzielnie wyodrębniający plik wykonywalny, który zawiera plik wykonywalny Narzędzia wdrażania pakietu Office (setup.exe) i przykładowy plik konfiguracyjny (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="a116d-104">After downloading the file, run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span>
  
 <span data-ttu-id="a116d-105">**Aby wykluczyć lub usunąć aplikacje usługi Microsoft 365 dla produktów dla przedsiębiorstw z komputerów klienckich:**</span><span class="sxs-lookup"><span data-stu-id="a116d-105">**To exclude or remove Microsoft 365 Apps for enterprise products from client computers:**</span></span>
  
<span data-ttu-id="a116d-106">Podczas instalowania aplikacji usługi Microsoft 365 dla przedsiębiorstw można wykluczyć określone produkty.</span><span class="sxs-lookup"><span data-stu-id="a116d-106">When installing Microsoft 365 Apps for enterprise, you can exclude specific products.</span></span> <span data-ttu-id="a116d-107">Aby to zrobić, wykonaj kroki dotyczące instalowania pakietu Office z ODT, ale dołącz excludeApp element w pliku konfiguracji.</span><span class="sxs-lookup"><span data-stu-id="a116d-107">To do so, follow the steps for installing Office with the ODT, but include the ExcludeApp element in your configuration file.</span></span> <span data-ttu-id="a116d-108">Na przykład ten plik konfiguracyjny instaluje wszystkie aplikacje microsoftu 365 dla produktów dla przedsiębiorstw z wyjątkiem programu Publisher:</span><span class="sxs-lookup"><span data-stu-id="a116d-108">For example, this configuration file installs all the Microsoft 365 Apps for enterprise products except Publisher:</span></span>
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[<span data-ttu-id="a116d-109">Omówienie narzędzia wdrażania pakietu Office</span><span class="sxs-lookup"><span data-stu-id="a116d-109">Overview of the Office Deployment Tool</span></span>](https://docs.microsoft.com/deployoffice/overview-office-deployment-tool)
  

