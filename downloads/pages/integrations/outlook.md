---
title: "Outlook and Microsoft 365 integration"
url: "/integrations/outlook/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Outlook and Microsoft 365 integration

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Connect supported Microsoft calendars or mailboxes and use the current Outlook add-in workflow where available.

<a id="supported-purpose"></a>
## Purpose and available evidence

The Help Center contains Outlook add-in installation and troubleshooting material from 2020, along with a later calendar-access article. These establish historical support context, not a verified current client/tenant compatibility matrix.

<a id="data-direction"></a>
## Data direction and permissions

Calendar discovery, email context and add-in controls are separate access paths. Confirm the selected account and application consent for each.

<a id="setup"></a>
## Setup prerequisites

Use current tenant-approved installation and consent instructions. Do not reissue the old workaround that publishes a work calendar and imports it into a personal account without security-owner review.

<a id="disconnect"></a>
## Disconnect and retained data

Confirm how to revoke calendar/mail access and remove the add-in separately. Organization consent and a local add-in installation are not the same state.

<a id="connector-questions"></a>
## Connector contract to confirm

These are unresolved implementation questions. The list is not a claim that all of the named controls already exist.

- Which Outlook clients and Microsoft tenant policies are supported?
- Is administrator consent required?
- Which calendars and mail folders are in scope?
- How is timezone determined?
- What is the approved solution when tenant access is restricted?
- What recording controls are available in the current add-in?

<a id="verify-connection"></a>
## Recommended connection check

Use a controlled source record or meeting, confirm that it arrives with the right owner and associations, and inspect any downstream write or notification. Repeat with a permission or validation exception and record the observed error path.

Record the integration version, scopes, tested objects, plan and verification date. Keep that acceptance record current when the provider changes its API or permissions.

<a id="connector-contract"></a>
## Connector contract to verify

Calendar and email access are distinct from the Outlook add-in. Legacy help documents tenant restrictions and installation issues.

| Contract field | Required confirmation |
| --- | --- |
| Owner | Microsoft 365 administrator |
| Authentication | Current authorization method, granted scopes and service or user identity |
| Data direction | Read, proposed write, executed write and unsupported operations |
| Coverage | Exact objects, fields, meeting conditions or channels |
| Freshness | Refresh timing, backfill and behavior after upstream changes |
| Lifecycle | Token expiry, revocation, disconnection and retained data |

<a id="explore"></a>
## Explore

- [Set up Outlook and Microsoft 365](outlook/setup.md)
- [Outlook and Microsoft 365 data and permissions](outlook/data-and-permissions.md)
- [Outlook and Microsoft 365 sync and recovery](outlook/recovery.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:3810034: [Install Oliv's Add-in for Outlook](https://help.oliv.ai/en/articles/3810034-install-oliv-s-add-in-for-outlook)
- HELP:4467669: [Missing "Get Add-Ins" button in Outlook](https://help.oliv.ai/en/articles/4467669-missing-get-add-ins-button-in-outlook)
- HELP:9144560: [Overcome Outlook Calendar Access Restrictions](https://help.oliv.ai/en/articles/9144560-overcome-outlook-calendar-access-restrictions)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
