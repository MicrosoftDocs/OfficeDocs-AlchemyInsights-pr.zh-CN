---
title: 授予用户对 SharePoint 和 OneDrive 的访问权限
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: a7e9c0b7ffa5c11a2e24ee5fda6491f049f985f1
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/14/2020
ms.locfileid: "47677197"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a>授予用户对 SharePoint 和 OneDrive 的访问权限

> [!NOTE]
> 如果 OneDrive 或 SharePoint 网站对之前有权访问的多个用户不可用，则可能存在暂时性的服务问题。 [检查服务运行状况仪表板](https://portal.office.com/adminportal/home#/servicehealth)
  
如果您希望组织中的人员能够登录并使用 SharePoint 和 OneDrive，您需要为他们添加帐户，并确保他们拥有访问 SharePoint 和 OneDrive 的许可证。 添加用户的最简单方法是在 Microsoft 365 管理中心。
  
1. 转到 [Microsoft 365 管理中心中的 "活动用户" 页](https://portal.office.com/adminportal/home#/users)，然后单击 " **添加用户**"。
    
2. 填写用户的信息，并确保 " **产品许可证**" 下已分配 "许可证" 并选择 " **SharePoint Online** "。 
    
请注意，如果您在组织中允许外部共享，则用户可以与组织外部的人员共享 SharePoint 和 OneDrive 内容。 您无需向这些外部用户授予许可证。 您也不需要为其添加帐户，除非将 "共享" 设置为 "仅现有外部用户"。 在这种情况下，如果人员不在组织的目录中，则需要在 Azure AD 管理中心中将其添加为来宾用户。
  

