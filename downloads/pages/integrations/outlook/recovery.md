---
title: "Outlook and Microsoft 365 sync and recovery"
url: "/integrations/outlook/recovery/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Outlook and Microsoft 365 sync and recovery

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Review Outlook and Microsoft 365 recovery using a verified connector contract and representative data.

<a id="scope"></a>
## Connection scope

Calendar and email access are distinct from the Outlook add-in. Legacy help documents tenant restrictions and installation issues.

<a id="procedure"></a>
## Procedure



1. Record the failed item, timestamps, connected identity and expected result.
2. Check source permissions, tenant policy, token health and record or meeting eligibility.
3. Compare the Oliv result with the source system before retrying to avoid duplicate actions.
4. Reconnect or retry only through a supported workflow, then verify the final state and unresolved errors.

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
