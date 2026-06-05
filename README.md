# fauna (fauna)

Fauna is a distributed document-relational database delivered as a cloud API that combines the relational query power of SQL with the flexibility of documents and global serverless distribution.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fauna/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fauna/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-19

## APIs

### Fauna Core HTTP API

The Fauna Core HTTP API provides direct access to the Fauna serverless document database through HTTPS endpoints. It allows developers to execute Fauna Query Language (FQL) queries, manage databases, and perform CRUD operations on documents. The API uses token-based authentication and supports features such as transactions, indexes, and set operations. It serves as the foundation upon which Fauna's client drivers and SDKs are built.

- **Human URL:** [https://docs.fauna.com/fauna/current/reference/http/reference/core-api/](https://docs.fauna.com/fauna/current/reference/http/reference/core-api/)
- **Base URL:** `https://db.fauna.com`

#### Tags

- Database
- Document Database
- NoSQL
- Queries
- Serverless

#### Properties

- [Documentation](https://docs.fauna.com/fauna/current/reference/http/reference/core-api/)
- [OpenAPI](openapi/fauna-core-http-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fauna-core-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fauna-core-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fauna Event Streaming API

The Fauna Event Streaming API enables real-time change data capture by maintaining an open connection to the Fauna database and pushing events to clients as they occur. Developers can subscribe to document or set changes and receive add, remove, and update events in real time. The API supports reconnection with a start timestamp to avoid missing events during disconnections. It is accessible via the /stream/1 HTTP endpoint with token-based authentication.

- **Human URL:** [https://docs.fauna.com/fauna/current/reference/streaming/](https://docs.fauna.com/fauna/current/reference/streaming/)
- **Base URL:** `https://db.fauna.com`

#### Tags

- Change Data Capture
- Database
- Events
- Real-Time
- Streaming

#### Properties

- [Documentation](https://docs.fauna.com/fauna/current/reference/streaming/)
- [AsyncAPI](asyncapi/fauna-event-streaming-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/fauna-core-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fauna-core-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/fauna-graphql-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fauna-graphql-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fauna Event Feeds API

The Fauna Event Feeds API provides a polling-based approach to change data capture, complementing the real-time Event Streaming API. Event feeds allow developers to retrieve batches of change events at their own pace rather than maintaining a persistent connection. This is useful for scheduled synchronization tasks, batch processing workflows, and scenarios where a pull-based model is preferred over push-based streaming. Event feeds track the same add, remove, and update events as streams.

- **Human URL:** [https://docs.fauna.com/fauna/current/learn/cdc/](https://docs.fauna.com/fauna/current/learn/cdc/)
- **Base URL:** `https://db.fauna.com`

#### Tags

- Change Data Capture
- Database
- Events
- Polling

#### Properties

- [Documentation](https://docs.fauna.com/fauna/current/learn/cdc/)
- [Postman Collection](collections/fauna-core-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fauna-core-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/fauna-graphql-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fauna-graphql-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fauna GraphQL API

The Fauna GraphQL API allows developers to interact with their Fauna databases using standard GraphQL queries and mutations. By uploading a GraphQL schema, Fauna automatically generates the necessary collections, indexes, and resolvers. This API can be used from any programming language or HTTP client without requiring a dedicated Fauna driver. It provides an alternative to FQL for developers who prefer the GraphQL query paradigm and ecosystem tooling.

- **Human URL:** [https://docs.fauna.com/fauna/current/](https://docs.fauna.com/fauna/current/)
- **Base URL:** `https://graphql.fauna.com`

#### Tags

- Database
- GraphQL
- Query Language
- Serverless

#### Properties

- [Documentation](https://docs.fauna.com/fauna/current/)
- [OpenAPI](openapi/fauna-graphql-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fauna-graphql-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fauna-graphql-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fauna JavaScript Driver

The Fauna JavaScript Driver is the official client SDK for interacting with Fauna from JavaScript and TypeScript applications. It provides template-based FQL query interpolation with type safety and a secure wire protocol that prevents injection vulnerabilities. The driver supports both Node.js server environments and browser-based applications, and includes built-in support for event streaming with automatic reconnection handling.

- **Human URL:** [https://docs.fauna.com/fauna/current/](https://docs.fauna.com/fauna/current/)
- **Base URL:** `https://api.example.com`

#### Tags

- Driver
- JavaScript
- Node.js
- SDK
- TypeScript

#### Properties

- [Documentation](https://docs.fauna.com/fauna/current/)
- [Postman Collection](collections/fauna-core-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fauna-core-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/fauna-graphql-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fauna-graphql-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fauna Python Driver

The Fauna Python Driver is the official client SDK for accessing Fauna from Python applications. It provides idiomatic Python interfaces for composing and executing FQL v10 queries, managing authentication tokens, and handling pagination. The driver includes support for event streaming and event feeds, allowing Python developers to build real-time and batch-oriented data processing pipelines against Fauna databases.

- **Human URL:** [https://docs.fauna.com/fauna/current/](https://docs.fauna.com/fauna/current/)
- **Base URL:** `https://api.example.com`

#### Tags

- Driver
- Python
- SDK

#### Properties

- [Documentation](https://docs.fauna.com/fauna/current/)
- [Postman Collection](collections/fauna-core-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fauna-core-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/fauna-graphql-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fauna-graphql-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fauna .NET Driver

The Fauna .NET Driver is the official client SDK for interacting with Fauna from C# and .NET applications. It is designed for use with FQL v10 and provides strongly-typed query construction and response handling. The driver enables .NET developers to perform document operations, run queries, and manage database resources using familiar C# patterns and conventions.

- **Human URL:** [https://github.com/fauna/fauna-dotnet](https://github.com/fauna/fauna-dotnet)
- **Base URL:** `https://api.example.com`

#### Tags

- .NET
- C#
- Driver
- SDK

#### Properties

- [Documentation](https://github.com/fauna/fauna-dotnet)
- [Postman Collection](collections/fauna-core-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fauna-core-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/fauna-graphql-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fauna-graphql-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/faunainc)
- [JSON-LD](json-ld/fauna-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/fauna-document-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/fauna-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/fauna-query-schema.json) — [JSON Schema](https://json-schema.org/specification)
