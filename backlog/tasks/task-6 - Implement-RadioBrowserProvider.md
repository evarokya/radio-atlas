---
id: TASK-6
title: Implement RadioBrowserProvider
status: To Do
assignee: []
created_date: '2026-09-17 15:40'
labels:
  - stations
dependencies:
  - TASK-4
  - TASK-5
priority: high
ordinal: 6000
---

## Description

<!-- SECTION:DESCRIPTION:BEGIN -->
StationProvider implementation on top of the client and normalizer: search with query mapping, getById, countries, languages, tags, reportClick.
<!-- SECTION:DESCRIPTION:END -->

## Acceptance Criteria
<!-- AC:BEGIN -->
- [ ] #1 Search always hides broken stations
- [ ] #2 Order options map to Radio Browser parameters
- [ ] #3 Facets are normalized and sorted by station count
- [ ] #4 Unit tests for query mapping
<!-- AC:END -->
