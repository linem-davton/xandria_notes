---
schema_version: 1
title: "Broken Wiki Link: reviews"
page_status: active
aliases:
  - broken link reviews
category: consistency
review_status: open
severity: medium
affected_pages:
  - reviews
detected_by: deterministic-maintenance
---

# "Broken Wiki Link: reviews"

## Problem

The affected page links to a Personal Wiki page that does not currently exist.

## Evidence

- Source page: `reviews` (Reviews)
- Link target: `unknown`
- Normalized target id: `wiki:unknown`
- Anchor text: `unknown`

## Candidate Fix

Create the missing target page if it is a real gap, or update/remove the link in `reviews` if it is stale.

## Resolution

Open until the source link resolves to an existing Personal Wiki page or is removed.
