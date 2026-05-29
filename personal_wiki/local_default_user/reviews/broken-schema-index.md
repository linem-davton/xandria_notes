---
schema_version: 1
title: "Broken Schema: Index"
page_status: active
aliases:
  - broken schema index
category: consistency
review_status: open
severity: medium
affected_pages:
  - index
detected_by: deterministic-maintenance
---

# "Broken Schema: Index"

## Problem

The affected page does not match the locked Personal Wiki frontmatter, typed-block, or generated-section schema.

## Evidence

- `missing_frontmatter`: Page is missing canonical YAML frontmatter.

## Candidate Fix

Update `index` so its frontmatter and typed blocks match the path-derived page family schema.

## Resolution

Open until the affected page validates cleanly.
