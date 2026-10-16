---
title: "Security and administration: Data protection"
url: "/features/security/data-protection/"
version: "1.1-expanded"
status: editorial
source_checked: 2026-10-16
product_owner_approved: false
---

# Security and administration: Data protection

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Evaluate data protection within security and administration, with 13 source-assessed criteria and explicit confirmation requirements.

<a id="group-scope"></a>
## Scope of this group

Review access, data protection, lifecycle controls and the evidence required by security and legal reviewers.

Certifications, residency, training use and contractual commitments require approved current evidence.

- [Security and privacy](../../administration/security-and-privacy.md)
- [Data lifecycle, export and deletion](../../administration/data-lifecycle.md)

<a id="parameter-sc11"></a>
### SC11 — Encryption at rest (AES-256)



Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Encryption at rest (AES-256) [SC11]](data-protection/sc11-encryption-at-rest-aes-256.md)

<a id="parameter-sc12"></a>
### SC12 — Encryption in transit (TLS 1.2 or higher)



Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Encryption in transit (TLS 1.2 or higher) [SC12]](data-protection/sc12-encryption-in-transit-tls-1-2-or-higher.md)

<a id="parameter-sc13"></a>
### SC13 — Customer data never used to train shared models

Will our calls train a model other companies use?

Source assessment: Unknown, ask Oliv. The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

- [Customer data never used to train shared models [SC13]](data-protection/sc13-customer-data-never-used-to-train-shared-models.md)

<a id="parameter-sc14"></a>
### SC14 — AI model providers named

Which AI providers process our data?

Source assessment: Unknown, ask Oliv. The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

- [AI model providers named [SC14]](data-protection/sc14-ai-model-providers-named.md)

<a id="parameter-sc15"></a>
### SC15 — Zero data retention with AI providers

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

<a id="sc15-buyer-question"></a>
#### Buyer question and terminology

Do AI providers keep our data after processing?

- Market names: ZDR
- Decision weight: Medium; primary reviewers: IT / security

<a id="sc15-evidence"></a>
#### Evidence and claim boundary

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

Assessment excerpt (9 October 2026): Not published

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="sc15-acceptance"></a>
#### Acceptance exercise

Request the current security packet and inspect a restricted user, retention request and access revocation in the actual deployment.

1. Translate this criterion into an observable result: Do AI providers keep our data after processing?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="sc15-limits"></a>
#### Scope and unresolved details

Certifications, residency, training use and contractual commitments require approved current evidence.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Security and privacy](../../administration/security-and-privacy.md)
- [Data lifecycle, export and deletion](../../administration/data-lifecycle.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=SC15)

<a id="parameter-sc16"></a>
### SC16 — Data residency (US and EU hosting)

Can our data stay in the EU?

Source assessment: Unknown, ask Oliv. The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

- [Data residency (US and EU hosting) [SC16]](data-protection/sc16-data-residency-us-and-eu-hosting.md)

<a id="parameter-sc17"></a>
### SC17 — Configurable data retention

Can we auto-delete recordings after a set period?

Source assessment: Unknown, ask Oliv. The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

- [Configurable data retention [SC17]](data-protection/sc17-configurable-data-retention.md)

<a id="parameter-sc18"></a>
### SC18 — Data deletion on request and at termination

Will you delete everything when we leave, and certify it?

Source assessment: Unknown, ask Oliv. The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

- [Data deletion on request and at termination [SC18]](data-protection/sc18-data-deletion-on-request-and-at-termination.md)

<a id="parameter-sc19"></a>
### SC19 — Full data export on termination

Do we get our data back if we leave?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Full data export on termination [SC19]](data-protection/sc19-full-data-export-on-termination.md)

<a id="parameter-sc20"></a>
### SC20 — Subprocessor list published

Who else touches our data?

Source assessment: Unknown, ask Oliv. The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

- [Subprocessor list published [SC20]](data-protection/sc20-subprocessor-list-published.md)

<a id="parameter-sc21"></a>
### SC21 — Data processing agreement

Will you sign our DPA?

Source assessment: Unknown, ask Oliv. The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

- [Data processing agreement [SC21]](data-protection/sc21-data-processing-agreement.md)

<a id="parameter-sc22"></a>
### SC22 — Tenant isolation

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="sc22-buyer-question"></a>
#### Buyer question and terminology

Is our data separated from other customers' data?

- Market names: data isolation
- Decision weight: Medium; primary reviewers: IT / security

<a id="sc22-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): "secure customer data workspace" (founder material)

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="sc22-acceptance"></a>
#### Acceptance exercise

Request the current security packet and inspect a restricted user, retention request and access revocation in the actual deployment.

1. Translate this criterion into an observable result: Is our data separated from other customers' data?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="sc22-limits"></a>
#### Scope and unresolved details

Certifications, residency, training use and contractual commitments require approved current evidence.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Security and privacy](../../administration/security-and-privacy.md)
- [Data lifecycle, export and deletion](../../administration/data-lifecycle.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=SC22)

<a id="parameter-sc23"></a>
### SC23 — Customer-managed encryption keys

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

<a id="sc23-buyer-question"></a>
#### Buyer question and terminology

Can we hold our own keys?

- Market names: BYOK
- Decision weight: Low; primary reviewers: IT / security

<a id="sc23-evidence"></a>
#### Evidence and claim boundary

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

Assessment excerpt (9 October 2026): Not stated

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="sc23-acceptance"></a>
#### Acceptance exercise

Request the current security packet and inspect a restricted user, retention request and access revocation in the actual deployment.

1. Translate this criterion into an observable result: Can we hold our own keys?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="sc23-limits"></a>
#### Scope and unresolved details

Certifications, residency, training use and contractual commitments require approved current evidence.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Security and privacy](../../administration/security-and-privacy.md)
- [Data lifecycle, export and deletion](../../administration/data-lifecycle.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=SC23)

<a id="explore"></a>
## Explore

- [Encryption at rest (AES-256) [SC11]](data-protection/sc11-encryption-at-rest-aes-256.md)
- [Encryption in transit (TLS 1.2 or higher) [SC12]](data-protection/sc12-encryption-in-transit-tls-1-2-or-higher.md)
- [Customer data never used to train shared models [SC13]](data-protection/sc13-customer-data-never-used-to-train-shared-models.md)
- [AI model providers named [SC14]](data-protection/sc14-ai-model-providers-named.md)
- [Data residency (US and EU hosting) [SC16]](data-protection/sc16-data-residency-us-and-eu-hosting.md)
- [Configurable data retention [SC17]](data-protection/sc17-configurable-data-retention.md)
- [Data deletion on request and at termination [SC18]](data-protection/sc18-data-deletion-on-request-and-at-termination.md)
- [Full data export on termination [SC19]](data-protection/sc19-full-data-export-on-termination.md)
- [Subprocessor list published [SC20]](data-protection/sc20-subprocessor-list-published.md)
- [Data processing agreement [SC21]](data-protection/sc21-data-processing-agreement.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:buyer-map: Buyer evaluation baseline — 9 October 2026
