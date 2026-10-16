---
title: "Integration and sync issues"
url: "/troubleshooting/integrations/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Integration and sync issues

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

A connected-looking interface does not prove that a particular object or action is authorized and working.

<a id="sync-symptoms"></a>
## Symptoms and checks



| Symptom | Check first |
| --- | --- |
| No source data | Account identity, connector authorization and selected scope |
| Some records missing | Supported objects, filters, ownership and historical import |
| Wrong account or opportunity | Association rules and duplicate or multi-opportunity cases |
| Proposed update not written | Approval state, field mapping and writable field type |
| CRM rejected value | Provider validation, enumeration, required fields and permissions |
| Notifications missing | Destination membership, app permissions and selected channel |
| Old values remain | Refresh cadence, conflict policy and source-of-truth rule |

<a id="safe-recovery"></a>
## Recovery boundary

Use the connector’s actual reconnect, retry or support path. Reinstalling, widening scopes or recreating records can have broader consequences and should not substitute for finding the failing stage.

Confirm whether the receiving system accepted the previous operation before retrying a write or message. The sources do not establish universal duplicate suppression.

<a id="sync-escalation"></a>
## Escalate with



- Connector and connected account or tenant.
- Relevant object and source/destination identifiers.
- Field or action affected.
- Observed authorization or validation message.
- Last known successful sync and the current time/timezone.
- Whether approval was required and completed.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:8532501: [Integrations settings for Oliv](https://help.oliv.ai/en/articles/8532501-integrations-settings-for-oliv)
- HELP:8671280: [Oliv <> HubSpot Integrations](https://help.oliv.ai/en/articles/8671280-oliv-hubspot-integrations)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
