# Epic 3: Query API & Filtering (8 points)

**Status:** Not Started  
**Priority:** High  
**Epic ID:** EPIC-03

## Description

Build a backend API to query logs with filters, paging, and basic aggregations.

## Key Tasks

- Design query language or adopt an existing one (Lucene-like or SQL-ish)
- Implement filters: time-range, service, level, text search, trace id, span id
- Add paging, limit, and cursor-based pagination for large result sets
- Implement basic aggregations (counts by level, errors over time)

## Acceptance Criteria

- API supports complex queries combining multiple filters
- Query performance under small-to-medium datasets meets SLOs (e.g., median < 500ms)

## Dependencies

- [Epic 2: Storage & Indexing](epic-02.md) - Requires indexed storage

## Related Epics

- [Epic 4: Website & UX](epic-04.md) - UI will consume this API
- [Epic 8: Alerts & Integrations](epic-08.md) - Alert evaluation uses query API

