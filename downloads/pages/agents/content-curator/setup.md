---
title: "Set up Content Curator"
url: "/agents/content-curator/setup/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Set up Content Curator

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Plan Content Curator inputs, process ownership, review controls and a representative acceptance exercise.

<a id="scope"></a>
## Choose the first task

Begin with one of the detailed task guides below. Agree the outcome and identify the source systems it requires.

- [Define clip-detection intents](intents.md)
- [Organize and review the clip library](clip-library.md)
- [Give relevance feedback on clips](feedback.md)
- [Evaluate library storage and synchronization](storage-sync.md)

<a id="connect"></a>
## Prepare inputs



1. Verify workspace entitlement and the current agent entry point with Oliv.
2. Connect the relevant CRM, calendar, recording, email or notification source with approved access.
3. Confirm account and user matching using representative data.
4. Document the process definitions, thresholds and output ownership needed for the first task.

<a id="review"></a>
## Start with human review

Require review of recommendations and external actions until the supported execution policy and permissions have been tested. A source describing automation is not enough to enable it for every action.

<a id="test"></a>
## Acceptance and recovery

Run one normal task and one case with missing, conflicting or restricted data. Inspect the source evidence and final result. If acceptance fails, stop external writes for that task and resolve the input, mapping or permission issue with its owner.

<a id="questions"></a>
## Agent-specific confirmation



- Confirm private, team and organization scope behavior in the current UI.
- Confirm exact filters, commenting, engagement metrics and clip-sharing permissions before teaching the live UI.
- Confirm whether feedback is per user, intent or organization and whether deletion affects the original recording.
- Highspot and LMS synchronization must remain unconfirmed until current technical evidence resolves the source conflict.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/content-curator: [Content Curator | Oliv AI](https://oliv.ai/agents/content-curator)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
