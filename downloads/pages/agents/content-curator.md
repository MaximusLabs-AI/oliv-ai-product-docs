---
title: "Content Curator agent"
url: "/agents/content-curator/"
version: "1.1-expanded"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Content Curator agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Content Curator identifies relevant moments in recorded conversations and organizes them into usable examples for enablement and coaching.

<a id="purpose"></a>
## Purpose and audience

Content Curator identifies relevant moments in recorded conversations and organizes them into usable examples for enablement and coaching.

Primary audience: Enablement, managers and customer-facing teams. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- Accessible call or meeting recordings
- A named intent describing the moments to find
- Library or playlist configuration
- The destination for notifications and sharing

<a id="trigger"></a>
## What starts the workflow

New recordings evaluated against the configured intent. The internal document describes proactive clipping and delivery rather than requiring a search for each example.

<a id="workflow"></a>
## Documented workflow



1. Define an intent in plain language and identify its audience.
2. Evaluate relevant recordings for matching moments.
3. Extract the useful segment and retain its source context.
4. Place the clip in the configured library or playlist.
5. Notify the intended users through the verified delivery route.
6. Review irrelevant clips through the supported feedback mechanism.

<a id="outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- Clips linked to source recordings
- Metadata such as participants, time and deal context
- Organized examples for coaching or enablement
- Notifications when relevant material is added

<a id="actions-and-review"></a>
## Actions and human review

Clip detection, library access, external syncing and feedback are distinct controls. The available sources do not establish that all advertised storage or LMS integrations are working in every deployment.

<a id="action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="rules"></a>
## Rules and configuration



- An intent defines what to detect; a library is the destination that organizes clips.
- The source describes private, team and organization sharing scopes, which require production verification.
- Historical backfill, pricing and learning-feedback thresholds remain unresolved.
- Internal copy describes Highspot storage while also listing LMS implementation as a pending area.

<a id="curator-intent"></a>
### Intent configuration

The source describes an intent with a name, a plain-language detection brief and an access scope. Examples include pricing objections, competitor mentions, useful discovery and onboarding moments. These are examples of detection intent, not keyword rules or guaranteed detections.

<a id="curator-artifact"></a>
### Clip context and destination

The document describes delivery via configured collaboration channels and a possible digest cadence. Confirm actual destination support, sharing permissions and the external-storage implementation.

| Artifact detail | Purpose |
| --- | --- |
| Source recording link | Preserve the surrounding conversation |
| Timestamp | Locate the selected moment |
| Participants and call date | Understand who spoke and when |
| Account/deal context | Connect the example to the relevant work |
| Library/playlist | Organize and control access to the selected examples |

<a id="collaboration"></a>
## How it works with other agents

Coach uses selected examples in the development cadence; Meeting Assistant and conversation capture provide source activity; Content Curator focuses on finding and organizing the examples.

<a id="boundaries"></a>
## Scope and limitations

Content Curator is not the call recorder or a full learning-management system. It depends on accessible recordings and does not establish a license to share every recording with every user.

<a id="verify"></a>
## Questions to resolve before publication



- Which storage and LMS integrations are available now?
- Can historical recordings be backfilled?
- How are library and clip permissions enforced?
- What does removing a clip change in later detection?
- What limits and credit costs apply to clips and storage?

<a id="related"></a>
## Related documentation



- [enable](../apps/enable.md)
- [coaching](../workflows/coaching.md)
- [access](../administration/access.md)

<a id="operational-guides"></a>
## Detailed operational guides



- [Define clip-detection intents](content-curator/intents.md)
- [Organize and review the clip library](content-curator/clip-library.md)
- [Give relevance feedback on clips](content-curator/feedback.md)
- [Evaluate library storage and synchronization](content-curator/storage-sync.md)
- [Set up Content Curator](content-curator/setup.md)

<a id="source-boundary"></a>
## Availability and validation

These guides explain the supplied agent reference in operational terms. They do not establish that every described control is shipped or included in every plan. Open questions remain visible in each task.

<a id="explore"></a>
## Explore

- [Define clip-detection intents](content-curator/intents.md)
- [Organize and review the clip library](content-curator/clip-library.md)
- [Give relevance feedback on clips](content-curator/feedback.md)
- [Evaluate library storage and synchronization](content-curator/storage-sync.md)
- [Set up Content Curator](content-curator/setup.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/content-curator: [Content Curator | Oliv AI](https://oliv.ai/agents/content-curator)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
