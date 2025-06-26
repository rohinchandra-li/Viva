---
title: "Add, block, or remove Viva Engage users"
f1.keywords:
- NOCSH
ms.author: donnabouldin
ms.reviewer: snarla
author: v-rgrace
manager: elizapo
ms.date: 06/23/2025
audience: Admin
ms.topic: how-to
ms.service: office-online-server
ms.localizationpriority: medium
ms.custom: Adm_Yammer
search.appverid:
- MET150
- MOE150
- YAE150
ms.assetid: 0fc72b66-cbf1-4202-bcf0-f2174ea96798
description: "Manage users and guests in Viva Engage."
---

# Manage GDPR data subject requests for Viva Engage users

Network admins, Verified admins & Engage admins can use the **Manage GDPR data subject requests** module in the Viva Engage admin center to process data subject requests for GDPR.

Before you proceed, if necessary, review the following documents:

- [Manage GDPR data subject requests in Viva Engage Enterprise](../manage-security-and-compliance/gdpr-requests-in-viva-engage-enterprise.md)

- [GDPR requests for Office 365](/compliance/regulatory/gdpr-dsr-Office365)

To remove user access to the Viva Engage network, consult the following documents:

- [Delete a user from your tenant](/entra/fundamentals/how-to-create-delete-users)

- [Manage access through Viva Engage licensing](../manage-engage-licenses-microsoft-365.md)

## Remove a user based upon a GDPR request

1. Go to the Viva Engage Admin Center.
2. Select **Governance and compliance > Data management**.
3. Check the options for **Manage GDPR data subject requests**. GDPR subject requests support three distinct options:

   - **Permanently remove this user, but retain their messages** - Removes the user and retains their posted messages and content.
   - **Permanently remove this user, and remove their messages** - Removes the user and their posted messages and content. You can't reverse this action.
   - **Erase this user. Wipe their name and personal information, but leave their messages (Can't be undone after 14 days)** - Deactivates the user for 14 days to give the admin time to evaluate files and messages before permanently deleting the user.

4. When finished, select **Remove user**.

The following image illustrates.

![Admins can remove users based upon Admin Center options](/viva/media/engage/admin/admin-center-data-management-request.png)

GDPR subject requests support three distinct options:

- **Permanently remove this user, but retain their messages** - Removes the user and retains their posted messages and content.
- **Permanently remove this user, and remove their messages** - Removes the user and their posted messages and content. You can't reverse this action.
- **Erase this user. Wipe their name and personal information, but leave their messages (Can't be undone after 14 days)** - Deactivates the user for 14 days to give the admin time to evaluate files and messages before permanently deleting the user.

All choices for deletion remove the following data:

- Who the user follows, what conversations and articles they follow, and who follows them

- The user's bookmarks, language preferences, notification settings, and account activity

- The user profile

- The user's group memberships

- Org chart

- The list of networks for which they were a member.

The first two deletion options preserve the user's name in Viva Engage's stored data. The **Erase this user** option also removes the user's name.
