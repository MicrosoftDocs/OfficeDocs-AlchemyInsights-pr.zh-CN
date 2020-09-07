---
title: 以 Microsoft 365 组的身份发送
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 08/19/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9003200"
ms.openlocfilehash: cfb4bd5ce59eeccdd0812d013b8a444aebeb1d4c
ms.sourcegitcommit: 9818d3c8e6b10f23244e51286e2463caf48fffd5
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/21/2020
ms.locfileid: "46852989"
---
# <a name="send-as-microsoft-365-group"></a><span data-ttu-id="5843f-102">以 Microsoft 365 组的身份发送</span><span class="sxs-lookup"><span data-stu-id="5843f-102">Send As Microsoft 365 group</span></span>

<span data-ttu-id="5843f-103">可以分配“发送方式”权限，允许特定用户以 Microsoft 365 组的身份发送邮件：</span><span class="sxs-lookup"><span data-stu-id="5843f-103">You can assign Send As permissions to allow specific users to send messages as a Microsoft 365 group:</span></span>  

1. <span data-ttu-id="5843f-104">连接到 Exchange Online PowerShell。</span><span class="sxs-lookup"><span data-stu-id="5843f-104">Connect to Exchange Online PowerShell.</span></span>  

2. <span data-ttu-id="5843f-105">运行以下命令：</span><span class="sxs-lookup"><span data-stu-id="5843f-105">Run the following command:</span></span>  

    <span data-ttu-id="5843f-106">Add-RecipientPermission `<GroupName>` -Trustee `<MailboxName>` -AccessRights SendAs</span><span class="sxs-lookup"><span data-stu-id="5843f-106">Add-RecipientPermission `<GroupName>` -Trustee `<MailboxName>` -AccessRights SendAs</span></span>

<span data-ttu-id="5843f-107">有关详细信息，请参阅[允许成员以组的身份或代表组发送](https://docs.microsoft.com/microsoft-365/admin/create-groups/allow-members-to-send-as-or-send-on-behalf-of-group?view=o365-worldwide)。</span><span class="sxs-lookup"><span data-stu-id="5843f-107">For more information, see [Allow members to send as or send on behalf of a group](https://docs.microsoft.com/microsoft-365/admin/create-groups/allow-members-to-send-as-or-send-on-behalf-of-group?view=o365-worldwide).</span></span>