---
schema_version: 1
title: "Broken Schema: Robotics"
page_status: active
aliases:
  - broken schema projects/robotics
category: consistency
review_status: open
severity: medium
affected_pages:
  - projects/robotics
detected_by: deterministic-maintenance
---

# "Broken Schema: Robotics"

## Problem

The affected page does not match the locked Personal Wiki frontmatter, typed-block, or generated-section schema.

## Evidence

- `missing_frontmatter_key`: Frontmatter is missing required key `schema_version`.
- `missing_frontmatter_key`: Frontmatter is missing required key `title`.
- `missing_frontmatter_key`: Frontmatter is missing required key `page_status`.
- `missing_frontmatter_key`: Frontmatter is missing required key `state`.
- `missing_frontmatter_key`: Frontmatter is missing required key `health`.
- `missing_frontmatter_key`: Frontmatter is missing required key `goals`.
- `missing_frontmatter_key`: Frontmatter is missing required key `life_areas`.
- `missing_frontmatter_key`: Frontmatter is missing required key `priority`.
- `missing_frontmatter_key`: Frontmatter is missing required key `started_on`.
- `missing_frontmatter_key`: Frontmatter is missing required key `target_date`.
- `missing_frontmatter_key`: Frontmatter is missing required key `people`.
- `unknown_frontmatter_key`: Frontmatter key `status` is not allowed for this page path.
- `unknown_frontmatter_key`: Frontmatter key `type` is not allowed for this page path.

## Candidate Fix

Update `projects/robotics` so its frontmatter and typed blocks match the path-derived page family schema.

## Resolution

Open until the affected page validates cleanly.
