---
title: 将 SharePoint Online 限制为经典模式
ms.author: kirks
author: Techwriter40
ms.date: 3/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6e99da1c-e61d-40ba-855e-1a8f346e42fd
ms.openlocfilehash: 6a7c0497243ef7425917f54815e61f1244838c54
ms.sourcegitcommit: b14aa00b42ce4ca9d7dc3aa1fd57e66eae115447
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/28/2019
ms.locfileid: "30953335"
---
# <a name="restrict-sharepoint-online-to-classic-mode"></a><span data-ttu-id="9aaa2-102">将 SharePoint Online 限制为经典模式</span><span class="sxs-lookup"><span data-stu-id="9aaa2-102">Restrict SharePoint Online to classic mode</span></span>

<span data-ttu-id="9aaa2-103">有些组织仍需要经典模式体验。</span><span class="sxs-lookup"><span data-stu-id="9aaa2-103">Some organizations still require the Classic mode experience.</span></span> <span data-ttu-id="9aaa2-104">虽然没有计划在粒度级别删除经典模式, 从2019年4月1日开始, 但不能再将整个组织 (租户) 限制为列表和库的经典模式。</span><span class="sxs-lookup"><span data-stu-id="9aaa2-104">While there are no plans to remove classic mode at a granular level, starting April 1,2019, it will no longer be possible to restrict an entire organization (tenant) to classic mode for lists and libraries.</span></span>

<span data-ttu-id="9aaa2-105">管理员可通过以下方式来管理采用经典模式的各个列表和库, 具体方法是使用我们在以下级别提供的具体选择退出开关:</span><span class="sxs-lookup"><span data-stu-id="9aaa2-105">The admin will have the following options to manage individual lists and libraries in classic mode using granular opt-out switches that we provide at the following levels:</span></span>

<span data-ttu-id="9aaa2-106">--网站集--列表--库</span><span class="sxs-lookup"><span data-stu-id="9aaa2-106">-- site collection -- site -- list -- library</span></span>

<span data-ttu-id="9aaa2-107">此外, 使用新式不支持的某些功能和自定义项的列表仍将自动切换到经典模式。</span><span class="sxs-lookup"><span data-stu-id="9aaa2-107">Additionally, lists that use certain features and customizations that are not supported by modern will still be automatically switched to classic mode.</span></span>

<span data-ttu-id="9aaa2-108">4月1日之后, 由于租户选择退出, 在经典模式下的列表和库将自动在网站级别和列表级别进行管理。</span><span class="sxs-lookup"><span data-stu-id="9aaa2-108">After April 1, lists and libraries that are in classic mode as a result of tenant opt-out will automatically be managed at the site level and list level.</span></span>

<span data-ttu-id="9aaa2-109">如果需要经典模式, 请参阅此处的详细信息和 PnP Powershell 说明, 这些说明可用于在4月1日准备删除租户级别自愿退出的选项和工具。</span><span class="sxs-lookup"><span data-stu-id="9aaa2-109">If you require classic mode please see more information here and PnP Powershell instruction here that describes options and tools you can use today to prepare for the removal of the tenant level opt-out on April 1.</span></span>
