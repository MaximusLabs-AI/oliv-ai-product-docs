---
title: "Forecasting: Prediction and accuracy"
url: "/features/forecasting/prediction-and-accuracy/"
version: "1.1-expanded"
status: editorial
source_checked: 2026-10-16
product_owner_approved: false
---

# Forecasting: Prediction and accuracy

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Evaluate prediction and accuracy within forecasting, with 5 source-assessed criteria and explicit confirmation requirements.

<a id="group-scope"></a>
## Scope of this group

Configure revenue periods and inspect forecast inputs, judgment, historical snapshots and accountability.

Evaluate forecast accuracy against a defined baseline and cohort. No universal accuracy figure is established by this review.

- [Forecaster agent](../../agents/forecaster.md)
- [Prepare and review a forecast](../../workflows/forecast-review.md)

<a id="parameter-fc23"></a>
### FC23 — Independent AI forecast alongside the human call

Is there an AI number I can compare with the team's call?

Source assessment: Partial. The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

- [Independent AI forecast alongside the human call [FC23]](prediction-and-accuracy/fc23-independent-ai-forecast-alongside-the-human-call.md)

<a id="parameter-fc24"></a>
### FC24 — Forecast accuracy tracked over time

Can I see how accurate past forecasts were?

Source assessment: Partial. The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

- [Forecast accuracy tracked over time [FC24]](prediction-and-accuracy/fc24-forecast-accuracy-tracked-over-time.md)

<a id="parameter-fc25"></a>
### FC25 — Accuracy improves from closed deals

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="fc25-buyer-question"></a>
#### Buyer question and terminology

Does it learn from what actually closed?

- Market names: self-learning forecast
- Decision weight: Medium; primary reviewers: RevOps

<a id="fc25-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /agents/forecaster "Every closed deal makes the next forecast better"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="fc25-acceptance"></a>
#### Acceptance exercise

Reconcile one forecast period with the CRM and a prior snapshot. Include a pushed close date, manager override and missing activity.

1. Translate this criterion into an observable result: Does it learn from what actually closed?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="fc25-limits"></a>
#### Scope and unresolved details

Evaluate forecast accuracy against a defined baseline and cohort. No universal accuracy figure is established by this review.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Forecaster agent](../../agents/forecaster.md)
- [Prepare and review a forecast](../../workflows/forecast-review.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=FC25)

<a id="parameter-fc26"></a>
### FC26 — Scenario modelling

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="fc26-buyer-question"></a>
#### Buyer question and terminology

What happens to the number if this deal slips a quarter?

- Market names: what-if; scenario planning; Scenario Simulator
- Decision weight: Medium; primary reviewers: VP Sales; CFO / finance

<a id="fc26-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): Outreach blurbs "models what happens if a deal slips"; Scenario Simulator in /agents-marketplace

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="fc26-acceptance"></a>
#### Acceptance exercise

Reconcile one forecast period with the CRM and a prior snapshot. Include a pushed close date, manager override and missing activity.

1. Translate this criterion into an observable result: What happens to the number if this deal slips a quarter?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="fc26-limits"></a>
#### Scope and unresolved details

Evaluate forecast accuracy against a defined baseline and cohort. No universal accuracy figure is established by this review.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Forecaster agent](../../agents/forecaster.md)
- [Prepare and review a forecast](../../workflows/forecast-review.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=FC26)

<a id="parameter-fc27"></a>
### FC27 — Headcount and budget scenarios

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="fc27-buyer-question"></a>
#### Buyer question and terminology

What if we add three reps or change win rate?

- Market names: capacity planning
- Decision weight: Low; primary reviewers: CRO; CFO / finance

<a id="fc27-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): Scenario Simulator (/agents-marketplace), availability unknown

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="fc27-acceptance"></a>
#### Acceptance exercise

Reconcile one forecast period with the CRM and a prior snapshot. Include a pushed close date, manager override and missing activity.

1. Translate this criterion into an observable result: What if we add three reps or change win rate?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="fc27-limits"></a>
#### Scope and unresolved details

Evaluate forecast accuracy against a defined baseline and cohort. No universal accuracy figure is established by this review.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Forecaster agent](../../agents/forecaster.md)
- [Prepare and review a forecast](../../workflows/forecast-review.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=FC27)

<a id="explore"></a>
## Explore

- [Independent AI forecast alongside the human call [FC23]](prediction-and-accuracy/fc23-independent-ai-forecast-alongside-the-human-call.md)
- [Forecast accuracy tracked over time [FC24]](prediction-and-accuracy/fc24-forecast-accuracy-tracked-over-time.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:buyer-map: Buyer evaluation baseline — 9 October 2026
