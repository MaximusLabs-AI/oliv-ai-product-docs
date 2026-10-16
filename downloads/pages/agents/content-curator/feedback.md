---
title: "Give relevance feedback on clips"
url: "/agents/content-curator/feedback/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Give relevance feedback on clips

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

The reference describes removing irrelevant results and using feedback to improve detection. The feedback contract and response speed are not specified.

<a id="prerequisites"></a>
## Before you begin

Use a workspace where the agent and required source connections have been enabled. Name the user responsible for review and verify access to the representative account, deal or recording.

- [Content Curator agent](../content-curator.md)
- [Agent configuration](../configuration.md)

<a id="procedure"></a>
## Review procedure



1. Identify why a candidate is irrelevant.
2. Record feedback using the supported control.
3. Inspect a later result set.
4. Retain examples for quality review..

<a id="expected-result"></a>
## Expected result to verify

A documented relevance decision and a way to evaluate subsequent quality. This is an acceptance target for the described workflow; record whether it actually occurs in the current deployment.

<a id="exceptions"></a>
## Exceptions and missing information

Confirm whether feedback is per user, intent or organization and whether deletion affects the original recording.

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

- WEB:/agents/content-curator: [Content Curator | Oliv AI](https://oliv.ai/agents/content-curator)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
