---
title: 更改公用文件夹权限
ms.author: dmaguire
author: msdmaguire
manager: dansimp
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "633"
- "3500007"
ms.assetid: 0c37ab75-c81c-44e7-bda8-ea43263f9fdf
ms.openlocfilehash: a2a902e8fdfd8628772364c173979c633d25a169
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/14/2020
ms.locfileid: "47714237"
---
# <a name="changing-public-folder-permissions"></a><span data-ttu-id="75d5e-102">更改公用文件夹权限</span><span class="sxs-lookup"><span data-stu-id="75d5e-102">Changing public folder permissions</span></span>

<span data-ttu-id="75d5e-103">用户和 Outlook 中的管理员可以更改公用文件夹权限。</span><span class="sxs-lookup"><span data-stu-id="75d5e-103">Public folder permissions can be changed by users and administrators in Outlook.</span></span> <span data-ttu-id="75d5e-104">管理员还可以通过执行以下操作，从 Exchange 管理中心 (EAC) 中控制权限：</span><span class="sxs-lookup"><span data-stu-id="75d5e-104">Administrators can also control permissions from the Exchange Admin Center (EAC), by doing the following:</span></span>
  
1. <span data-ttu-id="75d5e-105">在 Microsoft 365 管理中心，转到 " **管理员中心** \> **Exchange**"。</span><span class="sxs-lookup"><span data-stu-id="75d5e-105">In the Microsoft 365 admin center, go to **Admin centers** \> **Exchange**.</span></span>

2. <span data-ttu-id="75d5e-106">选择 " **公用文件夹**"。</span><span class="sxs-lookup"><span data-stu-id="75d5e-106">Select **Public folders**.</span></span>

3. <span data-ttu-id="75d5e-107">在这里，可以通过向权限分配安全组来更改单个公用文件夹的权限。</span><span class="sxs-lookup"><span data-stu-id="75d5e-107">From there, you can change permissions for individual public folders by assigning security groups to permissions.</span></span> <span data-ttu-id="75d5e-108">对于最终用户，若要更改公用文件夹权限，用户需要拥有对该文件夹的所有者权限。</span><span class="sxs-lookup"><span data-stu-id="75d5e-108">For an end user to change public folder permissions, the user needs to have Owner rights on the folder.</span></span>

<span data-ttu-id="75d5e-109">请按照 [如何诊断和修复公用文件夹权限问题](https://docs.microsoft.com/exchange/troubleshoot/public-folders/public-folder-permission-issues) 中所述的过程解决公用文件夹权限问题。</span><span class="sxs-lookup"><span data-stu-id="75d5e-109">Please follow the procedure described in [How to diagnose and fix public folder permission issues](https://docs.microsoft.com/exchange/troubleshoot/public-folders/public-folder-permission-issues) to troubleshoot public folder permission issues.</span></span>

<span data-ttu-id="75d5e-110">**注意**：当您尝试更改公用文件夹的权限时，可能会遇到几个已知问题。</span><span class="sxs-lookup"><span data-stu-id="75d5e-110">**Note**: There are several known issues you might encounter when you try to change permissions on public folders.</span></span> <span data-ttu-id="75d5e-111">有关详细信息，请参阅以下文章。</span><span class="sxs-lookup"><span data-stu-id="75d5e-111">See the following articles for more information.</span></span>

- [<span data-ttu-id="75d5e-112">无法在 EAC 中对公用文件夹子文件夹应用权限</span><span class="sxs-lookup"><span data-stu-id="75d5e-112">Can't apply permissions to public folder subfolders in EAC</span></span>](https://docs.microsoft.com/exchange/troubleshoot/public-folders/can%E2%80%99t-apply-permissions-public-folder-subfolders)

- [<span data-ttu-id="75d5e-113">"在访问公用文件夹时，在本地林中找不到邮箱" 错误</span><span class="sxs-lookup"><span data-stu-id="75d5e-113">"The mailbox is not found in the local forest" error when you access public folders</span></span>](https://docs.microsoft.com/exchange/troubleshoot/public-folders/mailbox-not-found-local-forest-public-folder)
