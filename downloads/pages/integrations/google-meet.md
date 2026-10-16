---
title: "Google Meet integration"
url: "/integrations/google-meet/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Google Meet integration

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Capture supported Google Meet meetings through the configured calendar and recording workflow.

<a id="supported-purpose"></a>
## Purpose and available evidence

The older integration guide includes Google Meet in the meeting-capture workflow after calendar connection. The newer recording guide explains organizer-dependent modes but does not establish every platform-specific native capability.

<a id="data-direction"></a>
## Data direction and permissions

The intended result is meeting content available for Oliv processing and associated with the relevant participants and business context.

<a id="setup"></a>
## Setup prerequisites

Confirm the supported capture route for the organization, the calendar connection, organizer identity and admission requirements. Do not assume that Zoom’s native-recording setup applies unchanged to Meet.

<a id="disconnect"></a>
## Disconnect and retained data

Confirm how calendar access and the meeting-capture route are disabled separately, and what happens to existing recordings.

<a id="connector-questions"></a>
## Connector contract to confirm

These are unresolved implementation questions. The list is not a claim that all of the named controls already exist.

- Which Meet capture modes are supported today?
- What happens when an external organizer controls admission?
- How are recurring, cancelled and private meetings handled?
- Who may stop or exclude capture?
- How is a meeting linked to the correct opportunity?
- What is retained after the connection is removed?

<a id="verify-connection"></a>
## Recommended connection check

Use a controlled source record or meeting, confirm that it arrives with the right owner and associations, and inspect any downstream write or notification. Repeat with a permission or validation exception and record the observed error path.

Record the integration version, scopes, tested objects, plan and verification date. Keep that acceptance record current when the provider changes its API or permissions.

<a id="connector-contract"></a>
## Connector contract to verify

The eligible recording mode depends on the organization and meeting conditions described by the current recording guide.

| Contract field | Required confirmation |
| --- | --- |
| Owner | Workspace administrator and meeting organizer |
| Authentication | Current authorization method, granted scopes and service or user identity |
| Data direction | Read, proposed write, executed write and unsupported operations |
| Coverage | Exact objects, fields, meeting conditions or channels |
| Freshness | Refresh timing, backfill and behavior after upstream changes |
| Lifecycle | Token expiry, revocation, disconnection and retained data |

<a id="explore"></a>
## Explore

- [Set up Google Meet](google-meet/setup.md)
- [Google Meet data and permissions](google-meet/data-and-permissions.md)
- [Google Meet sync and recovery](google-meet/recovery.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:8532501: [Integrations settings for Oliv](https://help.oliv.ai/en/articles/8532501-integrations-settings-for-oliv)
- HELP:15136310: [Understanding Oliv’s Meeting Recording Modes](https://help.oliv.ai/en/articles/15136310-understanding-oliv-s-meeting-recording-modes)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
