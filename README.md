# Upwork (upwork)
Upwork is a global freelancing platform that connects businesses with independent professionals through a talent marketplace. The Upwork API enables developers to integrate Upwork features into their applications, including job search, contract management, messaging, profile access, and webhook event subscriptions. The API is primarily GraphQL-based with OAuth 2.0 authentication, serving over 800,000 clients and 18 million freelancers across 180+ countries.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/upwork/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Freelancing, Jobs, Talent, Marketplace, Contracts, Hiring

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-03

## APIs

### Upwork GraphQL API
The primary Upwork API surface providing GraphQL queries and mutations for job search, profile access, contract management, and messaging. Authentication uses OAuth 2.0 authorization code flow.

**Human URL:** [https://www.upwork.com/developer/documentation/graphql/api/docs/index.html](https://www.upwork.com/developer/documentation/graphql/api/docs/index.html)

#### Tags:

 - GraphQL, Jobs, Contracts, Profiles, Messages, Freelancing

#### Properties

- [Documentation](https://www.upwork.com/developer/documentation/graphql/api/docs/index.html)
- [OpenAPI](openapi/upwork-graphql-api-openapi.yml)
- [JSONSchema - Job](json-schema/graphql-api-job-schema.json)
- [JSONSchema - Contract](json-schema/graphql-api-contract-schema.json)
- [JSONSchema - Freelancer Profile](json-schema/graphql-api-freelancer-profile-schema.json)
- [JSONSchema - Message](json-schema/graphql-api-message-schema.json)

### Upwork REST API
The legacy Upwork REST API covering reports, financial data, organization management, and time entries. Many resources have been migrated to GraphQL.

**Human URL:** [https://developers.upwork.com/](https://developers.upwork.com/)

#### Tags:

 - REST, Jobs, Contracts, Profiles, Reports

#### Properties

- [Documentation](https://developers.upwork.com/)
- [GettingStarted](https://developers.upwork.com/#get-started)
- [OpenAPI](openapi/upwork-rest-api-openapi.yml)

## Common Properties

- [Website](https://www.upwork.com/)
- [Documentation](https://www.upwork.com/developer/documentation/graphql/api/docs/index.html)
- [Portal](https://www.upwork.com/developer)
- [Support](https://support.upwork.com/hc/en-us/sections/17976982721555-Upwork-API)
- [Authentication](https://support.upwork.com/hc/en-us/articles/115015933448-API-authentication-and-security)
- [GitHubOrganization](https://github.com/upwork)
- [GitHubRepository - Python SDK](https://github.com/upwork/python-upwork-oauth2)
- [GitHubRepository - Node.js SDK](https://github.com/upwork/node-upwork-oauth2)
- [GitHubRepository - Java SDK](https://github.com/upwork/java-upwork-oauth2)
- [GitHubRepository - Go SDK](https://github.com/upwork/golang-upwork-oauth2)
- [GitHubRepository - Ruby SDK](https://github.com/upwork/ruby-upwork-oauth2)
- [GitHubRepository - PHP SDK](https://github.com/upwork/php-upwork-oauth2)
- [JSONLD](json-ld/upwork-context.jsonld)
- [SpectralRules](rules/upwork-spectral-rules.yml)
- [Vocabulary](vocabulary/upwork-vocabulary.yaml)
- [NaftikoCapability - Talent Marketplace](capabilities/talent-marketplace.yaml)
- [NaftikoCapability - GraphQL API Shared](capabilities/shared/graphql-api.yaml)

## Features

| Name | Description |
|------|-------------|
| Job Search | Search and filter job postings using marketplaceJobPostingsSearch GraphQL query. |
| Contract Management | Access active and completed contracts, terms, milestones, and time entries. |
| Messaging | Read and send messages within active contracts using GraphQL mutations. |
| Profile Access | Query freelancer and client profiles, skills, portfolios, and ratings. |
| Webhook Subscriptions | Subscribe to events for real-time notifications. |
| OAuth 2.0 Authentication | Secure API access using OAuth 2.0 authorization code grant flow. |
| Multi-Language SDKs | Official SDKs for Python, Node.js, Java, Go, Ruby, PHP, and Perl. |
| GraphQL Explorer | Interactive API explorer for testing queries. |

## Use Cases

| Name | Description |
|------|-------------|
| Freelancer Management | Managing a distributed freelancer workforce programmatically. |
| Job Monitoring | Tracking new job postings matching specific criteria. |
| Talent Analytics | Building talent scoring and market intelligence platforms. |
| CRM Integration | Connecting Upwork contract data to CRM systems. |
| Automated Reporting | Building dashboards from Upwork contract and billing data. |

## Integrations

| Name | Description |
|------|-------------|
| PowerBI Connector | Official Power BI connector for Upwork data. |
| OAuth 2.0 Providers | Standard OAuth 2.0 integration support. |
| Webhook Integration | Real-time event streaming via Upwork subscription webhooks. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Upwork GraphQL API](openapi/upwork-graphql-api-openapi.yml)
- [Upwork REST API](openapi/upwork-rest-api-openapi.yml)

### JSON Schema

- [Job](json-schema/graphql-api-job-schema.json)
- [Contract](json-schema/graphql-api-contract-schema.json)
- [Freelancer Profile](json-schema/graphql-api-freelancer-profile-schema.json)
- [Message](json-schema/graphql-api-message-schema.json)
- *(22 total schema files in json-schema/)*

### JSON Structure

- *(22 total structure files in json-structure/)*

### JSON-LD

- [Upwork Context](json-ld/upwork-context.jsonld)

### Examples

- [Job Example](examples/graphql-api-job-example.json)
- [Contract Example](examples/graphql-api-contract-example.json)
- [Freelancer Profile Example](examples/graphql-api-freelancer-profile-example.json)
- *(22 total example files in examples/)*

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [GraphQL API](capabilities/shared/graphql-api.yaml) — 9 operations for job search, contracts, profiles, and messaging

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Talent Marketplace](capabilities/talent-marketplace.yaml) | Upwork GraphQL API | 9 | Hiring Manager, Agency Manager, Developer |

## Vocabulary

- [Upwork Vocabulary](vocabulary/upwork-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 4 actions, 1 workflow, and 3 personas across operational and capability dimensions

## Rules

- [Upwork Spectral Rules](rules/upwork-spectral-rules.yml) — 22 rules across 10 categories enforcing Upwork API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
