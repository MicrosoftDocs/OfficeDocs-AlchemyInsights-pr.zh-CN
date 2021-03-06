---
title: '修复租户策略 (替代) '
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
ms.openlocfilehash: bc7ad8acd86c9d5b2f99ffdc6fe8a8b53e1fcb8b
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/11/2021
ms.locfileid: "50735609"
---
# <a name="fix-tenant-policy-action-override"></a>修复租户策略 (替代) 

租户中的反垃圾邮件策略影响此邮件。 若要查看策略，请执行下列操作：

1. 转到 [Office 365 安全&合规](https://go.microsoft.com/fwlink/p/?linkid=2077143)中心，然后转到"**威胁** 管理策略  >    >  [""反垃圾邮件"。](https://go.microsoft.com/fwlink/?linkid=2101518)
2. 检查策略源 **是否** 指示以下内容  **：Add-Xheader/ModifySubject/Redirect/Delete/No action/ BCC message**

    如果是，请在" **自定义"** 选项卡上，检查影响邮件的策略设置。 应用于所有 Exchange Online Protection 客户的 **标准** 设置可能会影响邮件。

有关配置垃圾邮件筛选器策略的信息，请参阅 [配置垃圾邮件筛选器策略](https://go.microsoft.com/fwlink/?linkid=2101431)。
