---
title: 条件访问策略
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002357"
- "4583"
ms.openlocfilehash: 8ce41d007988f2a45f1ded385ae50ac3def97c1b
ms.sourcegitcommit: 9923ce61344e22c4490549b12f65fa2896490b1f
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/01/2020
ms.locfileid: "43100410"
---
# <a name="conditional-access-policies"></a><span data-ttu-id="234bf-102">条件访问策略</span><span class="sxs-lookup"><span data-stu-id="234bf-102">Conditional Access policies</span></span>

<span data-ttu-id="234bf-103">条件访问是 Azure AD 的一项功能，可用于强制执行对环境中的应用程序的访问控制，所有这些都基于特定条件并在中心位置进行管理。</span><span class="sxs-lookup"><span data-stu-id="234bf-103">Conditional Access is a capability of Azure AD that enables you to enforce controls on the access to apps in your environment, all based on specific conditions and managed from a central location.</span></span>

<span data-ttu-id="234bf-104">了解有关 [Azure AD 条件访问](https://docs.microsoft.com/azure/active-directory/conditional-access/)的详细信息。</span><span class="sxs-lookup"><span data-stu-id="234bf-104">Learn more about [Azure AD Conditional Access](https://docs.microsoft.com/azure/active-directory/conditional-access/).</span></span>  

<span data-ttu-id="234bf-105">**注意**：如果你的租户在 2019 年 10 月 21 日后创建，并且意外收到了有关 MFA 的提示，则你的租户中可能启用了[安全性默认值](http://aka.ms/securitydefaults)。</span><span class="sxs-lookup"><span data-stu-id="234bf-105">**Note**: If your tenant was created after October 21st, 2019 and you're unexpectedly getting prompted for MFA, you likely have [security defaults](http://aka.ms/securitydefaults) enabled in your tenant.</span></span>

<span data-ttu-id="234bf-106">**管理安全性默认值**</span><span class="sxs-lookup"><span data-stu-id="234bf-106">**To Manage security defaults**</span></span>

1. <span data-ttu-id="234bf-107">使用全局管理员凭据登录[管理中心](https://go.microsoft.com/fwlink/p/?linkid=834822)。</span><span class="sxs-lookup"><span data-stu-id="234bf-107">Sign in to the [admin center](https://go.microsoft.com/fwlink/p/?linkid=834822) with your Global admin credentials.</span></span>

2. <span data-ttu-id="234bf-108">转到 [Azure Active Directory 属性](https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/Properties)。</span><span class="sxs-lookup"><span data-stu-id="234bf-108">Go to [Azure Active Directory Properties](https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/Properties).</span></span>

3. <span data-ttu-id="234bf-109">在页面底部，单击“**管理安全性默认值**”。</span><span class="sxs-lookup"><span data-stu-id="234bf-109">At the bottom of the page, click **Manage Security defaults**.</span></span>

4. <span data-ttu-id="234bf-110">单击“是”\*\*\*\* 启用安全性默认值，或单击“否”\*\*\*\* 禁用安全性默认值。</span><span class="sxs-lookup"><span data-stu-id="234bf-110">Click **Yes** to enable security defaults or **No** to disable security defaults.</span></span>