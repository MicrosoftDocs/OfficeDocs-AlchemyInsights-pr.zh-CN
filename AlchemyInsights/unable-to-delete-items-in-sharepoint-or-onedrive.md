---
title: 无法删除 SharePoint 或 OneDrive 中的项目
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 21d7b928fade48a6729c120e6ea33b16dafe799e
ms.sourcegitcommit: 22ce2315c8cf643137ab3420cdc1cda41433d44a
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/14/2019
ms.locfileid: "34057676"
---
# <a name="unable-to-delete-items"></a><span data-ttu-id="71af1-102">无法删除项目</span><span class="sxs-lookup"><span data-stu-id="71af1-102">Unable to delete items</span></span>

<span data-ttu-id="71af1-103">删除项目时遇到问题？</span><span class="sxs-lookup"><span data-stu-id="71af1-103">Having issues deleting items?</span></span>

- <span data-ttu-id="71af1-104">请始终确保你具有删除项目的[相应权限](https://docs.microsoft.com/en-us/sharepoint/default-sharepoint-groups), 或让[网站集管理员](https://docs.microsoft.com/en-us/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator)尝试删除该项目。</span><span class="sxs-lookup"><span data-stu-id="71af1-104">Always make sure you have the [appropriate permissions](https://docs.microsoft.com/en-us/sharepoint/default-sharepoint-groups) to delete the item or have a [site collection administrator](https://docs.microsoft.com/en-us/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) attempt remove the item.</span></span>

- <span data-ttu-id="71af1-105">确保项目上没有[保留策略](https://docs.microsoft.com/en-us/office365/securitycompliance/retention-policies)设置。</span><span class="sxs-lookup"><span data-stu-id="71af1-105">Ensure that there is not a [retention policy](https://docs.microsoft.com/en-us/office365/securitycompliance/retention-policies) setup on the item.</span></span>

- <span data-ttu-id="71af1-106">确保该项目未[签出](https://support.office.com/en-us/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de)给其他用户。</span><span class="sxs-lookup"><span data-stu-id="71af1-106">Ensure the item is not [checked out](https://support.office.com/en-us/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) to another user.</span></span>

- <span data-ttu-id="71af1-107">最后, 管理员可以使用[SharePoint 模式和做法](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation)(PnP), 其中包含一个 PowerShell 命令库, 这些命令允许您执行复杂的管理操作, 例如强制删除 stubborn 项目。</span><span class="sxs-lookup"><span data-stu-id="71af1-107">Finally, administrators can use [SharePoint Patterns and Practices](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) which contains a library of PowerShell commands that allow you to perform complex management actions such as force deleting stubborn items.</span></span> 
- [<span data-ttu-id="71af1-108">删除 PNP 文件</span><span class="sxs-lookup"><span data-stu-id="71af1-108">Remove PNP File</span></span>](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [<span data-ttu-id="71af1-109">删除 PNP 文件夹</span><span class="sxs-lookup"><span data-stu-id="71af1-109">Remove PNP Folder</span></span>](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [<span data-ttu-id="71af1-110">删除 PNP 列表项</span><span class="sxs-lookup"><span data-stu-id="71af1-110">Remove PNP List Item</span></span>](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [<span data-ttu-id="71af1-111">删除 PNP 列表</span><span class="sxs-lookup"><span data-stu-id="71af1-111">Remove PNP List</span></span>](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [<span data-ttu-id="71af1-112">删除 PNP 字段 (列)</span><span class="sxs-lookup"><span data-stu-id="71af1-112">Remove PNP Field (Column)</span></span>](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)