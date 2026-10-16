---
title: "Slack integration"
url: "/integrations/slack/"
version: "1.0"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Slack integration

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Deliver supported briefs, alerts and review-related messages into the team’s collaboration workflow.

<a id="supported-purpose"></a>
## Purpose and available evidence

The revenue-workflow help material describes meeting notifications and summaries, and agent documents describe alerts and briefs. A much older Slack bot manages status and Do Not Disturb from a calendar; that legacy product must be kept separate.

<a id="data-direction"></a>
## Data direction and permissions

Message delivery into Slack and importing Slack activity as context are distinct capabilities. Confirm which is enabled, the destination and the allowed source history.

<a id="setup"></a>
## Setup prerequisites

Identify the workspace, installing role, application and intended user/channel destinations. Verify app installation or a support-assisted shared-channel route for the actual workflow.

<a id="disconnect"></a>
## Disconnect and retained data

Confirm how to disconnect the app or shared channel and how to stop each notification type. Removing a Slack connection does not itself establish deletion of imported context.

<a id="connector-questions"></a>
## Connector contract to confirm

These are unresolved implementation questions. The list is not a claim that all of the named controls already exist.

- Which users and channels can receive each message?
- Which app permissions are requested?
- Is Slack context imported, or are messages only delivered?
- What history and private/shared-channel coverage applies?
- Where do approvals appear, if Slack approvals are supported?
- What happens when a user leaves or a channel is archived?

<a id="verify-connection"></a>
## Recommended connection check

Use a controlled source record or meeting, confirm that it arrives with the right owner and associations, and inspect any downstream write or notification. Repeat with a permission or validation exception and record the observed error path.

Record the integration version, scopes, tested objects, plan and verification date. Keep that acceptance record current when the provider changes its API or permissions.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:9133182: [Messages Sent by Oliv to Slack](https://help.oliv.ai/en/articles/9133182-messages-sent-by-oliv-to-slack)
- HELP:8532501: [Integrations settings for Oliv](https://help.oliv.ai/en/articles/8532501-integrations-settings-for-oliv)
