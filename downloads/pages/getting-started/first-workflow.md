---
title: "Run a first workflow"
url: "/getting-started/first-workflow/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Run a first workflow

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Begin with a low-volume, identifiable case so the team can explain exactly what happened and why.

<a id="choose-record"></a>
## Choose a representative case

Select a meeting linked to an active opportunity, a CRM field update with clear evidence, or an account review with known risk signals. Avoid starting with a broad historical cleanup or a large outbound audience.

Identify the expected source data and the person responsible for checking the result. Remove ambiguity about who owns an opportunity or which account a conversation concerns before judging the agent output.

<a id="review-sequence"></a>
## Recommended first-run sequence



1. Confirm that the selected agent or workflow is enabled for the workspace.
2. Check the source connections and the relevant account or opportunity.
3. Review the applicable process rules and configured action permissions.
4. Trigger the workflow using the verified production mechanism.
5. Inspect the output, source evidence, destination and any approval request.
6. Accept or reject the result through the verified interface and check the resulting state.

<a id="prototype-boundary"></a>
## Do not use the prototype as an execution guide

The supplied October 15 extraction describes a frontend prototype. It records controls whose actions or persistence were not implemented in that source. Labels such as Run Agent, Clone Agent or Send therefore cannot establish the production procedure.

The current V1 describes the intended workflow and verification requirements. Exact production clicks, error messages and expected save states must be confirmed in a running environment before this page becomes an end-user tutorial.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:agents: Supplied original Oliv agent references — authored review basis
