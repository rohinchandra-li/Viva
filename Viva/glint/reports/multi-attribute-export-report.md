---
title: Use Viva Glint's Multi-attribute export
description: Microsoft Viva Glint Administrators can deep dive into survey scores and view results of combinations of up to three attributes.
ms.author: AWeixelman
author: AliciaWeixelman
manager: MelissaBarry
audience: admin
f1.keywords: NOCSH
keywords: multi-attribute export, combined attribute export
ms.collection:  
- m365initiative-viva
- selfserve 
search.appverid: MET150 
ms.topic: how-to
ms.service: viva-glint
ms.localizationpriority: high
ms.date: 06/24/2025
---

# Use Viva Glint's Multi-attribute export

Microsoft Viva Glint Administrators can deep dive into survey scores and view results of combinations of up to three attributes. The Multi-attribute export is available for both Engagement-type surveys and Employee Lifecycle surveys. 

## Access the Multi-attribute export

Only Viva Glint Admins can access this export.

1. Select **Reports** from the Viva Glint Dashboard.
2. In the **Survey programs** list on the left, select a survey.
3. Select the **Multi-attribute export** tile.
4. Depending on the survey type, use the following information to export results:
   - [Recurring or Ad Hoc surveys](#export-results-for-recurring-and-ad-hoc-surveys)
   - [Always-On and Employee Lifecycle surveys](#export-results-for-always-on-and-employee-lifecycle-surveys)

## Export results for Recurring and Ad Hoc surveys

In the Multi-attribute export dialog that appears:

1. Confirm that the **Survey program** displayed is the survey initially selected from the **Survey programs** list.
2. Select a survey cycle from the **Program cycle** dropdown menu.
3. In the Attributes field, select an attribute. The number of unique attribute values displays next to the selected attribute.

   > [!NOTE]
   > When an attribute has zero values, a warning message appears. Select attributes that have at least one value.
   
4. To add up to three total attributes, use the **+ Add an attribute** option and select more attributes.

   :::image type="content" source="../../media/glint/reports/multi-attribute-recurring.png" alt-text="Screenshot of survey and attribute selections for a recurring survey.":::

   > [!NOTE]
   > When the attribute value combinations for selected attributes exceed 12,000, a warning message appears. Remove or select a different combination of attributes.

5. Select **Export** after making all selections.

## Export results for Always-On and Employee Lifecycle surveys

In the Multi-attribute export dialog that appears:

1. Confirm that the **Survey program** displayed is the survey initially selected from the **Survey programs** list.
2. Select a Start and End date in the **Date range** section.
3. In the Attributes field, select an attribute. The number of unique attribute values displays next to the selected attribute.

   > [!NOTE]
   > When an attribute has zero values, a warning message appears. Select attributes that have at least one value.

4. To add up to three total attributes, use the **+ Add an attribute** option and select more attributes.
  
   :::image type="content" source="../../media/glint/reports/multi-attribute-always-on.png" alt-text="Screenshot of date and attribute selections for an always-on survey.":::

   > [!NOTE]
   > When the attribute value combinations for selected attributes exceed 12,000, a warning message appears. Remove or select a different combination of attributes.
   
## Multi-attribute export content

Rows 1 - 5 include information about exported data, including:

- The Multi-attribute export file name
- The program type
- The survey name
- The export date
- The survey date range (for Always-On and Lifecycle surveys) or the program cycle date (for Recurring and Ad Hoc surveys)

The column headers for results data start on row 6 and include:

1. (First selected attribute)
2. (Second selected attribute)
3. (Third selected attribute)
4. Overall Invitees
5. Overall Respondents
6. Overall Response Rate
7. Questions
8. Question Text
9. Question Respondents
10. Average Score
11. Percent Favorable

## Attribute selection order and data suppression

The Multi-attribute export adheres to your organization's selected confidentiality and suppression thresholds. The export evaluates data to suppress each time the export is generated and takes into account the order that users select attributes.

### Example

When a Viva Glint Admin selects Location and then Gender as attributes for their export, they see that data for the Female + Mexico combination is suppressed due to the low respondent count for the "Other" value for Gender:

:::image type="content" source="../../media/glint/reports/multi-attribute-loc-gender.png" alt-text="Screenshot of attribute value combinations when location is selected before gender.":::

But when the admin selects Gender first and then Location for the same survey, they see results for Mexico + Female:

:::image type="content" source="../../media/glint/reports/multi-attribute-gender-loc.png" alt-text="Screenshot of attribute value combinations when gender is selected before location.":::

The first combination of attribute values evaluates based on suppressed Gender + Location values, while the second combination evaluates on suppressed Location + Gender values.

