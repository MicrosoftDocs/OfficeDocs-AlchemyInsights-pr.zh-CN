---
title: 为Office 365、SharePoint和OneDrive启用 ATP Microsoft Teams
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Admin_O365
ms.custom: 3100021
ms.openlocfilehash: dd367176f8d6f38f1f94ae6627229234f15c81ff
ms.sourcegitcommit: f4866e94918c7b591ad0cd3b58169d340bcc7f00
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/19/2021
ms.locfileid: "52543918"
---
# <a name="enable-microsoft-defender-for-office-365-for-sharepoint-online-onedrive-and-microsoft-teams"></a>为 Office 365 Online SharePoint、OneDrive 和 Microsoft Teams 启用 Microsoft Defender for Microsoft Teams

1. 转到 https://protection.office.com 并登录。
2. 选择 **"威胁管理**  >  **策略**  >  **保险箱附件"。**
3. 选择 **打开 Defender for Office 365 for SharePoint、OneDrive 和 Microsoft Teams，****然后单击保存。**
4.  (建议) 全局管理员或 SharePoint Online 管理员，运行 [Set-SPOTenant](/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) cmdlet，将 **DisallowInfectedFileDownload** 参数设置为 *true。*
5.  (推荐) [设置检测到的文件](/microsoft-365/security/office-365-security/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) 的警报。

> [!NOTE]
> Microsoft Defender for Office 365不会扫描 SharePoint Online、OneDrive 或 Microsoft Teams。 通过使用共享和来宾活动事件以及智能启发和威胁信号识别恶意文件的过程，以异步方式扫描文件。 请参阅[Microsoft Defender for Office 365 for SharePoint、OneDrive 和 Microsoft Teams。](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)