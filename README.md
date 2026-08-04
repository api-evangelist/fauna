# fauna (fauna)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
