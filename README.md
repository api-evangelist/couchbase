# Couchbase (couchbase)
Couchbase is a distributed NoSQL cloud database platform that provides high-performance data management for enterprise applications. Their developer platform offers a comprehensive suite of APIs covering server management, query services, analytics, full-text search, mobile synchronization, and their fully managed Capella database-as-a-service offering.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - NoSQL, Database, Cloud, DBaaS, Mobile, Sync, Analytics, Full-Text Search

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-03-20

## APIs

### Couchbase Server REST API
The Couchbase Server REST API provides programmatic access to manage and configure Couchbase Server clusters. It includes endpoints for cluster management, bucket operations, node administration, security settings, and server configuration. The API enables automation of deployment, monitoring, and maintenance tasks for Couchbase Server instances across distributed environments.

**Human URL:** [https://docs.couchbase.com/server/current/rest-api/rest-intro.html](https://docs.couchbase.com/server/current/rest-api/rest-intro.html)


#### Tags:

 - NoSQL, Database, Clusters, Buckets, Administration

#### Properties

- [Documentation](https://docs.couchbase.com/server/current/rest-api/rest-intro.html)

### Couchbase Query Service REST API
The Couchbase Query Service REST API enables developers to execute SQL++ (formerly N1QL) queries against Couchbase Server and manage query service settings. It supports ad-hoc queries, prepared statements, and request-level parameter configuration. The API provides endpoints for query execution, monitoring active requests, and managing query service configuration across cluster nodes.

**Human URL:** [https://docs.couchbase.com/server/current/n1ql/n1ql-rest-api/index.html](https://docs.couchbase.com/server/current/n1ql/n1ql-rest-api/index.html)


#### Tags:

 - NoSQL, Database, Query, SQL++, N1QL

#### Properties

- [Documentation](https://docs.couchbase.com/server/current/n1ql/n1ql-rest-api/index.html)

### Couchbase Analytics Service REST API
The Couchbase Analytics Service REST API provides access to the Analytics service for running complex analytical queries on operational data without impacting performance of key-value operations. It supports SQL++ queries for analytics, management of links to external data sources, and configuration of user-defined libraries. The service enables real-time analytics on JSON data alongside transactional workloads.

**Human URL:** [https://docs.couchbase.com/server/current/analytics/rest-analytics.html](https://docs.couchbase.com/server/current/analytics/rest-analytics.html)


#### Tags:

 - NoSQL, Database, Analytics, SQL++

#### Properties

- [Documentation](https://docs.couchbase.com/server/current/analytics/rest-analytics.html)

### Couchbase Search Service REST API
The Couchbase Search Service REST API allows developers to create, manage, and query Full Text Indexes on Couchbase Server. It supports full-text search queries with features like fuzzy matching, faceted search, highlighting, and geospatial queries. The API provides endpoints for index definition, index management, and executing search queries across JSON documents stored in Couchbase buckets.

**Human URL:** [https://docs.couchbase.com/server/current/rest-api/rest-fts.html](https://docs.couchbase.com/server/current/rest-api/rest-fts.html)


#### Tags:

 - NoSQL, Database, Full-Text Search, Indexing

#### Properties

- [Documentation](https://docs.couchbase.com/server/current/rest-api/rest-fts.html)

### Couchbase Eventing Service REST API
The Couchbase Eventing Service REST API provides methods for deploying and managing Eventing Functions that respond to data changes in real time. Eventing Functions allow developers to write server-side JavaScript logic triggered by document mutations, timers, or external events. The API supports creating, deploying, pausing, and undeploying functions, as well as monitoring their execution status and statistics.

**Human URL:** [https://docs.couchbase.com/server/current/eventing/eventing-api.html](https://docs.couchbase.com/server/current/eventing/eventing-api.html)


#### Tags:

 - NoSQL, Database, Eventing, Serverless Functions

#### Properties

- [Documentation](https://docs.couchbase.com/server/current/eventing/eventing-api.html)

### Couchbase Backup Service REST API
The Couchbase Backup Service REST API supports management of the Backup Service for Couchbase Server, providing endpoints for cluster configuration, repository management, backup plans, task scheduling, and data operations. It enables automated backup and restore workflows for Couchbase data, allowing administrators to define backup policies, monitor backup tasks, and manage backup repositories programmatically.

**Human URL:** [https://docs.couchbase.com/server/current/rest-api/backup-rest-api.html](https://docs.couchbase.com/server/current/rest-api/backup-rest-api.html)


#### Tags:

 - NoSQL, Database, Backup, Disaster Recovery

#### Properties

- [Documentation](https://docs.couchbase.com/server/current/rest-api/backup-rest-api.html)

### Couchbase XDCR REST API
The Couchbase XDCR (Cross Data Center Replication) REST API enables configuration and management of data replication between Couchbase clusters across different data centers. It provides endpoints for creating replication references, configuring replication streams, monitoring replication statistics, and managing replication settings. XDCR supports both unidirectional and bidirectional replication for high availability and disaster recovery scenarios.

**Human URL:** [https://docs.couchbase.com/server/current/rest-api/rest-xdcr-intro.html](https://docs.couchbase.com/server/current/rest-api/rest-xdcr-intro.html)


#### Tags:

 - NoSQL, Database, Replication, Cross Data Center

#### Properties

- [Documentation](https://docs.couchbase.com/server/current/rest-api/rest-xdcr-intro.html)

### Couchbase Capella Management API
The Couchbase Capella Management API is a REST API for provisioning, deploying, and configuring Couchbase Capella database-as-a-service deployments across AWS, Azure, and Google Cloud. It enables programmatic management of clusters, buckets, users, and organizations using API key authentication. The API supports automation of cloud database operations including scaling, configuration changes, and access management, with requests limited to 100 per minute per API key.

**Human URL:** [https://docs.couchbase.com/cloud/management-api-reference/index.html](https://docs.couchbase.com/cloud/management-api-reference/index.html)


#### Tags:

 - NoSQL, Database, Cloud, DBaaS, Management

#### Properties

- [Documentation](https://docs.couchbase.com/cloud/management-api-reference/index.html)

### Couchbase Capella App Services Public API
The Couchbase Capella App Services Public API provides REST endpoints for mobile and edge application data synchronization with Couchbase Capella. It enables developers to manage document access, handle user authentication, and synchronize data between mobile devices and the cloud database. The API supports operations for reading and writing documents through Sync Gateway, managing changes feeds, and handling replication for offline-first mobile applications.

**Human URL:** [https://docs.couchbase.com/cloud/app-services/references/rest_api_public.html](https://docs.couchbase.com/cloud/app-services/references/rest_api_public.html)


#### Tags:

 - NoSQL, Database, Cloud, Mobile, Sync

#### Properties

- [Documentation](https://docs.couchbase.com/cloud/app-services/references/rest_api_public.html)

### Couchbase Capella App Services Admin API
The Couchbase Capella App Services Admin API provides administrative REST endpoints for managing Sync Gateway configurations within Couchbase Capella. It enables administrators to manage databases, users, roles, sync functions, and replication settings for mobile data synchronization. The API supports full administrative control over App Services deployments, including user provisioning, access control, and monitoring of sync operations.

**Human URL:** [https://docs.couchbase.com/cloud/app-services/references/rest_api_admin.html](https://docs.couchbase.com/cloud/app-services/references/rest_api_admin.html)


#### Tags:

 - NoSQL, Database, Cloud, Mobile, Administration

#### Properties

- [Documentation](https://docs.couchbase.com/cloud/app-services/references/rest_api_admin.html)

### Couchbase Sync Gateway Public REST API
The Couchbase Sync Gateway Public REST API provides endpoints for mobile and edge clients to synchronize data with Couchbase Server through the Sync Gateway middleware. It supports document CRUD operations, changes feeds for real-time data synchronization, and user authentication. The API enables offline-first mobile applications to replicate data bidirectionally between Couchbase Lite embedded databases and Couchbase Server clusters.

**Human URL:** [https://docs.couchbase.com/sync-gateway/current/rest-api.html](https://docs.couchbase.com/sync-gateway/current/rest-api.html)


#### Tags:

 - NoSQL, Database, Mobile, Sync, Gateway

#### Properties

- [Documentation](https://docs.couchbase.com/sync-gateway/current/rest-api.html)

### Couchbase Sync Gateway Admin REST API
The Couchbase Sync Gateway Admin REST API provides administrative endpoints for configuring and managing Sync Gateway instances. It supports database management, user and role administration, sync function configuration, and replication setup. The API is intended for server-side administration and is typically bound to localhost for security, enabling full control over Sync Gateway behavior, access control policies, and data synchronization rules.

**Human URL:** [https://docs.couchbase.com/sync-gateway/current/rest-api-admin.html](https://docs.couchbase.com/sync-gateway/current/rest-api-admin.html)


#### Tags:

 - NoSQL, Database, Mobile, Sync, Administration

#### Properties

- [Documentation](https://docs.couchbase.com/sync-gateway/current/rest-api-admin.html)

## Common Properties

- [Portal](https://docs.couchbase.com/)
- [Documentation](https://docs.couchbase.com/home/server.html)
- [Website](https://www.couchbase.com/)
- [PrivacyPolicy](https://www.couchbase.com/privacy-policy/)
- [TermsOfService](https://www.couchbase.com/terms-of-use/)
- [Support](https://support.couchbase.com/)
- [Blog](https://www.couchbase.com/blog/)
- [Login](https://cloud.couchbase.com/sign-in)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
