---
title: "Enable advanced moderation from the admin center"
description: "Describes the straightforward process for enabling and verifying the Viva Engage AI Summarization service."
ms.reviewer: shreyanarla
ms.author: donnabouldin
author: v-rgrace
manager: donnabouldin
ms.date: 05/21/2025
audience: Admin
f1.keywords:
- NOCSH
ms.topic: how-to
ms.service: viva-engage
ms.localizationpriority: high
ms.collection:  
- M365initiative-viva
- highpri
search.appverid:
- MET150
---

# Enable advanced moderation from the admin center

Verified admins, network admins, and corporate communicators with Advanced Moderation permissions can set custom themes to moderate and monitor conversations across the Viva Engage network. You can use theme moderation to automatically mute and report conversations. Admins and corporate communicators can quickly review conversations that match any given theme within the advanced moderation dashboard.

Theme moderation is built on the [Viva Engage **AI Summarization** service](/viva/engage/engage-ai-summarization). This feature gives Viva Engage users and admins access to Large Language Model (LLM) technology with [Microsoft Responsible AI protections](https://www.microsoft.com/ai/responsible-ai).

>[!NOTE]
>Theme moderation requires at least 50% of users in your organization to have the Viva Suite license, or the Viva Employee Communications and Communities license. The Microsoft 365 enterprise plan includes keyword monitoring, detected conversations, and the advanced moderation feature set.

:::image type="content" source="../media/engage/admin/lmc-adv-moderation-themes-design.png" alt-text="Define themes under the Advanced moderation tab":::

## Set up theme moderation

Check your Viva Engage Admin Center settings to ensure that the **AI Summarization** setting reflects your network preferences. You can find the controls for this setting through Viva Feature Access Management. It controls all AI data processing for your network. By default, AI summarization is enabled and processes data across all users in your network unless you specify otherwise.

:::image type="content" source="../media/engage/admin/admin-center-ai-summarization-settings.png" alt-text="AI summarization in Admin Center":::

Network admins and corporate communicators can use theme moderation to track conversations related to their themes. Viva Engage supports concurrent use of up to 30 themes at a time. The feature is available in the Advanced Moderation page of the Communications dashboard.

When you add new themes, ongoing conversations that match themes start to populate the **Advanced moderation > Detected conversations** table.

>[!NOTE]
>Retroactive detection doesn't take place for existing conversations that match newly added themes.

## See also

[The Communications dashboard](https://support.microsoft.com/topic/communications-dashboard-bbef4b52-ffb2-4832-8e5b-709bd04bee3b)

For a more detailed walkthrough of advanced moderation and its use of themes, see [Communications dashboard: Advanced moderation](https://support.microsoft.com/topic/communications-dashboard-bbef4b52-ffb2-4832-8e5b-709bd04bee3b).

[AI Summarization and theme extraction FAQ](lmc-ai-summ-and-theme-extraction-faq.md)

[Admin roles for Advanced moderation and Keyword monitoring](lmc-keyword-monitoring-admin-article.md)

[Advanced moderation: keyword monitoring for Viva Engage admins](lmc-keyword-monitoring-howto-for-admin-audience.md)

For more information about how AI works in Viva Engage, see [Data, Privacy, and Security for Microsoft 365 Copilot in Viva Engage](/viva/engage/manage-security-and-compliance/data-privacy-security-copilot-engage).
