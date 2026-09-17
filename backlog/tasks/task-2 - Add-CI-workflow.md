---
id: TASK-2
title: Add CI workflow
status: To Do
assignee: []
created_date: '2026-09-17 15:40'
labels:
  - setup
dependencies:
  - TASK-1
priority: high
ordinal: 2000
---

## Description

<!-- SECTION:DESCRIPTION:BEGIN -->
GitHub Actions workflow that runs lint, typecheck, unit tests and build on pushes to main and on pull requests.
<!-- SECTION:DESCRIPTION:END -->

## Acceptance Criteria
<!-- AC:BEGIN -->
- [ ] #1 Workflow runs on push to main and pull_request
- [ ] #2 Uses npm ci with dependency caching
- [ ] #3 Fails when any step fails
<!-- AC:END -->
