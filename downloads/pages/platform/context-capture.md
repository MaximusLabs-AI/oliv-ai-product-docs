---
title: "Context Capture"
url: "/platform/context-capture/"
version: "1.1-expanded"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Context Capture

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Context Capture brings customer activity into Oliv so teams and agents can work from more than manually entered CRM notes.

<a id="captured-sources"></a>
## Activity sources

The current website describes meetings, phone calls, email, messages and in-person conversations, alongside connected business records and supporting data. Availability depends on the source, integration, plan and organization configuration.

For each source, distinguish metadata from full content. An event title or call log is not a transcript; a linked email is not necessarily a mailbox-wide archive. Confirm the actual imported fields, access scope and historical coverage.

| Input | Document the boundary |
| --- | --- |
| Online meetings | Organizer, recording mode, consent, transcript and participant access |
| Phone calls | Supported dialer or capture route and recording availability |
| Email | Mailbox scope, included threads, attachments and retention |
| Messaging | Connected workspace/channel scope and supported history |
| In-person activity | Supported capture application/device and upload process |
| CRM and usage/support data | Objects, fields, event coverage and sync direction |

<a id="recording-conditions"></a>
## Recording has conditions

The May 2026 recording guide distinguishes internally organized meetings from externally organized meetings when native recording is enabled. An external organizer can require a visible note taker and lobby admission.

A claim that Oliv supports botless recording should therefore include the platform and organization prerequisites. Do not describe every meeting as botless or assume the same behavior for every conferencing tool.

- [Meeting recording workflow](../workflows/meeting-recording.md)

<a id="capture-checks"></a>
## Recommended verification

Before relying on a downstream agent, check a known activity for its content, participants, timestamps and destination record. Check what happens to private, cancelled, declined or inaccessible meetings, and how a user stops capture.

Missing context can cause an incomplete result without indicating a reasoning failure. Troubleshooting should first establish whether the source activity arrived and was accessible.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/context-capture: [Context Capture – Every Interaction, Captured | Oliv AI](https://oliv.ai/context-capture)
- HELP:15136310: [Understanding Oliv’s Meeting Recording Modes](https://help.oliv.ai/en/articles/15136310-understanding-oliv-s-meeting-recording-modes)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
