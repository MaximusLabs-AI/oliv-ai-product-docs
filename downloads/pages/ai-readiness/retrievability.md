---
title: "Retrievability: can the engine find it? — AI checks"
url: "/ai-readiness/retrievability/"
version: "1.1-expanded"
status: editorial
source_checked: 2026-10-16
product_owner_approved: false
---

# Retrievability: can the engine find it? — AI checks

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Inspect the original requirements, dated evidence and current review disposition for retrievability: can the engine find it?.

<a id="parameter-ae1"></a>
### AE1 — A page for every capability buyers ask about

Is there a URL whose main subject is "conversation intelligence", "revenue intelligence", "sales forecasting", "customer success platform", "sales engagement" and "AI agents for revenue teams"?

<a id="ae1-baseline"></a>
#### Audit baseline

Partial — App and persona pages exist; market-language category pages are in build (preview 2026-09-25)

<a id="ae1-review"></a>
#### Review disposition

Historical production audit; not remeasured by this review build.

<a id="ae1-action"></a>
#### Production action to review

Source recommendation (not executed): Ship one market-language page per category, one owner each, per the no-overlap rule

- Accountable owner: Oliv product marketing; MaximusLabs
- Acceptance requires a dated check of the actual production URL, its rendered output and the relevant external evidence.

<a id="parameter-ae2"></a>
### AE2 — Category pages indexable

Can the engine index the category page at all?

<a id="ae2-baseline"></a>
#### Audit baseline

Missing or failing — /conversation-intelligence and /engage served noindex, nofollow and were missing from the sitemap (2026-10-02)

<a id="ae2-review"></a>
#### Review disposition

Intentionally noindex in this review. The source suggestion to remove noindex is not applied. Production indexing needs a separate approved launch decision.

<a id="ae2-action"></a>
#### Production action to review

Keep review noindex enabled. Decide production indexing only when claims, access policy and official origin have been approved.

- Accountable owner: Oliv web and publishing
- Acceptance requires a dated check of the actual production URL, its rendered output and the relevant external evidence.

<a id="parameter-ae3"></a>
### AE3 — Every important page in the sitemap

Is the page listed where crawlers look?

<a id="ae3-baseline"></a>
#### Audit baseline

Partial — Category pages missing from the sitemap (2026-10-02)

<a id="ae3-review"></a>
#### Review disposition

Historical production audit; not remeasured by this review build.

<a id="ae3-action"></a>
#### Production action to review

Source recommendation (not executed): Regenerate the sitemap from the page master tracker

- Accountable owner: Oliv web and publishing
- Acceptance requires a dated check of the actual production URL, its rendered output and the relevant external evidence.

<a id="parameter-ae4"></a>
### AE4 — One canonical URL per capability

Is there exactly one page per topic?

<a id="ae4-baseline"></a>
#### Audit baseline

Missing or failing — Near-duplicates live: /process-graph and /process-graph-v2; /agents/prospector and /agents/prospector-old; /crm-manager and /agents/crm-manager (2026-08-04)

<a id="ae4-review"></a>
#### Review disposition

Historical production audit; not remeasured by this review build.

<a id="ae4-action"></a>
#### Production action to review

Source recommendation (not executed): 301 the older page of each pair

- Accountable owner: Oliv web and publishing
- Acceptance requires a dated check of the actual production URL, its rendered output and the relevant external evidence.

<a id="parameter-ae5"></a>
### AE5 — Retired URLs redirected

Do old URLs point to the current page?

<a id="ae5-baseline"></a>
#### Audit baseline

Missing or failing — /blog/gong-alternatives still returned 200 alongside /gong-alternative (2026-10-02)

<a id="ae5-review"></a>
#### Review disposition

Historical production audit; not remeasured by this review build.

<a id="ae5-action"></a>
#### Production action to review

Source recommendation (not executed): 301 to /gong-alternative

- Accountable owner: Oliv web and publishing
- Acceptance requires a dated check of the actual production URL, its rendered output and the relevant external evidence.

<a id="parameter-ae6"></a>
### AE6 — A page for each agent

Can the engine find what each named agent does?

<a id="ae6-baseline"></a>
#### Audit baseline

Partial — About nine agent pages for 37 marketplace agents (2026-08-04)

<a id="ae6-review"></a>
#### Review disposition

Historical production audit; not remeasured by this review build.

<a id="ae6-action"></a>
#### Production action to review

Source recommendation (not executed): One page per generally available agent, with inputs, outputs and permissions

- Accountable owner: Oliv product marketing
- Acceptance requires a dated check of the actual production URL, its rendered output and the relevant external evidence.

<a id="parameter-ae7"></a>
### AE7 — A page for each integration

Can the engine confirm "works with Salesforce", "works with Gong"?

<a id="ae7-baseline"></a>
#### Audit baseline

Missing or failing — One hub page, logos only; called "very boring very old" by Oliv (2026-09-15)

<a id="ae7-review"></a>
#### Review disposition

Historical production audit; not remeasured by this review build.

<a id="ae7-action"></a>
#### Production action to review

Source recommendation (not executed): One page per major integration with what syncs, which direction and setup

- Accountable owner: Oliv product marketing; Oliv web and publishing
- Acceptance requires a dated check of the actual production URL, its rendered output and the relevant external evidence.

<a id="parameter-ae8"></a>
### AE8 — Public product documentation and help centre

Is there neutral, factual documentation the engine trusts more than marketing pages?

<a id="ae8-baseline"></a>
#### Audit baseline

Missing or failing — None evidenced (2026-10-09)

<a id="ae8-review"></a>
#### Review disposition

Historical production audit; not remeasured by this review build.

<a id="ae8-action"></a>
#### Production action to review

Source recommendation (not executed): Build the documentation site from this inventory; the CTO kit collects the detail

- Accountable owner: Oliv product and engineering; Oliv product marketing
- Acceptance requires a dated check of the actual production URL, its rendered output and the relevant external evidence.

<a id="parameter-ae9"></a>
### AE9 — A comparison page for each main competitor

Is there a page for "Oliv vs Gong", "Oliv vs Clari", "Oliv vs Gainsight"?

<a id="ae9-baseline"></a>
#### Audit baseline

Partial — /gong-alternative live; Clari and Gainsight pages in progress (2026-09-29)

<a id="ae9-review"></a>
#### Review disposition

Historical production audit; not remeasured by this review build.

<a id="ae9-action"></a>
#### Production action to review

Source recommendation (not executed): Finish Clari and Gainsight, then Fathom, tl;dv, ChurnZero, Salesloft, Outreach

- Accountable owner: Oliv product marketing
- Acceptance requires a dated check of the actual production URL, its rendered output and the relevant external evidence.

<a id="parameter-ae10"></a>
### AE10 — Alternatives pages

Is there a page for "Gong alternatives", "Clari alternatives"?

<a id="ae10-baseline"></a>
#### Audit baseline

Partial — Gong alternatives covered; others planned

<a id="ae10-review"></a>
#### Review disposition

Historical production audit; not remeasured by this review build.

<a id="ae10-action"></a>
#### Production action to review

Source recommendation (not executed): Follow the competitor order agreed on 2026-09-29

- Accountable owner: MaximusLabs
- Acceptance requires a dated check of the actual production URL, its rendered output and the relevant external evidence.

<a id="parameter-ae11"></a>
### AE11 — Owned "best X software" guides

Does Oliv publish its own category guides?

<a id="ae11-baseline"></a>
#### Audit baseline

Partial — /blog/best-revenue-intelligence-software-platforms live

<a id="ae11-review"></a>
#### Review disposition

Historical production audit; not remeasured by this review build.

<a id="ae11-action"></a>
#### Production action to review

Source recommendation (not executed): One per category

- Accountable owner: MaximusLabs
- Acceptance requires a dated check of the actual production URL, its rendered output and the relevant external evidence.

<a id="parameter-ae12"></a>
### AE12 — AI crawlers allowed in robots.txt

Can GPTBot, ClaudeBot, PerplexityBot and Google-Extended crawl?

<a id="ae12-baseline"></a>
#### Audit baseline

Not checked yet — Not checked

<a id="ae12-review"></a>
#### Review disposition

Historical production audit; not remeasured by this review build.

<a id="ae12-action"></a>
#### Production action to review

Source recommendation (not executed): Check and allow

- Accountable owner: Oliv web and publishing
- Acceptance requires a dated check of the actual production URL, its rendered output and the relevant external evidence.

<a id="parameter-ae13"></a>
### AE13 — llms.txt present

Is there a machine-readable index of key pages?

<a id="ae13-baseline"></a>
#### Audit baseline

Not checked yet — Not checked

<a id="ae13-review"></a>
#### Review disposition

Historical production audit; not remeasured by this review build.

<a id="ae13-action"></a>
#### Production action to review

Source recommendation (not executed): Publish llms.txt listing category, agent, integration and pricing pages

- Accountable owner: Oliv web and publishing
- Acceptance requires a dated check of the actual production URL, its rendered output and the relevant external evidence.

<a id="parameter-ae14"></a>
### AE14 — Content rendered without JavaScript

Can a crawler read the text without running scripts?

<a id="ae14-baseline"></a>
#### Audit baseline

Not checked yet — Mixed stack: Next.js homepage and nav, Webflow elsewhere (2026-09-18)

<a id="ae14-review"></a>
#### Review disposition

Historical production audit; not remeasured by this review build.

<a id="ae14-action"></a>
#### Production action to review

Source recommendation (not executed): Test key pages with JavaScript off

- Accountable owner: Oliv web and publishing
- Acceptance requires a dated check of the actual production URL, its rendered output and the relevant external evidence.

<a id="parameter-ae15"></a>
### AE15 — Proof readable without a form

Can the engine read the case study results?

<a id="ae15-baseline"></a>
#### Audit baseline

Missing or failing — All four case studies are email-gated (2026-08-04)

<a id="ae15-review"></a>
#### Review disposition

Historical production audit; not remeasured by this review build.

<a id="ae15-action"></a>
#### Production action to review

Source recommendation (not executed): Ungate the results; gate only the PDF if needed

- Accountable owner: Oliv marketing; Oliv web and publishing
- Acceptance requires a dated check of the actual production URL, its rendered output and the relevant external evidence.

<a id="parameter-ae16"></a>
### AE16 — Past-dated pages removed or marked

Does stale content signal neglect?

<a id="ae16-baseline"></a>
#### Audit baseline

Missing or failing — Five webinar pages with past dates still live (2026-08-04)

<a id="ae16-review"></a>
#### Review disposition

Historical production audit; not remeasured by this review build.

<a id="ae16-action"></a>
#### Production action to review

Source recommendation (not executed): Archive or mark as on-demand

- Accountable owner: Oliv web and publishing
- Acceptance requires a dated check of the actual production URL, its rendered output and the relevant external evidence.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:ai-audit: AI evaluation baseline — 9 October 2026
