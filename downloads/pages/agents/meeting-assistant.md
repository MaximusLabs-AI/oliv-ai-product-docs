---
title: "Meeting Assistant agent"
url: "/agents/meeting-assistant/"
version: "1.1-expanded"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Meeting Assistant agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Meeting Assistant prepares an existing opportunity’s context before a meeting and helps turn the conversation into follow-up work afterward.

<a id="purpose"></a>
## Purpose and audience

Meeting Assistant prepares an existing opportunity’s context before a meeting and helps turn the conversation into follow-up work afterward.

Primary audience: Sellers, CSMs and account managers. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- A meeting associated with an active opportunity
- Stakeholders and previous conversations
- Deal fields and qualification methodology
- A recording or transcript for post-meeting work

<a id="trigger"></a>
## What starts the workflow

A verified calendar or meeting workflow before a scheduled meeting, followed by processing of the recorded conversation. The exact trigger path differs across integrations and needs confirmation.

<a id="workflow"></a>
## Documented workflow



1. Identify the opportunity and participants for the upcoming meeting.
2. Prepare the deal summary, qualification gaps, stakeholder context and recommended agenda.
3. Deliver the brief through the configured channel.
4. After the meeting is processed, prepare a follow-up draft and proposed field updates.
5. Review the suggested next steps and apply the verified approval policy.

<a id="outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- A concise pre-meeting brief
- A follow-up email draft
- Proposed opportunity or qualification updates
- Flags for missing or changed information

<a id="actions-and-review"></a>
## Actions and human review

The source describes drafts and proposed field updates. It does not establish that every follow-up is sent automatically or that every proposed value is written without review.

<a id="action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="rules"></a>
## Rules and configuration



- Opportunity context distinguishes Meeting Assistant from first-contact Researcher.
- The September agent document describes a thirty-minute prep window.
- Older public Help Center workflows describe other prep timings; confirm the product and configuration before using a single number.
- Recording completion and processing are prerequisites for transcript-based follow-up.

<a id="meeting-brief-fields"></a>
### Preparation contents



| Part | Documented context |
| --- | --- |
| Deal summary | Stage, value, close date, recent activity and next steps |
| Qualification | Known evidence and gaps against the active framework |
| Stakeholders | Participant role and relevant prior context |
| Agenda | Topics appropriate to the opportunity and open questions |

<a id="meeting-followup-parts"></a>
### Post-meeting outputs

The source distinguishes a follow-up draft, proposed deal-field updates and qualification-gap flags. These depend on the processed conversation. None should be described as sent or applied until the relevant destination confirms the action.

<a id="collaboration"></a>
## How it works with other agents

Researcher adds first-contact intelligence; CRM Manager handles supported writes; Deal Driver uses meeting context for management awareness; qualification and process rules come from the playbook.

<a id="boundaries"></a>
## Scope and limitations

Preparation for an active opportunity is different from prospecting a new account. A pre-meeting brief is not a substitute for obtaining the meeting recording or reviewing an outbound message.

<a id="verify"></a>
## Questions to resolve before publication



- Which event starts preparation for each calendar integration?
- What is the current delivery time and channel?
- How are meetings discussing several deals handled?
- Can users customize the brief or agenda?
- Where are follow-up drafts reviewed and sent?

<a id="related"></a>
## Related documentation



- [meeting preparation](../workflows/meeting-preparation.md)
- [meeting recording](../workflows/meeting-recording.md)
- [researcher](researcher.md)

<a id="operational-guides"></a>
## Detailed operational guides



- [Review an existing-deal meeting brief](meeting-assistant/preparation.md)
- [Review post-meeting follow-through](meeting-assistant/follow-through.md)
- [Verify ongoing deal-context updates](meeting-assistant/deal-context.md)
- [Set up Meeting Assistant](meeting-assistant/setup.md)

<a id="source-boundary"></a>
## Availability and validation

These guides explain the supplied agent reference in operational terms. They do not establish that every described control is shipped or included in every plan. Open questions remain visible in each task.

<a id="explore"></a>
## Explore

- [Review an existing-deal meeting brief](meeting-assistant/preparation.md)
- [Review post-meeting follow-through](meeting-assistant/follow-through.md)
- [Verify ongoing deal-context updates](meeting-assistant/deal-context.md)
- [Set up Meeting Assistant](meeting-assistant/setup.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/meeting-assistant: [Meeting Assistant – AI Briefs &amp; Follow-ups | Oliv AI](https://oliv.ai/agents/meeting-assistant)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
