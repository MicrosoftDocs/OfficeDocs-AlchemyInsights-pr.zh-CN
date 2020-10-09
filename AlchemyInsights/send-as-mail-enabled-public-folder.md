---
title: 在 EXO 中以启用邮件的形式发送公用文件夹
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1956"
- "3500007"
ms.openlocfilehash: 0765262c04571e7df139de993611fd6e67068c54
ms.sourcegitcommit: 45635cc7a6c36d6c7b5f78215ad32f2aa7e3aed0
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/08/2020
ms.locfileid: "48394685"
---
# <a name="sendas-mail-enabled-public-folder"></a>SendAs 启用邮件的公用文件夹

下面的示例将已启用邮件的公用文件夹 NewPF1 的 "代理发送" 权限分配给用户 Jason。

Add-RecipientPermission-Identity "NewPF1"-受信者 "Jason"-AccessRights "SendAs"

有关详细的语法和参数信息，请参阅为 [已启用邮件的公用文件夹分配 "代理发送" 或 "代表发送" 权限](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/assign-permissions-mail-enabled-pfs)。
