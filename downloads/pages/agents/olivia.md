---
title: "Olivia agent"
url: "/agents/olivia/"
version: "1.1-expanded"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Olivia agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Olivia is the front-facing agent that brings revenue context into team work and coordinates specialists when a task needs a more specific capability.

<a id="purpose"></a>
## Purpose and audience

Olivia is the front-facing agent that brings revenue context into team work and coordinates specialists when a task needs a more specific capability.

Primary audience: AEs, BDRs, CSMs and account managers. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- Account, opportunity and stakeholder context
- Meetings, email and other connected activity
- The process playbook maintained with Oliver
- The user’s request and the current workflow state

<a id="trigger"></a>
## What starts the workflow

A user request or a configured proactive workflow. The sources describe both conversational interaction and activity-driven follow-through; exact channel availability must be confirmed.

<a id="workflow"></a>
## Documented workflow



1. Read the relevant account, opportunity and activity context.
2. Identify the task and the process rules that apply.
3. Prepare the response or route the job to an appropriate specialist.
4. Bring the specialist’s output back into the user’s workflow.
5. Continue the agreed follow-through within the configured action boundary.

<a id="outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- Contextual answers and preparation
- Briefs, alerts and suggested next actions
- Specialist work assembled for the requesting team member

<a id="actions-and-review"></a>
## Actions and human review

Olivia can coordinate work whose effects depend on the specialist and connected tool. A prepared response, a draft, a CRM change and a sent message need separate explanations.

<a id="action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="rules"></a>
## Rules and configuration



- Use Oliver’s organizational process context when coordinating the job.
- Do not assume an individual’s access permits organization-wide visibility.
- A specialist’s action permission still needs to be established for the task.

<a id="orchestration-context"></a>
### Context used in coordination

The internal reference describes an ongoing view of deals, accounts, conversations and upcoming work. Proactive alerts and requested actions use that context together with the organization’s process knowledge. Data visibility and personal versus shared context still require explicit permission documentation.

<a id="orchestration-handoff"></a>
### Specialist handoff

A complete handoff identifies the job, source record, relevant process constraint and expected output. The specialist’s result returns to the requesting workflow. This recommended description should be matched to actual runtime evidence before documenting a guaranteed handoff protocol.

<a id="collaboration"></a>
## How it works with other agents

Researcher can prepare first-contact intelligence, Meeting Assistant handles opportunity-aware meeting support, CRM Manager applies field updates, and other specialists handle their defined jobs. The named ensemble is a source description, not a promise that every specialist is enabled.

<a id="boundaries"></a>
## Scope and limitations

Olivia does not replace the organization’s accountable decision makers or independently define the company process. Oliver owns the process layer described in the source documents.

<a id="verify"></a>
## Questions to resolve before publication



- Which interaction channels are enabled in the current workspace?
- What happens when a user request conflicts with an organizational rule?
- Which specialists may Olivia call, and who controls that list?
- How are cross-functional tasks assigned without duplicate work?
- Which conversation setting takes precedence over a tool-level setting?

<a id="related"></a>
## Related documentation



- [oliver](oliver.md)
- [agent harness](../platform/agent-harness.md)
- [approvals](configuration/approvals.md)

<a id="operational-guides"></a>
## Detailed operational guides



- [Review account and deal context](olivia/context.md)
- [Request and review specialist work](olivia/delegate.md)
- [Triage Olivia’s proactive signals](olivia/proactive-alerts.md)
- [Verify Olivia’s alignment with Oliver](olivia/process-alignment.md)
- [Set up Olivia](olivia/setup.md)

<a id="source-boundary"></a>
## Availability and validation

These guides explain the supplied agent reference in operational terms. They do not establish that every described control is shipped or included in every plan. Open questions remain visible in each task.

<a id="explore"></a>
## Explore

- [Review account and deal context](olivia/context.md)
- [Request and review specialist work](olivia/delegate.md)
- [Triage Olivia’s proactive signals](olivia/proactive-alerts.md)
- [Verify Olivia’s alignment with Oliver](olivia/process-alignment.md)
- [Set up Olivia](olivia/setup.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/olivia: [Olivia – Chief of AI Staff for GTM Teams | Oliv AI](https://oliv.ai/agents/olivia)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
