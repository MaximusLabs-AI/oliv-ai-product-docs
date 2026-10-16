---
title: "Slack data and permissions"
url: "/integrations/slack/data-and-permissions/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Slack data and permissions

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Review Slack data and permissions using a verified connector contract and representative data.

<a id="scope"></a>
## Connection scope

Notifications and interaction paths are described in Help material. Channel scope and current bot behavior need review.

<a id="procedure"></a>
## Procedure



1. List the exact objects, fields, channels or recording artifacts required by the workflow.
2. Map users and account identities, then test a permitted and a restricted example.
3. Distinguish readable context, generated proposals and actual source-system writes.
4. Verify which data remains after source access is revoked or the integration is disconnected.

<a id="acceptance"></a>
## Acceptance evidence



- Source identity and approved permission scopes.
- A permitted item with the correct account, user and timestamp.
- A restricted or ineligible item that remains unavailable.
- Confirmed downstream state for any approved write.

<a id="limits"></a>
## Known documentation limits

The supplied Help references mix current recording guidance with older integration UI. This task describes the acceptance sequence; it does not invent unverified button names or promise every object and field is supported.

<a id="references"></a>
## Related references



- [Slack integration](../slack.md)
- [Integrations and extensibility reference](../../features/integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:9133182: [Messages Sent by Oliv to Slack](https://help.oliv.ai/en/articles/9133182-messages-sent-by-oliv-to-slack)
- WEB:/integrations: [Integrations – Oliv Works With Your Tech Stack | Oliv AI](https://www.oliv.ai/integrations)
