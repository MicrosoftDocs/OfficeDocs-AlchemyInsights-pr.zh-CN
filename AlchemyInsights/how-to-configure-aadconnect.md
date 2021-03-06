---
title: 646如何配置 AADConnect
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "646"
- "1300023"
ms.assetid: 599698ac-6709-477a-a66f-169b3165064e
ms.openlocfilehash: 6327e42b74283d732247c9a847c68db72082c56a
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/14/2020
ms.locfileid: "47704479"
---
# <a name="configure-sync-features"></a>配置同步功能

Azure AD Connect 包括在默认情况下启用的几项功能，或者您可以稍后启用的功能。 某些功能需要在特定环境中进行额外配置。

- [筛选](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) 限制将对象同步到 Azure AD。 默认情况下，将同步所有用户、联系人、组和 Windows 10 计算机帐户。 您可以基于域、Ou 或其他属性包含或排除对象。

- [密码哈希同步](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) 将密码哈希从本地 Active Directory 同步到 Azure AD。 这将允许在一个位置进行密码管理，但在本地和云环境中使用相同的密码。 由于 Active Directory 是权威源，因此您可以使用自己的密码策略。

- [自助服务密码重置 (SSPR) ](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) 允许用户在应用内部部署密码策略的同时重置自己在云中的密码。

- [设备写回](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) 允许 Azure AD 中的注册设备被写回本地 Active Directory，以便它们可用于条件访问。

- 默认情况下，[阻止发生意外删除](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes)，以帮助防止同时删除的对象数过多 (每个同步) 多个对象多于500个。 您可以更改此设置以满足组织的需求。

- 默认情况下会为 express 安装启用[自动升级](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade)，并有助于确保你的 Azure AD Connect 版本始终是最新的。
