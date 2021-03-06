---
title: 性能问题-SharePoint 或 OneDrive
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.openlocfilehash: 39ec9b746c47414f1cfaad1342491b8f33a47d6f
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/15/2020
ms.locfileid: "47771234"
---
# <a name="sharepoint-or-onedrive-slow-inaccessible-or-unavailable-for-multiple-users"></a>SharePoint 或 OneDrive 速度慢、对多个用户不可访问或不可用

如果 OneDrive 或 SharePoint 网站对之前有权访问的多个用户不可用，则可能存在暂时性的服务问题。 [检查服务运行状况仪表板](https://portal.office.com/adminportal/home#/servicehealth)。

**添加和许可用户**

确保 [将许可证分配给 Microsoft 365 for business 中的用户](https://docs.microsoft.com/microsoft-365/admin/add-users/add-users)。


**分配权限**

如果已为用户分配了 Sharepoint 许可证，但仍收到 "拒绝访问" 消息，请确保已为其分配了 [适当的权限级别](https://docs.microsoft.com/sharepoint/understanding-permission-levels) 。

**考虑使用访问请求功能**

[访问请求功能](https://support.office.com/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3)允许用户请求对他们当前无权查看的内容的访问权限。

**允许自定义脚本可能导致访问被拒绝问题**

在某些情况下，可能会出现 " *允许自定义脚本* " 功能显示访问被拒绝的情况。 有关受影响的功能的列表、安全注意事项和禁用该功能的功能。 请访问 [允许或阻止自定义脚本](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)。

