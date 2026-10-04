---
name: couchbase-create-and-get-bucket
description: Create a new bucket and retrieve its details.
api: openapi/couchbase-buckets-api-openapi.yml
operations:
- createCapellaBucket
- getCapellaBucket
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/couchbase-buckets-api-openapi.yml ; every operationId checked against the contract
---

# couchbase-create-and-get-bucket

Create a new bucket and retrieve its details.

## Steps

1. 1. Use `createCapellaBucket` with required body fields (e.g., name, memoryQuota, bucketType) and authentication header.
2. 2. Use `getCapellaBucket` with path parameters organizationId, projectId, clusterId, bucketId and authentication header.

## Rules

- Authentication: provide either a Basic, Bearer, or Session (apiKey) auth header as defined by the auth schemes.
- Idempotency: the create operation is not idempotent; repeat calls will create duplicate buckets unless the bucket name already exists.
- Errors: on failure the API returns standard HTTP error codes; no specific rate‑limit headers are defined.
