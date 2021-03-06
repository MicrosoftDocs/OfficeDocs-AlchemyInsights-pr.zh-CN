---
title: 适用于美国银行帐户编号的 DLP 规则不起作用
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1287"
- "3200001"
ms.assetid: 80b40145-8376-4c3a-8d22-6efb9f9cb271
ms.openlocfilehash: eb399e4b23de32a757562833ed32d97daa6a1247
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/14/2020
ms.locfileid: "47679286"
---
# <a name="dlp-issues-with-us-bank-account-numbers"></a>包含美国银行帐户号的 DLP 问题

**重要信息：** 在这段前所未有的时期，我们正在采取措施确保 SharePoint Online 和 OneDrive 服务高度可用，请访问 [SharePoint Online 临时功能调整](https://aka.ms/ODSPAdjustments)，获取详细信息。

**包含美国银行帐户号的 DLP 问题**

您是否遇到 **数据丢失防护问题 (dlp) ** 在 O365 中使用 DLP 敏感信息类型时，不能处理包含 **美国银行帐号** 的内容？ 如果是这样，请确保您的内容包含在评估时 DLP 策略要查找的内容所需的信息。
  
例如，对于配置为可信度为85% 的 **美国银行帐户号** 策略，将对其进行评估，并且必须检测到规则才能触发以下条件：
  
- **[格式：](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-77)** 8-17 位

- **[Pattern：](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-77)** 8-17 连续数字。

- **[校验和：](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-76)** 否，没有校验和

- **[定义：](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)** 如果 DLP 策略在300个字符的邻近度内检测到此类型的敏感信息，则 DLP 策略75% 确信它检测到这种类型的敏感信息：

  - 正则表达式 Regex_usa_bank_account_number 找到与该模式匹配的内容

  - 找到 Keyword_usa_Bank_Account 中的一个关键字。

    例如，以下示例将触发 **美国银行帐户号** 策略：检查帐户78344011

若要详细了解为你的内容检测 **美国银行帐号** 所需的内容，请参阅本文中的以下部分： [这些敏感信息类型对美国银行帐号的外观](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#us-bank-account-number)
  
使用不同的内置敏感信息类型，请参阅以下文章，了解其他类型所需的信息： [敏感信息类型查找的内容](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)
  