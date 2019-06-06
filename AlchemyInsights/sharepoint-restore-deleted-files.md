---
title: 还原已删除的文件或文件夹
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: ba1573a5-9f44-482b-8082-6f648f169449
ms.openlocfilehash: d5250d75a982c0afc9d3e1b2a43be2ba9c3e8f59
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/04/2019
ms.locfileid: "34716497"
---
## <a name="restore-a-deleted-file-or-folder"></a><span data-ttu-id="8049f-102">还原已删除的文件或文件夹</span><span class="sxs-lookup"><span data-stu-id="8049f-102">Restore a deleted file or folder</span></span>

<span data-ttu-id="8049f-103">除了实际删除之外, SharePoint Online 还会将所有内容的备份保留14天。</span><span class="sxs-lookup"><span data-stu-id="8049f-103">SharePoint Online retains backups of all content for 14 additional days beyond actual deletion.</span></span> <span data-ttu-id="8049f-104">如果无法通过 "回收站" 或 "文件还原" 来还原内容, 管理员可以联系 Microsoft 支持, 在14天的时间内随时请求还原。</span><span class="sxs-lookup"><span data-stu-id="8049f-104">If content cannot be restored via the Recycle Bin or Files Restore, an administrator can contact Microsoft Support to request a restore any time inside the 14 day window.</span></span> <span data-ttu-id="8049f-105">仅可对网站集或子网站 (而不是特定文件、列表或库) 完成备份的还原。</span><span class="sxs-lookup"><span data-stu-id="8049f-105">Restorations from backups can only be completed for site collections or sub-sites, not for specific files, lists, or libraries.</span></span>

<span data-ttu-id="8049f-106">从 Sharepoint 中删除项目或网站时, 不会立即将其删除。</span><span class="sxs-lookup"><span data-stu-id="8049f-106">When you delete an item or site from Sharepoint, it isn't immediately removed.</span></span> <span data-ttu-id="8049f-107">已删除邮件在一段时间内进入回收站。</span><span class="sxs-lookup"><span data-stu-id="8049f-107">Deleted items go into the recycle bin for a period of time.</span></span> <span data-ttu-id="8049f-108">在这段时间内, 您可以将删除的项目还原到其原始位置。</span><span class="sxs-lookup"><span data-stu-id="8049f-108">During that time, you can restore the items you deleted to their original location.</span></span> <span data-ttu-id="8049f-109">有关详细信息, 请访问下面的链接。</span><span class="sxs-lookup"><span data-stu-id="8049f-109">For more information, please visit the links below.</span></span>

<span data-ttu-id="8049f-110">[在 SharePoint 网站的回收站中还原项目](https://support.office.com/en-us/article/restore-deleted-items-from-the-site-collection-recycle-bin-5fa924ee-16d7-487b-9a0a-021b9062d14b?ui=en-US&amp;rs=en-US&amp;ad=US)。</span><span class="sxs-lookup"><span data-stu-id="8049f-110">[Restore items in the Recycle Bin of a SharePoint site](https://support.office.com/en-us/article/restore-deleted-items-from-the-site-collection-recycle-bin-5fa924ee-16d7-487b-9a0a-021b9062d14b?ui=en-US&amp;rs=en-US&amp;ad=US).</span></span>

[<span data-ttu-id="8049f-111">在 OneDrive 中还原已删除的文件或文件夹</span><span class="sxs-lookup"><span data-stu-id="8049f-111">Restore deleted files or folders in OneDrive</span></span>](https://support.office.com/en-us/article/Restore-deleted-files-or-folders-in-OneDrive-949ada80-0026-4db3-a953-c99083e6a84f)

[<span data-ttu-id="8049f-112">还原已删除的网站集 (包括组、通信和其他网站)</span><span class="sxs-lookup"><span data-stu-id="8049f-112">Restore a deleted site collection (Including group, communication and other sites)</span></span>](https://docs.microsoft.com/sharepoint/restore-deleted-site-collection)

[<span data-ttu-id="8049f-113">还原已删除的 OneDrive 网站</span><span class="sxs-lookup"><span data-stu-id="8049f-113">Restore a deleted OneDrive site</span></span>](https://docs.microsoft.com/en-us/onedrive/restore-deleted-onedrive)

<span data-ttu-id="8049f-114">对于批量回收站操作, 管理员可以考虑使用[Sharepoint ONLINE PNP](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps)。</span><span class="sxs-lookup"><span data-stu-id="8049f-114">For bulk recycle bin actions, admins may consider using [Sharepoint Online PNP](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps).</span></span>

## <a name="files-restore-feature"></a><span data-ttu-id="8049f-115">文件还原功能</span><span class="sxs-lookup"><span data-stu-id="8049f-115">Files Restore feature</span></span>

<span data-ttu-id="8049f-116">如果大量 OneDrive 或 Sharepoint 文件被恶意软件删除、覆盖、损坏或感染, 则可以使用 "文件还原" 功能将整个 OneDrive 或 Sharepoint 库还原到以前的某个时间。</span><span class="sxs-lookup"><span data-stu-id="8049f-116">If lots of your OneDrive or Sharepoint files get deleted, overwritten, corrupted, or infected by malware, you can restore your entire OneDrive or Sharepoint library to a previous time using the files restore feature.</span></span>

[<span data-ttu-id="8049f-117">还原 OneDrive 库</span><span class="sxs-lookup"><span data-stu-id="8049f-117">Restore a OneDrive library</span></span>](https://support.office.com/en-us/article/restore-your-onedrive-fa231298-759d-41cf-bcd0-25ac53eb8a15)

[<span data-ttu-id="8049f-118">还原文档库</span><span class="sxs-lookup"><span data-stu-id="8049f-118">Restore a Document library</span></span>](https://support.office.com/en-us/article/restore-a-document-library-317791c3-8bd0-4dfd-8254-3ca90883d39a?ui=en-US&amp;rs=en-US&amp;ad=US.)
