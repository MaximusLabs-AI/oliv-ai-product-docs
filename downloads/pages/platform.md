---
title: "Platform concepts"
url: "/platform/"
version: "1.0"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Platform concepts

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Oliv’s platform story is a sequence from customer activity to connected context and useful action, with process knowledge guiding how agents operate.

<a id="foundation-model"></a>
## A conceptual model

Capture brings in the activity. Context Graph associates it with business entities. Signal Graph interprets revenue questions. Process Graph supplies the organization’s rules and exceptions. Agents prepare or execute work using that context; apps organize the related team workflows.

This is a user-level explanation of the current product presentation. It is not a backend deployment diagram, a database schema or a guarantee about internal event ordering.

Activity and records → Context Graph → Signals + process knowledge → Agents → Apps and team outputs

*Conceptual model, not a deployment diagram.*

<a id="separate-concepts"></a>
## Keep the concepts distinct

An activity is an input; a signal is an interpretation of that input; a process rule defines how the organization should act; an agent performs a job; an app is a workspace for related work. Keeping those terms separate makes it easier to explain an incorrect result and identify its owner.

<a id="explore"></a>
## Explore

- [Context Capture](platform/context-capture.md)
- [Context Graph](platform/context-graph.md)
- [Signal Graph](platform/signal-graph.md)
- [Process Graph](platform/process-graph.md)
- [Agent execution and coordination](platform/agent-harness.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/oliv-tech: [Oliv Tech | Oliv AI](https://oliv.ai/oliv-tech)
