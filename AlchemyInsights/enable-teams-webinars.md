---
title: 启用 Teams 网络研讨会
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 06/02/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "11513"
- "9006672"
ms.openlocfilehash: 5a732e6746e9fd23e54a0b2ffeabb59623012a0e
ms.sourcegitcommit: 9de78b30602f917d58705057cdcce31fec349969
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/04/2021
ms.locfileid: "52760827"
---
# <a name="enable-teams-webinars"></a>启用 Teams 网络研讨会

默认情况下启用网络研讨会。 可以通过使用 Teams PowerShell 命令来管理谁可以安排和注册 Teams 网络研讨会。

- 所有可以创建会议的用户也可以创建网上研讨会会议。 如果要管理谁可以安排团队网络研讨会，请使用 *AllowMeetingRegistration*。 
- 默认情况下，*WhoCanRegister* 处于启用状态，并已设置为“**所有人**”。 如果要关闭会议注册，请将 *AllowMeetingRegistration* 设置为 **False**。

要更改这些设置，必须安装 [Teams PowerShell](/microsoftteams/teams-powershell-install)。 并将对 Teams 网络研讨会强制实施会议策略。 例如，如果在会议设置中关闭了匿名加入，则匿名用户将无法加入网络研讨会。

要了解关于配置谁可以注册网络研讨会的详细信息，请参阅 [配置谁可以注册网络研讨会](/microsoftteams/set-up-webinars?source=docs#configure-who-can-register-for-webinars)。 有关 Microsoft Lists 设置的详细信息，请参阅 [Microsoft Lists 的控制设置](/sharepoint/control-lists)。