---
title: 将SharePoint库映射到网络驱动器
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 4b8245c3-a179-4524-ae83-0c22d539c202
ms.openlocfilehash: 6b7cb38362baa26bd39fe7478ef6dd1971b5b063
ms.sourcegitcommit: f4866e94918c7b591ad0cd3b58169d340bcc7f00
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/19/2021
ms.locfileid: "52542811"
---
# <a name="map-a-sharepoint-library-to-a-network-drive"></a><span data-ttu-id="5b775-102">将SharePoint库映射到网络驱动器</span><span class="sxs-lookup"><span data-stu-id="5b775-102">Map a SharePoint library to a network drive</span></span>

<span data-ttu-id="5b775-103">与映射网络驱动器不同，SharePoint新的 OneDrive 同步客户端同步文件，该客户端提供按需文件。</span><span class="sxs-lookup"><span data-stu-id="5b775-103">Instead of mapping a network drive, sync SharePoint files with the new OneDrive sync client, which provides Files On-Demand.</span></span> <span data-ttu-id="5b775-104">无需本地存储空间即可访问所有 OneDrive 中的文件。</span><span class="sxs-lookup"><span data-stu-id="5b775-104">Access all your files in OneDrive without using local storage space.</span></span> <span data-ttu-id="5b775-105">有关详细信息，请参阅[Sync SharePoint and Teams files with your computer](https://support.microsoft.com/office/sync-sharepoint-and-teams-files-with-your-computer-6de9ede8-5b6e-4503-80b2-6190f3354a88)和 Save disk space with OneDrive Files [On-Demand for Windows 10](https://support.microsoft.com/office/save-disk-space-with-onedrive-files-on-demand-for-windows-10-0e6860d3-d9f3-4971-b321-7092438fb38e)。</span><span class="sxs-lookup"><span data-stu-id="5b775-105">For more information, see [Sync SharePoint and Teams files with your computer](https://support.microsoft.com/office/sync-sharepoint-and-teams-files-with-your-computer-6de9ede8-5b6e-4503-80b2-6190f3354a88) and [Save disk space with OneDrive Files On-Demand for Windows 10](https://support.microsoft.com/office/save-disk-space-with-onedrive-files-on-demand-for-windows-10-0e6860d3-d9f3-4971-b321-7092438fb38e).</span></span>

<span data-ttu-id="5b775-106">如果你选择映射驱动器而不是使用新的 OneDrive[同步客户端，](https://support.microsoft.com/office/sync-sharepoint-and-teams-files-with-your-computer-6de9ede8-5b6e-4503-80b2-6190f3354a88)请确保按照以下步骤操作：</span><span class="sxs-lookup"><span data-stu-id="5b775-106">If you choose to map a drive instead of using [the new OneDrive sync client](https://support.microsoft.com/office/sync-sharepoint-and-teams-files-with-your-computer-6de9ede8-5b6e-4503-80b2-6190f3354a88), make sure you follow these steps:</span></span>

- [<span data-ttu-id="5b775-107">对连接到 SharePoint Online 的映射的网络驱动器进行故障排除</span><span class="sxs-lookup"><span data-stu-id="5b775-107">Troubleshoot mapped network drives that connect to SharePoint Online</span></span>](/sharepoint/support/administration/troubleshoot-mapped-network-drives)

- [<span data-ttu-id="5b775-108">当客户端不支持 TLS 1.2 时，将发生身份验证错误</span><span class="sxs-lookup"><span data-stu-id="5b775-108">Authentication errors occur when client doesn't have TLS 1.2 support</span></span>](/sharepoint/troubleshoot/administration/authentication-errors-tls12-support#network-drive-mapped-to-a-sharepoint-library)  

<span data-ttu-id="5b775-109">**注意：** 如果使用 Internet Explorer 10 或 Windows 8 Windows 7，并且映射驱动器时收到访问被拒绝或路径不可访问，请安装此修补程序来 [解决此问题。](https://support.microsoft.com/topic/error-when-you-open-a-sharepoint-document-library-in-windows-explorer-or-map-a-network-drive-to-the-library-after-you-install-internet-explorer-10-96e640ba-059f-9b09-bb91-2a0319ee8b1d)</span><span class="sxs-lookup"><span data-stu-id="5b775-109">**NOTE:** If you use Internet Explorer 10 with Windows 8 or Windows 7, and receive **Access denied** or **Path is not accessible** when mapping a drive, resolve this problem by installing this [hotfix](https://support.microsoft.com/topic/error-when-you-open-a-sharepoint-document-library-in-windows-explorer-or-map-a-network-drive-to-the-library-after-you-install-internet-explorer-10-96e640ba-059f-9b09-bb91-2a0319ee8b1d).</span></span>