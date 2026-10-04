---
name: couchbase-create-and-list-scopes
description: Create a new scope in a bucket and then list all scopes in that bucket.
api: openapi/couchbase-scopes-and-collections-api-openapi.yml
operations:
- createScope
- listScopes
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/couchbase-scopes-and-collections-api-openapi.yml ; every operationId checked against the contract
---

# couchbase-create-and-list-scopes

Create a new scope in a bucket and then list all scopes in that bucket.

## Steps

1. `createScope` – requires the bucket name path parameter and the request body defining the new scope name.
2. `listScopes` – requires the bucket name path parameter to retrieve the current list of scopes.

## Rules

- Authentication: use one of the supported schemes – basicAuth (http), bearerAuth (http), or sessionAuth (apiKey).
