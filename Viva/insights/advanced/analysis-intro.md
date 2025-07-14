---
ms.date: 06/23/2025
title: Advanced analysis introduction
description: Learn how to use the advanced analysis features of the Microsoft Viva Insights web app 
author: zachminers
ms.author: v-zachminers
ms.topic: overview
ms.localizationpriority: medium
ms.collection: viva-insights-advanced
ms.service: viva-insights
manager: anirudhbajaj
audience: Admin
---

# Advanced analysis introduction

Microsoft Viva Insights provides tools to help analysts understand how employees use Microsoft 365 Copilot, and discover the impact of Copilot on key business outcomes within the organization. These tools include pre-defined reports, and the ability to customize reports based on organizational needs.

Viva Insights also provides scope information and research-based behavioral insights into how  an organization gets work done—for example, whether employees maintain work-life balance, how to protect employee wellbeing, and the ways hybrid work affects the employee experience. 

Viva Insights includes the [Viva Insights web app](https://go.microsoft.com/fwlink/?linkid=2201482), which has advanced analysis tools for deep-diving into data. The advanced analysis tools available in the app include different ways of analyzing and reporting custom analysis to your company’s business leaders.

* Advanced analysis [privacy](./privacy/privacy.md) explains what's important to consider for protecting your company's data and how to keep your employees' personal data private.
* [Set up](./setup-maint/setup-overview.md) describes what's required to set up the app before you can use the advanced analysis tools.
* Other documentation provides information on [preparing](./admin/prepare-org-data.md) and [uploading](./admin/upload-org-data-first.md) data, running [queries](./analyst/person-query.md), accessing query [results](./analyst/query-results.md), and using predefined [Power BI templates](./analyst/templates/introduction-to-templates.md).
* Analysts can use Microsoft 365 Copilot in Viva Insights to help them set up their queries. [Learn more](./analyst/copilot-query.md).

>[!Note]
>Advanced analysis features allow analysts to set up reports from a variety of data sources. Some of these reports might be designated as a "preview" or "preview report." Preview reports are provided under your organization's Microsoft volume licensing agreement, including the [Product Terms](https://www.microsoft.com/licensing/terms) and the [Microsoft Products and Services Data Protection Addendum](https://aka.ms/dpa) and its Processing Personal Data, GDPR, Data Security, and HIPAA Business Associate terms. A preview report, however, might rely on data from an application or service that is subject to separate terms and conditions. Microsoft might change or discontinue a preview report at any time.

## Analysis features

### Create analysis

As an analyst, the **Create analysis** page is your jumping-off point to run a custom query or run a predefined Power BI query.

> [!VIDEO 1ecc3fb9-aad1-48f3-bb8c-7ab93524219b]

Copilot can also help you choose a Power BI report or query type, and simplify the report building process by suggesting the best metrics and filters. [Learn more](./analyst/copilot-query.md).

### Analysis results

Use the **Analysis results** page to view the results of queries you and other analysts in your organization have run. 

In **Analysis results**, you can:

* Download query results as CSV, Power BI, or a direct link copied to your clipboard.
* Check a query’s status.
* **Stop** a running query.
* **Edit** or **Delete** queries if you’re the analyst who originally ran them.
* **Favorite** or **Clone** queries.
* Filter by result types.

For more information about the **Analysis results** page, refer to [Access query results and modify existing queries](./analyst/query-results.md).

### Publish reports 

Use the **Publish reports** page to share insights and reports directly with leaders, decision-makers, or an entire organization. A "report" can refer to any Power BI report within the Viva Insights web app, or other custom reports. [Learn more](./analyst/publish-reports.md). 

## Analysis Setup features

### Metric rules

Create metric rules to leave out certain non-collaboration events from your analyses. Learn more in [Metric rules](../advanced/analyst/metric-rules.md).

### Metric library 

This page identifies and defines the various metrics that you can use when you create queries. [Learn more](./reference/metrics.md). 

### Data quality

You as an analyst might receive warning messages related to the quality of uploaded data.  

After you select **View data quality**, the app takes you to the **Organizational data** page, which provides a summary of missing or low-quality data and attribute-specific information.

For information about data quality, refer to [Data quality in the analyst experience](./analyst/data-quality-analyst-experience.md).

### Data hub 

As an analyst, use the **Data hub** to get an overview of your data quality, including how many insights are available, how many are low-quality or missing, and how many days it's been since your data was last refreshed. 

## Admin Platform Setup features

### Data quality 

This page highlights any warning messages related to the quality of uploaded data. 

After you select **View data quality**, the app takes you to the **Organization data** page, which provides a summary of missing or low-quality data and attribute-specific information. [Learn more about data quality](./analyst/data-quality-analyst-experience.md).

### Data hub

As an admin, use the **Data hub** to:

* Get an overview of your data quality, including how many insights are available, how many are low-quality or missing, and how many days it's been since your data was last refreshed.
* Manage your current data sources, including starting a new update or switching sources. To learn how to upload data into Viva Insights, refer to [Upload organizational data (first upload)](../advanced/admin/upload-org-data-first.md).

### Organizational data

On the **Organizational data** page, check your upload status, view your field mapping results, and download related errors.

For a tour of the **Organizational data** page, refer to [Organizational data overview](../advanced/admin/org-data-overview.md#organizational-data-in-the-viva-insights-web-app).

### Business data 

Use this page to upload business outcome data for your organization. With this data, analysts can run the Copilot business impact report to understand how Copilot usage relates to the most relevant business outcomes at your organization. [Learn more](./analyst/templates/copilot-business-impact.md).

### Survey data 

Use this page to import survey results from Viva Glint into Viva Insights. By doing so, your organization can learn more about the employee experience, by combining data around how employees feel (Viva Glint) with how employees work (Viva Insights). Then, analysts can run the Glint and organizational insights report. [Learn more](./admin/import-survey-glint.md). 

### Manager settings

In **[Manager settings](./setup-maint/manager-settings.md)**, control who can see [organization insights](../org-team-insights/org-insights.md) in the Viva Insights app in Teams. Organization insights show managers aggregated wellbeing and productivity insights about their direct and indirect reports based on organizational hierarchy.

### Privacy settings

Use [**Privacy settings**](setup-maint/setup.md#customize-privacy-settings) to set the minimum group size, prevent sensitive keywords from appearing in any place that uses Viva Insights data, and allow end users to opt out of personal insights and person queries. To learn more about how Viva Insights keeps personal data private, refer to [Privacy](./privacy/privacy.md).

## Other resources

### Video demos

Go to **Video demos** to learn more about what you can do with the Viva Insights web app. The page provides several video walk-throughs, including those about running custom queries, using each Power BI template, and getting familiar with the Viva Insights interface. 

In addition to the left pane, you can reach these videos by selecting **Watch demo videos** on the **Help and documentation** menu on the **Advanced analysis** home page. 

### Send feedback

We welcome your feedback on the platform! Like in other Microsoft products, you can send us feedback through the feedback icon in the top-right of your screen.

### Community

Visit the [Viva Insights community](https://techcommunity.microsoft.com/t5/viva-insights/ct-p/VivaInsights) to connect with other Viva Insights users and share your experiences, contribute and receive support for common questions, and stay up to date on the latest features and tools.