---
schema_version: 1
title: Broken Review Schema
page_status: active
aliases:
  - broken review schema
category: consistency
review_status: open
severity: medium
affected_pages:
  - reviews/missing-review-pages-from-job-hints.md
detected_by: deterministic-maintenance
---

# Broken Review Schema

## Problem

One or more review issue pages have frontmatter that cannot feed the generated Reviews dashboard.

## Evidence

- `reviews/missing-review-pages-from-job-hints.md` has invalid review issue frontmatter.

## Candidate Fix

Update each affected review page so it has `category`, `review_status`, `severity`, `affected_pages`, and `detected_by` fields with valid values.

## Resolution

Open until all affected review pages validate cleanly.
