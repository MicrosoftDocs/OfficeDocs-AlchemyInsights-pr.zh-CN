---
title: 解决在 Microsoft Intune 中注册 Android 设备的问题
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d0269461-20a8-4c9e-83b2-8fcf608dc0a5
ms.custom:
- "787"
- "6200002"
ms.openlocfilehash: 08620a44dcf693482c65ff05e19f11870f67afbe
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/15/2021
ms.locfileid: "51830932"
---
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a>解决在 Microsoft Intune 中注册 Android 设备的问题

查看下面列出的资源，以现在解决问题。
  
一些常见问题和解决步骤：
  
 **公司门户中的设备未加密错误：** 较新版本的 Android（特别是从 v7.0 开始）需要启动密码以确保设备已完全加密。 常见解决方案是启用启动引脚或完全加密设备。 有关详细信息 [，](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) 请查看本文档。
  
 **设备无法签入 Intune** 服务或在 Intune 管理控制台中显示为"不正常"：某些 Samsung 4.4 和 5.5 设备可能无法签入服务。 此问题有 3 种可能的解决方案：
  
1. 手动打开 Intune 公司门户应用，该应用将自动启动设备同步。

2. 将设备更新到 Android 6.0 或更高版本。

3. 禁止 Samsung 智能管理器管理 Intune 公司门户。 有关 [这些问题和](https://docs.microsoft.com/troubleshoot/mem/intune/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) 解决方法的进一步详细信息，请查看本文档。

 **用户许可证类型无效** 或用户名无法识别 **错误** ：需要为用户分配 Intune 或 EMS 许可证。 查看以下文档以通过以下方式分配许可证：Office 管理中心或 Azure 门户。
  
有助于解决问题的其他资源：
  
1. 使用 [Intune 疑难解答门户](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) 诊断和解决常见的注册失败。 有关详细信息 [，](https://docs.microsoft.com/intune/help-desk-operators) 请查看本文档。

2. 查看 [本文档，](https://docs.microsoft.com/troubleshoot/mem/intune/troubleshoot-device-enrollment-in-intune) 了解阻止注册和解决每个错误的常见错误列表。

3. [了解如何在 Microsoft Intune 中注册 Android 设备](https://docs.microsoft.com/intune/android-enroll)。
