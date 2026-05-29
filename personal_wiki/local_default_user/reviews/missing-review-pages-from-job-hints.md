---
schema_version: 1
title: Missing review pages from job hints
page_status: active
aliases: []
category: gap
review_status: open
severity: medium
affected_pages:
  - index.md
  - reviews/index.md
  - reviews/missing-review-pages-from-job-hints.md
detected_by: wiki-health
---

# Missing review pages from job hints

## Problem

A concrete review page referenced by the background job hints was missing from `reviews/` after deletion. `reviews/index.md` is only the dashboard, so unresolved issues must exist as concrete pages under `reviews/`.

## Evidence

- The current job input lists `wiki:reviews/missing-review-pages-from-job-hints` as a deleted changed page at `reviews/missing-review-pages-from-job-hints.md`.
- The current `reviews/index.md` page is a generated dashboard with no authored concrete issue content and explicitly separates correctness, consistency, gaps, and resolved items.
- Personal Wiki architecture requires unresolved concrete review items to live in `reviews/<issue-slug>.md` with review frontmatter and evidence-bearing sections.

## Candidate Fix

Keep this concrete review page present until the underlying missing-page condition is resolved or the issue is shown to be ungrounded.

## Resolution

Unresolved.
