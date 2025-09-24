# Epic 2: Storage & Indexing (13 points)

**Status:** Not Started  
**Priority:** High  
**Epic ID:** EPIC-02

## Description

Provide efficient, cost-conscious storage and an indexing layer to support search and retention policies.

## Key Tasks

- Choose storage backend (Elasticsearch/OpenSearch, ClickHouse, or object+index approach)
- Implement indexing pipeline for searchable fields (timestamp, service, level, trace id)
- Implement configurable retention (hot/warm/cold tiers)
- Provide bulk ingestion and compaction strategies

## Acceptance Criteria

- Logs are queryable by indexed fields and time range
- Retention rules drop or archive logs per policy
- Storage metrics and cost estimates are documented and validated via small-scale test

## Dependencies

- [Epic 1: Logging Ingestion & Transport](epic-01.md) - Requires transport layer

## Related Epics

- [Epic 3: Query API & Filtering](epic-03.md) - Depends on storage schema
- [Epic 6: Security, Privacy & Compliance](epic-06.md) - Encryption and retention policies

## Stories

This epic is broken down into individual user stories. See the [stories directory](epic-02/) for detailed story specifications.

**Story Summary:**

- 4 stories totaling 13 story points
- Focus on storage backend selection, indexing, and retention
- Critical path for search functionality

[View all stories →](epic-02/README.md)
