# Upwork (upwork)

Upwork is a global freelancing platform that connects businesses with independent professionals through a talent marketplace. The Upwork API enables developers to integrate Upwork features into their applications, including job search, contract management, messaging, profile access, and webhook event subscriptions. The API is primarily GraphQL-based at api.upwork.com/graphql, with OAuth 2.0 authentication. Key resources include job postings, contracts, user profiles, messages, and freelancer search. The platform serves over 800,000 clients and 18 million freelancers across 180+ countries.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/upwork/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/upwork/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Freelancing
- Jobs
- Talent
- Marketplace
- Contracts
- Hiring

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Upwork GraphQL API

The primary Upwork API surface, providing GraphQL queries and mutations for job search, profile access, contract management, and messaging. Authentication uses OAuth 2.0 authorization code flow. The API supports subscriptions for real-time event notifications via webhooks.

- **Human URL:** [https://www.upwork.com/developer/documentation/graphql/api/docs/index.html](https://www.upwork.com/developer/documentation/graphql/api/docs/index.html)
- **Base URL:** `https://api.upwork.com/graphql`

#### Tags

- GraphQL
- Jobs
- Contracts
- Profiles
- Messages
- Freelancing

#### Properties

- [Documentation](https://www.upwork.com/developer/documentation/graphql/api/docs/index.html)
- [OpenAPI](openapi/upwork-graphql-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/upwork-graphql-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/upwork-graphql-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/graphql-api-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/graphql-api-contract-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/graphql-api-freelancer-profile-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/graphql-api-message-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Upwork REST API

The legacy REST API surface for Upwork, covering job search, contracts, reporting, organization management, and freelancer profiles. OAuth 2.0 authentication is required. Many endpoints have been migrated to GraphQL.

- **Human URL:** [https://developers.upwork.com/](https://developers.upwork.com/)
- **Base URL:** `https://www.upwork.com/api`

#### Tags

- REST
- Jobs
- Contracts
- Profiles
- Reports

#### Properties

- [Documentation](https://developers.upwork.com/)
- [Getting Started](https://developers.upwork.com/#get-started)
- [OpenAPI](openapi/upwork-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/upwork-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/upwork-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/rest-api-report-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/rest-api-engagement-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/upwork)
- [Website](https://www.upwork.com/)
- [Documentation](https://www.upwork.com/developer/documentation/graphql/api/docs/index.html)
- [Portal](https://www.upwork.com/developer)
- [Support](https://support.upwork.com/hc/en-us/sections/17976982721555-Upwork-API)
- [Authentication](https://support.upwork.com/hc/en-us/articles/115015933448-API-authentication-and-security)
- [GitHub Organization](https://github.com/upwork)
- [GitHub Repository](https://github.com/upwork/python-upwork-oauth2)
- [GitHub Repository](https://github.com/upwork/node-upwork-oauth2)
- [GitHub Repository](https://github.com/upwork/java-upwork-oauth2)
- [GitHub Repository](https://github.com/upwork/golang-upwork-oauth2)
- [GitHub Repository](https://github.com/upwork/ruby-upwork-oauth2)
- [GitHub Repository](https://github.com/upwork/php-upwork-oauth2)
- [GitHub Repository](https://github.com/upwork/perl-upwork-oauth2)
- [JSON-LD](json-ld/upwork-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/upwork-spectral-rules.yml)
- [Vocabulary](vocabulary/upwork-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
