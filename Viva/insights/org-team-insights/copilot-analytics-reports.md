---
ms.date: 06/23/2025
title: Access insights easily with ready-to-use Copilot Analytics reports
description: Explains how to access and investigate insights provided by Copilot Analytics reports in the Viva Insights app in Teams.
author: zachminers
ms.author: v-zachminers
ms.topic: how-to
ms.collection: 
- viva-insights-personal
- essentials-manage
- viva-copilot
- magic-ai-copilot
ms.localizationpriority: medium 
ms.service: viva-insights
manager: anirudhbajaj
audience: user
---

# Access insights easily with ready-to-use Copilot Analytics reports

If you have access to the Microsoft Copilot Dashboard, you can also access ready-to-use Copilot Analytics reports in the Viva Insights web app. These reports provide a variety of targeted insights about the adoption and impact of Microsoft 365 Copilot across your organization. You can find them in the Viva Insights web app by selecting **Reports** on the left.

:::image type="content" source="images/copilot-reports-01.png" alt-text="Screenshot that shows where to find Copilot Analytics reports.":::

## Prerequisites 

To view these reports, you must meet **at least one** of the following requirements:  

* You must have automatic access to the Copilot Dashboard based on Microsoft Entra ID data. [Learn more](./copilot-dashboard.md#how-automatic-access-to-the-copilot-dashboard-is-determined).  

* You must have been given delegate access to the Copilot Dashboard. [Learn more](./delegate-access.md). 

* You must be a **Viva Insights Analyst** with global partition access.

## Out-of-the-box reports 

These pre-built reports help business leaders understand how employees are using Copilot across the organization, and how Copilot is impacting employee work behaviors and business objectives. Unlike custom Power BI queries, these reports can't be customized with unique filters or attributes. Select **View report** to see the insights for each.

**Copilot Studio agents** – This report can help business leaders understand the adoption and impact of Microsoft 365 Copilot custom agents across the organization. It can help users learn the top agents being used and the impact of individual agents, such as the impact of agent-assisted hours. [Learn more about this report's insights](..//advanced/analyst/templates/copilot-studio-agents.md).

:::image type="content" source="images/copilot-reports-studio-agents-01.png" alt-text="Screenshot that shows the Copilot Studio agents report.":::

**Copilot for Sales adoption** – This report can help leaders understand usage of Copilot for Sales across their organization. The insights can help business leaders accelerate Copilot for Sales adoption, and help sales teams transform their work using Copilot for Sales. The insights can help users see which Copilot for Sales actions are contributing to key sales tasks, and how Copilot for Sales usage compares across groups and apps, among other insights. [Learn more](../advanced/analyst/templates/copilot-for-sales-adoption.md).

## Shared reports

These reports are customized queries created by analysts which are shared with business leaders and users with delegate access. The report could be any configured Power BI report within Viva Insights, or a custom report that includes Viva Insights metrics or other types of metrics like surveys or Copilot metrics. Recipients of these reports can't customize them, but they can easily view their insights by selecting **View report** on the card. Shared reports have a **Shared** label at the top right.

:::image type="content" source="images/copilot-reports-shared-01.png" alt-text="Screenshot that shows shared Copilot Analytics reports.":::

## If you don't have any reports

You might see the message "No reports available" if your organization doesn't have ready-to-use reports or no reports have been shared with you. If so, contact your administrator to identify someone who can do advanced analysis in your organization.  

If your organization has already designated analysts to carry out advanced analysis, you can work with them to identify Viva Insights reports you might need, and have them customized to your needs. Once these reports are ready, the analyst can share them with you using **Publish reports**. [Learn more](../advanced/analyst/publish-reports.md).

If no one in your organization is assigned an **Insights Analyst** role, contact your administrator to assign the role in the Microsoft admin center. [Learn more about how to assign roles](../advanced/setup-maint/assign-user-roles.md).

If you don't see any admins listed in the **Contact admin** page, contact your Global admin to assign someone the **Insights Administrator** role. [Learn more about how to assign roles](../advanced/setup-maint/assign-user-roles.md).
