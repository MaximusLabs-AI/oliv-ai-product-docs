---
title: "Accept, edit or reject a proposed CRM update"
url: "/agents/crm-manager/proposed-updates/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Accept, edit or reject a proposed CRM update

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

The reference describes a proposal containing the current value, proposed value and source reasoning. Review outcomes include accept, edit-and-accept and reject.

<a id="prerequisites"></a>
## Before you begin

Use a workspace where the agent and required source connections have been enabled. Name the user responsible for review and verify access to the representative account, deal or recording.

- [CRM Manager agent](../crm-manager.md)
- [Agent configuration](../configuration.md)

<a id="procedure"></a>
## Review procedure



1. Open the proposal.
2. Inspect the cited interaction.
3. Compare the existing crm value.
4. Choose the review outcome.
5. Verify the final crm value..

<a id="expected-result"></a>
## Expected result to verify

A reviewed change with evidence and a confirmed downstream result. This is an acceptance target for the described workflow; record whether it actually occurs in the current deployment.

<a id="exceptions"></a>
## Exceptions and missing information

Confirm current control labels, rejected-proposal behavior, edit history and whether proposals expire after later changes.

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
