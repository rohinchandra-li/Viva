---
title: Key roles for Viva Glint
description: Assigning roles for Viva Glint leadership is among the first tasks for the Microsoft 365 Global Admin. Using consistent terminology for all roles helps support your Viva Glint programs.
ms.author: JudithWeiner
author: JudyWeiner
manager: mbarry
audience: admin
f1.keywords: NOCSH
keywords: Microsoft 365 Global Administrator, Viva Glint Administrator, Viva Glint manager, Viva Glint end user, Viva Glint Tenant Administrator
ms.collection:  
- m365initiative-viva
- selfserve 
search.appverid: MET150 
ms.topic: concept-article
ms.service: viva-glint
ms.localizationpriority: high
ms.date: 06/20/2025
---

# Key roles for Viva Glint

Assigning roles for Viva Glint leadership is among the first tasks for the Microsoft 365 Global Administrator. Using consistent terminology for Viva Glint roles helps support your Viva Glint programs.

## Viva Glint and Microsoft 365 admin center access by role

|Role  | Assigned by | Role grants access to the Microsoft 365 admin center to submit support requests  | Role grants access to the Viva Glint app |
|:----------|:-----------|:------------|:------------|
|Microsoft 365 Global Administrator   | Entra organization signup (automatic) | Yes | No  |
|Viva Glint Tenant Administrator (optional)   | Microsoft 365 Global Administrator | Yes | No  |
|Viva Glint Administrator             | Viva Glint Tenant Administrator | No  | Yes |
|Viva Glint manager                   | Viva Glint Administrator | No  | Yes |
|Viva Glint end user                  | Distribution list | No  | No  |

> [!TIP]
> If Viva Glint Admins who manage the Viva Glint app should also have access to the Microsoft 365 admin enter to submit support requests, [add them to the Viva Glint Tenant Administrator role](/viva/glint/setup/post-provisioning-next-steps#assign-viva-glint-tenant-admins). Also consider these roles to grant Viva Glint Admins additional permissions in the Microsoft 365 admin center or as alternatives to the Viva Glint Tenant Admin role, depending on the permissions users need:
>
> - [Service Support Administrator](/entra/identity/role-based-access-control/permissions-reference#service-support-administrator)
> - [Reports Reader](/entra/identity/role-based-access-control/permissions-reference#reports-reader)

> [!IMPORTANT]
> 
> To provision Viva Glint tenants as a **Microsoft 365 Global Admin**:
>
> - Admin users that access resources with a [Privileged Identity Management (PIM)](/entra/id-governance/privileged-identity-management/pim-configure) enabled account must have Global Admin privileges with [Direct assignment and **not** Group assignment](/entra/fundamentals/concept-learn-about-groups#assignment-types) access rights.
>
> To manage settings in the Microsoft 365 admin center as a **Viva Glint Tenant Admin**:
>
> - Admin users that access resources with a [Privileged Identity Management (PIM)](/entra/id-governance/privileged-identity-management/pim-configure) enabled account must be assigned with [Direct assignment and **not** Group assignment](/entra/fundamentals/concept-learn-about-groups#assignment-types) access rights.


## [Microsoft 365 Global Administrator](/entra/identity/role-based-access-control/permissions-reference#global-administrator)

- Provisions Viva Glint tenants
- Represents your organization, initiates, and controls Viva Glint product subscriptions and licenses
- Assigns Viva Glint Tenant Administrators (optional)*
- Assigns Viva Glint Administrators
- Views message center information in the Microsoft 365 admin center
- Files Microsoft 365 and Azure support tickets
- Views service health information
- Views Usage Reports

\* The Viva Glint Tenant Administrator role is designed to reduce the workload of the Microsoft 365 Global Administrator by allowing the delegation of Viva Glint-specific administrative tasks to another individual. When assigned, the Viva Glint Tenant Administrator can perform the following functions within the Viva Glint platform.

- Assigns Viva Glint Administrators
- Views message center information in the Microsoft 365 admin center
- Files Microsoft 365 and Azure support tickets
- Views service health information
- Views Usage Reports

## [Viva Glint Tenant Administrator](/entra/identity/role-based-access-control/permissions-reference#viva-glint-tenant-administrator )

- Assigned by the Microsoft 365 Global Administrator to manage Viva Glint settings in the Microsoft 365 admin center
- Assigns Viva Glint Administrators
- Views message center information in the Microsoft 365 admin center
- Files Microsoft 365 and Azure support tickets
- Views service health information
- Views Usage Reports

## Viva Glint Administrator

- Also known as:
  - Viva Glint Service Administrator in the Microsoft 365 admin center
  - Company Admin in the Viva Glint app
- Assigned by the Viva Glint Tenant Administrator to have responsibility for admin tasks in the Viva Glint platform
- Can access all data
- Sets up programs and surveys, distribution lists, and reporting features
- Supports managers in all aspects of action taking
- Best practice is to assign no more than five Viva Glint Admins

## Viva Glint manager

- Works with Viva Glint Admins as an organizational team leader to assist with survey administration
- Is assigned reporting access and can develop action plans

## Viva Glint end user

- Survey takers within your organization
