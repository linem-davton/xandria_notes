---
schema_version: 1
title: Missing review pages from job hints
page_status: active
aliases:
  - stale review page hints
category: consistency
review_status: open
severity: medium
affected_pages:
  - [[reviews]]
  - [[resources]]
  - [[projects]]
  - [[index]]
detected_by: wiki_health_reconcile
---
# Missing review pages from job hints

## Evidence

The current [[reviews]] dashboard contains only generated empty-state sections and no links to concrete review items.

The current wiki also has no concrete review pages under `reviews/` beyond `reviews/index.md`.

However, this job's changed-page and affected-hub hints referenced missing review page ids including:

- `wiki:reviews/broken-link-resources-to-resources-books`
- `wiki:reviews/broken-link-resources-to-resources-papers`
- `wiki:reviews/broken-link-resources-to-resources-tools`
- `wiki:reviews/broken-link-resources-to-resources-websites`
- `wiki:reviews/broken-link-reviews-to-unknown`
- `wiki:reviews/broken-schema-projects-robotics`

Hydrating those page ids returned not found.

This indicates a consistency problem between background-job routing hints and the current canonical Personal Wiki state.

## Candidate Fix

Confirm whether the missing review pages were intentionally removed or whether the job hint source is stale.

If the hints are stale, refresh or repair the upstream manifest or review-index derivation so future jobs do not route through nonexistent review pages.

If any of the hinted issues are still grounded, recreate them as concrete `reviews/<issue-slug>.md` pages with evidence-bearing frontmatter and sections.

## Resolution

Unresolved.
