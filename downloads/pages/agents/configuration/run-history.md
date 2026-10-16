---
title: "Run history and outputs"
url: "/agents/configuration/run-history/"
version: "1.1-expanded"
status: needs-confirmation
source_checked: 2026-10-16
product_owner_approved: false
---

# Run history and outputs

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Run history should help a user explain what an agent attempted, what it produced and what happened next.

<a id="run-concepts"></a>
## Run concepts



| Concept | Meaning |
| --- | --- |
| Trigger | Why work began |
| Input context | The record and source information used |
| Attempt | A particular execution of the job |
| Output | The prepared answer, draft, proposed change or completed action |
| Review state | Whether a human decision is required or recorded |
| Destination result | What the receiving system accepted or rejected |

<a id="history-source"></a>
## What the prototype establishes

The extraction records run lists, a details drawer, output presentations and an Agent Feed. Its runs are hand-written examples, predominantly successful, rather than production telemetry.

Those examples do not establish complete logging of every action, failure-state coverage, retention, pagination, export or an audit guarantee. A cleared feed row is also not evidence that a run or its source data was deleted.

<a id="run-evidence"></a>
## Recommended evidence for a support case



- Agent and workflow name.
- Time, timezone and initiating event.
- Account, opportunity or meeting identifier.
- Observed output and destination.
- Approval or rejection state if shown.
- Error text or the point where expected behavior stopped.

<a id="run-open-questions"></a>
## Rules to verify

Confirm failed, queued, running, cancelled and retried states; whether retries create new attempts; what the user can correct; and how long history is retained.

If native run IDs or logs are unavailable, describe the support process that actually exists. Do not invent a run export API or a retry button.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:agents: Supplied original Oliv agent references — authored review basis
