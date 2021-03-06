---
title: 1336 RecoverableItems 文件夹已满
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
- "1336"
- "3700003"
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: 6ae608b776332402fe333315f5e4ff6072b0a651
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/14/2020
ms.locfileid: "47741257"
---
# <a name="the-recoverable-items-folder-is-full"></a>"可恢复的项目" 文件夹已满

对于 Exchange Online 邮箱，"可恢复的项目" 文件夹的默认存储限制为 30 GB。 如果将邮箱置于诉讼保留、电子数据展示保留或被分配到保留策略，则 "可恢复的项目" 文件夹的存储限制将自动增加到 100 GB。

当 "可恢复的项目" 文件夹达到存储限制时，邮箱功能将受到以下几种影响：

- 用户不能删除邮箱中的项目。

- 托管文件夹助理无法基于保留标记或托管文件夹设置删除项目。

- 对于启用了单个项目恢复或置于保留状态的邮箱，"写入时复制" 页面保护过程无法维护用户编辑的项目的版本。

- 对于启用了邮箱审核日志记录的邮箱，不能将邮箱审核日志条目保存在 "可恢复的项目" 文件夹的 "审核" 子文件夹中。

对于不处于保留状态的邮箱，管理员可以使用 `Search-Mailbox -SearchDumpsterOnly -DeleteContent` Exchange Online PowerShell 中的命令删除 "可恢复的项目" 文件夹中的项目。 有关详细信息，请参阅下列主题：

- [搜索和删除邮件](https://docs.microsoft.com/microsoft-365/compliance/search-for-and-delete-messagesadmin-help)

- [搜索-邮箱](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)

对于处于保留状态的邮箱，管理员必须先删除保留，然后才能从 "可恢复的项目" 文件夹中删除项目。 有关详细信息，请参阅 [在保留时，删除基于云的邮箱的 "可恢复的项目" 文件夹中的项目](https://docs.microsoft.com/microsoft-365/compliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold)。

为了帮助防止 "可恢复的项目" 文件夹变满，管理员可以增加保留邮箱的 "可恢复的项目" 文件夹的存储限制，并设置将项目从 "可恢复的项目" 文件夹移动到用户的存档邮箱的邮箱保留策略。 请参阅 [增大保留邮箱的可恢复邮件配额](https://docs.microsoft.com/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold)。
