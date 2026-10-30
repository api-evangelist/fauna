# Fauna

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

> **No longer operating.** This company or product has shut down, been discontinued, or been deprecated. This profile is kept as a historical record and is not maintained or rated.

Fauna, Inc. built a distributed document-relational database delivered as a cloud API, combining the relational query power of SQL with the flexibility of documents, global serverless distribution and strictly serializable ACID transactions over plain HTTPS. Fauna announced End-of-Service in March 2025 and shut the hosted service down on 2025-05-30; as of 2026-09-17 every Fauna service host returns NXDOMAIN and the apex domain forwards to an unrelated company. This profile is maintained as an archival record of the API surface as it stood at shutdown.

**Areas:** Database · Document Database · Serverless · Distributed Systems · Change Data Capture · GraphQL · Cloud · Developer Tools · Defunct

## Fauna on APIs.io (historical record)

Everything profiled for Fauna is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/fauna/](https://apis.io/providers/fauna/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [Fauna Event Streaming API](https://apis.io/apis/fauna/event-streaming-api/) — The Fauna Event Streaming API enables real-time change data capture by maintaining an open connection to the Fauna database and pushing events to clients as…
- [Fauna Event Feeds API](https://apis.io/apis/fauna/event-feeds-api/) — The Fauna Event Feeds API provides a polling-based approach to change data capture, complementing the real-time Event Streaming API. Event feeds allow…
- [Fauna JavaScript Driver](https://apis.io/apis/fauna/javascript-driver/) — The Fauna JavaScript Driver is the official client SDK for interacting with Fauna from JavaScript and TypeScript applications. It provides template-based…
- [Fauna Python Driver](https://apis.io/apis/fauna/python-driver/) — The Fauna Python Driver is the official client SDK for accessing Fauna from Python applications. It provides idiomatic Python interfaces for composing and…
- [Fauna .NET Driver](https://apis.io/apis/fauna/dotnet-driver/) — The Fauna .NET Driver is the official client SDK for interacting with Fauna from C# and .NET applications. It is designed for use with FQL v10 and provides…
- [fauna EventFeeds API](https://apis.io/apis/fauna/fauna-eventfeeds-api/) — Poll-based change data capture using event feeds. Retrieve batches of change events at your own pace for scheduled synchronization and batch processing…
- [fauna Query API](https://apis.io/apis/fauna/fauna-query-api/) — Execute Fauna Query Language (FQL) queries against a Fauna database.
- [fauna Schema API](https://apis.io/apis/fauna/fauna-schema-api/) — Fetch, update, validate, and manage a database's schema as FSL files. Supports staged schema changes with status checking, committing, and abandoning.
- [Fauna Graph QL API](https://apis.io/apis/fauna/fauna-graph-ql-api/) — Execute GraphQL queries and mutations against a Fauna database.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Fauna Event Streaming](https://apis.io/asyncapis/fauna/fauna-event-streaming-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/stream/1](https://apis.io/channels/fauna/stream-1/)

#### GraphQL (1)

GraphQL schemas.

- [fauna GraphQL API](https://apis.io/graphqls/fauna/fauna-graphql/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Fauna Agentic Access](https://apis.io/agentic-access/fauna/fauna-agentic-access/)

#### JSON Schema (21)

The data models the API reads and writes.

- [Fauna Document](https://apis.io/schemas/fauna/fauna-document/)
- [ErrorResponse](https://apis.io/schemas/fauna/fauna-errorresponse/)
- [Fauna Event](https://apis.io/schemas/fauna/fauna-event/)
- [EventFeedRequest](https://apis.io/schemas/fauna/fauna-eventfeedrequest/)
- [EventFeedResponse](https://apis.io/schemas/fauna/fauna-eventfeedresponse/)
- [EventStats](https://apis.io/schemas/fauna/fauna-eventstats/)
- [GraphQLError](https://apis.io/schemas/fauna/fauna-graphqlerror/)
- [GraphQLErrorResponse](https://apis.io/schemas/fauna/fauna-graphqlerrorresponse/)
- [GraphQLRequest](https://apis.io/schemas/fauna/fauna-graphqlrequest/)
- [GraphQLResponse](https://apis.io/schemas/fauna/fauna-graphqlresponse/)
- [Fauna Query](https://apis.io/schemas/fauna/fauna-query/)
- [QueryRequest](https://apis.io/schemas/fauna/fauna-queryrequest/)
- [QueryResponse](https://apis.io/schemas/fauna/fauna-queryresponse/)
- [QueryStats](https://apis.io/schemas/fauna/fauna-querystats/)
- [SchemaAbandonResponse](https://apis.io/schemas/fauna/fauna-schemaabandonresponse/)
- [SchemaCommitResponse](https://apis.io/schemas/fauna/fauna-schemacommitresponse/)
- [SchemaFile](https://apis.io/schemas/fauna/fauna-schemafile/)
- [SchemaFilesResponse](https://apis.io/schemas/fauna/fauna-schemafilesresponse/)
- [SchemaStatusResponse](https://apis.io/schemas/fauna/fauna-schemastatusresponse/)
- [SchemaUpdateResponse](https://apis.io/schemas/fauna/fauna-schemaupdateresponse/)
- [SchemaValidationResponse](https://apis.io/schemas/fauna/fauna-schemavalidationresponse/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Fauna Structure](https://apis.io/json-structure/fauna/fauna-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Fauna Context](https://apis.io/jsonld/fauna/fauna-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Fauna Domain Vocabulary](https://apis.io/vocabularies/fauna/fauna-vocabulary/)

#### Collections (5)

Postman and Open Collection request collections.

- [Fauna Core HTTP API](https://apis.io/collections/fauna/open-fauna-core-http-api/)
- [Fauna Core HTTP EventFeeds API](https://apis.io/collections/fauna/open-fauna-eventfeeds-api/)
- [Fauna Core HTTP EventFeeds GraphQL API](https://apis.io/collections/fauna/open-fauna-graphql-api/)
- [Fauna Core HTTP EventFeeds Query API](https://apis.io/collections/fauna/open-fauna-query-api/)
- [Fauna Core HTTP EventFeeds Schema API](https://apis.io/collections/fauna/open-fauna-schema-api/)

#### Overlays (4)

OpenAPI overlays, including conversational phrasing for each operation.

- [Fauna Eventfeeds Api Overlay](https://apis.io/overlays/fauna/fauna-eventfeeds-api-overlay/)
- [Fauna Graph Ql Api Overlay](https://apis.io/overlays/fauna/fauna-graph-ql-api-overlay/)
- [Fauna Query Api Overlay](https://apis.io/overlays/fauna/fauna-query-api-overlay/)
- [Fauna Schema Api Overlay](https://apis.io/overlays/fauna/fauna-schema-api-overlay/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Fauna — asyncapi rules](https://apis.io/rules/fauna/fauna-asyncapi-spectral-rules/)
- [Fauna — jsonschema rules](https://apis.io/rules/fauna/fauna-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Fauna Authentication](https://apis.io/security/fauna/fauna-authentication/)
- [Fauna Domain Security](https://apis.io/security/fauna/fauna-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Fauna Plans Pricing](https://apis.io/plans/fauna/fauna-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Fauna Rate Limits](https://apis.io/rate-limits/fauna/fauna-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Fauna Finops](https://apis.io/finops/fauna/fauna-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [GitHub](https://github.com/fauna)

## API Evangelist rating

**Not rated** — this company is recorded as no longer operating, so no score is published. If it is in fact operating, say so on this repository and it will be re-profiled.

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Fauna: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/fauna/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
