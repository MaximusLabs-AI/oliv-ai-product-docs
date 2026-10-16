---
title: "Record meetings with Oliv"
url: "/workflows/meeting-recording/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Record meetings with Oliv

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Understand when Oliv records natively and when a visible note taker joins, then check the prerequisites for your meeting.

<a id="before-you-start"></a>
## Before you start



- The relevant calendar and meeting platform connection.
- Organization-level native recording setup where required.
- Appropriate platform permissions and recording indication.
- The ability to admit a visible note taker when needed.

<a id="steps"></a>
## Workflow sequence

This sequence describes the documented handoffs. Verify current production controls before using it as a click-by-click end-user procedure.

1. Identify who organized the meeting.
2. If the organization has native recording enabled and an internal user organized it, check the supported native recording setup.
3. If an external organizer owns the meeting, expect the visible note-taker route described by the current guide.
4. Admit the note taker from the lobby where required and confirm that recording started.
5. After processing, check the recording, transcript and meeting association.

<a id="result"></a>
## Expected result

The May 2026 guide describes native/botless recording for internally organized meetings and a visible note taker for externally organized meetings, conditional on organization setup.

<a id="exceptions"></a>
## Variations and exceptions

Without native setup, an internal meeting is not automatically evidence of botless capture. Host permissions, lobby controls, platform settings and unsupported meeting conditions can prevent recording.

<a id="acceptance-checks"></a>
## Recommended acceptance checks

The following checks are proposed validation work, not claims that the product already provides every control mentioned.

- Verify the behavior for an internally organized test meeting.
- Verify an externally organized meeting with a lobby.
- Check the recording indication visible to participants.
- Confirm the stop or exclusion control for the current client.
- Check the resulting recording access and sharing boundary.

<a id="related"></a>
## Related references



- [converse](../apps/converse.md)
- [zoom](../integrations/zoom.md)
- [microsoft teams](../integrations/microsoft-teams.md)
- [meetings](../troubleshooting/meetings.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:15136310: [Understanding Oliv’s Meeting Recording Modes](https://help.oliv.ai/en/articles/15136310-understanding-oliv-s-meeting-recording-modes)
- HELP:9979279: [How to enable admin-level Zoom recording permissions with Oliv](https://help.oliv.ai/en/articles/9979279-how-to-enable-admin-level-zoom-recording-permissions-with-oliv)
- HELP:8796010: [Copilot management options](https://help.oliv.ai/en/articles/8796010-copilot-management-options)
- WEB:/converse: [Converse – AI Conversation Capture | Oliv AI](https://www.oliv.ai/converse)
