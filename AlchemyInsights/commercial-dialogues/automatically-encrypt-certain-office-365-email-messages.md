---
title: 自动加密某些 Office 365 电子邮件
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
ms.openlocfilehash: e4b2f4ffcacf03e145b4c6d5ff6e73a75cb7c184
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/11/2021
ms.locfileid: "50735644"
---
# <a name="automatically-encrypt-certain-office-365-email-messages"></a>自动加密某些 Office 365 电子邮件

您可以自动加密用户发送给特定外部人员或组织的邮件。 为此，请执行下列步骤：

1. 从 [Exchange 管理中心，](https://outlook.office365.com/ecp/)选择"**邮件流>规则"。** 
2. 单击" **新建 (+) "** 图标，然后单击"将 Office **365** 邮件加密和权限保护应用于邮件"。
3. 在 **"** 名称"中，输入规则的名称，例如 *"加密发送到DrToniRamos@gmail.com"。*
4. In **Apply this rule if**， choose The recipient > is this **person**. 
5. 在 **"选择成员**"窗口中，选择要应用加密规则的人的姓名，然后单击"添加 **"。** 
6. 添加完用户后，单击"确定 **"。**
7. 在"执行以下操作 **"字段旁边**，单击"选择 **一个"。** 
8. 在 **RMS 模板下拉菜单中**，选择"加密 **"，** 然后单击"确定 **"。**  (如果未看到此选项，则意味着你的计划不包括自动加密。 但你可以添加它！) 
9. 从此时 (可选选择列表中选择任何可选选项，其中很多选项都可以使用默认设置，以简化) 。
10. 单击“**保存**”。

> [!IMPORTANT]
> 稍后始终可以返回并编辑此规则。

有关创建加密规则的信息，请参阅在 [Office 365](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email)中定义用于加密电子邮件的邮件流规则。

