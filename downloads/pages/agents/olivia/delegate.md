---
title: "Request and review specialist work"
url: "/agents/olivia/delegate/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Request and review specialist work

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

The described front-facing workflow routes a request to an appropriate specialist and returns a synthesized result.

<a id="prerequisites"></a>
## Before you begin

Use a workspace where the agent and required source connections have been enabled. Name the user responsible for review and verify access to the representative account, deal or recording.

- [Olivia agent](../olivia.md)
- [Agent configuration](../configuration.md)

<a id="procedure"></a>
## Review procedure



1. State the account, desired outcome and boundary.
2. Inspect the selected specialist and evidence.
3. Review the result before external action..

<a id="expected-result"></a>
## Expected result to verify

A reviewed specialist output in the correct account context. This is an acceptance target for the described workflow; record whether it actually occurs in the current deployment.

<a id="exceptions"></a>
## Exceptions and missing information

Confirm which specialists are available and how conflicting requests or duplicate work are handled.

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

- WEB:/agents/olivia: [Olivia – Chief of AI Staff for GTM Teams | Oliv AI](https://oliv.ai/agents/olivia)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
