---
title: 随 Office 更新一起安装的 Teams
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2599"
- "9000140"
- "9000660"
- "2509"
ms.openlocfilehash: 36b0b1a7bf37c27304b4124157dba9aba337678c
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/15/2021
ms.locfileid: "51832372"
---
# <a name="microsoft-teams-installed-with-office-updates"></a>随 Office 更新一起安装的 Microsoft Teams

Microsoft Teams 包含在新安装的Microsoft 365 企业应用版、Microsoft 365 商业应用版和 Office for Mac。 有关详细信息，请参阅 Microsoft Teams 何时开始包含在新安装的 [Office 中？](https://docs.microsoft.com/deployoffice/teams-install#when-will-microsoft-teams-start-being-included-with-new-installations-of-microsoft-365-apps)

此外，从当前频道的版本 1906 开始，当你将现有安装更新到最新版本时，Teams 将逐渐添加到运行 Windows 的设备上 Microsoft 365 企业应用版 (和 Microsoft 365 企业应用版) 的现有安装中。 有关详细信息，请参阅 [What about existing installations of Office？](https://docs.microsoft.com/deployoffice/teams-install#what-about-existing-installations-of-microsoft-365-apps)

**注意：** 如果不想等待此推出计划，可以按照以下说明为用户将 Teams 部署为独立版，也可以 [](https://docs.microsoft.com/MicrosoftTeams/msi-deployment)让用户从 自行安装 https://teams.microsoft.com/downloads Teams。

如果你的组织尚未准备好部署 Teams，你可以将 Teams 从 ***新的*** 或 [](https://docs.microsoft.com/deployoffice/teams-install#how-to-exclude-microsoft-teams-from-new-installations-of-microsoft-365-apps)[现有的](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-control-the-installation-of-microsoft-teams)Office 安装中排除。 如果你希望安装 Teams，但不希望 Teams 在安装后自动为用户启动，请参阅防止 Microsoft Teams 在安装后 [自动启动](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-prevent-microsoft-teams-from-starting-automatically-after-installation)。

若要 ***从运行*** Windows 的设备卸载 Teams，请参阅 [卸载 Microsoft Teams。](https://support.office.com/article/uninstall-microsoft-teams-3b159754-3c26-4952-abe7-57d27f5f4c81) 若要从多个目标计算机或用户清理 Microsoft Teams，请参阅 [Microsoft Teams 部署清理](https://docs.microsoft.com/microsoftteams/scripts/powershell-script-teams-deployment-clean-up)。

如果你使用的是共享计算机、远程桌面服务 (RDS) 或虚拟桌面基础结构 (VDI) ，请参阅使用 Microsoft Teams 共享计算机和 [VDI 环境](https://docs.microsoft.com/deployoffice/teams-install#shared-computer-and-vdi-environments-with-microsoft-teams)。 如果你使用的是 Microsoft Office for Mac，请参阅 Mac [上的 Microsoft Teams 安装](https://docs.microsoft.com/deployoffice/teams-install#microsoft-teams-installations-on-a-mac)。

**注意：** 安装 Teams 后，它大约 [](https://docs.microsoft.com/deployoffice/teams-install#feature-and-quality-updates-for-microsoft-teams)每两周自动更新一次，并包含新功能和质量更新。 