---
title: '将 Google Chrome 扩展移植到 Microsoft Edge (Chromium) '
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 12/03/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004032"
- "7102"
- "8297"
- "9004617"
ms.openlocfilehash: 1c71d74d01c1e38e4c7789aea2c0b43701b3a5de
ms.sourcegitcommit: 7b2e5078dd65f11af6650e692a7ea48e91f544e0
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/02/2021
ms.locfileid: "51505274"
---
# <a name="port-google-chrome-extensions-to-microsoft-edge-chromium"></a>将 Google Chrome 扩展移植到 Microsoft Edge (Chromium) 

可轻松将 Google [Chrome 扩展移植到 Microsoft Edge (Chromium) 。 ](https://docs.microsoft.com/microsoft-edge/extensions-chromium/developer-guide/port-chrome-extension) 在大多数情况下，在 Microsoft Edge 上运行这些扩展只需要最少的更改。

Google Chrome 支持的扩展 API 和清单密钥与 Microsoft Edge 代码兼容。 但是，Microsoft Edge 不支持扩展 API chrome.gcm、chrome.identity.getAccounts、chrome.identity.getAuthToken 和 chrome.instanceID。