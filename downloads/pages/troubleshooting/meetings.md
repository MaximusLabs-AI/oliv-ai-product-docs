---
title: "Meeting capture and brief issues"
url: "/troubleshooting/meetings/"
version: "1.0"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Meeting capture and brief issues

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

A missing brief and a missing recording can have different causes. Establish the stage that stopped before changing the workflow.

<a id="meeting-symptoms"></a>
## Symptoms and checks



| Symptom | Check first |
| --- | --- |
| Meeting not recognized | Connected calendar, attendee details, scheduling-tool settings and timezone |
| Visible note taker did not join | Organizer, lobby/admission and configured capture route |
| Expected botless capture did not occur | Organization native-recording setup and supported platform conditions |
| Recording unavailable | Recording permission, completion and access to the artifact |
| Brief missing or late | Correct workflow, delivery channel, current schedule and source coverage |
| Wrong opportunity in brief | Activity association and multi-deal context |
| Follow-up missing | Recording/transcript processing and review state |

<a id="timing"></a>
## Do not assume one preparation time

The available sources describe different preparation windows. Confirm the current product and workspace rule before treating a ten-, twenty- or thirty-minute expectation as a defect.

A rescheduled meeting or a changed participant can also affect the input context. The refresh and cutoff rules need production confirmation.

<a id="recording-scope"></a>
## Recording controls

Use the current recording guide and verified client controls to stop or exclude capture. Older calendar-assistant instructions about Slack availability do not necessarily control the 2026 meeting recorder.

If native recording is not enabled, contact the implementation owner for the current platform setup; do not infer a local workaround from a marketing promise.

<a id="meeting-escalation"></a>
## Escalate with



- Meeting platform, organizer and scheduled time/timezone.
- Connected calendar and attendee-recognition context.
- Expected versus observed recording mode.
- Lobby/admission or permission evidence.
- Recording or meeting identifier and relevant delivery destination.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:15136310: [Understanding Oliv’s Meeting Recording Modes](https://help.oliv.ai/en/articles/15136310-understanding-oliv-s-meeting-recording-modes)
- HELP:9979279: [How to enable admin-level Zoom recording permissions with Oliv](https://help.oliv.ai/en/articles/9979279-how-to-enable-admin-level-zoom-recording-permissions-with-oliv)
- HELP:10511705: [How to configure Calendly to work with Oliv](https://help.oliv.ai/en/articles/10511705-how-to-configure-calendly-to-work-with-oliv)
