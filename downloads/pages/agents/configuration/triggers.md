---
title: "Triggers and schedules"
url: "/agents/configuration/triggers/"
version: "1.0"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Triggers and schedules

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

An agent may start from a request, a source event or a schedule. The trigger mechanism and the action permission are separate decisions.

<a id="trigger-types"></a>
## Trigger types described in sources



| Type | Examples in the product material | Confirm |
| --- | --- | --- |
| Activity-driven | New meeting, call or email context | Supported event and completion condition |
| Record change | Opportunity or account state changes | Fields, filters and event ordering |
| Scheduled | Forecast and portfolio review cadence | Timezone, recurrence and delivery |
| Direct request | Ask an agent to prepare or analyze work | User identity and permitted scope |

<a id="schedule-rules"></a>
## Schedule rules to document

Record the timezone, recurrence, owner, effective start and destination. State how holidays, missed runs, daylight-saving changes and unavailable inputs are handled.

The prototype schedule dialog contains fixed timezone text and does not demonstrate persistence. Its displayed timezone is not a workspace policy, and a closed dialog does not prove a schedule was created.

<a id="stop-conditions"></a>
## Stop and duplicate conditions

For event-driven work, confirm duplicate suppression, concurrent runs and what happens when a source record changes again. For customer outreach, confirm reply, opt-out, ownership change and manual-pause behavior.

The available sources do not establish a universal agent pause, global stop or automatic undo facility. Those must be verified before they appear as product instructions.

<a id="trigger-acceptance"></a>
## Recommended trigger acceptance test



1. Create a known qualifying event in a controlled scope.
2. Verify one corresponding run and its input record.
3. Repeat or modify the event and observe duplicate handling.
4. Check a non-qualifying event that should not start work.
5. Pause or disable the verified trigger path and confirm the observed result.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.


