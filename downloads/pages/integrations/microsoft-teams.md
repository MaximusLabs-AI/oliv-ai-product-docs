---
title: "Microsoft Teams integration"
url: "/integrations/microsoft-teams/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Microsoft Teams integration

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Use supported Teams meeting recording and collaboration routes in Oliv.

<a id="supported-purpose"></a>
## Purpose and available evidence

The current recording guide includes Teams in its native-recording explanation when the organization is configured for that mode. Older integration material separately describes a Teams shared-channel route for notifications.

<a id="data-direction"></a>
## Data direction and permissions

Meeting capture and message delivery are different connections. Enabling one does not establish the permissions or availability of the other.

<a id="setup"></a>
## Setup prerequisites

Confirm tenant administration, organization recording setup, meeting organizer conditions and the intended collaboration destination. Obtain current tenant-specific steps rather than applying the older generic no-integration-needed wording to native recording.

<a id="disconnect"></a>
## Disconnect and retained data

Confirm how each meeting and collaboration connection is revoked and what imported recordings or messages remain available.

<a id="connector-questions"></a>
## Connector contract to confirm

These are unresolved implementation questions. The list is not a claim that all of the named controls already exist.

- Which tenant and accounts are authorized?
- Which meetings use native capture versus a visible note taker?
- What happens for external organizers and guests?
- Which users or channels receive output?
- Are external/shared channels supported for this workflow?
- How are access and retention handled after disconnect?

<a id="verify-connection"></a>
## Recommended connection check

Use a controlled source record or meeting, confirm that it arrives with the right owner and associations, and inspect any downstream write or notification. Repeat with a permission or validation exception and record the observed error path.

Record the integration version, scopes, tested objects, plan and verification date. Keep that acceptance record current when the provider changes its API or permissions.

<a id="connector-contract"></a>
## Connector contract to verify

Meeting capture and notification scope must be confirmed separately; a Teams meeting link is not a complete capture contract.

| Contract field | Required confirmation |
| --- | --- |
| Owner | Microsoft tenant administrator |
| Authentication | Current authorization method, granted scopes and service or user identity |
| Data direction | Read, proposed write, executed write and unsupported operations |
| Coverage | Exact objects, fields, meeting conditions or channels |
| Freshness | Refresh timing, backfill and behavior after upstream changes |
| Lifecycle | Token expiry, revocation, disconnection and retained data |

<a id="explore"></a>
## Explore

- [Set up Microsoft Teams](microsoft-teams/setup.md)
- [Microsoft Teams data and permissions](microsoft-teams/data-and-permissions.md)
- [Microsoft Teams sync and recovery](microsoft-teams/recovery.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:15136310: [Understanding Oliv’s Meeting Recording Modes](https://help.oliv.ai/en/articles/15136310-understanding-oliv-s-meeting-recording-modes)
- HELP:8532501: [Integrations settings for Oliv](https://help.oliv.ai/en/articles/8532501-integrations-settings-for-oliv)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
