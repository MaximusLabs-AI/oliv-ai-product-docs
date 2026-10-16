---
title: "Choose CRM review and execution modes"
url: "/agents/crm-manager/operating-modes/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Choose CRM review and execution modes

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

The source describes activity-driven updates and direct-command batch work. Ask First and Auto-Pilot are described control modes; exact enforcement requires verification.

<a id="prerequisites"></a>
## Before you begin

Use a workspace where the agent and required source connections have been enabled. Name the user responsible for review and verify access to the representative account, deal or recording.

- [CRM Manager agent](../crm-manager.md)
- [Agent configuration](../configuration.md)

<a id="procedure"></a>
## Review procedure



1. Begin with review-required writes.
2. Inspect a permitted update.
3. Test a denied field.
4. Agree which changes can ever run without review..

<a id="expected-result"></a>
## Expected result to verify

A documented write policy matched to CRM permissions. This is an acceptance target for the described workflow; record whether it actually occurs in the current deployment.

<a id="exceptions"></a>
## Exceptions and missing information

Confirm per-field and per-action granularity, audit logs, rollback and criteria for automatic execution.

If the result is absent or inconsistent, retain the source record, timestamps and the review decision. Verify connector health and permissions before repeating an action that could produce an external change.

<a id="acceptance-record"></a>
## Record acceptance



| Field | What to retain |
| --- | --- |
| Scope | Workspace, user role, account/deal/recording and test date |
| Evidence | Source interaction and the output being reviewed |
| Decision | Approved, edited, rejected, blocked or needs confirmation |
| Downstream result | Final CRM, email, report or configuration state, where applicable |
| Owner | Person responsible for unresolved behavior and the next review |

<a id="links"></a>
## Related documentation



- [Tool modes and action boundaries](../configuration/approvals.md)
- [Agent output and execution issues](../../troubleshooting/agents.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/crm-manager: [CRM Manager | Oliv AI](https://oliv.ai/agents/crm-manager)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
