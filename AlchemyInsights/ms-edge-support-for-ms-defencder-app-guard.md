---
title: Microsoft Edge 对 Microsoft Defender 应用程序防护的支持
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 12/05/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004024"
- "7090"
ms.openlocfilehash: 65cbc867ea7d1c73ca2906f51f72aa3376f31b5d
ms.sourcegitcommit: 2e4a5153e530bf15744a52e982eeb0d99757e9d2
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 12/04/2020
ms.locfileid: "49576436"
---
# <a name="microsoft-edges-support-for-microsoft-defender-application-guard"></a><span data-ttu-id="328ad-102">Microsoft Edge 对 Microsoft Defender 应用程序防护的支持</span><span class="sxs-lookup"><span data-stu-id="328ad-102">Microsoft Edge's support for Microsoft Defender Application Guard</span></span>

<span data-ttu-id="328ad-103">为 Windows 10 和 Microsoft Edge 而设计，应用程序防护使用硬件隔离方法，该方法允许用户在独立的、支持 Hyper-v 的容器（与主机操作系统分开）中导航不受信任的网站。</span><span class="sxs-lookup"><span data-stu-id="328ad-103">Designed for Windows 10 and Microsoft Edge, Application Guard uses a hardware-isolation approach that lets a user navigate an untrusted site from inside an isolated, Hyper-V–enabled container, separated from the host operating system.</span></span>

<span data-ttu-id="328ad-104">企业管理员定义了受信任的网站、云资源和内部网络的列表。</span><span class="sxs-lookup"><span data-stu-id="328ad-104">An enterprise admin defines a list of trusted websites, cloud resources, and internal networks.</span></span> <span data-ttu-id="328ad-105">当用户访问不在列表中的网站时，Microsoft Edge 将在容器中打开该网站。</span><span class="sxs-lookup"><span data-stu-id="328ad-105">When a user visits a site that's not on the list, Microsoft Edge will open the site in the container.</span></span> <span data-ttu-id="328ad-106">这意味着，如果网站发出恶意，主机将保持受保护状态，并且攻击者无法访问企业数据。</span><span class="sxs-lookup"><span data-stu-id="328ad-106">This means that if the site turns out to be malicious, the host PC will remain protected and the attacker won't get to the enterprise data.</span></span>

<span data-ttu-id="328ad-107">Microsoft Edge 版本81支持容器中的扩展安装，并且可以通过策略对其进行控制。</span><span class="sxs-lookup"><span data-stu-id="328ad-107">Installation of extensions in the container is supported as of Microsoft Edge version 81, and it can be controlled via a policy.</span></span> <span data-ttu-id="328ad-108">应在 ExtensionInstallForcelist 策略中使用的 updateURL 地址作为应用程序防护使用的网络隔离策略中的非特定资源添加。</span><span class="sxs-lookup"><span data-stu-id="328ad-108">The updateURL address that gets used in the ExtensionInstallForcelist policy should be added as a Neutral Resource in the Network Isolation policies used by Application Guard.</span></span>

<span data-ttu-id="328ad-109">有关详细信息，请参阅 microsoft [Edge 支持的 Microsoft Defender 应用程序防护](https://go.microsoft.com/fwlink/?linkid=2134229)。</span><span class="sxs-lookup"><span data-stu-id="328ad-109">For more info, see [Microsoft Edge support for Microsoft Defender Application Guard](https://go.microsoft.com/fwlink/?linkid=2134229).</span></span>
