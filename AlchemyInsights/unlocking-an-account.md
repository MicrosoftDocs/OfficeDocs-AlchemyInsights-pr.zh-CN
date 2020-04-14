---
title: 解除帐户锁定
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002449"
- "4748"
ms.openlocfilehash: f66eb26df12412162e6f092c2528138bb30b7eb2
ms.sourcegitcommit: 6010e6b55f6d3057f9038979cda3987df12aae93
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/11/2020
ms.locfileid: "43231410"
---
# <a name="unlocking-an-account"></a><span data-ttu-id="11c9f-102">解除帐户锁定</span><span class="sxs-lookup"><span data-stu-id="11c9f-102">Unlocking an account</span></span>

<span data-ttu-id="11c9f-103">用户可能会因密码尝试不当或其他威胁而被锁定，无法再使用 Office 365。</span><span class="sxs-lookup"><span data-stu-id="11c9f-103">It's possible users are locked out of Office 365 due to bad password attempts or other compromises.</span></span> <span data-ttu-id="11c9f-104">若要帮助用户重新登录到 Microsoft 365，**可在考虑开启支持请求之前先尝试执行以下步骤**。</span><span class="sxs-lookup"><span data-stu-id="11c9f-104">To help users sign back in to Microsoft 365, **you can attempt the following steps before opening a Support Request**.</span></span> 

<span data-ttu-id="11c9f-105">**电子邮件发送受限**</span><span class="sxs-lookup"><span data-stu-id="11c9f-105">**Email Restricted**</span></span>

<span data-ttu-id="11c9f-106">作为管理员，如果你的一个用户被限制发送电子邮件，可以[自行为其解除帐户锁定](https://docs.microsoft.com/microsoft-365/security/office-365-security/removing-user-from-restricted-users-portal-after-spam)。</span><span class="sxs-lookup"><span data-stu-id="11c9f-106">As an admin, if one of your users is restricted from sending email, you can [unblock the account yourself](https://docs.microsoft.com/microsoft-365/security/office-365-security/removing-user-from-restricted-users-portal-after-spam).</span></span> <span data-ttu-id="11c9f-107">解除限制后，该用户在一小时之内便可发送电子邮件。</span><span class="sxs-lookup"><span data-stu-id="11c9f-107">The user will be able to send email within an hour after removing the restriction.</span></span>

<span data-ttu-id="11c9f-108">**重置用户密码**</span><span class="sxs-lookup"><span data-stu-id="11c9f-108">**Reset the User Password**</span></span>

1. <span data-ttu-id="11c9f-109">在管理中心中，转到 **“用户”>“活动用户”**。</span><span class="sxs-lookup"><span data-stu-id="11c9f-109">In the admin center, go to **Users > Active Users**.</span></span>

2. <span data-ttu-id="11c9f-110">选择用户，随后选择“**重置密码**”。</span><span class="sxs-lookup"><span data-stu-id="11c9f-110">Select the user and click **Reset Password**.</span></span>

<span data-ttu-id="11c9f-111">**确保允许用户登录**</span><span class="sxs-lookup"><span data-stu-id="11c9f-111">**Make sure the user is allowed to sign in**</span></span>

1. <span data-ttu-id="11c9f-112">在管理中心中，转到 **“用户”>“活动用户”**。</span><span class="sxs-lookup"><span data-stu-id="11c9f-112">In the admin center, go to **Users > Active Users**.</span></span>

2. <span data-ttu-id="11c9f-113">选择用户，然后单击“**更多操作 (...)**”，然后单击“**编辑登录状态**”。</span><span class="sxs-lookup"><span data-stu-id="11c9f-113">Select the user and click **More Actions (...)**, then click **Edit sign-in status**.</span></span>

<span data-ttu-id="11c9f-114">有关更多密码重置方案（包括自助服务密码重置）的信息，请参阅[重置 Microsoft 365 商业版密码](https://docs.microsoft.com/microsoft-365/admin/add-users/reset-passwords?view=o365-worldwide)。</span><span class="sxs-lookup"><span data-stu-id="11c9f-114">For more password reset scenarios, including Self-Service Password Reset, see [Reset Microsoft 365 business passwords](https://docs.microsoft.com/microsoft-365/admin/add-users/reset-passwords?view=o365-worldwide).</span></span>


<span data-ttu-id="11c9f-115">作为管理员，如果一个用户被限制发送邮件，可以[自行取消阻止账户](https://docs.microsoft.com/microsoft-365/security/office-365-security/removing-user-from-restricted-users-portal-after-spam)，**无需打开支持案例**。</span><span class="sxs-lookup"><span data-stu-id="11c9f-115">As an admin, if one of your users is restricted from sending email, you can [unblock the account yourself](https://docs.microsoft.com/microsoft-365/security/office-365-security/removing-user-from-restricted-users-portal-after-spam) **without opening a support case**.</span></span> <span data-ttu-id="11c9f-116">用户在解除限制后一小时内无法发送邮件。</span><span class="sxs-lookup"><span data-stu-id="11c9f-116">The user will be able to send email within an hour after removing the restriction.</span></span>

<span data-ttu-id="11c9f-117">该服务在检测到帐户被盗用和/或出站垃圾邮件的证据后，阻止用户发送电子邮件。</span><span class="sxs-lookup"><span data-stu-id="11c9f-117">The service prevents a user from sending email after detecting evidence of a compromised account and/or outbound spam.</span></span> <span data-ttu-id="11c9f-118">为预防起见，按照[响应 Office 365 中遭到入侵的电子邮件帐户](https://docs.microsoft.com/office365/securitycompliance/responding-to-a-compromised-email-account)的用户步骤执行操作。</span><span class="sxs-lookup"><span data-stu-id="11c9f-118">As a precaution, follow the steps in [Responding to a Compromised Email Account in Office 365](https://docs.microsoft.com/office365/securitycompliance/responding-to-a-compromised-email-account) for the user.</span></span>