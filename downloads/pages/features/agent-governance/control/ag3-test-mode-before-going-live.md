---
title: "Test mode before going live [AG3]"
url: "/features/agent-governance/control/ag3-test-mode-before-going-live/"
version: "1.1-expanded"
status: needs-confirmation
source_checked: 2026-10-16
product_owner_approved: false
---

# Test mode before going live [AG3]

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Buyer criterion AG3: Can we see what an agent would have done before it acts for real?

<a id="parameter-ag3"></a>
## Test mode before going live

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="ag3-buyer-question"></a>
### Buyer question and terminology

Can we see what an agent would have done before it acts for real?

- Market names: dry run; shadow mode; sandbox mode
- Decision weight: High; primary reviewers: RevOps; IT / security

<a id="ag3-evidence"></a>
### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): Ask-first and AI-Assisted modes let teams review every action first; a separate dry-run mode is not described

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="ag3-acceptance"></a>
### Acceptance exercise

Run a permitted action, an action requiring approval and a denied action. Check the responsible identity and the final external-system state.

1. Translate this criterion into an observable result: Can we see what an agent would have done before it acts for real?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="ag3-limits"></a>
### Scope and unresolved details

Confirm actual enforcement and audit evidence; a prototype control or policy description does not prove enforcement.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Tool modes and action boundaries](../../../agents/configuration/approvals.md)
- [Approval governance](../../../administration/approvals.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=AG3)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:buyer-map: Buyer evaluation baseline — 9 October 2026
