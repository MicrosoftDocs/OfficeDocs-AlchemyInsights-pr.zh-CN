---
title: 美国银行帐号不起作用的 DLP 规则
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 80b40145-8376-4c3a-8d22-6efb9f9cb271
ms.openlocfilehash: 6eae9146d33f5fc307085dbf931d57bdbb28b82e
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 01/15/2019
ms.locfileid: "28278120"
---
<span data-ttu-id="fca47-p101">您是否有问题**数据丢失防护 (DLP)** 包含**美国银行帐号**O365 中使用的 DLP 敏感信息类型时的内容不起作用？如果是这样，确保您的内容包含所需的信息的 DLP 策略查找的内容时对它求值。</span><span class="sxs-lookup"><span data-stu-id="fca47-p101">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US Bank Account Number** when using a DLP sensitive information type in O365? If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span> 
  
<span data-ttu-id="fca47-104">例如，**美国银行帐号**策略配置了 85%可信度，以下计算和必须要触发的规则检测到：</span><span class="sxs-lookup"><span data-stu-id="fca47-104">For example, for a **US Bank Account Number** policy configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span> 
  
- <span data-ttu-id="fca47-105">**[格式：](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8 17 数字</span><span class="sxs-lookup"><span data-stu-id="fca47-105">**[Format:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 digits</span></span> 
    
- <span data-ttu-id="fca47-106">**[模式：](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8 17 连续的数字。</span><span class="sxs-lookup"><span data-stu-id="fca47-106">**[Pattern:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 consecutive digits.</span></span> 
    
- <span data-ttu-id="fca47-107">**[校验和：](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** 否，没有无校验和</span><span class="sxs-lookup"><span data-stu-id="fca47-107">**[Checksum:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span> 
    
- <span data-ttu-id="fca47-108">**[定义：](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)** DLP 策略是相信它已检测到此类型的敏感信息的 75 %if、 内 300 个字符的邻近性：</span><span class="sxs-lookup"><span data-stu-id="fca47-108">**[Definition:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span> 
    
  - <span data-ttu-id="fca47-109">正则表达式 Regex_usa_bank_account_number 找到与模式匹配的内容</span><span class="sxs-lookup"><span data-stu-id="fca47-109">The regular expression Regex_usa_bank_account_number finds content that matches the pattern</span></span>
    
  - <span data-ttu-id="fca47-110">找到 Keyword_usa_Bank_Account 中的一个关键字。</span><span class="sxs-lookup"><span data-stu-id="fca47-110">A keyword from Keyword_usa_Bank_Account is found.</span></span>
    
    <span data-ttu-id="fca47-111">例如，下面的示例将触发**美国银行帐号**策略： 检查帐户 78344011</span><span class="sxs-lookup"><span data-stu-id="fca47-111">For example, the following sample would trigger for the **US Bank Account Number** policy: Checking Account 78344011</span></span> 
    
<span data-ttu-id="fca47-112">什么是**美国银行帐号**检测到了用于您的内容所需的详细信息，请参阅本文中的以下部分：[什么敏感信息类型查找美国银行帐号](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span><span class="sxs-lookup"><span data-stu-id="fca47-112">For more information on what is required for a **US Bank Account Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US Bank Account Number](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span></span>
  
<span data-ttu-id="fca47-113">使用不同的内置敏感信息类型，请参阅以下文章，获取信息什么是需要其他类型：[查找什么敏感信息类型](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="fca47-113">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  

