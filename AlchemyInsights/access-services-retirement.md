---
title: 访问服务退休
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "9000356"
- "2009"
ms.assetid: ''
ms.openlocfilehash: 943066d5ac76c0630554ee724bbab9a94086fae4
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/14/2020
ms.locfileid: "47698636"
---
# <a name="access-services-retirement"></a>访问服务退休

正如我们最初在 MC97576 中宣布的那样，在2017年3月，并持续与过去一年的通信。将停用 Access Services。 此过程的下一阶段将是删除使用 SharePoint 列表作为其基础数据存储的 Access Web 数据库。

**这对我有何影响？**

从2019年6月起，我们将停止在 SharePoint Online 中创建新的 Access 数据库，并在4月2020关闭服务和任何剩余的应用。

**为此更改做准备需要做些什么？**

我们鼓励你为组织的 Access web 数据库创建过渡计划。 管理员可以使用 [SharePoint access 应用程序扫描](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.AccessApp.Scanner) 程序获取网站正在使用的 Access 应用程序的清单。

有几种方法可以迁移 Access web 数据库数据：

- 导入到本地 Access 数据库 (。.ACCDB) 或 Excel 文件。
- 我们还建议研究 Microsoft PowerApps 作为替代平台，以便为 web 和移动设备创建无代码业务解决方案。