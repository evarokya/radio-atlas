---
id: TASK-4
title: Implement station normalizer
status: To Do
assignee: []
created_date: '2026-09-17 15:40'
labels:
  - stations
dependencies:
  - TASK-3
priority: high
ordinal: 4000
---

## Description

<!-- SECTION:DESCRIPTION:BEGIN -->
Convert raw Radio Browser station JSON into the internal Station model. Trim, split, lowercase and dedupe tags and languages, prefer url_resolved, reject stations without a valid http(s) stream URL.
<!-- SECTION:DESCRIPTION:END -->

## Acceptance Criteria
<!-- AC:BEGIN -->
- [ ] #1 Handles missing and malformed fields without throwing
- [ ] #2 Detects HLS streams
- [ ] #3 Unit tests cover edge cases
<!-- AC:END -->
