---
title: "Documentation contract and publishing"
url: "/review/documentation-contract/"
version: "1.0"
status: editorial
source_checked: 2026-10-16
product_owner_approved: false
---

# Documentation contract and publishing

*V1 review draft · 2026-10-16 · Implementation and editorial specification*

<a id="overview"></a>
## Overview

The documentation is authored for clear user tasks and source accountability. Machine-readable delivery should reflect the same approved content that a person reads.

<a id="url-contract"></a>
## URLs and section IDs

Use lowercase, hyphenated path segments and one canonical route per distinct task or reference. Keep route depth shallow; this V1 has no route deeper than three path segments.

Every H2, H3 and H4 has an explicit stable ID and a copyable section link. The URL path locates the document; the fragment locates its section. Changing a heading’s wording should not change its ID.

<a id="heading-contract"></a>
### Heading hierarchy

Use one H1 for the page title, H2 for major sections, H3 for subordinate topics and H4 only for a meaningful detail.

<a id="fragment-contract"></a>
#### Fragment behavior

Use ordinary fragment links such as /agents/crm-manager/#actions-and-review. The fragment is resolved in the browser and is not a separate server resource or sitemap URL.

<a id="content-contract"></a>
## Content model

The canonical source is lib/content.json. Each page has a URL, title, description, summary, sections, sources, evidence status and availability note. Sections carry stable IDs and can contain prose, steps, lists, tables and subordinate sections.

Markdown and downloads are generated review exports. Editing an export alone does not update the site. Page and section IDs should remain stable when a source changes.

<a id="crawlability"></a>
## Readable delivery

The static build includes the full authored content in HTML without requiring client-side rendering. Navigation, breadcrumbs, section links and related references are ordinary links. Search adds convenience without being the only way to discover a page.

The build generates Markdown downloads, a route/metadata inventory, a sitemap and optional llms.txt and llms-full.txt aids. Those aids do not guarantee crawling, understanding or citation by an AI system.

<a id="indexing-policy"></a>
## Review and production indexing

This live preview is public and marked noindex. The full authoring repository and original evidence worksheets remain private. Robots directives do not provide access control.

Before an official product documentation launch, approve the claims, choose the production origin, confirm the access policy and regenerate indexing files.

<a id="abuse-controls"></a>
## Operational controls for a future public site

Use normal caching, conditional requests, observability and measured rate limits. Keep the main documentation readable without a challenge on every request; escalate controls based on observed abuse.

Do not hide different factual content from humans and bots, generate thin keyword variants, or publish unverified capabilities to influence AI answers. Content accuracy and access policy take priority over crawler volume.

<a id="maintenance"></a>
## Maintenance

Assign owners for product behavior, integration contracts, commercial terms and security claims. Re-review pages when those underlying facts change. Use the documentation history for editorial changes and the announcement archive for verified product releases.

A publication check should validate claims, links, anchors, metadata, generated exports, mobile navigation and search. Technical correctness does not substitute for product-owner approval.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.


