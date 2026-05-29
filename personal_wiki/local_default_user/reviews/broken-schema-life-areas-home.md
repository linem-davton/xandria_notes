---
schema_version: 1
title: "Broken Schema: Home"
page_status: active
aliases:
  - broken schema life-areas/home
category: consistency
review_status: open
severity: medium
affected_pages:
  - life-areas/home
detected_by: deterministic-maintenance
---

# "Broken Schema: Home"

## Problem

The affected page does not match the locked Personal Wiki frontmatter, typed-block, or generated-section schema.

## Evidence

- `missing_frontmatter_key`: Frontmatter is missing required key `schema_version`.
- `missing_frontmatter_key`: Frontmatter is missing required key `title`.
- `missing_frontmatter_key`: Frontmatter is missing required key `page_status`.
- `missing_frontmatter_key`: Frontmatter is missing required key `state`.
- `missing_frontmatter_key`: Frontmatter is missing required key `review_cadence`.
- `unknown_frontmatter_key`: Frontmatter key `status` is not allowed for this page path.
- `unknown_frontmatter_key`: Frontmatter key `type` is not allowed for this page path.

## Candidate Fix

Update `life-areas/home` so its frontmatter and typed blocks match the path-derived page family schema.

## Resolution

Open until the affected page validates cleanly.
