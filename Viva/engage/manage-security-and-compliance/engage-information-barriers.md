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

# Set up Information Barriers for Viva Engage

Viva Engage supports a Publisher information bar for users that belong to an [information barriers segment](/purview/information-barriers-policies.md). Users who compose new posts or post replies receive reminders that their content is visible to every user of their network. To enable this feature for your Viva Engage network, you must [file a request in Microsoft Purview](/purview/purview-portal).

[Microsoft Purview Information Barriers](/purview/information-barriers) (IB) is a compliance feature to limit two-way communication and collaboration between certain groups and users in Microsoft Teams, Viva Engage, SharePoint, and OneDrive. Businesses in highly regulated sectors widely use this capability to observe compliance requirements, and it's suitable for all organizations that need to prevent information leakage. IBs help to avoid conflicts of interest and safeguard internal information between users and organizational areas.

## Prerequisites

Ensure you meet the following requirements to apply information bar notifications in your Viva Engage network:

- Microsoft 365 E5 Licenses
- Information barrier _segments_ and associated Microsoft Purview _policies_ must be in place. The policies are sets of data loss rules that define when engagement between different information barrier segments is allowed or blocked.

## Admin enablement process

A Viva Engage administrator can enable the information bar in the Admin center:

1) Go to **Admin center > Governance and compliance > Information barrier**.

2) The **Information barrier** toggle is disabled by default. When you enable the toggle, the page shows a list of the information barrier segments tied to your network. Any selected segments see the warnings associated with a policy.

    ![Admin panel for enabling information barriers for a network](../media/engage/admin/info-barrier-admin-settings.png)

3) Select **Save**. The information bars appear for the selected segments.

You can disable this feature for particular segments, or turn them on and off for all users through the same process.

## Experiences

Users that belong to an information barriers segment see the information bar attached to their Publisher.
