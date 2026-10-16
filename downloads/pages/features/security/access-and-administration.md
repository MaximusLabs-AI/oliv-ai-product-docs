---
title: "Security and administration: Access and administration"
url: "/features/security/access-and-administration/"
version: "1.1-expanded"
status: editorial
source_checked: 2026-10-16
product_owner_approved: false
---

# Security and administration: Access and administration

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Evaluate access and administration within security and administration, with 11 source-assessed criteria and explicit confirmation requirements.

<a id="group-scope"></a>
## Scope of this group

Review access, data protection, lifecycle controls and the evidence required by security and legal reviewers.

Certifications, residency, training use and contractual commitments require approved current evidence.

- [Security and privacy](../../administration/security-and-privacy.md)
- [Data lifecycle, export and deletion](../../administration/data-lifecycle.md)

<a id="parameter-sc24"></a>
### SC24 — Single sign-on (SAML, Okta, Azure AD, Google)

Do you support our identity provider?

Source assessment: Unknown, ask Oliv. The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

- [Single sign-on (SAML, Okta, Azure AD, Google) [SC24]](access-and-administration/sc24-single-sign-on-saml-okta-azure-ad-google.md)

<a id="parameter-sc25"></a>
### SC25 — SCIM user provisioning

Are users added and removed from our directory automatically?

Source assessment: Unknown, ask Oliv. The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

- [SCIM user provisioning [SC25]](access-and-administration/sc25-scim-user-provisioning.md)

<a id="parameter-sc26"></a>
### SC26 — Multi-factor authentication

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

<a id="sc26-buyer-question"></a>
#### Buyer question and terminology



- Market names: MFA
- Decision weight: Medium; primary reviewers: IT / security

<a id="sc26-evidence"></a>
#### Evidence and claim boundary

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

Assessment excerpt (9 October 2026): Not stated

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="sc26-acceptance"></a>
#### Acceptance exercise

Request the current security packet and inspect a restricted user, retention request and access revocation in the actual deployment.

1. Translate this criterion into an observable result: 
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="sc26-limits"></a>
#### Scope and unresolved details

Certifications, residency, training use and contractual commitments require approved current evidence.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Security and privacy](../../administration/security-and-privacy.md)
- [Data lifecycle, export and deletion](../../administration/data-lifecycle.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=SC26)

<a id="parameter-sc27"></a>
### SC27 — Role-based access control

Can access follow role and department?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Role-based access control [SC27]](access-and-administration/sc27-role-based-access-control.md)

<a id="parameter-sc28"></a>
### SC28 — Recording visibility rules

Can we control who sees which calls, for example HR or legal calls?

Source assessment: Unknown, ask Oliv. The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

- [Recording visibility rules [SC28]](access-and-administration/sc28-recording-visibility-rules.md)

<a id="parameter-sc29"></a>
### SC29 — Admin console

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

<a id="sc29-buyer-question"></a>
#### Buyer question and terminology

Is there one place to manage users, settings and integrations?

- Market names: admin settings
- Decision weight: Medium; primary reviewers: RevOps; IT / security

<a id="sc29-evidence"></a>
#### Evidence and claim boundary

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

Assessment excerpt (9 October 2026): Not stated

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="sc29-acceptance"></a>
#### Acceptance exercise

Request the current security packet and inspect a restricted user, retention request and access revocation in the actual deployment.

1. Translate this criterion into an observable result: Is there one place to manage users, settings and integrations?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="sc29-limits"></a>
#### Scope and unresolved details

Certifications, residency, training use and contractual commitments require approved current evidence.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Security and privacy](../../administration/security-and-privacy.md)
- [Data lifecycle, export and deletion](../../administration/data-lifecycle.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=SC29)

<a id="parameter-sc30"></a>
### SC30 — Audit logs

Is every user and admin action logged?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Audit logs [SC30]](access-and-administration/sc30-audit-logs.md)

<a id="parameter-sc31"></a>
### SC31 — Log of who viewed which recordings

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

<a id="sc31-buyer-question"></a>
#### Buyer question and terminology

Can we see who opened a sensitive call?

- Market names: access logs
- Decision weight: Medium; primary reviewers: IT / security; Legal / procurement

<a id="sc31-evidence"></a>
#### Evidence and claim boundary

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

Assessment excerpt (9 October 2026): Not stated

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="sc31-acceptance"></a>
#### Acceptance exercise

Request the current security packet and inspect a restricted user, retention request and access revocation in the actual deployment.

1. Translate this criterion into an observable result: Can we see who opened a sensitive call?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="sc31-limits"></a>
#### Scope and unresolved details

Certifications, residency, training use and contractual commitments require approved current evidence.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Security and privacy](../../administration/security-and-privacy.md)
- [Data lifecycle, export and deletion](../../administration/data-lifecycle.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=SC31)

<a id="parameter-sc32"></a>
### SC32 — Free seats for viewers and leadership

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="sc32-buyer-question"></a>
#### Buyer question and terminology

Do people who only read need a paid seat?

- Market names: viewer seats; free seats
- Decision weight: Medium; primary reviewers: CFO / finance; RevOps

<a id="sc32-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /pricing Amplify $0

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="sc32-acceptance"></a>
#### Acceptance exercise

Request the current security packet and inspect a restricted user, retention request and access revocation in the actual deployment.

1. Translate this criterion into an observable result: Do people who only read need a paid seat?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="sc32-limits"></a>
#### Scope and unresolved details

Certifications, residency, training use and contractual commitments require approved current evidence.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Security and privacy](../../administration/security-and-privacy.md)
- [Data lifecycle, export and deletion](../../administration/data-lifecycle.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=SC32)

<a id="parameter-sc33"></a>
### SC33 — Teams, groups and hierarchy management

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

<a id="sc33-buyer-question"></a>
#### Buyer question and terminology

Can we mirror our org structure?

- Market names: user hierarchy
- Decision weight: Medium; primary reviewers: RevOps

<a id="sc33-evidence"></a>
#### Evidence and claim boundary

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

Assessment excerpt (9 October 2026): Not stated

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="sc33-acceptance"></a>
#### Acceptance exercise

Request the current security packet and inspect a restricted user, retention request and access revocation in the actual deployment.

1. Translate this criterion into an observable result: Can we mirror our org structure?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="sc33-limits"></a>
#### Scope and unresolved details

Certifications, residency, training use and contractual commitments require approved current evidence.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Security and privacy](../../administration/security-and-privacy.md)
- [Data lifecycle, export and deletion](../../administration/data-lifecycle.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=SC33)

<a id="parameter-sc34"></a>
### SC34 — Multiple business units or workspaces

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="sc34-buyer-question"></a>
#### Buyer question and terminology

Can two divisions run separately?

- Market names: multi-org
- Decision weight: Medium; primary reviewers: RevOps; IT / security

<a id="sc34-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): Revenue process mapping per segment (founder material)

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="sc34-acceptance"></a>
#### Acceptance exercise

Request the current security packet and inspect a restricted user, retention request and access revocation in the actual deployment.

1. Translate this criterion into an observable result: Can two divisions run separately?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="sc34-limits"></a>
#### Scope and unresolved details

Certifications, residency, training use and contractual commitments require approved current evidence.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Security and privacy](../../administration/security-and-privacy.md)
- [Data lifecycle, export and deletion](../../administration/data-lifecycle.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=SC34)

<a id="explore"></a>
## Explore

- [Single sign-on (SAML, Okta, Azure AD, Google) [SC24]](access-and-administration/sc24-single-sign-on-saml-okta-azure-ad-google.md)
- [SCIM user provisioning [SC25]](access-and-administration/sc25-scim-user-provisioning.md)
- [Role-based access control [SC27]](access-and-administration/sc27-role-based-access-control.md)
- [Recording visibility rules [SC28]](access-and-administration/sc28-recording-visibility-rules.md)
- [Audit logs [SC30]](access-and-administration/sc30-audit-logs.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:buyer-map: Buyer evaluation baseline — 9 October 2026
