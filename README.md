# Couchbase (couchbase)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
