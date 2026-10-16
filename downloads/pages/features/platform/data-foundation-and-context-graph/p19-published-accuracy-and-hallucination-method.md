---
title: "Published accuracy and hallucination method [P19]"
url: "/features/platform/data-foundation-and-context-graph/p19-published-accuracy-and-hallucination-method/"
version: "1.1-expanded"
status: needs-confirmation
source_checked: 2026-10-16
product_owner_approved: false
---

# Published accuracy and hallucination method [P19]

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Buyer criterion P19: Is there evidence behind the accuracy claim?

<a id="parameter-p19"></a>
## Published accuracy and hallucination method

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="p19-buyer-question"></a>
### Buyer question and terminology

Is there evidence behind the accuracy claim?

- Market names: accuracy benchmark; eval results
- Decision weight: High; primary reviewers: IT / security; RevOps

<a id="p19-evidence"></a>
### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): "<1% hallucinations" and "100x cost reduction" claimed on /intent-graph; no methodology or benchmark published

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="p19-acceptance"></a>
### Acceptance exercise

Map an account, its contacts and an opportunity across connected sources. Check conflicting owners, stale fields and restricted records.

1. Translate this criterion into an observable result: Is there evidence behind the accuracy claim?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="p19-limits"></a>
### Scope and unresolved details

Compare source links, identity matching and permissions before an action is proposed.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Context Graph](../../../platform/context-graph.md)
- [Process Graph](../../../platform/process-graph.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=P19)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:buyer-map: Buyer evaluation baseline — 9 October 2026
