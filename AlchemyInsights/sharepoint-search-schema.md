---
title: 在 SharePoint Online 中管理搜索架构
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fe00f4c0-44d5-49d4-9db0-a62698bcd1d1
ms.openlocfilehash: f2d8d3e07fe32d21af484e4c59e0f5ac6fe8081c
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/15/2020
ms.locfileid: "47770541"
---
# <a name="manage-search-schema-in-sharepoint-online"></a>在 SharePoint Online 中管理搜索架构

搜索架构可控制用户可以搜索的内容、用户可以搜索的内容以及在搜索网站上显示结果的方式。 

请参阅 [在 SharePoint Online 中管理搜索架构](https://docs.microsoft.com/sharepoint/manage-search-schema) ，了解如何执行以下操作： 
- 更改搜索架构。
- 创建托管属性。
- 将已爬网映射的已爬网属性映射到托管属性。

请注意以下关于管理搜索架构的内容：

- 如果您收到一条警告，指出在进行架构更改时 **应用程序已暂停** ，这只是临时发生，因为存在服务维护。 

    如果超过了24小时，但仍遇到警告，请记录一种支持案例。
- 当您更改托管属性或添加新属性时，更改将仅在重新对内容进行爬网后才会生效。 在 SharePoint Online 中，爬网会根据定义的爬网计划自动进行。
- 若要确保对所做的更改进行爬网，您可以专门 [请求对列表或库重新编制索引](https://docs.microsoft.com/sharepoint/manage-search-schema#request-re-indexing-of-a-document-library-or-list) 

有关搜索架构的完整概述，请参阅 [简介搜索架构](https://blogs.technet.microsoft.com/tothesharepoint/2012/11/25/introducing-search-schema-for-sharepoint-2013/) 


