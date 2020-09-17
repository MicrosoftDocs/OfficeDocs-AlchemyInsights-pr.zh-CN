---
title: 并非所有成员都会收到发送到 Microsoft 365 组的邮件
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9003200"
- "5995"
ms.openlocfilehash: d2f0674f6be135927dc5995575c14f3c2708df49
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/15/2020
ms.locfileid: "47806137"
---
# <a name="messages-sent-to-a-microsoft-365-group-are-not-received-by-all-members"></a>并非所有成员都会收到发送到 Microsoft 365 组的邮件

确保所有组成员均已订阅以接收电子邮件。 请参阅 [关注 Outlook 中的组](https://support.microsoft.com/office/e147fc19-f548-4cd2-834f-80c6235b7c36)。  

若要查看已订阅组电子邮件的成员的消息状态，请在 [EXO PowerShell](https://docs.microsoft.com/powershell/exchange/connect-to-exchange-online-powershell?view=exchange-ps) 上运行以下命令：

`Get-UnifiedGroup <GroupName> | Get-UnifiedGroupLinks -LinkType Subscribers`