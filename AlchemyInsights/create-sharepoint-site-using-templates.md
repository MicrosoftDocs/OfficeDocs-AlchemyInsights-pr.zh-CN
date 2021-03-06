---
title: 在 SharePoint Online 中创建网站
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 84f2b70e-2b23-4039-8305-85783798feed
ms.openlocfilehash: b554bfa4ccccbd68d0c3df27cf17397f860735c2
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/14/2020
ms.locfileid: "47732203"
---
# <a name="create-sharepoint-sites-using-templates"></a>使用模板创建 SharePoint 网站

新式通信或工作组网站不支持将网站保存为模板的功能。 有关使用模板的详细信息，请参阅 [保存、下载和上载 SharePoint 网站作为模板](https://docs.microsoft.com/sharepoint/dev/general-development/save-download-and-upload-a-sharepoint-site-as-a-template)。

下面是有关在 Sharepoint Online 中将网站或列表保存为模板的一些常见问题/解决方案。 

**"保存网站/列表模板" 按钮不可用或缺失**

管理员将需要允许自定义脚本启用模板功能。 有关详细步骤，示例和注意事项，请参阅 

- [允许或阻止自定义脚本](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)

- "将网站另存为模板" 命令不受支持，并且可能会在使用 SharePoint Server 发布基础结构的网站上出现问题。

**网站模板无法创建或无法正常工作**

模板可能缺少 [功能](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) ，无法激活。 如果在当前网站集中无法激活该功能，则不能使用网站模板创建网站。

- 检查以查看是否有任何列表或库超出了5000个项目的 [列表视图限制阈值](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) ，因为这可能会阻止创建网站模板。

- 网站可能使用过多的资源，因此网站模板超过了 50 MB 的限制。


- 显示使用查阅列的列表中的数据时出现问题。 有关详细信息，请参阅 [模板生成的列表不会在 SharePoint Online 中显示正确的查找列表中的数据](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data)。

有关常见问题和解决方案的更多详细信息，请选中 " [创建和使用网站模板](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989)"。



