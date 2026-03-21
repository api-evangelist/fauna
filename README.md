# Fauna (fauna)
Fauna is a serverless document database platform that provides distributed, ACID-compliant data storage accessible through HTTP APIs, GraphQL, and native client drivers. Their developer platform offers APIs for querying and managing databases, real-time event streaming, change data capture, and client SDKs for multiple programming languages.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/fauna/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Database, Serverless, NoSQL, Document Database, Real-Time, GraphQL

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-03-20

## APIs

### Fauna Core HTTP API
The Fauna Core HTTP API provides direct access to the Fauna serverless document database through HTTPS endpoints. It allows developers to execute Fauna Query Language (FQL) queries, manage databases, and perform CRUD operations on documents. The API uses token-based authentication and supports features such as transactions, indexes, and set operations. It serves as the foundation upon which Fauna's client drivers and SDKs are built.

**Human URL:** [https://docs.fauna.com/fauna/current/reference/http/reference/core-api/](https://docs.fauna.com/fauna/current/reference/http/reference/core-api/)


#### Tags:

 - Database, Serverless, Document Database, NoSQL, Queries

#### Properties

- [Documentation](https://docs.fauna.com/fauna/current/reference/http/reference/core-api/)
- [OpenAPI](openapi/fauna-core-http-api-openapi.yml)

### Fauna Event Streaming API
The Fauna Event Streaming API enables real-time change data capture by maintaining an open connection to the Fauna database and pushing events to clients as they occur. Developers can subscribe to document or set changes and receive add, remove, and update events in real time. The API supports reconnection with a start timestamp to avoid missing events during disconnections. It is accessible via the /stream/1 HTTP endpoint with token-based authentication.

**Human URL:** [https://docs.fauna.com/fauna/current/reference/streaming/](https://docs.fauna.com/fauna/current/reference/streaming/)


#### Tags:

 - Streaming, Events, Real-Time, Change Data Capture, Database

#### Properties

- [Documentation](https://docs.fauna.com/fauna/current/reference/streaming/)
- [AsyncAPI](asyncapi/fauna-event-streaming-asyncapi.yml)

### Fauna Event Feeds API
The Fauna Event Feeds API provides a polling-based approach to change data capture, complementing the real-time Event Streaming API. Event feeds allow developers to retrieve batches of change events at their own pace rather than maintaining a persistent connection. This is useful for scheduled synchronization tasks, batch processing workflows, and scenarios where a pull-based model is preferred over push-based streaming. Event feeds track the same add, remove, and update events as streams.

**Human URL:** [https://docs.fauna.com/fauna/current/learn/cdc/](https://docs.fauna.com/fauna/current/learn/cdc/)


#### Tags:

 - Events, Change Data Capture, Polling, Database

#### Properties

- [Documentation](https://docs.fauna.com/fauna/current/learn/cdc/)

### Fauna GraphQL API
The Fauna GraphQL API allows developers to interact with their Fauna databases using standard GraphQL queries and mutations. By uploading a GraphQL schema, Fauna automatically generates the necessary collections, indexes, and resolvers. This API can be used from any programming language or HTTP client without requiring a dedicated Fauna driver. It provides an alternative to FQL for developers who prefer the GraphQL query paradigm and ecosystem tooling.

**Human URL:** [https://docs.fauna.com/fauna/current/](https://docs.fauna.com/fauna/current/)


#### Tags:

 - GraphQL, Database, Serverless, Query Language

#### Properties

- [Documentation](https://docs.fauna.com/fauna/current/)
- [OpenAPI](openapi/fauna-graphql-api-openapi.yml)

### Fauna JavaScript Driver
The Fauna JavaScript Driver is the official client SDK for interacting with Fauna from JavaScript and TypeScript applications. It provides template-based FQL query interpolation with type safety and a secure wire protocol that prevents injection vulnerabilities. The driver supports both Node.js server environments and browser-based applications, and includes built-in support for event streaming with automatic reconnection handling.

**Human URL:** [https://docs.fauna.com/fauna/current/](https://docs.fauna.com/fauna/current/)


#### Tags:

 - JavaScript, SDK, Node.js, TypeScript, Driver

#### Properties

- [Documentation](https://docs.fauna.com/fauna/current/)

### Fauna Python Driver
The Fauna Python Driver is the official client SDK for accessing Fauna from Python applications. It provides idiomatic Python interfaces for composing and executing FQL v10 queries, managing authentication tokens, and handling pagination. The driver includes support for event streaming and event feeds, allowing Python developers to build real-time and batch-oriented data processing pipelines against Fauna databases.

**Human URL:** [https://docs.fauna.com/fauna/current/](https://docs.fauna.com/fauna/current/)


#### Tags:

 - Python, SDK, Driver

#### Properties

- [Documentation](https://docs.fauna.com/fauna/current/)

### Fauna .NET Driver
The Fauna .NET Driver is the official client SDK for interacting with Fauna from C# and .NET applications. It is designed for use with FQL v10 and provides strongly-typed query construction and response handling. The driver enables .NET developers to perform document operations, run queries, and manage database resources using familiar C# patterns and conventions.

**Human URL:** [https://github.com/fauna/fauna-dotnet](https://github.com/fauna/fauna-dotnet)


#### Tags:

 - .NET, C#, SDK, Driver

#### Properties

- [Documentation](https://github.com/fauna/fauna-dotnet)

## Common Properties

- [Portal](https://docs.fauna.com/)
- [Documentation](https://docs.fauna.com/fauna/current/)
- [Website](https://fauna.com/)
- [PrivacyPolicy](https://fauna.com/privacy)
- [TermsOfService](https://fauna.com/terms)
- [Blog](https://fauna.com/blog)
- [Login](https://dashboard.fauna.com/)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
