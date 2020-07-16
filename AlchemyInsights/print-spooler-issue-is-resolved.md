---
title: 打印后台处理程序问题已解决
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/8/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "5151"
- "9002659"
ms.openlocfilehash: 53b1c9a8efa3cc978af8b602c8ed90430042186a
ms.sourcegitcommit: 4265a9e79db6c2a396aa80ec0ebd467bbaadf366
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/08/2020
ms.locfileid: "45083924"
---
# <a name="print-spooler-issue-is-resolved"></a>打印后台处理程序问题已解决

如果你的设备已使用 Windows 10 **操作系统内部版本 19041.329** 进行更新，你可能已观察到某些打印机无法进行打印的问题。 打印后台处理程序可能会在尝试打印时抛出错误或意外关闭，并且受影响的打印机没有输出。 该问题已在操作系统内部版本 **19041.331** 中得到解决，[KB4567523](https://support.microsoft.com/help/4567523/windows-10-update-kb4567523)。  

**持续调查**

本地安全机构子系统服务 (LSASS) 文件 (**Isass.exe**) 在某些设备上可能无法使用，显示错误消息“关键系统进程 C:\WINDOWS\system32\Isass.exe 失败，状态代码是 c0000008。 现在必须重新启动计算机。”  **Microsoft 正在努力解决问题，并将在即将发布的版本中提供更新。**

有关详细信息，请参阅 [Windows 10 版本 2004 中的已知问题](https://docs.microsoft.com/windows/release-information/status-windows-10-2004#442msgdesc)。