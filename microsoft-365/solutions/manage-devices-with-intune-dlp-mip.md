---
title: "Step 7. Implement data loss prevention (DLP) with information protection capabilities"
ms.author: bcarter
author: brendacarter
f1.keywords:
- NOCSH
manager: dougeby
audience: ITPro
ms.topic: article
ms.prod: microsoft-365-enterprise
ms.localizationpriority: high
ms.collection:
- M365-security-compliance
ms.custom: 
keywords: 
description: 
---

# Step 7. Implement data loss prevention (DLP) with information protection capabilities

If your organization has already put the time into understanding your data, developing a data sensitivity schema, and applying the schema, you might be ready to extend elements of this schema to endpoints by using data loss prevention (DLP) policies. 

DLP policies are created by your information protection and governance team. Each DLP policy defines what elements within a data set to look for, like sensitive information types or labels, and how to protect this data. 

For example, a DLP policy can look for personal data like a passport number. The DLP policy will include a condition that triggers the policy to take action, such as when a passport number is shared with people outside your organization. The action the policy takes can be configured as well. Options range from simply reporting the action to admins, warning users, or even preventing the data from being shared.

The DLP policy also specifies the location to apply the policy to, such as Exchange email and SharePoint sites. One of the locations available to admins is devices. If devices is selected, you can specify which users and user groups to apply the policy to. You can also specify users and user groups to exclude from the policy.

If your information protection and governance team is ready to extend DLP policies to endpoints, you’ll need to coordinate with them to onboard devices, test and tune the policies, train users, and monitor the results. 

Use the following steps to work with your information protection team.


|Step  |Description  |
|---------|---------|
|1     |  [Learn about Microsoft 365 Endpoint data loss prevention](../compliance/endpoint-dlp-learn-about.md).        |
|2     | Onboard devices to Microsoft 365 Compliance solutions. See [Get started with Endpoint data loss prevention](../compliance/endpoint-dlp-getting-started.md) for instructions for:<br>- Windows 10 and Windows 11 onboarding<br>- MacOS onboarding       |
|3     |   Work with your information protection and governance team to define, test, and tune policies. This includes monitoring the results. See these resources:<br>- [Using Endpoint data loss prevention](../compliance/endpoint-dlp-using.md)<br>- [View the reports for data loss prevention](../compliance/view-the-dlp-reports.md)      |
|     |         |
