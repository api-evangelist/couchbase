# Couchbase (couchbase)

Couchbase is a distributed, document-oriented NoSQL cloud database platform that combines the flexibility of JSON, the power of SQL++ querying, and the performance of an in-memory key-value store. The Couchbase product line includes Couchbase Server (self-managed), Couchbase Capella (fully managed database-as-a-service across AWS, Azure, and Google Cloud), Sync Gateway and App Services for mobile and edge synchronization, and Couchbase Lite embedded databases. Couchbase exposes a comprehensive set of REST APIs covering cluster administration, SQL++ query execution, full-text and vector search, analytics, eventing, backup, cross data center replication, and Capella management.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Public

## Tags

- Analytics
- App Services
- Backup
- Capella
- Cloud
- Database
- DBaaS
- Eventing
- Full-Text Search
- Gateway
- JSON
- Mobile
- NoSQL
- Replication
- SQL++
- Sync
- Vector Search
- XDCR

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-19

## APIs

### Couchbase Server REST API

The Couchbase Server REST API provides programmatic access to manage and configure Couchbase Server clusters. It includes endpoints for cluster management, bucket operations, node administration, security settings, and server configuration. The API enables automation of deployment, monitoring, and maintenance tasks for Couchbase Server instances across distributed environments.

- **Human URL:** [https://docs.couchbase.com/server/current/rest-api/rest-intro.html](https://docs.couchbase.com/server/current/rest-api/rest-intro.html)
- **Base URL:** `https://localhost:8091`

#### Tags

- Administration
- Buckets
- Clusters
- Database
- NoSQL

#### Properties

- [Documentation](https://docs.couchbase.com/server/current/rest-api/rest-intro.html)
- [OpenAPI](openapi/couchbase-server-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/couchbase-server-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/couchbase-server-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Rules](rules/couchbase-server-rules.yml)
- [Capabilities](capabilities/couchbase-server-capabilities.yml)

### Couchbase Query Service REST API

The Couchbase Query Service REST API enables developers to execute SQL++ (formerly N1QL) queries against Couchbase Server and manage query service settings. It supports ad-hoc queries, prepared statements, and request-level parameter configuration. The API provides endpoints for query execution, monitoring active requests, and managing query service configuration across cluster nodes.

- **Human URL:** [https://docs.couchbase.com/server/current/n1ql/n1ql-rest-api/index.html](https://docs.couchbase.com/server/current/n1ql/n1ql-rest-api/index.html)
- **Base URL:** `https://localhost:8093`

#### Tags

- Database
- N1QL
- NoSQL
- Query
- SQL++

#### Properties

- [Documentation](https://docs.couchbase.com/server/current/n1ql/n1ql-rest-api/index.html)
- [OpenAPI](openapi/couchbase-query-service-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/couchbase-query-service-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/couchbase-query-service-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Rules](rules/couchbase-query-rules.yml)
- [Capabilities](capabilities/couchbase-query-capabilities.yml)

### Couchbase Analytics Service REST API

The Couchbase Analytics Service REST API provides access to the Analytics service for running complex analytical queries on operational data without impacting performance of key-value operations. It supports SQL++ queries for analytics, management of links to external data sources, and configuration of user-defined libraries. The service enables real-time analytics on JSON data alongside transactional workloads.

- **Human URL:** [https://docs.couchbase.com/server/current/analytics/rest-analytics.html](https://docs.couchbase.com/server/current/analytics/rest-analytics.html)
- **Base URL:** `https://localhost:8095`

#### Tags

- Analytics
- Database
- NoSQL
- SQL++

#### Properties

- [Documentation](https://docs.couchbase.com/server/current/analytics/rest-analytics.html)
- [OpenAPI](openapi/couchbase-analytics-service-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/couchbase-analytics-service-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/couchbase-analytics-service-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Couchbase Search Service REST API

The Couchbase Search Service REST API allows developers to create, manage, and query Full Text Indexes on Couchbase Server. It supports full-text search queries with features like fuzzy matching, faceted search, highlighting, and geospatial queries. The API provides endpoints for index definition, index management, and executing search queries across JSON documents stored in Couchbase buckets.

- **Human URL:** [https://docs.couchbase.com/server/current/rest-api/rest-fts.html](https://docs.couchbase.com/server/current/rest-api/rest-fts.html)
- **Base URL:** `https://localhost:8094`

#### Tags

- Database
- Full-Text Search
- Indexing
- NoSQL
- Vector Search

#### Properties

- [Documentation](https://docs.couchbase.com/server/current/rest-api/rest-fts.html)
- [OpenAPI](openapi/couchbase-search-service-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/couchbase-search-service-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/couchbase-search-service-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Rules](rules/couchbase-search-rules.yml)
- [Capabilities](capabilities/couchbase-search-capabilities.yml)

### Couchbase Eventing Service REST API

The Couchbase Eventing Service REST API provides methods for deploying and managing Eventing Functions that respond to data changes in real time. Eventing Functions allow developers to write server-side JavaScript logic triggered by document mutations, timers, or external events.

- **Human URL:** [https://docs.couchbase.com/server/current/eventing/eventing-api.html](https://docs.couchbase.com/server/current/eventing/eventing-api.html)
- **Base URL:** `https://localhost:8096`

#### Tags

- Database
- Eventing
- NoSQL
- Serverless Functions

#### Properties

- [Documentation](https://docs.couchbase.com/server/current/eventing/eventing-api.html)
- [OpenAPI](openapi/couchbase-eventing-service-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/couchbase-eventing-service-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/couchbase-eventing-service-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Couchbase Backup Service REST API

The Couchbase Backup Service REST API supports management of the Backup Service for Couchbase Server, providing endpoints for cluster configuration, repository management, backup plans, task scheduling, and data operations.

- **Human URL:** [https://docs.couchbase.com/server/current/rest-api/backup-rest-api.html](https://docs.couchbase.com/server/current/rest-api/backup-rest-api.html)
- **Base URL:** `https://localhost:8097`

#### Tags

- Backup
- Database
- Disaster Recovery
- NoSQL

#### Properties

- [Documentation](https://docs.couchbase.com/server/current/rest-api/backup-rest-api.html)
- [OpenAPI](openapi/couchbase-backup-service-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/couchbase-backup-service-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/couchbase-backup-service-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Couchbase XDCR REST API

The Couchbase XDCR (Cross Data Center Replication) REST API enables configuration and management of data replication between Couchbase clusters across different data centers. It provides endpoints for creating replication references, configuring replication streams, monitoring replication statistics, and managing replication settings.

- **Human URL:** [https://docs.couchbase.com/server/current/rest-api/rest-xdcr-intro.html](https://docs.couchbase.com/server/current/rest-api/rest-xdcr-intro.html)
- **Base URL:** `https://localhost:8091`

#### Tags

- Cross Data Center
- Database
- NoSQL
- Replication

#### Properties

- [Documentation](https://docs.couchbase.com/server/current/rest-api/rest-xdcr-intro.html)
- [OpenAPI](openapi/couchbase-xdcr-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/couchbase-xdcr-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/couchbase-xdcr-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Couchbase Capella Management API

The Couchbase Capella Management API is a REST API for provisioning, deploying, and configuring Couchbase Capella database-as-a-service deployments across AWS, Azure, and Google Cloud. It enables programmatic management of clusters, buckets, users, and organizations using API key authentication.

- **Human URL:** [https://docs.couchbase.com/cloud/management-api-reference/index.html](https://docs.couchbase.com/cloud/management-api-reference/index.html)
- **Base URL:** `https://cloudapi.cloud.couchbase.com`

#### Tags

- Capella
- Cloud
- Database
- DBaaS
- Management
- NoSQL

#### Properties

- [Documentation](https://docs.couchbase.com/cloud/management-api-reference/index.html)
- [OpenAPI](openapi/couchbase-capella-management-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/couchbase-capella-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/couchbase-capella-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Rules](rules/couchbase-capella-management-rules.yml)
- [Capabilities](capabilities/couchbase-capella-management-capabilities.yml)

### Couchbase Capella App Services Public API

The Couchbase Capella App Services Public API provides REST endpoints for mobile and edge application data synchronization with Couchbase Capella. It enables developers to manage document access, handle user authentication, and synchronize data between mobile devices and the cloud database.

- **Human URL:** [https://docs.couchbase.com/cloud/app-services/references/rest_api_public.html](https://docs.couchbase.com/cloud/app-services/references/rest_api_public.html)

#### Tags

- App Services
- Capella
- Cloud
- Mobile
- NoSQL
- Sync

#### Properties

- [Documentation](https://docs.couchbase.com/cloud/app-services/references/rest_api_public.html)
- [OpenAPI](openapi/couchbase-capella-app-services-public-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/couchbase-capella-app-services-public-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/couchbase-capella-app-services-public-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Couchbase Capella App Services Admin API

The Couchbase Capella App Services Admin API provides administrative REST endpoints for managing Sync Gateway configurations within Couchbase Capella. It enables administrators to manage databases, users, roles, sync functions, and replication settings for mobile data synchronization.

- **Human URL:** [https://docs.couchbase.com/cloud/app-services/references/rest_api_admin.html](https://docs.couchbase.com/cloud/app-services/references/rest_api_admin.html)

#### Tags

- Administration
- App Services
- Capella
- Cloud
- Mobile
- NoSQL

#### Properties

- [Documentation](https://docs.couchbase.com/cloud/app-services/references/rest_api_admin.html)
- [OpenAPI](openapi/couchbase-capella-app-services-admin-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/couchbase-capella-app-services-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/couchbase-capella-app-services-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Couchbase Sync Gateway Public REST API

The Couchbase Sync Gateway Public REST API provides endpoints for mobile and edge clients to synchronize data with Couchbase Server through the Sync Gateway middleware. It supports document CRUD operations, changes feeds for real-time data synchronization, and user authentication.

- **Human URL:** [https://docs.couchbase.com/sync-gateway/current/rest-api.html](https://docs.couchbase.com/sync-gateway/current/rest-api.html)
- **Base URL:** `https://localhost:4984`

#### Tags

- Database
- Gateway
- Mobile
- NoSQL
- Sync

#### Properties

- [Documentation](https://docs.couchbase.com/sync-gateway/current/rest-api.html)
- [OpenAPI](openapi/couchbase-sync-gateway-public-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/couchbase-sync-gateway-public-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/couchbase-sync-gateway-public-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Rules](rules/couchbase-sync-gateway-rules.yml)
- [Capabilities](capabilities/couchbase-sync-gateway-capabilities.yml)

### Couchbase Sync Gateway Admin REST API

The Couchbase Sync Gateway Admin REST API provides administrative endpoints for configuring and managing Sync Gateway instances. It supports database management, user and role administration, sync function configuration, and replication setup.

- **Human URL:** [https://docs.couchbase.com/sync-gateway/current/rest-api-admin.html](https://docs.couchbase.com/sync-gateway/current/rest-api-admin.html)
- **Base URL:** `https://localhost:4985`

#### Tags

- Administration
- Database
- Mobile
- NoSQL
- Sync

#### Properties

- [Documentation](https://docs.couchbase.com/sync-gateway/current/rest-api-admin.html)
- [OpenAPI](openapi/couchbase-sync-gateway-admin-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/couchbase-sync-gateway-admin-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/couchbase-sync-gateway-admin-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/couchbase)
- [Website](https://www.couchbase.com/)
- [Documentation](https://docs.couchbase.com/)
- [Capella](https://www.couchbase.com/products/capella/)
- [Server](https://www.couchbase.com/products/server/)
- [Mobile](https://www.couchbase.com/products/mobile/)
- [Login](https://cloud.couchbase.com/sign-in)
- [Pricing](https://www.couchbase.com/pricing/)
- [Blog](https://www.couchbase.com/blog/)
- [Forums](https://www.couchbase.com/forums/)
- [Support](https://support.couchbase.com/)
- [Status Page](https://status.couchbase.com/)
- [GitHub Organization](https://github.com/couchbase)
- [Changelog](https://docs.couchbase.com/server/current/release-notes/relnotes.html)
- [Privacy Policy](https://www.couchbase.com/privacy-policy/)
- [Terms of Service](https://www.couchbase.com/terms-of-use/)
- [JSON-LD](json-ld/couchbase-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/couchbase-document-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/couchbase-bucket-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/couchbase-cluster-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Vocabulary](vocabulary/couchbase-vocabulary.yml)
- [Features](undefined)
- [L L Ms Txt](https://docs.couchbase.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
