---
title: 1048 5.7.750 服务不可用。 阻止从未注册的域发送的客户端
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 9/28/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 8cf6d70b-9a78-4f04-ac59-7ffcf44ffd22
ms.custom: 1048
ms.openlocfilehash: 5eb42679f123fcd1b680327329721cb47e18e11a
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/22/2019
ms.locfileid: "30776492"
---
# <a name="57750-client-blocked-from-sending-from-unregistered-domain"></a>阻止从未注册域发送的5.7.750 客户端

当从未在 Office 365 中预配的域 (添加为接受域并经过验证) 中发送大量邮件时, 将发生此错误。
  
若要避免此错误, 可以使用基于证书的邮件流连接器 (其中证书的域是已设置的域), 也可以设置所有发送域。
  
