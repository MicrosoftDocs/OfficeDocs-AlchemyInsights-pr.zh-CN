---
title: 启用邮箱审核
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 404ef9ecd824541f98471bb8797f5f6e025012b7
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/15/2020
ms.locfileid: "47806281"
---
# <a name="enable-mailbox-auditing"></a>启用邮箱审核

若要为单个用户或整个组织启用邮箱审核，必须从远程 Power Shell 运行以下 cmdlet：
  
 **单个用户**
  
Set-邮箱-Identity "Jane Dow"-AuditEnabled $true
  
 **组织**
  
ResultSize 无限制-筛选器 {RecipientTypeDetails-eq "UserMailbox"} |Set-邮箱-AuditEnabled $true
  
[了解更多](https://docs.microsoft.com/microsoft-365/compliance/enable-mailbox-auditing)
  

