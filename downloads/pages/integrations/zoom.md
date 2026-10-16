---
title: "Zoom integration"
url: "/integrations/zoom/"
version: "1.0"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Zoom integration

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Capture supported Zoom meetings and use recordings or meeting context in Oliv workflows.

<a id="supported-purpose"></a>
## Purpose and available evidence

The Help Center distinguishes a meeting-bot integration from an in-meeting app. A May 2026 guide adds the conditional distinction between native recording for internally organized meetings and a visible note taker for externally organized meetings.

<a id="data-direction"></a>
## Data direction and permissions

Meeting and recording context flows into Oliv. The in-meeting interface described in the older guide is not evidence of every current write or sharing capability.

<a id="setup"></a>
## Setup prerequisites

Confirm which Zoom application and organization recording mode are being enabled. The admin-level guide requires a Zoom administrator and coordination with Oliv; exact current scopes must be checked against the installed application.

<a id="disconnect"></a>
## Disconnect and retained data

Use the current approved Zoom/Oliv disconnect process and confirm recording access after revocation. The older guide describes support-assisted removal.

<a id="connector-questions"></a>
## Connector contract to confirm

These are unresolved implementation questions. The list is not a claim that all of the named controls already exist.

- Who organized the meeting?
- Is native recording enabled for this organization?
- Which host/admin permissions apply?
- What happens in the lobby or without host admission?
- Who can access and share the resulting recording?
- Which scopes are requested by the current app version?

<a id="verify-connection"></a>
## Recommended connection check

Use a controlled source record or meeting, confirm that it arrives with the right owner and associations, and inspect any downstream write or notification. Repeat with a permission or validation exception and record the observed error path.

Record the integration version, scopes, tested objects, plan and verification date. Keep that acceptance record current when the provider changes its API or permissions.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:8638345: [Oliv <> Zoom integrations](https://help.oliv.ai/en/articles/8638345-oliv-zoom-integrations)
- HELP:9979279: [How to enable admin-level Zoom recording permissions with Oliv](https://help.oliv.ai/en/articles/9979279-how-to-enable-admin-level-zoom-recording-permissions-with-oliv)
- HELP:15136310: [Understanding Oliv’s Meeting Recording Modes](https://help.oliv.ai/en/articles/15136310-understanding-oliv-s-meeting-recording-modes)
