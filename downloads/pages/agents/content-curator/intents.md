---
title: "Define clip-detection intents"
url: "/agents/content-curator/intents/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Define clip-detection intents

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Content Curator’s reference separates detection intents from the clip library. An intent names the moments to find and describes them in plain language.

<a id="prerequisites"></a>
## Before you begin

Use a workspace where the agent and required source connections have been enabled. Name the user responsible for review and verify access to the representative account, deal or recording.

- [Content Curator agent](../content-curator.md)
- [Agent configuration](../configuration.md)

<a id="procedure"></a>
## Review procedure



1. Choose a narrow teaching need.
2. Define an intent and access scope.
3. Inspect candidate moments.
4. Refine ambiguous wording..

<a id="expected-result"></a>
## Expected result to verify

A reviewed intent tied to the intended audience and example type. This is an acceptance target for the described workflow; record whether it actually occurs in the current deployment.

<a id="exceptions"></a>
## Exceptions and missing information

Confirm private, team and organization scope behavior in the current UI.

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
