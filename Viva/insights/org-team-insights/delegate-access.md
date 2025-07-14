---
ms.date: 06/23/2025
title: Delegate access to Copilot Dashboard and organizational insights
description: Learn how to delegate access to organization insights and Copilot Dashboard in Viva Insights.
author: zachminers
ms.author: v-zachminers
ms.topic: how-to
ms.localizationpriority: medium 
ms.collection:
 - viva-insights-advanced
 - magic-ai-copilot
ms.service: viva-insights
search.appverid: 
- MET150 
manager: abelutk
audience: Admin
---
# Delegate access to Copilot Dashboard and organizational insights

You can delegate access to the Microsoft Copilot Dashboard, Copilot Analytics reports, and other organizational insights to other people within your company.

By granting delegate access, someone else at your company, such as your chief of staff or one of your direct reports, would have the same access you have to the insights. They can view them and operationalize business decisions based on the data.

There are no changes to the metrics, aggregation, or filtering tools available to the delegate. However, the delegate doesn't have access to your personal insights or personal recommended actions, like sharing insights or sending praise to a recent collaborator.

>[!Note]
>To delegate access to the Copilot Dashboard and Copilot Analytics reports, you need to have access to the dashboard, but neither the Group Manager role nor a Viva Insights subscription is required. [Learn more about how access to the Copilot Dashboard is determined](./copilot-dashboard.md#how-automatic-access-to-the-copilot-dashboard-is-determined).
>
>To delegate access to organizational insights in the Viva Insights app in Teams, you need a Viva Insights subscription and must be assigned the Group Manager role. [Learn more about roles and access for organizational insights](org-insights.md#subscriptions-roles-and-access). Viva Insights admins can also delegate access to organizational insights on your behalf using PowerShell.

Here are a few other things to note:

* You can delegate access to whomever you want and to as many people as you want (maximum limit of 75), as long as they're in your tenant.

* You can revoke access to whomever you want at any time.

* A delegate can't delegate access to others.

* You can only delegate access to organizational insights in the Viva Insights app in Teams to people who have a Viva Insights license. 

* If you assign delegates for organizational insights, and you're removed as a group manager from Viva Insights, the delegates you assigned are also removed along with their access.

* If you assign delegates for the Copilot Dashboard and Copilot Analytics reports, and your access to the dashboard is removed, the delegates you assigned are also removed along with their access.

## Assign and remove delegates for the Copilot Dashboard and Copilot Analytics reports

### Method 1

*Applies to: People with access to the [Copilot Dashboard](../org-team-insights/copilot-dashboard-advanced-features.md)*

1. In the Viva Insights web app, under **Settings** on the left, select **Delegation**.

2. If you've already assigned delegates, you'll see them listed under **My delegates**, along with the start date of their access.
    * To revoke access for an existing delegate, select the **Delete** (trashcan) icon next to their name.

    :::image type="content" source="images/add-delegate-cdb-01.png" alt-text="Screenshot showing how to delegate access and revoke access for Copilot Dashboard.":::

3. To add delegates, at the top right, select **Add delegates**.

4. Type in the name or names of the people you want to assign as delegates. You can also add a personal note, but it's not required.

5. At the bottom right, select **Confirm**. Whenever you add a delegate, they're notified in email and Teams chat of their access status.

    :::image type="content" source="images/add-delegate-cdb-02.png" alt-text="Screenshot showing how those given delegate status are notified.":::

### Method 2 

*Applies to: People with access to the Copilot Dashboard*

1. On the Copilot Dashboard page in the Viva Insights web app, under **Share** on the top right, select **Add delegates**.

    :::image type="content" source="images/add-delegate-cdb-03.png" alt-text="Screenshot showing how to add delegates within the Copilot Dashboard.":::

2. Type in the name or names of the people you want to assign as delegates. You can also add a personal note, but it's not required.

3. At the bottom right, select **Confirm**. Whenever you add a delegate, they're notified in email and Teams chat of their access status.

## Assign and remove delegates for organizational insights

*Applies to: People with access to organizational insights in the Viva Insights app in Teams*

1. In the Viva Insights app in Teams, select the ellipses (…) at the top right.
2. Select **Settings.**
3. Select **Delegate access.**
4. Here you can find your delegates and the start date of their access.
5. To add a new delegate, select **Add new.**
6. To revoke access for an existing delegate, select the **Delete** (trashcan) icon.

Whenever you add a delegate, they're notified in Teams Chat of their access status.

## Assign delegate access to organizational insights using Powershell 

If you're a Viva Insights admin in the destination organization, you can assign delegate access to group managers' colleagues on their behalf using PowerShell cmdlets. 

You'll use these three cmdlets: 

* Add-VivaOrgInsightsDelegatedRole. [Learn more about this cmdlet](/powershell/module/exchange/add-vivaorginsightsdelegatedrole). 

* Get-VivaOrgInsightsDelegatedRole. [Learn more about this cmdlet](/powershell/module/exchange/get-vivaorginsightsdelegatedrole). 

* Remove-VivaOrgInsightsDelegatedRole. [Learn more about this cmdlet](/powershell/module/exchange/remove-vivaorginsightsdelegatedrole). 

## Request and approve delegate access to organizational insights in the Viva Insights app in Teams

*Applies to: People without delegate access, and group managers*

Employees who need delegate access can request it for organizational insights (not the Copilot Dashboard) from as many group managers as they'd like. Once the employee is given access by the group manager, they'll have the same view of organizational insights as the group manager who approved their access.

1. To request access, in the Viva Insights app, select the ellipses (…) at the top right. 

2. Select **Settings**. 

3. Select **Delegate access**. 

4. Select **Request delegate access**. 

5. Enter the name of the group manager or group managers from whom you'd like to request access. You can also add an optional note. Select **Send request**.

    :::image type="content" source="images/request-delegate-access-02.png" alt-text="Screenshot showing how to request delegate access.":::

6. If you're the group manager who was selected in the step above, you'll receive a notification in Teams about the request. To approve or deny the request, select **Go to settings**. 

7. You'll see a list of employees who have requested delegate access from you. Select **Approve** or **Decline** for each employee's request.

    :::image type="content" source="images/delegate-org-insights-01.png" alt-text="Screenshot showing how to approve or decline delegate access requests.":::

## Delegate access view

### Copilot Dashboard and Copilot Analytics reports 

*Applies to: People given delegate access to the Copilot Dashboard and Copilot Analytics reports in the Viva Insights web app*

1. If you're given delegate access, you receive an automated message in email and Teams from the leader who gave you access. 

2. On the message, select **View insights**. You'll see the leader's view of the Copilot Dashboard.

3. On the top right, a banner tells you which leader's insights you're viewing. If you're given delegate access by multiple leaders, select the banner to switch between different dashboards.

### Organizational insights

*Applies to: People given delegate access to organizational insights in the Viva Insights app in Teams*

1. If you're given delegate access, you receive an automated message in Teams from the manager who gave you access.
2. On the message, **select View insights**. You're then redirected to the manager’s view of the respective dashboard.  
3. On the top left, a banner tells you which leader's insights you're viewing. If you're given delegate access by multiple leaders, select the banner to switch between different dashboards.

## Remove access to delegate Copilot Dashboard with Powershell

[Learn more about using policies to control access to features in Viva](/viva/feature-access-management).

You can set a policy to disable delegation for Copilot Dashboard for the tenant using Powershell cmdlets. You can set a policy for a tenant, user, or group. Users included in the policy can't delegate access to Copilot Dashboard until you remove or update the policy. Before you can use the cmdlet, you need to install a module and sign in to be authenticated. [Learn more about how to set these policies](/viva/feature-access-management).

1. [Connect to Exchange Online](../advanced/setup-maint/configure-personal-insights.md#connect-to-exchange-online) and when prompted, sign in with your admin credentials.

2. After you’ve signed in, you can manage access for your tenant using the Add-VivaModuleFeaturePolicy cmdlet:[Add-VivaModuleFeaturePolicy](/powershell/module/exchange/add-vivamodulefeaturepolicy).

**Example: Turn off delegation for Copilot Dashboard for all users in your tenant.**

```powershell
 ModuleId : VivaInsights
 FeatureId : CopilotDashboardDelegation  
 Name : DisableFeatureForAll
 IsFeatureEnabled : false
 Everyone
```

>[!Note]
>After disabling the delegate feature for Copilot Dashboard, it may take up to 12 hours to reflect the change.

## Audit who has delegate access

Admins can use audit logs to identify which users have access to Viva Insights through delegation. [Learn more about how to search the audit log](/purview/audit-search).

| Friendly name | Operation | Actor | Target | Modified properties name | Modified properties value | 
|---|---|---|---|---|---|
| Added delegate access | AddDelegates | The user who provided access | The user whose access was changed | Leader Insights delegate | Enabled |
| Removed delegate access | RemoveDelegates |  The user who provided access | The user whose access was changed  | Copilot Dashboard delegate | Disabled |


### Related topics

- [Learn more about the Copilot Dashboard](copilot-dashboard.md)
- [Learn more about organization insights](org-insights.md)