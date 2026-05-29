---
schema_version: 1
title: "Broken Schema: Weekly Plan"
page_status: active
aliases:
  - broken schema plans/weekly
category: consistency
review_status: open
severity: medium
affected_pages:
  - plans/weekly
detected_by: deterministic-maintenance
---

# "Broken Schema: Weekly Plan"

## Problem

The affected page does not match the locked Personal Wiki frontmatter, typed-block, or generated-section schema.

## Evidence

- `missing_frontmatter_key`: Frontmatter is missing required key `schema_version`.
- `missing_frontmatter_key`: Frontmatter is missing required key `title`.
- `missing_frontmatter_key`: Frontmatter is missing required key `page_status`.
- `missing_frontmatter_key`: Frontmatter is missing required key `plan_type`.
- `missing_frontmatter_key`: Frontmatter is missing required key `state`.
- `missing_frontmatter_key`: Frontmatter is missing required key `period_start`.
- `missing_frontmatter_key`: Frontmatter is missing required key `period_end`.
- `missing_frontmatter_key`: Frontmatter is missing required key `goals`.
- `missing_frontmatter_key`: Frontmatter is missing required key `projects`.
- `unknown_frontmatter_key`: Frontmatter key `status` is not allowed for this page path.
- `unknown_frontmatter_key`: Frontmatter key `type` is not allowed for this page path.

## Candidate Fix

Update `plans/weekly` so its frontmatter and typed blocks match the path-derived page family schema.

## Resolution

Open until the affected page validates cleanly.
