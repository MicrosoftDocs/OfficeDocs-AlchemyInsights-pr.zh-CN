---
title: 将 ClientAccessServerEnabled 设置为 True
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/24/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000078"
- "7342"
ms.openlocfilehash: 2adf35662797e9e9e354ddd0c513f5ce2463d07c
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/11/2021
ms.locfileid: "50736060"
---
# <a name="set-clientaccessserverenabled-to-true"></a>将 ClientAccessServerEnabled 设置为 True

如果您无法打开加密的电子邮件，而是看到 **rpmsg** 附件，请执行以下步骤：

1. 连接到 Exchange Online PowerShell。

> [!NOTE]
> 若要连接到 Exchange Online PowerShell，必须使用全局管理员或 Exchange 管理员帐户登录。

   a. 打开Windows PowerShell，然后运行以下命令： `$UserCredential = Get-Credential`
b. 在 **"Windows PowerShell凭据请求** "对话框中，输入你的工作或学校帐户和密码 c。 单击 **确定**。 

2. 运行以下命令以创建新会话：

    `$Session = New-PSSession -ConfigurationName Microsoft.Exchange -ConnectionUri https://outlook.office365.com/powershell-liveid/ -Credential $UserCredential -Authentication Basic -AllowRedirection`

    a. 运行以下命令：
    
    `Import-PSSession $Session -DisableNameChecking`

3. 运行 `Get-IRMConfiguration` 命令。

4. 检查 **ClientAccessServerEnabled** 设置。 

    a. 如果 **ClientAccessServerEnabled** 设置设置为 **False，** 请运行以下 cmdlet： `Set-IRMConfiguration -ClientAccessServerEnabled $True`

> [!TIP]
> 始终通过以下命令关闭 powershell 会话： `Remove-PSSession $Session`

有关详细信息，请参阅 [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/connect-to-exchange-online-powershell)。

