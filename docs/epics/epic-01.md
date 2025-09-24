# Epic 1: Logging Ingestion & Transport (13 points)

**Status:** Not Started  
**Priority:** High  
**Epic ID:** EPIC-01

## Description

Build the backend pipeline for receiving logs from services, normalizing payloads, and reliably transporting them into storage.

## Key Tasks

- Design ingestion API (HTTP/gRPC) with authentication and rate limiting
- Implement agents/SDKs for common platforms (Go, Node.js) to ship logs
- Add batching, retry, and backpressure handling
- Support structured (JSON) and plain-text logs
- Implement transport to the chosen storage (e.g., object store, time-series DB, or log index)

## Acceptance Criteria

- Ingestion API accepts test payloads and returns appropriate status codes
- SDKs can send logs that appear in downstream storage within expected latency
- System recovers from transient failures without data loss (verified via load test)

## Dependencies

- None (foundational epic)

## Related Epics

- [Epic 2: Storage & Indexing](epic-02.md) - Depends on this epic's transport layer
- [Epic 5: Observability & Monitoring](epic-05.md) - Needs metrics from ingestion pipeline

## Stories

This epic is broken down into individual user stories. See the [stories directory](epic-01/) for detailed story specifications.

**Story Summary:**

- 4 stories totaling 13 story points
- Focus on API design, server implementation, and SDK development
- Critical path for MVP launch

[View all stories →](epic-01/README.md)
