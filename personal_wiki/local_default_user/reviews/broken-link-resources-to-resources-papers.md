---
schema_version: 1
title: "Broken Wiki Link: resources"
page_status: active
aliases:
  - broken link resources
category: consistency
review_status: open
severity: medium
affected_pages:
  - resources
detected_by: deterministic-maintenance
---

# "Broken Wiki Link: resources"

## Problem

The affected page links to a Personal Wiki page that does not currently exist.

## Evidence

- Source page: `resources` (Resources)
- Link target: `resources/papers`
- Normalized target id: `wiki:resources/papers`
- Anchor text: `Papers`

## Candidate Fix

Create the missing target page if it is a real gap, or update/remove the link in `resources` if it is stale.

## Resolution

Open until the source link resolves to an existing Personal Wiki page or is removed.
