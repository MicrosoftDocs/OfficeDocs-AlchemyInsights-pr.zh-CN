---
title: 在门户中复制设备记录
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001495"
- "4386"
ms.openlocfilehash: 277afc59705e6040f0f9ae0c8cad965bd7d3ef65
ms.sourcegitcommit: 89ae9e8b36d1980f89f07b016fff0ec48f96b620
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2020
ms.locfileid: "43789587"
---
# <a name="duplicate-device-record-in-the-portal"></a><span data-ttu-id="d6590-102">在门户中复制设备记录</span><span class="sxs-lookup"><span data-stu-id="d6590-102">Duplicate device record in the portal</span></span>

<span data-ttu-id="d6590-103">如果设备未正确向 Configuration Manager 网站报告共同管理状态，则可能会在门户中看到一个设备的 2 个记录。</span><span class="sxs-lookup"><span data-stu-id="d6590-103">You may see 2 records for a device in the portal if the device does not correctly report the co-management status to the Configuration Manager site.</span></span> <span data-ttu-id="d6590-104">要检查设备的共同管理状态，请查看 Configuration Manager 控制台中设备的“**共同托管**”列。</span><span class="sxs-lookup"><span data-stu-id="d6590-104">To check the co-management status of a device, review the **Co-managed** column for the device in the Configuration Manager console.</span></span> <span data-ttu-id="d6590-105">如果看不到该列，可通过右键单击任一列标题，然后从列表中选择来进行添加。</span><span class="sxs-lookup"><span data-stu-id="d6590-105">If the column is not visible, you may add it by right-clicking any of the column headers, and selecting it from the list.</span></span>

<span data-ttu-id="d6590-106">“共同托管”值必须为“**是**”。</span><span class="sxs-lookup"><span data-stu-id="d6590-106">The Co-managed value must be **Yes**.</span></span> <span data-ttu-id="d6590-107">如果该值为“**否**”，请在客户端设备上打开 Configuration Manager 客户端小程序，然后勾选“常规”选项卡中的“**共同管理**”属性。</span><span class="sxs-lookup"><span data-stu-id="d6590-107">If the value is **No**, open the Configuration Manager client applet on the client device and check the **Co-management** property in the General tab.</span></span>

- <span data-ttu-id="d6590-108">如果该值为“**已启用**”，则表示与管理点的客户端通信存在问题。</span><span class="sxs-lookup"><span data-stu-id="d6590-108">If the value is **Enabled**, this indicates problems with client communication with the Management Point.</span></span> <span data-ttu-id="d6590-109">请查看设备上的 **CcmMessaging.log**，调查可能存在的连接性问题。</span><span class="sxs-lookup"><span data-stu-id="d6590-109">Please review the **CcmMessaging.log** on the device to investigate potential connectivity issues.</span></span>

- <span data-ttu-id="d6590-110">如果该值为“**已禁用**”且设备已在 Intune 中注册，请查看设备上的 **CoManagementHandler.log**，确保设备已收到共同管理策略。</span><span class="sxs-lookup"><span data-stu-id="d6590-110">If the value is **Disabled** and the device is enrolled in Intune, please ensure that the device has received the Co-management policy by reviewing the **CoManagementHandler.log** on the device.</span></span>