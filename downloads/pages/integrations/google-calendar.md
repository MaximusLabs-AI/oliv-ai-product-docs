---
title: "Google Calendar and Gmail integration"
url: "/integrations/google-calendar/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Google Calendar and Gmail integration

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Provide meeting and email context for supported preparation, capture and follow-up workflows.

<a id="supported-purpose"></a>
## Purpose and available evidence

The integration material describes calendar and Gmail connections. A separate guide addresses Calendly’s participant-recognition setup. The agent documents use calendar events and conversation context for preparation.

<a id="data-direction"></a>
## Data direction and permissions

Meeting metadata, email content, draft creation and sending are distinct permissions and should be documented separately.

<a id="setup"></a>
## Setup prerequisites

Confirm the connected Google account, requested scopes, included calendars and mailbox coverage. Verify attendee recognition for scheduling tools used by the organization.

<a id="disconnect"></a>
## Disconnect and retained data

Confirm account revocation, capture exclusions, disconnected-mailbox behavior and retained-data policy. Do not assume logging out revokes every integration.

<a id="connector-questions"></a>
## Connector contract to confirm

These are unresolved implementation questions. The list is not a claim that all of the named controls already exist.

- Are secondary or shared calendars included?
- How are aliases and multiple participant identities matched?
- What Gmail read/draft/send scopes are required?
- How are private events and attachments handled?
- How does rescheduling affect a prepared brief?
- What changes when Calendly supplies attendee details?

<a id="verify-connection"></a>
## Recommended connection check

Use a controlled source record or meeting, confirm that it arrives with the right owner and associations, and inspect any downstream write or notification. Repeat with a permission or validation exception and record the observed error path.

Record the integration version, scopes, tested objects, plan and verification date. Keep that acceptance record current when the provider changes its API or permissions.

<a id="connector-contract"></a>
## Connector contract to verify

Calendar identity supports meeting context; Gmail access and sending permissions require an explicit current contract.

| Contract field | Required confirmation |
| --- | --- |
| Owner | Google Workspace administrator |
| Authentication | Current authorization method, granted scopes and service or user identity |
| Data direction | Read, proposed write, executed write and unsupported operations |
| Coverage | Exact objects, fields, meeting conditions or channels |
| Freshness | Refresh timing, backfill and behavior after upstream changes |
| Lifecycle | Token expiry, revocation, disconnection and retained data |

<a id="explore"></a>
## Explore

- [Set up Google Calendar and Gmail](google-calendar/setup.md)
- [Google Calendar and Gmail data and permissions](google-calendar/data-and-permissions.md)
- [Google Calendar and Gmail sync and recovery](google-calendar/recovery.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:8532501: [Integrations settings for Oliv](https://help.oliv.ai/en/articles/8532501-integrations-settings-for-oliv)
- HELP:10511705: [How to configure Calendly to work with Oliv](https://help.oliv.ai/en/articles/10511705-how-to-configure-calendly-to-work-with-oliv)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
