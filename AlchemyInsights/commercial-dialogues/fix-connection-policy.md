---
title: 修复连接策略
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
ms.openlocfilehash: 0b6286350e706e493f6d30b7978aacedc02daff5
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/11/2021
ms.locfileid: "50736156"
---
# <a name="fix-connection-policy"></a><span data-ttu-id="12bef-102">修复连接策略</span><span class="sxs-lookup"><span data-stu-id="12bef-102">Fix connection policy</span></span>

<span data-ttu-id="12bef-103">电子邮件被标记为安全并传递到用户收件箱，因为发送 IP 地址在连接筛选器策略中标记为安全。</span><span class="sxs-lookup"><span data-stu-id="12bef-103">The email was marked safe and delivered to the user's inbox because the sending IP address was marked safe in the Connection Filter policy.</span></span> <span data-ttu-id="12bef-104">若要查看策略，请执行下列操作：</span><span class="sxs-lookup"><span data-stu-id="12bef-104">To review the policy, do the following:</span></span>

1. <span data-ttu-id="12bef-105">转到 [Office 365 安全&合规](https://go.microsoft.com/fwlink/p/?linkid=2077143)中心，然后转到"**威胁** 管理策略  >    >  [""反垃圾邮件"。](https://go.microsoft.com/fwlink/?linkid=2101518)</span><span class="sxs-lookup"><span data-stu-id="12bef-105">Go to the [Office 365 Security & Compliance Center](https://go.microsoft.com/fwlink/p/?linkid=2077143), and then go to **Threat management** > **Policy** > [Anti-spam](https://go.microsoft.com/fwlink/?linkid=2101518).</span></span>
2. <span data-ttu-id="12bef-106">在"**自定义"** 选项卡上，选择 **"连接筛选器策略**"，然后选择"编辑 **策略"。**</span><span class="sxs-lookup"><span data-stu-id="12bef-106">On the **Custom** tab, select the **Connection filter policy**, and then select **Edit policy**.</span></span>
3. <span data-ttu-id="12bef-107">查看 **IP 允许** 列表。</span><span class="sxs-lookup"><span data-stu-id="12bef-107">Review the **IP Allow** list.</span></span> <span data-ttu-id="12bef-108">查看安全 **列表** 是否已启用。</span><span class="sxs-lookup"><span data-stu-id="12bef-108">See if **Safe list** is enabled.</span></span>

    > [!NOTE]
    > <span data-ttu-id="12bef-109">Microsoft 订阅到第三方受信任发件人来源。</span><span class="sxs-lookup"><span data-stu-id="12bef-109">Microsoft subscribes to third-party sources of trusted senders.</span></span> <span data-ttu-id="12bef-110">如果 **启用** 安全列表，这些受信任的发件人不会错误地标记为垃圾邮件。</span><span class="sxs-lookup"><span data-stu-id="12bef-110">If **Safe list** is enabled, these trusted senders aren't mistakenly marked as spam.</span></span> <span data-ttu-id="12bef-111">建议选择此选项，因为这样可以减少被归类为垃圾邮件 (垃圾邮件的误报) 数量。</span><span class="sxs-lookup"><span data-stu-id="12bef-111">I recommend selecting this option, because it will reduce the number of false positives (good mail that's classified as spam) that you receive.</span></span>