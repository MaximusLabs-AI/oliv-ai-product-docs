---
title: "Review a warm introduction draft"
url: "/agents/gold-digger/warm-introduction/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Review a warm introduction draft

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

The described workflow drafts a contextual introduction from the CSM to the relevant stakeholder. A human reviews and sends or authorizes delegation.

<a id="prerequisites"></a>
## Before you begin

Use a workspace where the agent and required source connections have been enabled. Name the user responsible for review and verify access to the representative account, deal or recording.

- [Gold Digger agent](../gold-digger.md)
- [Agent configuration](../configuration.md)

<a id="procedure"></a>
## Review procedure



1. Verify the customer context.
2. Remove unsupported assumptions.
3. Confirm sender and recipient.
4. Approve the final introduction..

<a id="expected-result"></a>
## Expected result to verify

A reviewed customer-facing draft. This is an acceptance target for the described workflow; record whether it actually occurs in the current deployment.

<a id="exceptions"></a>
## Exceptions and missing information

Confirm sending permissions and delegation; a generated draft is not evidence that an email was sent.

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

- WEB:/agents/gold-digger: [Gold Digger – Expansion Signal Agent | Oliv AI](https://oliv.ai/agents/gold-digger)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
