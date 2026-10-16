---
title: "Limits and availability"
url: "/reference/limits-and-availability/"
version: "1.1-expanded"
status: needs-confirmation
source_checked: 2026-10-16
product_owner_approved: false
---

# Limits and availability

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

This V1 does not invent quotas, retention periods or feature rollout states where the source set cannot establish them.

<a id="availability-states"></a>
## Availability states to confirm



| State | Meaning required in the final docs |
| --- | --- |
| GA | Available to the specified users and conditions |
| Beta | Available with explicit limitations and support conditions |
| Limited rollout | Restricted to named cohorts, regions or workspaces |
| Planned | Not available; no inferred launch date |
| Deprecated/retired | Replacement and migration behavior stated |
| Unconfirmed | The reviewed sources cannot establish the current state |

<a id="limits-register"></a>
## Limit categories



| Category | Current evidence state |
| --- | --- |
| Agents, tools and triggers per workspace | Not established |
| Runs, concurrency and rate limits | Not established |
| Credit consumption per action | Not established |
| Knowledge storage and upload quotas | Prototype labels do not establish production limits |
| Recording length and storage | Requires current plan/technical evidence |
| Run-history and content retention | Not established |
| Connector API limits and retries | Requires connector-specific reference |
| Language and region availability | Marketing claims require supported-scope confirmation |

<a id="limit-source"></a>
## What counts as a verified limit

A final reference should record the value, unit, applicable plan, scope, enforcement behavior, overage or error, and effective date. A prototype’s ‘Max 5 files’ label does not establish a universal upload limit.

A displayed count of example runs or a fixed last-run timestamp is sample data, not a quota or retention rule.

<a id="limit-ownership"></a>
## Publication requirement

The responsible product or engineering owner should confirm each limit before publication. Keep unknowns explicit in V1 and route them to the correct page rather than filling them with general software conventions.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/pricing: [Pricing — Role-Based Plans for Revenue Teams | Oliv AI](https://www.oliv.ai/pricing)
