---
title: "Information barriers in Viva Engage"
f1.keywords:
- NOCSH
ms.author: donnabouldin
author: v-rgrace
manager: kateol
ms.date: 06/30/2025
audience: Admin
ms.topic: how-to
ms.service: viva-engage
ms.collection: essentials-compliance
ms.localizationpriority: medium
search.appverid:
- MET150
- MOE150
- YAE150
ms.assetid: 
description: "Implementing Information barriers for Viva Engage"
---

# Data residency for Viva Engage

Viva Engage supports a Publisher information bar for users that belong to an [information barriers segment](https://learn.microsoft.com/purview/information-barriers-policies). Users who compose new posts or post replies receive reminders that their content is visible to every user of their network.

## Prerequisites

- Microsoft 365 E5 Licenses
- Information barrier segments and associated [Microsoft Purview](https://www.microsoft.com/en-us/security/business/information-protection/microsoft-purview-data-loss-prevention?msockid=0bc1179f3bbf637f196f02dc3a9262da) policies that are in place. The _policies_ are sets of data loss rules to define when engagement between different information barrier segments is allowed or blocked.

## Admin enablement process

A Viva Engage administrator can enable the information bar in the Admin Center:

1) Go to **Admin center > Governance and compliance > Information barrier**.

2) The **Information barrier** toggle is disabled by default. When you enable the toggle, the page shows a list of the information barrier segments tied to your network. Any selected segments see the warnings associated with a policy.

    ![Admin panel for enabling information barriers for a network](../media/engage/admin/info-barrier-admin-settings.png)

3) Select **Save**. The information bars appear for the selected segments.

You can disable this feature for particular segments or turn them on and off for all users through the same process.

## Experiences

Users that belong to an information barriers segment see the following information bar attached to their Publisher.
