---
title: "Review rep-level next-step nudges"
url: "/agents/deal-driver/rep-nudges/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Review rep-level next-step nudges

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

The described nudges remind reps about stalled deals, overdue actions and activity gaps. CRM Manager remains responsible for task creation and logging.

<a id="prerequisites"></a>
## Before you begin

Use a workspace where the agent and required source connections have been enabled. Name the user responsible for review and verify access to the representative account, deal or recording.

- [Deal Driver agent](../deal-driver.md)
- [Agent configuration](../configuration.md)

<a id="procedure"></a>
## Review procedure



1. Inspect the underlying task or deal.
2. Confirm owner and due date.
3. Resolve the commitment.
4. Check whether the nudge closes or repeats..

<a id="expected-result"></a>
## Expected result to verify

A resolved or explicitly deferred next step. This is an acceptance target for the described workflow; record whether it actually occurs in the current deployment.

<a id="exceptions"></a>
## Exceptions and missing information

Confirm cadence, escalation, quiet hours and control over notification volume.

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

- WEB:/agents/deal-driver: [Deal Driver – AI Deal Risk Agent | Oliv AI](https://oliv.ai/agents/deal-driver)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
