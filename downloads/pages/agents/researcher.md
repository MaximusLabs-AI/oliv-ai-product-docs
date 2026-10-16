---
title: "Researcher agent"
url: "/agents/researcher/"
version: "1.0"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Researcher agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Researcher prepares account and contact context for a meeting with a new person or an account the team has not engaged recently.

<a id="purpose"></a>
## Purpose and audience

Researcher prepares account and contact context for a meeting with a new person or an account the team has not engaged recently.

Primary audience: Sellers and account managers. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- The upcoming meeting and participants
- Company and contact identifiers
- Accessible professional and company information
- Relevant account history where available

<a id="trigger"></a>
## What starts the workflow

A scheduled first-contact meeting in the workflow described by the internal document. Exact calendar triggers and supported sources require confirmation.

<a id="workflow"></a>
## Documented workflow



1. Identify the company and the people on the calendar event.
2. Gather relevant business, role and recent-event context.
3. Select the most useful points for the meeting.
4. Prepare a short brief and a specific conversation opener.
5. Provide a route to deeper detail where supported.

<a id="outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- A concise account and contact brief
- Relevant recent company context
- A suggested icebreaker or opening topic

<a id="actions-and-review"></a>
## Actions and human review

Researcher prepares information. The available description does not establish automatic outbound sending, contact enrichment writes or a lead-qualification decision.

<a id="action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="rules"></a>
## Rules and configuration



- Use Researcher for first-contact preparation and Meeting Assistant for active-opportunity context.
- The source describes a short, prioritized brief rather than an exhaustive dossier.
- Private or unsupported data sources must not be inferred from a broad ‘research’ label.
- The stated prep time needs reconciliation with the other meeting workflows.

<a id="research-scope"></a>
### Account and contact scope

Confirm external-source freshness and correction behavior. Do not turn inferred interests or incomplete public profiles into established personal facts.

| Research area | Source-described examples |
| --- | --- |
| Company | Business, size, sector, products and recent developments |
| Person | Professional role, background and relevant priorities |
| Conversation opening | A specific point useful for the scheduled meeting |

<a id="collaboration"></a>
## How it works with other agents

Prospector prioritizes whom to work and prepares outreach. Researcher prepares for a meeting already scheduled. Olivia can coordinate that preparation with other work.

<a id="boundaries"></a>
## Scope and limitations

Researcher is present in the accessible internal documentation and public marketplace. It was not a dedicated agent page in the current navigation snapshot; its availability remains an owner-confirmation item.

<a id="verify"></a>
## Questions to resolve before publication



- Is Researcher enabled as a standalone agent in the current offer?
- Which sources, regions and languages are supported?
- What initiates the brief and when is it delivered?
- How are stale or conflicting external facts handled?
- Can the user request corrections or refresh the research?

<a id="related"></a>
## Related documentation



- [prospector](prospector.md)
- [meeting assistant](meeting-assistant.md)
- [meeting preparation](../workflows/meeting-preparation.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents-marketplace: [Create custom AI agents in minutes](https://www.oliv.ai/agents-marketplace)
