---
ms.date: 07/2/2025
title: Learning Culture report
description: Learn how to use the Microsoft Viva Insights Power BI template to understand how employees engage with Viva Learning content.
author: zachminers
ms.author: v-zachminers
ms.topic: how-to
ms.localizationpriority: medium 
ms.collection: viva-insights-advanced 
ms.service: viva-insights
search.appverid: 
- MET150 
manager: anirudhbajaj
audience: Admin
---

# Learning Culture report

This report helps HR professionals and business leaders understand how employees in their organization engage with Viva Learning content. The report also lets you drill down into viewing trends for specific departments and time periods, giving you a better picture of which areas of your company you might want to upskill based on the insights. 

The report provides three core Learning insights:

1. **Learning usage** – Provides insights about the employees who have launched the Viva Learning app in the selected time frame. The data is filtered by organization hierarchy.

2. **Learning culture** – Provides insights about the number of non-assigned trainings played by employees.

3. **Content played** – Provides insights about the total number of videos played by employees in Viva Learning.

## How to get started

### Prerequisites

Only people with the **Viva Insights Analyst** role can set up and run this report. Here's a list of other roles involved in setting up and using this report: 

* Learning admin (also known as Knowledge admin) 

* Microsoft 365 global admin 

* Insights Administrator

Note the following:

1. Your Viva Insights admin must assign the Viva Insights Analyst role to your designated Learning analysts to enable them set up and run this report in Viva Insights.

2. The Knowledge admin needs to share Learning data with Viva Insights by following **Viva Learning > Admin > Settings**.  

3. The employees you want to analyze must have eligible Viva Insights licenses to be included in this report.

## 1. Learning admin sets up data transfer

First, the Learning admin must provide consent to share Viva Learning data with Viva Insights.

1. Go to **Viva Learning > Settings**. 

2. At the bottom, select **Share Learning data to Viva Insights**.

    :::image type="content" source="../../images/viva-learning-settings.png" alt-text="Screenshot that shows the Viva Learning settings page.":::

> [!NOTE]
> Reports are updated weekly on Mondays, and are based on data that's always delayed by at least three days.
>
> Once you enable the reporting feature by turning on the toggle, reports will appear the following Tuesday at the earliest, since data is processed weekly and updated every Monday.

### Examples

* If you enable reports on **Tuesday, June 10**, you'll see reports starting **Tuesday, June 17**.

* If you enable reports on **Sunday, June 15**, reports will also be available **Tuesday, June 17**. 

* If you enable reports on **Monday, June 16 (just before the update)**, you'll have to wait for the next week's update, so reports will be available **Tuesday, June 24**.

## 2. Viva Insights Analyst runs the query

1. In the Viva Insights analyst experience, select **Create analysis**. 

2. Under Power BI templates, navigate to Learning and select **Set up analysis**. 

3. Under Query setup: 
    1. Enter a **Query name**. 
    2. Enter a **Description** (optional). 
    3. Select a **time period** of up to three months.

    > [!NOTE]
    > This Power BI query is set to **Group by Day**, and you can't edit this field.

4. Set **Auto-refresh** (optional). You can set the query to automatically update by selecting **Auto-refresh**. When you select **Auto-refresh**, your query automatically runs and computes a new result every week.

    > [!NOTE]
    > If organizational data used in an auto-refreshing query changes (for example, an attribute name is altered or an attribute is removed), the query might stop auto-refreshing.

5. In **Select which employees you want to include in the query**, add filters to narrow down the employees in scope for your report. [Learn more about filter and metric options](..//filters.md).

    > [!IMPORTANT]
    > Only people with valid Viva Insights licenses and Learning data are included in this report. The query won't return reports for employees in the Learning data who have no Viva Insights license assigned. The Insights Administrator can assign the required licenses.

6. Under **Select which employee attributes you want to include in the query**, add organizational attributes. Once the query runs, you can use these attributes to group and filter the reports.

    > [!IMPORTANT]
    > This Power BI query includes the **Organization** attribute by default. This attribute appears in gray, and you can't remove it. If you notice attributes marked with yellow warnings, that attribute's quality is low. If you notice attributes marked in red and the query's Run button disabled, then your organizational data is missing that attribute. [Learn more about attributes and data quality](..//data-quality-analyst-experience.md).

7. Select **Run** on the upper right side of the screen. The query might take a few minutes to run.

8. When your query results are ready, go to the **Analysis results** page and select the **Power BI icon**. Download the Power BI template and get the partition and query identifiers. You'll need these identifiers later.

## 3. Viva Insights Analyst accesses query results and views the Power BI report

Analysts can access the report in two different ways: 

* View the report in the browser. Use this option if you only want to view the report. 

* Open the Power BI template in Power BI desktop and connect to your query results. Use this option if you want to customize the report or share it with others in your organization by publishing the report to the Power BI Service.

### View report in the browser

To view the report in the browser, go to the **Analysis results** page and select the eye icon in the View column. Select **Open in new tab** if you want to keep the report in the background while doing other tasks in the analyst workbench.

:::image type="content" source="../../images/learning-analysis-results.png" alt-text="Screenshot that shows how to access the analysis results.":::

### Open the Power BI template in Power BI Desktop

Select **Analysis results** in the left-hand navigation menu to view your query status. When you see a "Success" status, select the Power BI icon to download the file and open it in Power BI desktop.

:::image type="content" source="../../images/open-template-desktop.png" alt-text="Screenshot that shows how to access the results in Power BI desktop.":::

Select the **link** icon to get the partition and query identifiers.

:::image type="content" source="../../images/template-identifier.png" alt-text="Screenshot that shows how to get the partition and query identifier.":::

Then:

1. Open Power BI desktop.

2. Enter the query identifiers in Power BI to open and populate the report with your query results. 

3. Open the downloaded template. 

4. If you're prompted to select a program, select **Power BI**.

5. When you're prompted by Power BI: 
    1. Paste in the partition and query identifiers. 
    2. Set the **Minimum group size** for data aggregation within this report's visualizations in accordance with your company's policy for viewing Viva Insights data. 
    3. Select **Load** to import the query results into Power BI. 
    4. If prompted by Power BI, sign in using your organizational account. If available, select **Organizational account** from the left.  
    5. You need to sign in to Power BI with the same account you use to access Viva Insights. You might have to sign in more than once.

        :::image type="content" source="../../images/analyst-pbi-org-account1.png" alt-text="Screenshot that shows signing into to Power BI on the Organizational account tab":::

    1. Power BI then loads and prepares the data. For large files, this process might take a few minutes.
    
    > [!NOTE]
    > You need to have the December 2022 (or newer) version of Power BI Desktop installed.

## 4. Share the report with your team

Once the report is set up in Power BI, you can publish the report to a designated Power BI workspace. [Learn how](/power-bi/create-reports/desktop-upload-desktop-files#to-publish-a-power-bi-desktop-semantic-model-and-reports).

Open the report once it's published.

:::image type="content" source="../../images/publish-power-bi.png" alt-text="Screenshot that shows how to open the published report.":::

In the published report, to generate a sharable link or send the report to the selected users, select **Share**.

:::image type="content" source="../../images/share-report.png" alt-text="Screenshot that shows how to share the published report.":::

## About the Learning Culture report 

This report has four pages (tabs in the left pane): Overview, Adoption, Learning culture, and Content played.

### Report settings 

After you set up the Learning Culture report and populate it with Viva Insights data in Power BI, you can view and set the following parameters on the Settings page:

| Setting | Description |
|---|---|
| Select the time period for the report | Select the time period for which you want to view data in the report. |
| Select an attribute to group data by | Select the primary group-by attribute shown in all the report pages. You can change this attribute at any time and all report pages will show group values by the new attribute. |
| Select optional report filter | To filter the measured employee population, you can filter by any selected organizational attribute, and then filter by any of the values for these attributes. If you use filters, the measured employees count will reflect a reduced number. Measured employees reflect the number of employees in the filtered population who were active during the specified time period. Active employees are those who’ve sent at least one email or Teams chat during a work week included in the current time period. |
| Exclusions  | Use the boxes to: <br><br /><li>Exclude employees who are likely non-knowledge workers (that is, those spending less than five hours per week in meetings, emails, and/or Teams calls and chats).<li> Exclude weeks that are likely holiday or paid-time-off weeks or weeks that individuals are on other types of leave. |

> [!NOTE]
> The Exclusions listed above aren't available if you view the report in the browser.
>
> The Exclusions are only available if you download the Power BI template and open it on Power BI Desktop.  
>
> After confirming the settings, check the number of measured employees to confirm this is the population you want to analyze.

:::image type="content" source="../../images/learning-report-settings.png" alt-text="Screenshot that shows the settings for the report.":::

## Power BI tips, FAQs, and troubleshooting 

For details about how to share the report and other Power BI tips, troubleshoot any issues, or review the FAQ, see:

* [Power BI tips, FAQ, and troubleshooting](./power-bi-faq-troubleshoot.md)
* [Access query results and modify existing queries](..//query-results.md)
* [Filters](..//filters.md)

## Confidentiality and security of employee data

The following measures and protocols are in place to ensure that data sharing adheres to the highest standards of privacy and compliance: 

* **Consent and compliance**: Initiates data sharing after consent from the Microsoft 365 Knowledge admin, aligning with organizational data policies and organizational standards. 

* **Minimum group size threshold**: Prioritizes employee privacy by using the minimum group size threshold in the report. The minimum group size can be customized and must be at least 10 people. Only groups that meet or exceed the minimum group size appear in the report.

## FAQs

**Why am I seeing fewer people than expected in this report?**

There can be a couple reasons:

* Some employees might not have the required licenses. To be included in the report, a user must have either the Viva Suite license or Copilot licenses. Consult your Microsoft 365 admin on the Viva license deployment in your organization. 

* Some employees might not have their organizational data uploaded or successfully uploaded to Viva Insights. To check the measured population coverage in the analyst workbench, use the Data quality page in the Viva Insights web app. Review the Data fields you plan to use in the report and  the number of employees with this field. If the employee count is lower than expected, work with your Insights admin to update the organizational file. [Learn more about organizational data](..//..//admin/org-data-overview.md).

**Why is the total count of people correct in the report, but some organizations don't appear in the breakdown view?**

This report has a minimum group size threshold, which is set to 10 people by default. Any group that does not meet this minimum size isn't displayed in the report breakdown view.

**I'm new to Viva Insights. How do I get started?**

First, refer to our [video learning courses](..//..//video-learning-courses.md) to understand the various features and tools across Viva Insights. And, [get an introduction to advanced analysis](..//..//analysis-intro.md).

Then, refer to our [setup checklist](..//..//setup-maint/setup-overview.md), which lays out the various steps to set up Viva Insights.