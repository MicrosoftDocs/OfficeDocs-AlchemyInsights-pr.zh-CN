---
title: 一名用户在 Outlook 中看不到加载项
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/16/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: ''
ms.openlocfilehash: 8c99b443a2d83f3ac24362d63cd6363a66a81393
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/14/2020
ms.locfileid: "47719655"
---
# <a name="single-user-not-seeing-add-ins-in-outlook"></a><span data-ttu-id="26a51-102">一名用户在 Outlook 中看不到加载项</span><span class="sxs-lookup"><span data-stu-id="26a51-102">Single user not seeing add-ins in Outlook</span></span>

<span data-ttu-id="26a51-103">该用户属于的角色可能没有正确的 AppsForOfficeEnabled 参数。</span><span class="sxs-lookup"><span data-stu-id="26a51-103">The user might be part of a role that doesn’t have the correct AppsForOfficeEnabled parameter.</span></span> <span data-ttu-id="26a51-104">请运行以下 cmdlet，检查该用户是否已关联适当的角色：</span><span class="sxs-lookup"><span data-stu-id="26a51-104">Run this cmdlet to find out if the correct role is associated with the user:</span></span>

<span data-ttu-id="26a51-105">Get-ManagementRoleAssignment -RoleAssignee user@domain.com -Delegating $false | Format-Table -Auto Role,RoleAssigneeName,RoleAssigneeType</span><span class="sxs-lookup"><span data-stu-id="26a51-105">Get-ManagementRoleAssignment -RoleAssignee user@domain.com -Delegating $false | Format-Table -Auto Role,RoleAssigneeName,RoleAssigneeType</span></span>

<span data-ttu-id="26a51-106">有关详细信息，请参阅[指定可安装和管理 Outlook 加载项的管理员和用户](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/add-ins-for-outlook/specify-who-can-install-and-manage-add-ins)。</span><span class="sxs-lookup"><span data-stu-id="26a51-106">For more info, see [Specify the administrators and users who can install and manage add-ins for Outlook](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/add-ins-for-outlook/specify-who-can-install-and-manage-add-ins).</span></span>
