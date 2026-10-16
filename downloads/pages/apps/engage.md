---
title: "Engage app"
url: "/apps/engage/"
version: "1.0"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Engage app

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Engage is the workspace for account prioritization and outreach, using shared account context to organize the next action.

<a id="engagement-work"></a>
## Engagement work

The live page describes a ranked account queue, contextual next actions, email and LinkedIn workflows, plays, signals and flows, with optional calling or messaging channels.

A prioritized account is an input to a workflow. It does not by itself authorize sending or establish that a contact is eligible for outreach.

<a id="agents"></a>
## Agents in the workflow

Prospector prepares account prioritization and outreach. The public page also presents a reactivation workflow for stalled accounts. The exact current agent identity, stop conditions and supported sequence behavior require confirmation.

The Prospector page distinguishes a human-reviewed first email from automatic no-response follow-ups. Treat that as a specific described policy to verify, rather than assuming every channel has the same rule.

- [Prospector agent](../agents/prospector.md)
- [Prospecting workflow](../workflows/prospecting.md)

<a id="channels"></a>
## Channel configuration

Confirm the primary mailbox, additional mailboxes, phone number and calling allowance, and each selected messaging channel. Sending identity, ownership, stop conditions and external platform limits belong in the setup contract.

The current sources do not establish a universal rate limit, bounce threshold or opt-out implementation. Those require the current connector and sending-policy documentation.

<a id="pricing-conflict"></a>
## Current pricing conflict

The live Engage page shows a $39 starting figure in some sections and $29 in another. The main pricing page describes a $29 per-user monthly add-on to an app subscription.

This V1 preserves the conflict for commercial review and does not turn either page into a contractual quote. Use the approved order form and current commercial owner’s confirmation.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/engage: [Engage – AI-Native Sales Engagement | Oliv AI](https://oliv.ai/engage)
- WEB:/pricing: [Pricing — Role-Based Plans for Revenue Teams | Oliv AI](https://www.oliv.ai/pricing)
