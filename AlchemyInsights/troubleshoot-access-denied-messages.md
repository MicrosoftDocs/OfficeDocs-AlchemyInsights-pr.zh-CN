---
title: 访问被拒绝邮件疑难解答
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 6c8ad84123fb58b73b9c378592ce970997893ea2
ms.sourcegitcommit: 0eb4f9bde53395b5fd4b5cd4ffc56ca96db91298
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/10/2021
ms.locfileid: "50704884"
---
# <a name="troubleshoot-access-denied-messages"></a><span data-ttu-id="5be93-102">访问被拒绝邮件疑难解答</span><span class="sxs-lookup"><span data-stu-id="5be93-102">Troubleshoot Access Denied messages</span></span>

<span data-ttu-id="5be93-103">如果有人收到 SharePoint 中共享文件夹的"拒绝访问"消息，网站集管理员可能已启用"受限访问用户权限锁定模式"。</span><span class="sxs-lookup"><span data-stu-id="5be93-103">If someone got an "Access Denied" message to a shared folder in SharePoint, the site collection administrator might have enabled "Limited-access user permission lockdown mode."</span></span> <span data-ttu-id="5be93-104">若要关闭此功能，请：</span><span class="sxs-lookup"><span data-stu-id="5be93-104">To turn this off:</span></span> 
  
1. <span data-ttu-id="5be93-105">浏览到该网站，单击"设置"图标，然后单击"**网站设置"。**</span><span class="sxs-lookup"><span data-stu-id="5be93-105">Browse to the site, click the Settings icon, and then click **Site Settings**.</span></span>
    
2. <span data-ttu-id="5be93-106">在“网站集管理”下，单击“网站集功能”。</span><span class="sxs-lookup"><span data-stu-id="5be93-106">Under **Site Collection Administration**, click **Site collection features**.</span></span>
    
3. <span data-ttu-id="5be93-107">在 **受限访问权限用户权限锁定模式** 旁边，单击 **"停用"。**</span><span class="sxs-lookup"><span data-stu-id="5be93-107">Next to **Limited-access user permission lockdown mode**, click **Deactivate**.</span></span>
    
<span data-ttu-id="5be93-108">如果共享文件夹是发布网站，则也会发生"访问被拒绝"消息。</span><span class="sxs-lookup"><span data-stu-id="5be93-108">An Access Denied message can also occur for shared folders if the site is a publishing site.</span></span> <span data-ttu-id="5be93-109">有关信息，请参阅 [访问共享文件夹时拒绝访问](https://answers.microsoft.com/windows/forum/windows_7-files/access-denied-to-share-folder/79fae49d-cddf-4845-8ac8-c141884d85fb)。</span><span class="sxs-lookup"><span data-stu-id="5be93-109">For info, see [Access Denied when accessing a shared folder](https://answers.microsoft.com/windows/forum/windows_7-files/access-denied-to-share-folder/79fae49d-cddf-4845-8ac8-c141884d85fb).</span></span>
  
<span data-ttu-id="5be93-110">如果某人在尝试查看访问请求时收到"访问被拒绝"消息，则用户需要添加为网站集管理员或 Owners 组的成员。</span><span class="sxs-lookup"><span data-stu-id="5be93-110">If a someone got an "Access Denied" message when trying to view access requests, the user needs to be added as either a site collection administrator or a member of the Owners group for the site.</span></span> <span data-ttu-id="5be93-111">有关详细信息，请参阅 ["访问被拒绝访问请求"列表](https://go.microsoft.com/fwlink/?linkid=2004220)。</span><span class="sxs-lookup"><span data-stu-id="5be93-111">For more info, see [Access Denied to Access Requests list](https://go.microsoft.com/fwlink/?linkid=2004220).</span></span>
  
<span data-ttu-id="5be93-112">如果用户从本地 Active Directory 中删除并添加回后收到"访问被拒绝"消息，请参阅用户帐户同步到 [Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2004318)时拒绝访问。</span><span class="sxs-lookup"><span data-stu-id="5be93-112">If a user got an "Access Denied" message after they were removed from Active Directory on-premises and then added back, see [Access Denied when a user account is synced to Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2004318).</span></span>
  

