---
title: "Gold Digger agent"
url: "/agents/gold-digger/"
version: "1.0"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Gold Digger agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Gold Digger turns expansion indications in customer conversations into evidence-bearing alerts and a warm handoff for the responsible commercial team.

<a id="purpose"></a>
## Purpose and audience

Gold Digger turns expansion indications in customer conversations into evidence-bearing alerts and a warm handoff for the responsible commercial team.

Primary audience: Account managers, AEs and CSMs. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- Customer-facing CS and AM conversations
- The customer’s current footprint and account context
- Relevant products, use cases and stakeholder relationships
- AE/CSM ownership and the approved handoff process

<a id="trigger"></a>
## What starts the workflow

An expansion indication detected in a customer conversation. The source describes alerts after processing the relevant call.

<a id="workflow"></a>
## Documented workflow



1. Identify a potentially relevant expansion signal in the conversation.
2. Relate the signal to the customer’s current use and stakeholder context.
3. Attach the source moment and a recommended next step.
4. Prepare a warm-introduction draft for human review.
5. Log the confirmed opportunity through the supported CRM workflow.

<a id="outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- An expansion alert with evidence
- Context about the account and stakeholder
- A proposed warm introduction
- An expansion opportunity record where configured

<a id="actions-and-review"></a>
## Actions and human review

The source describes a CSM review/send step or an agreed delegation to the AE. Detection alone does not authorize a message or establish a qualified expansion opportunity.

<a id="action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="rules"></a>
## Rules and configuration



- Adjacent-team interest, a new use case, growth or a scaling event can be a signal.
- A routine comment is not automatically qualified buying intent.
- The evidence should include the source conversation and relevant moment.
- Do not treat illustrative ARR values or customer names in demonstrations as real proof.

<a id="expansion-signal-types"></a>
### Signal examples

The internal reference gives examples such as adjacent-team interest, a new use case, team growth, budget availability, a scaling event, a champion moving roles and dissatisfaction with another tool. They are candidate signals whose relevance depends on the account context.

<a id="expansion-evidence"></a>
### Alert and handoff context



| Detail | Why it matters |
| --- | --- |
| Account and participants | Identify the customer relationship |
| Source moment | Verify what was actually said |
| Current footprint | Explain why the need may be adjacent |
| Suggested next step | Give the owner an actionable option |
| Reviewed introduction | Preserve the warm, human-owned handoff |

<a id="collaboration"></a>
## How it works with other agents

Portfolio Manager provides account-health and relationship context, CRM Manager supports record maintenance, and the commercial owner decides how to approach the new stakeholder.

<a id="boundaries"></a>
## Scope and limitations

Gold Digger is an expansion workflow, not a blanket authorization for cold outreach. A detected signal, a reviewed opportunity and a booked expansion outcome are different states.

<a id="verify"></a>
## Questions to resolve before publication



- What distinguishes a candidate signal from a confirmed opportunity?
- Who confirms the signal and owns the CRM record?
- Which channels and destinations receive alerts?
- How are duplicate expansion records prevented?
- What happens when a CSM or AE rejects the proposed handoff?

<a id="related"></a>
## Related documentation



- [expansion](../workflows/expansion.md)
- [portfolio manager](portfolio-manager.md)
- [slack](../integrations/slack.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/gold-digger: [Gold Digger – Expansion Signal Agent | Oliv AI](https://oliv.ai/agents/gold-digger)
