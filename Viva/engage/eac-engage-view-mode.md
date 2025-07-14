---
title: "Manage user privileges with view-only mode in Viva Engage"
description: "View-only mode lets Viva Engage admins remove content creation privileges from users when the need arises."
ms.reviewer: ethli
ms.author: donnabouldin
author: v-rgrace
manager: kateol
ms.date: 06/28/2025
audience: Admin
f1.keywords:
- NOCSH
ms.topic: how-to
ms.service: viva-engage
ms.localizationpriority: medium
ms.collection:  
- M365initiative-viva
- highpri
search.appverid:
- MET150
---
# Manage user privileges with view-only mode in Viva Engage

Engage admins and network admins can use view-only mode to prevent a user from contributing content to the Viva Engage network.

## User experience in view-only mode

In view-only mode, an information banner appears at the top of the Viva Engage experience, and publisher and creation features are unavailable. Users assigned to view-only mode can continue to follow others, receive and manage notifications, view analytics, report conversations, and bookmark threads. Users can also view announcements and browse content in any Viva Engage app (desktop, web, mobile, Teams, Outlook, or SharePoint).

## Limitations of view-only mode

Users of view-only mode have **no access** to the following features in Viva Engage (applies to desktop, web, mobile, Teams, Outlook, and SharePoint):

- Creation of new posts, comments, or replies to posts

- Edits of existing posts, comments, or replies

- Share content between storylines or communities (public or private)

View-only mode applies to delegators and their delegates. If the delegator is in view-only mode, their delegates don't see the information banner.

## Manage users in view-only mode

Admins can set view-only mode from the Viva Engage admin center. It works by assigning specific users to view-only mode. Once assigned, a user remains in view-only mode until removal at the admin's discretion. Viva Engage admins can add or remove view-only mode for a user at any time.

While view-only mode only affects the user's experience and privileges in Viva Engage, users can still access linked SharePoint sites and shared files.

**To assign a user to view-only mode:**

1. Go to the [Viva Engage admin center](/viva/engage/eac-overview).

2. From the **Governance and compliance tab**, select the **Manage users** option.

3. Select **Add a user**.

4. Use the search function to find and select the user name you want, and then confirm your selection.

    The user's name appears in the list of users in view-only mode with the date the status was applied and the admin who applied the status.

**To unassign a user from view-only mode:**

- In the **View-only mode** list, select the trash icon next to the user's name.

View-only mode doesn't apply to Viva Engage admin roles. Consider removing a user’s admin role before activating view-only mode.

>[!NOTE]
>When you set a user's account to view-only mode, the user isn't notified of changes to their Viva Engage network access. Admins must communicate the change by other methods such as email or messaging.

## Track activity in the Microsoft 365 user audit log

All activity from the view-only mode feature is available through the user audit logs, including:

- User ID of the user in view-only mode
- User ID of the admin who assigned the user to view-only mode or removed view-only status
- Date and time the user was placed in view-only mode or removed status
