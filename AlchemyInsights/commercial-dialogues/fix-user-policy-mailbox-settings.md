---
title: 修复用户策略/邮箱设置
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000760"
- "7391"
ms.openlocfilehash: ca998c453fcb0905b122436f0eea384a9b8a9992
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/11/2021
ms.locfileid: "50736151"
---
# <a name="fix-user-policymailbox-settings"></a><span data-ttu-id="63273-102">修复用户策略/邮箱设置</span><span class="sxs-lookup"><span data-stu-id="63273-102">Fix user policy/mailbox settings</span></span>

<span data-ttu-id="63273-103">邮箱上的垃圾邮件设置影响此邮件。</span><span class="sxs-lookup"><span data-stu-id="63273-103">The junk mail settings on the mailbox affected this message.</span></span> <span data-ttu-id="63273-104">若要查看设置，请执行下列操作：</span><span class="sxs-lookup"><span data-stu-id="63273-104">To review the settings, do the following:</span></span>

1. <span data-ttu-id="63273-105">启动 Exchange 命令行管理程序。</span><span class="sxs-lookup"><span data-stu-id="63273-105">Launch Exchange Management Shell.</span></span> <span data-ttu-id="63273-106">有关详细信息，请参阅[Open the Exchange Management Shell](https://go.microsoft.com/fwlink/?linkid=2101432)。</span><span class="sxs-lookup"><span data-stu-id="63273-106">For more information, see [Open the Exchange Management Shell](https://go.microsoft.com/fwlink/?linkid=2101432).</span></span>
2. <span data-ttu-id="63273-107">使用用户 (电子邮件地址运行此命令  **) ：get-mailboxjunkmailconfiguration -identity "user@domain.com"**</span><span class="sxs-lookup"><span data-stu-id="63273-107">Run this command (using the user's email address):  **get-mailboxjunkmailconfiguration -identity "user@domain.com"**</span></span>
3. <span data-ttu-id="63273-108">检查发件人的电子邮件地址是 **TrustedSendersAndDomains** 还是 **BlockedSendersAndDomains 的一部分**。</span><span class="sxs-lookup"><span data-stu-id="63273-108">Check if the sender's email address is part of **TrustedSendersAndDomains** or **BlockedSendersAndDomains**.</span></span> <span data-ttu-id="63273-109">如果电子邮件地址位于其中一个列表中，您可能需要将其删除。</span><span class="sxs-lookup"><span data-stu-id="63273-109">If the email address is in one of the lists, you may have to remove it.</span></span> <span data-ttu-id="63273-110">若要了解更多信息，请参阅 [Set-MailboxJunkEmailConfiguration](https://go.microsoft.com/fwlink/?linkid=2101047)。</span><span class="sxs-lookup"><span data-stu-id="63273-110">To learn more, see [Set-MailboxJunkEmailConfiguration](https://go.microsoft.com/fwlink/?linkid=2101047).</span></span>