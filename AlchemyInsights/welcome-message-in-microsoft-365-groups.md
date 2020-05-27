---
title: Microsoft 365 组中的欢迎消息
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "5685"
ms.openlocfilehash: d82931ae6978a09e674b00640d1dd413bcce7cfd
ms.sourcegitcommit: b196100759b29aecd62b693a2bfedbbd25a697c6
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/19/2020
ms.locfileid: "44320445"
---
# <a name="welcome-message-in-microsoft-365-groups"></a><span data-ttu-id="9806b-102">Microsoft 365 组中的欢迎消息</span><span class="sxs-lookup"><span data-stu-id="9806b-102">Welcome message in Microsoft 365 Groups</span></span>

<span data-ttu-id="9806b-103">如果 "UnifiedGroupWelcomeMessageEnabled" 属性为 True，则加入 Microsoft 365 组的新用户将收到欢迎电子邮件。</span><span class="sxs-lookup"><span data-stu-id="9806b-103">New users joining Microsoft 365 group will receive welcome email if the "UnifiedGroupWelcomeMessageEnabled" property is True.</span></span>

<span data-ttu-id="9806b-104">如果想要禁用欢迎邮件，请使用以下 [LOP-EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps) 命令：</span><span class="sxs-lookup"><span data-stu-id="9806b-104">In case you want to disable the welcome message, use the following [EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps) command:</span></span>

`
Set-UnifiedGroup <groupname> -UnifiedGroupWelcomeMessageEnabled:$False
`
