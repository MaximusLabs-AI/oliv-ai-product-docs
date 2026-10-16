---
title: "Configure coaching scorecards"
url: "/agents/coach/scorecards/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Configure coaching scorecards

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Coach’s supplied reference describes scoring across pipeline coverage, deal execution, meeting effectiveness and foundational skills. Criteria can be aligned to the team’s methodology.

<a id="prerequisites"></a>
## Before you begin

Use a workspace where the agent and required source connections have been enabled. Name the user responsible for review and verify access to the representative account, deal or recording.

- [Coach agent](../coach.md)
- [Agent configuration](../configuration.md)

<a id="procedure"></a>
## Review procedure



1. Select representative recorded activity.
2. Agree criterion definitions and weights.
3. Inspect examples for each score.
4. Verify reviewer visibility..

<a id="expected-result"></a>
## Expected result to verify

A scorecard with understandable criteria and source-linked examples. This is an acceptance target for the described workflow; record whether it actually occurs in the current deployment.

<a id="exceptions"></a>
## Exceptions and missing information

Confirm pre-built scorecard availability, customization permissions and minimum data volume. The BDR version is unresolved in the original reference.

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

- WEB:/agents/coach: [Coach – AI Sales Coaching Agent | Oliv AI](https://oliv.ai/agents/coach)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
