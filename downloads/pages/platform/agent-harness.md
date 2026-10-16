---
title: "Agent execution and coordination"
url: "/platform/agent-harness/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Agent execution and coordination

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

The agent layer combines a defined job, relevant context, available tools and an action boundary. Coordination determines which specialist handles the work.

<a id="agent-components"></a>
## The parts of an agent workflow



| Part | Purpose |
| --- | --- |
| Job and instructions | Define the intended work and success condition |
| Context | Provide the relevant account, opportunity and process knowledge |
| Tools | Read or change information through supported connections |
| Trigger or request | Start work from a verified event, schedule or user interaction |
| Review boundary | Determine what needs human confirmation |
| Run result | Show the output, destination and any unresolved issue |

<a id="coordination"></a>
## Super agents and specialists

Olivia is presented as the frontline execution and orchestration agent. Oliver maintains the process and configuration context. Specialist agents focus on particular jobs such as forecast preparation, CRM updates or coaching.

The current public pages provide this conceptual distinction. The prototype’s dropdowns and demo run data do not establish production permission enforcement or runtime precedence.

<a id="execution-boundaries"></a>
## Confirm boundaries per action

Separate read-only analysis, draft creation, CRM writes, outbound sending and process configuration. One general ‘autonomous’ label is insufficient to explain those different consequences.

For each action, document whose identity is used, who can enable it, whether approval expires, where the request appears, what is logged and how a failed or rejected action is handled. These are acceptance questions until verified.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/olivia: [Olivia – Chief of AI Staff for GTM Teams | Oliv AI](https://oliv.ai/agents/olivia)
- WEB:/agents/oliver: [Oliver – Revenue Process Agent | Oliv AI](https://oliv.ai/agents/oliver)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
