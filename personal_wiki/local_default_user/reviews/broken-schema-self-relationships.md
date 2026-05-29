---
schema_version: 1
title: "Broken Schema: Relationships"
page_status: active
aliases:
  - broken schema self/relationships
category: consistency
review_status: open
severity: medium
affected_pages:
  - self/relationships
detected_by: deterministic-maintenance
---

# "Broken Schema: Relationships"

## Problem

The affected page does not match the locked Personal Wiki frontmatter, typed-block, or generated-section schema.

## Evidence

- `missing_frontmatter_key`: Frontmatter is missing required key `schema_version`.
- `missing_frontmatter_key`: Frontmatter is missing required key `title`.
- `missing_frontmatter_key`: Frontmatter is missing required key `page_status`.
- `unknown_frontmatter_key`: Frontmatter key `status` is not allowed for this page path.
- `unknown_frontmatter_key`: Frontmatter key `type` is not allowed for this page path.

## Candidate Fix

Update `self/relationships` so its frontmatter and typed blocks match the path-derived page family schema.

## Resolution

Open until the affected page validates cleanly.
