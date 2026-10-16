---
title: "Outlook and Microsoft 365 data and permissions"
url: "/integrations/outlook/data-and-permissions/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Outlook and Microsoft 365 data and permissions

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Review Outlook and Microsoft 365 data and permissions using a verified connector contract and representative data.

<a id="scope"></a>
## Connection scope

Calendar and email access are distinct from the Outlook add-in. Legacy help documents tenant restrictions and installation issues.

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



- [Outlook and Microsoft 365 integration](../outlook.md)
- [Integrations and extensibility reference](../../features/integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:9144560: [Overcome Outlook Calendar Access Restrictions](https://help.oliv.ai/en/articles/9144560-overcome-outlook-calendar-access-restrictions)
- WEB:/integrations: [Integrations – Oliv Works With Your Tech Stack | Oliv AI](https://www.oliv.ai/integrations)
