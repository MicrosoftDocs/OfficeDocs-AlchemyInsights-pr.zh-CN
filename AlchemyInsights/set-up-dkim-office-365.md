---
title: 安装 DKIM
ms.author: chrisda
author: chrisda
manager: dansimp
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1388
ms.assetid: ''
ms.openlocfilehash: b34bfdafcab6229a4dd2e9d9f23103fa13556482
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/15/2020
ms.locfileid: "47808697"
---
# <a name="setup-dkim"></a>安装 DKIM

在 Microsoft 365 中为自定义域配置 DKIM 的完整[说明如下所示。](https://docs.microsoft.com/microsoft-365/security/office-365-security/use-dkim-to-validate-outbound-email#steps-you-need-to-do-to-manually-set-up-dkim)

1. 对于 **每个** 自定义域，您需要在您的域的 DNS 托管服务 (中创建 **两个** DKIM CNAME 记录。通常，域注册器) 。 例如，contoso.com 和 fourthcoffee.com 需要四个 DKIM CNAME 记录：两个用于 contoso.com，两个用于 fourthcoffee.com。

   **每个**自定义域的 DKIM CNAME 记录使用以下格式：

   - **主机名**： `selector1._domainkey.<CustomDomain>`

     **指向 "地址" 或 "值**"： `selector1-<DomainGUID>._domainkey.<InitialDomain>`

     **TTL**：3600

   - **主机名**： `selector2._domainkey.<CustomDomain>`

     **指向 "地址" 或 "值**"： `selector2-<DomainGUID>._domainkey.<InitialDomain>`

     **TTL**：3600

   \<DomainGUID\> 是左侧的自定义域的 `.mail.protection.outlook.com` 自定义 MX 记录中的文本 (例如， `contoso-com` 对于 domain contoso.com) 。 \<InitialDomain\> 是注册 Microsoft 365 时使用的域 (例如，contoso.onmicrosoft.com) 。

2. 为自定义域创建 CNAME 记录后，请完成以下说明：

   a. 使用你的工作或学校帐户[登录到 Microsoft 365](https://support.office.microsoft.com/article/e9eb7d51-5430-4929-91ab-6157c5a050b4) 。

   b. 选择左上角的应用启动器图标，然后选择“**管理员**”。

   c. 在左下侧导航中，展开“管理”并选择“Exchange”。

   d. 转到**保护**  >  **DKIM**。

   e. 选择域，然后选择 " **Enable**为**此域使用 DKIM 签名启用签名邮件**"。 为每个自定义域重复执行这一步。
