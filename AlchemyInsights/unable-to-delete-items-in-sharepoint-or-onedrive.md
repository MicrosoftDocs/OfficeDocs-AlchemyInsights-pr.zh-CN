---
title: 无法删除 SharePoint 或 OneDrive 中的项目
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1851"
- "2377"
- "9000255"
ms.assetid: ''
ms.openlocfilehash: db45aa8df40484fdcda7c430f1ca27482a1dd4ce
ms.sourcegitcommit: a9415f3ae8c7ba267b5134bcbdc1e070cea41a0f
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/12/2020
ms.locfileid: "49019573"
---
# <a name="unable-to-delete-items"></a>无法删除项目

- 保留策略可以导致这种情况，您需要禁用或排除导致此问题的相应保留。 在删除保留策略或保留后，可能需要长达24小时才能使更改生效。 确保项目上没有 [保留策略](https://docs.microsoft.com/microsoft-365/compliance/retention-policies) 设置。

- 网站可能已超出存储限制，请增加 [网站配额](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) 并删除该项。

- 确保该项目未 [签出](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) 给其他用户。

- 最后，管理员可以使用 [SharePoint 模式和做法](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) ，其中包含一个 PowerShell 命令库，使您可以执行复杂的管理操作，例如强制删除 stubborn 项目。
- [删除 PNP 文件](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [删除 PNP 文件夹](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [删除 PNP 列表项](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [删除 PNP 列表](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [删除 PNP 字段 (列) ](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)