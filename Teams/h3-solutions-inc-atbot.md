---
title: Application Information for AtBot by H3 Solutions, Inc.
ms.author: 
ms.date: 05/06/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for AtBot, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data-mcas
---
# AtBot

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: April 29, 2019</p>

* <a href="https://teams.microsoft.com/l/app/7c01af81-ae7d-416e-98a3-c139cae8cfb0" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381219" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by H3 Solutions, Inc. to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | AtBot |
| ID | 7c01af81-ae7d-416e-98a3-c139cae8cfb0 |
| Capabilities | Bot |
| Partner company name | H3 Solutions, Inc. |
| Physical address | 10432 Balls Ford Rd. STE 230 Manassas, VA 20109 |
| Contact information for this app | hello@atbot.io |
| URL of partner website | <https://atbot.io> |
| URL of Teams application info page | <https://admin.atbot.io/Docs/GettingStarted> |
| URL of Privacy Policy | <https://admin.atbot.io/privacy> |
| URL of Terms of Use | <https://admin.atbot.io/terms> |
| Main telephone number | 1 (855) 464-5914 |
| Description of available licensing options, if any | Free, Pro, Enterprise \| https://admin.atbot.io/Docs/BizzyTiers |
| Licensing contact | support@atbot.io |
| Licensing telephone number | 1 (855) 464-5914 |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by H3 Solutions, Inc. on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/en-us/graph/permissions-reference) this app requires, and for each, whether they are delegate or application permissions, the justification and purpose for this permission (what does the app use this information for?), and whether the app stores any of this information in its databases.

>| **Permission**  | **Delegated/Application** | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:----------------|:--------------------------|:--------------------------|:---------------------------------------------------|
>| Directory.Read.All | Delegated | Enumerate AAD groups to allow security trimming of bot skills. Enumerate users to be able to apply licenses. Enumerate users to add as Administrators/Contributors | AAD Group Name, AAD Group GUID, UPN |
>| Directory.Read.All | Application | Enumerate AAD groups to allow security trimming of bot skills. Enumerate users to be able to apply licenses. Enumerate users to add as Administrators/Contributors | AAD Group Name, AAD Group GUID, UPN |
>| People.Read | Delegated | Enumerate people in a Get Person action from Flow.  Allows the bot to retrieve people from the /People endpoint in Microsoft Graph | No |
>| User.Read | Delegated | Gives us access to the user’s Tenant ID and UPN to allow us to tie Flows/Logic Apps created to the users that created them | Tenant ID, UPN |
>| email | Delegated | Gives us access to the user&#x27;s email address | No |
>| offline_access | Delegated | Allows us to use a refresh token to keep users logged in | Access/Refresh tokens. |
>| openid | Delegated | Allows users to log in | No |
>| profile | Delegated | Access to user&#x27;s UPN | UPN |

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Does this app make use of this capability?


>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Yes | The creation of mentions in bot-generated chat messages | No |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>Tenant ID, UPN
We use Application Insights and our logs will last for 90 days before being automatically archived. (https://docs.microsoft.com/en-us/azure/azure-monitor/app/data-retention-privacy)

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>All AtBot Web Applications, Databases, Caching and Storage resources are located in a 	subscription that is not connected to our company AAD with only Administrators who 	have access to the resources.  2FA is required for these administrators.  All databases are 	encrypted and firewalled to only allow Azure IPs and our corporate office in Manassas, 	VA.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>Administrators have the ability to delete bot configurations that may contain AAD Group Names/GUIDs.
Upon cancellation of service, all UPNs will be removed from the licensing database.
See &#x27;Azure Services&#x27; under Data Residency.  Much of the customer-specific data produced via the use of AtBot is stored in the customer&#x27;s tenant and so admins of that tenant have full control of the data there.

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Information from the [Microsoft Cloud App Security](https://www.microsoft.com/en-us/enterprise-mobility-security/cloud-app-security) catalog appears below.

> [!NOTE]
> Information from the Microsoft Cloud App Security catalog is based on a variety of sources. Microsoft works to keep the information current but makes no guarantees of the accuracy of all the data sources. Contact us if you believe information about an app is outdated.

<iframe height='1020' title='Microsoft Cloud App Security Information' src='https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/35672' frameborder='no'  style='width: 100%;'></iframe>

<a href="https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/35672" target="_blank">View in a new tab</a>

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

