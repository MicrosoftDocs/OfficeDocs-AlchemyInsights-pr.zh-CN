---
title: 在 SharePoint 或 OneDrive 中限制访问权限
ms.author: mikeplum
author: MikePlumleyMSFT
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: d8be1eb5bdcd0b5b08ddad32a45b6282c788c26a
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/14/2020
ms.locfileid: "47720672"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a>在 SharePoint 或 OneDrive 中限制访问权限

在 SharePoint 和 OneDrive 中，通过仅向要访问的组或个人授予访问权限，可以限制对文件、文件夹和列表等项目的访问。 默认情况下，SharePoint 中的权限从层次结构中的较高版本继承。 因此，文件从文件夹继承其权限，这将从库继承其权限，这将从网站继承权限。
  
您可以在更高的级别上进行共享 (例如，通过共享整个网站) ，如果您不想在网站上共享所有项目，则中断继承。 但是，我们不建议这样做，因为这会使这些权限在将来保持更复杂和更容易混淆。 您可以改为执行以下操作：
  
- 例如，如果您想要共享一个文件夹中除一个文件之外的所有内容，请将该文件移动到一个不共享的新位置。
    
- 如果文件夹中有两个子文件夹，并且您想要与组 A 和 B 共享一个子文件夹，并且只允许组访问第二个子文件夹，请与组 A 共享父文件夹，并将组 B 添加到第一个子文件夹中。
    
[停止共享文件或文件夹 ](https://go.microsoft.com/fwlink/?linkid=2008861)
  

