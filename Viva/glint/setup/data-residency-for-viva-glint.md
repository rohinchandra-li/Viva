---
title: Data residency for Viva Glint
description: "Data residency for Viva Glint"
ms.reviewer: 
ms.author: hasrivas
author: hasrivas
manager: josemm
audience: Admin
f1.keywords: NOCSH
ms.date: 06/24/2025
ms.topic: concept-article
ms.service: viva-glint
ms.localizationpriority: medium
ms.collection:
- m365initiative-viva-glint 
- essentials-compliance
- essentials-security
search.appverid: MET150
---

# Data residency for Viva Glint

## Summary

Microsoft Viva Glint helps organizations measure employee engagement and experiences so they can take action to improve them. Grounded in our [approach to employee engagement](https://aka.ms/VivaGlintAModernApproach), Glint offers a flexible surveying approach so organizations can gain a greater understanding of key experiences that shape an employee's journey and the resulting impact on individual and business outcomes.

## Customer Data residency for Viva Glint

Viva Glint customer data residency is limited to three regions: West US, EU, and Australia. This applies to data stored at rest, which constitutes metadata for the Glint surveys authored and responded to, and reports generated for those surveys. 

**West US data residency**

Required conditions:
1. _Tenant_ has a tenant hosting location country that is non-EU.
2. _Tenant_ has a valid Viva Glint license.  

**EU data residency**

Required conditions:
1. _Tenant_ has a tenant hosting country included in European Union Data Boundary (EUDB). 
2. _Tenant_ has a valid Viva Glint license.

**Australia data residency**

Required conditions:
1. _Tenant_ has a tenant hosting location country that is Australia or New Zealand.
2. _Tenant_ has a valid Viva Glint license.
3. For existing customers, _Tenant_ needs to opt into migration to Australian data center. For new Viva Glint customers after July 1, 2025, your data will be residing in an Australian data center.

> [!IMPORTANT]
> - We may temporarily move the data outside Australia into US/EU for processing data using Microsoft 365 core services. Any data that moves outside Australia won't reside for more than 24 hours and will be deleted at the end of processing operations. <br>
> - When integrating Glint with another service, refer to that services terms and documentation to understand whether your data may leave Australia. <br>
> - For existing Viva Glint customers, your instance won't be automatically migrated to Australia. Your account managers work with your tenant admins to gain approval if you want your data to reside in Australia. Post that, we'll work with you to align on a migration timeline. <br>

## User experience

Viva Glint data residency is seamless to the end user. The application will appropriately redirect the user to the correct region where their data is hosted.


## How long is my Viva Glint data stored for?
Viva Glint will retain Customer Personal Data (Personal Data that Customer uploads or otherwise provides to Microsoft in connection with its use of the Viva Glint service) for the duration of the term of the services specified on the ordering document and in accordance with the [Microsoft Products and Services Data Protection Addendum (DPA)](https://www.microsoft.com/licensing/docs/view/Microsoft-Products-and-Services-Data-Protection-Addendum-DPA). As your company’s data controller, Microsoft Viva Glint admins can delete nonactive survey data. This action deletes every data entity directly related to the survey, including overall survey configuration, items/questions, reports, responses, etc. The action won’t delete distribution lists, or any roles related with the survey. Survey data deletion in Viva Glint is an irreversible process.


