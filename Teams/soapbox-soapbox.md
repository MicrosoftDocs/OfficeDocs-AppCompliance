---
title: Application Information for SoapBox by SoapBox
ms.author: 
ms.date: 05/06/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for SoapBox, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data-mcas
---
# SoapBox

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: April 24, 2019</p>

* <a href="https://teams.microsoft.com/l/app/b49e7913-3b3f-4125-adde-2b698fc12c8b" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381501" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by SoapBox to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | SoapBox |
| ID | b49e7913-3b3f-4125-adde-2b698fc12c8b |
| Capabilities | Bot, Tab |
| Partner company name | SoapBox |
| URL of partner website | <https://soapboxhq.com> |
| URL of Teams application info page | <https://msteams.services.soapboxhq.com/faqs> |
| URL of Privacy Policy | <https://soapboxhq.com/privacy-policy/microsoft-teams> |
| URL of Terms of Use | <https://soapboxhq.com/terms-of-service> |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by SoapBox on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/en-us/graph/permissions-reference) this app requires, and for each, whether they are delegate or application permissions, the justification and purpose for this permission (what does the app use this information for?), and whether the app stores any of this information in its databases.

>| **Permission**  | **Delegated/Application** | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:----------------|:--------------------------|:--------------------------|:---------------------------------------------------|
>| User.Read | Delegated | Name and email are used to create SoapBox users | Name, email, microsoft user id |
>| Calendars.ReadWrite | Delegated | Calendar access is needed to sync SoapBox meetings to calendar events | Sync token |
>| offline_access | Delegated | Offline access to calendars is needed to make SoapBox notifications time relevant to synced calendar events |  |


#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>Not specified.

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>Not specified.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>Not specified.

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Information from the [Microsoft Cloud App Security](https://www.microsoft.com/en-us/enterprise-mobility-security/cloud-app-security) catalog appears below.

> [!NOTE]
> Information from the Microsoft Cloud App Security catalog is based on a variety of sources. Microsoft works to keep the information current but makes no guarantees of the accuracy of all the data sources. Contact us if you believe information about an app is outdated.

<iframe height='1020' title='Microsoft Cloud App Security Information' src='https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/35464' frameborder='no'  style='width: 100%;'></iframe>

<a href="https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/35464" target="_blank">View in a new tab</a>

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

