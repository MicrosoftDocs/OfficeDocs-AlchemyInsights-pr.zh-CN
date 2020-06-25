---
title: 创建组织关系，以允许你的用户与另一个组织进行协作
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3800014"
- "898"
ms.openlocfilehash: 2c6cd6a178c6e012bfe1c8d769b037168ffa3254
ms.sourcegitcommit: 722e9a0ed058cb1eab2dd053be2418b60f7d4aac
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/23/2020
ms.locfileid: "44853982"
---
# <a name="create-an-organization-relationship-to-allow-your-users-to-collaborate-with-another-organization"></a><span data-ttu-id="ae4b4-102">创建组织关系，以允许你的用户与另一个组织进行协作</span><span class="sxs-lookup"><span data-stu-id="ae4b4-102">Create an Organization Relationship to allow your users to collaborate with another organization</span></span>

1. <span data-ttu-id="ae4b4-103">从 Microsoft 365 管理中心主控板中，转到“**管理员**” > “**Exchange**”。</span><span class="sxs-lookup"><span data-stu-id="ae4b4-103">From the Microsoft 365 admin center dashboard, go to **Admin** > **Exchange**.</span></span>
2. <span data-ttu-id="ae4b4-104">转到“**组织**” > “**共享**”。</span><span class="sxs-lookup"><span data-stu-id="ae4b4-104">Go to **organization** > **sharing**.</span></span>
3. <span data-ttu-id="ae4b4-105">在“**组织共享**”下，单击“**新建**”。</span><span class="sxs-lookup"><span data-stu-id="ae4b4-105">Under **Organization Sharing**, click **New** .</span></span>
4. <span data-ttu-id="ae4b4-106">在“**新建组织关系**”中的“**关系名称**”框中，为组织关系键入友好名称。</span><span class="sxs-lookup"><span data-stu-id="ae4b4-106">In **new organization relationship**, in the **Relationship name** box, type a friendly name for the organization relationship.</span></span>
5. <span data-ttu-id="ae4b4-107">在“**要共享的域**”框中，为允许其查看日历的外部 Office 365 或 Exchange 本地组织键入域。</span><span class="sxs-lookup"><span data-stu-id="ae4b4-107">In the **Domains to share with** box, type the domain for the external Office 365 or Exchange on-premises organization you want to let see your calendars.</span></span> <span data-ttu-id="ae4b4-108">如果需要输入多个域，请用逗号将域名分隔开。</span><span class="sxs-lookup"><span data-stu-id="ae4b4-108">If you need to enter more than one domain, separate the domain names with a comma.</span></span> <span data-ttu-id="ae4b4-109">例如，contoso.com、service.contoso.com。</span><span class="sxs-lookup"><span data-stu-id="ae4b4-109">For example, contoso.com, service.contoso.com.</span></span>
6. <span data-ttu-id="ae4b4-110">Select the **Enable calendar free/busy information sharing** check box to turn on calendar sharing with the domains you listed.</span><span class="sxs-lookup"><span data-stu-id="ae4b4-110">Select the **Enable calendar free/busy information sharing** check box to turn on calendar sharing with the domains you listed.</span></span> <span data-ttu-id="ae4b4-111">Set the sharing level for calendar free/busy information and set which users can share calendar free/busy information.</span><span class="sxs-lookup"><span data-stu-id="ae4b4-111">Set the sharing level for calendar free/busy information and set which users can share calendar free/busy information.</span></span>  

<span data-ttu-id="ae4b4-112">若要设置忙/闲访问级别，请选择以下项目之一：</span><span class="sxs-lookup"><span data-stu-id="ae4b4-112">To set the free/busy access level, select one of the following:</span></span>

- <span data-ttu-id="ae4b4-113">**仅包含时间的日历忙/闲信息**</span><span class="sxs-lookup"><span data-stu-id="ae4b4-113">**Calendar free/busy information with time only**</span></span>
- <span data-ttu-id="ae4b4-114">**包含时间、主题和位置的日历忙/闲信息**</span><span class="sxs-lookup"><span data-stu-id="ae4b4-114">**Calendar free/busy with time, subject, and location**</span></span>  

 <span data-ttu-id="ae4b4-115">若要设置将共享日历忙/闲信息的用户，请选择以下项目之一：</span><span class="sxs-lookup"><span data-stu-id="ae4b4-115">To set which users will share calendar free/busy information, select one of the following:</span></span>

- <span data-ttu-id="ae4b4-116">**组织中的所有人**</span><span class="sxs-lookup"><span data-stu-id="ae4b4-116">**Everyone in your organization**</span></span>
- <span data-ttu-id="ae4b4-117">**指定安全组**</span><span class="sxs-lookup"><span data-stu-id="ae4b4-117">**A specified security group**</span></span>  

<span data-ttu-id="ae4b4-118">单击“**浏览**”从列表中选取安全组，然后单击“**确定**”。</span><span class="sxs-lookup"><span data-stu-id="ae4b4-118">Click **browse** to pick the security group from a list, then click **ok**.</span></span>

<span data-ttu-id="ae4b4-119">单击“**保存**”创建组织关系。</span><span class="sxs-lookup"><span data-stu-id="ae4b4-119">Click **save** to create the organization relationship.</span></span>  

<span data-ttu-id="ae4b4-120">**注意：** 交叉租户配置不支持针对个人联系人的忙/闲查找。</span><span class="sxs-lookup"><span data-stu-id="ae4b4-120">**Note:** Cross-tenant configurations do not support personal contacts for free/busy lookup.</span></span> <span data-ttu-id="ae4b4-121">联系人必须包含在全局地址列表中，才能进行忙/闲查找。</span><span class="sxs-lookup"><span data-stu-id="ae4b4-121">Contacts must be included in the global address list for free/busy lookup to work.</span></span>

<span data-ttu-id="ae4b4-122">**如需全面了解本主题，请阅读：**</span><span class="sxs-lookup"><span data-stu-id="ae4b4-122">**For full understanding of this topic please read:**</span></span>

- [<span data-ttu-id="ae4b4-123">在 Exchange Online 中创建组织关系</span><span class="sxs-lookup"><span data-stu-id="ae4b4-123">Create an organization relationship in Exchange Online</span></span>](https://docs.microsoft.com/exchange/sharing/organization-relationships/create-an-organization-relationship)
- [<span data-ttu-id="ae4b4-124">在 Exchange Online 中修改组织关系</span><span class="sxs-lookup"><span data-stu-id="ae4b4-124">Modify an organization relationship in Exchange Online</span></span>](https://docs.microsoft.com/exchange/sharing/organization-relationships/modify-an-organization-relationship)
- [<span data-ttu-id="ae4b4-125">在 Exchange Online 中删除组织关系</span><span class="sxs-lookup"><span data-stu-id="ae4b4-125">Remove an organization relationship in Exchange Online</span></span>](https://docs.microsoft.com/exchange/sharing/organization-relationships/remove-an-organization-relationship)