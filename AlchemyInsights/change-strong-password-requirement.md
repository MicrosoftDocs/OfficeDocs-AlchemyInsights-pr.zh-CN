---
title: 更改强密码要求
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000105"
- "1600"
ms.openlocfilehash: 53affd2a347c004e7b21b353c2b3df98bc30a585
ms.sourcegitcommit: a7e5ca472000dfec471950bafd12eee8d7144f74
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/16/2019
ms.locfileid: "35701574"
---
# <a name="change-strong-password-requirement"></a>更改强密码要求

默认情况下需要强密码。 

使用 PowerShell 您可以使用此命令为特定用户禁用强密码:<br>
*Get-msoluser – UserPrincipalName <UserPrincipalName> – StrongPasswordRequired $false*

- [密码策略的详细信息](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [如何使用 PowerShell 连接到 O365](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [有关 PowerShell Get-msoluser 命令的详细信息](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)