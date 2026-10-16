---
title: "Signal Graph"
url: "/platform/signal-graph/"
version: "1.0"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Signal Graph

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Signal Graph describes Oliv’s interpretation layer: activity is turned into revenue-relevant context that can be updated as new evidence arrives.

<a id="signal-meaning"></a>
## What a signal means

A signal can represent an observed risk, qualification detail, stakeholder change, customer need or expansion indication. It is an interpretation grounded in source activity, not an independently guaranteed outcome.

The website presents specialized models for revenue questions. This V1 explains the user-facing behavior without treating model counts or accuracy claims as verified benchmarks.

<a id="signal-evidence"></a>
## Read the signal with its evidence



- Identify the question the signal is answering.
- Check the account or opportunity and the source activity.
- Distinguish a directly stated fact from an interpretation or recommendation.
- Check whether newer information changed the signal.
- Confirm how the signal reaches the relevant agent or workflow.

<a id="signal-example"></a>
## Illustrative workflow

An account conversation indicates that a previously supportive stakeholder has changed roles. The account association gives the signal a business location; the process playbook supplies the escalation rule; an agent can prepare a recommended next step.

This example explains the relationship between concepts. It is not a promise that a specific trigger, threshold or escalation is enabled in every workspace.

<a id="signal-open-rules"></a>
## Rules still requiring confirmation

Confidence display, refresh timing, human corrections, conflicting evidence and downstream recalculation need production verification. The documentation should describe those rules once established rather than substituting a generic ‘AI confidence’ explanation.

For forecast and health workflows, evaluate the signal against observed outcomes over time. A product example or forecast percentage on a marketing page is not a performance commitment.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/signal-graph: [Signal Graph | Oliv AI](https://oliv.ai/signal-graph)
