---
title: 配置发送给用户的隔离通知
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
- "9002531"
- "7375"
ms.openlocfilehash: 3e3e350f74b19420155c29cb282f065e7db6d4d7
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/11/2021
ms.locfileid: "50735528"
---
# <a name="configure-quarantine-notifications-sent-to-users"></a>配置发送给用户的隔离通知

若要向用户发送有关隔离内容的通知：

1. In the admin center， navigate to **admin centers**  >  **Exchange**  >  **Protection**  >  **spam filter**.
2. 选择要打开通知的垃圾邮件筛选策略。
3. 在右侧窗格中，选择" **配置最终用户垃圾邮件通知"** 链接。
4. In the next dialog box， choose **Enable end-user spam notifications**. 选择为此策略启用垃圾邮件通知。
5. 在 **"每两天发送最终用户垃圾邮件 () ，** 指定发送用户垃圾邮件通知的发送时间。 默认值为 3 天。 您可以指定一个介于 1 到 15 天之间的值。 例如，如果您指定 7 天，则该通知将包括在过去 7 天内预期发送给该用户但实际发送到垃圾邮件隔离邮箱的所有邮件列表。
6. 在 **"通知** 语言"中，选择为此策略编写用户垃圾邮件通知的语言。
7. 选择“**保存**”。
