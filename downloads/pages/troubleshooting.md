---
title: "Troubleshooting"
url: "/troubleshooting/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Troubleshooting

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Troubleshooting begins by separating missing input, incorrect association, incomplete processing, review state and destination failure.

<a id="diagnostic-order"></a>
## Recommended diagnostic order



1. Confirm the source activity or record exists and is accessible.
2. Check whether it arrived in Oliv with the correct identity and time.
3. Verify the account, opportunity and participants.
4. Check the relevant agent or workflow state.
5. Determine whether human review is pending.
6. Inspect the destination system and any observed error.
7. Escalate with the minimum useful evidence.

<a id="support-package"></a>
## Support evidence

Include the workflow and agent name, time and timezone, relevant record or meeting ID, the expected result, the observed state and any exact error text. Avoid sending unrelated customer content.

Do not repeatedly retry a consequential action until you know whether the previous attempt succeeded. The current sources do not establish a universal idempotency or undo mechanism.

<a id="explore"></a>
## Explore

- [Meeting capture and brief issues](troubleshooting/meetings.md)
- [Integration and sync issues](troubleshooting/integrations.md)
- [Agent output and execution issues](troubleshooting/agents.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:8796010: [Copilot management options](https://help.oliv.ai/en/articles/8796010-copilot-management-options)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
