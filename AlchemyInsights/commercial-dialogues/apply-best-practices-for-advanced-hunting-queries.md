---
title: 应用高级搜寻查询的最佳实践
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
ms.openlocfilehash: cd13e2e8801db3df91140ce371813d900d72e38b
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/11/2021
ms.locfileid: "50735652"
---
# <a name="apply-best-practices-for-advanced-hunting-queries"></a><span data-ttu-id="87c83-102">应用高级搜寻查询的最佳实践</span><span class="sxs-lookup"><span data-stu-id="87c83-102">Apply best practices for advanced hunting queries</span></span>

<span data-ttu-id="87c83-103">若要更快地获取结果并避免在运行复杂查询时出现超时，请应用以下最佳实践：</span><span class="sxs-lookup"><span data-stu-id="87c83-103">To get results faster and to avoid timeouts while running complex queries, apply these best practices:</span></span>

- <span data-ttu-id="87c83-104">尝试新查询时，请始终使用限制，以避免获得非常大的结果集。</span><span class="sxs-lookup"><span data-stu-id="87c83-104">When trying new queries, always use a limit, to avoid getting extremely large result sets.</span></span> <span data-ttu-id="87c83-105">此外，使用 对应用程序结果集 `count` 进行初始评估。</span><span class="sxs-lookup"><span data-stu-id="87c83-105">Also, use `count` to make an initial assessment of the result set's size.</span></span>
- <span data-ttu-id="87c83-106">首先使用时间筛选器。</span><span class="sxs-lookup"><span data-stu-id="87c83-106">Use time filters first.</span></span> <span data-ttu-id="87c83-107">理想情况下，将查询限制为七天。</span><span class="sxs-lookup"><span data-stu-id="87c83-107">Ideally, limit your queries to seven days.</span></span>
- <span data-ttu-id="87c83-108">在查询的开头，在时间筛选器之后，添加预计会删除大部分数据的筛选器。</span><span class="sxs-lookup"><span data-stu-id="87c83-108">In the beginning of a query, right after the time filter, add the filters expected to remove most of the data.</span></span>
- <span data-ttu-id="87c83-109">在查找完整令牌时，请使用 `has` 运算符，而不是 `contains` 。</span><span class="sxs-lookup"><span data-stu-id="87c83-109">When looking for full tokens, use the `has` operator rather than `contains`.</span></span>
- <span data-ttu-id="87c83-110">对特定列而不是跨所有列运行搜索。</span><span class="sxs-lookup"><span data-stu-id="87c83-110">Run a search on a specific column rather than across all columns.</span></span>
- <span data-ttu-id="87c83-111">联接表时，首先指定行数较少的表。</span><span class="sxs-lookup"><span data-stu-id="87c83-111">When joining tables, first specify the table with fewer rows.</span></span>
- <span data-ttu-id="87c83-112">`project` 仅联接表中的必要列。</span><span class="sxs-lookup"><span data-stu-id="87c83-112">`project` only the necessary columns from the tables you've joined.</span></span>

<span data-ttu-id="87c83-113">若要了解更多信息，请参阅 [高级搜寻查询最佳实践](https://go.microsoft.com/fwlink/?linkid=2144812)。</span><span class="sxs-lookup"><span data-stu-id="87c83-113">To learn more, see [Advanced hunting query best practices](https://go.microsoft.com/fwlink/?linkid=2144812).</span></span>