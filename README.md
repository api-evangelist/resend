# Resend

Resend is a developer-first email API platform that simplifies sending and managing transactional and marketing emails. It provides a clean REST API with bearer token authentication, supporting email sending, domain management, API key management, audience and contact management, and broadcast campaigns. Resend offers SDKs for Node.js, Python, Go, Ruby, PHP, Java, .NET, Rust, Elixir, and more, along with a React Email library and official MCP server.

**URL:** [https://raw.githubusercontent.com/api-evangelist/resend/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/resend/refs/heads/main/apis.yml)

## Tags

Email, Developer Tools, Transactional Email, Marketing Email

## APIs

### Resend API

The Resend REST API provides endpoints for sending emails, managing domains, API keys, audiences, contacts, and broadcast campaigns. Rate limit: 5 requests per second per team.

- **Base URL:** https://api.resend.com
- **Authentication:** Bearer token
- **Human URL:** [https://resend.com/](https://resend.com/)

#### Properties

- [Documentation](https://resend.com/docs/api-reference/introduction)
- [OpenAPI](openapi/resend-openapi.yml)
- [Webhooks](https://resend.com/docs/dashboard/webhooks/introduction)
- [JSONSchema - Email](json-schema/resend-email-schema.json)
- [JSONSchema - Audience](json-schema/resend-audience-schema.json)
- [JSONSchema - Domain](json-schema/resend-domain-schema.json)
- [JSONStructure - Email](json-structure/resend-email-structure.json)
- [JSONLDContext](json-ld/resend-context.jsonld)
- [SpectralRules](rules/resend-rules.yml)
- [Capabilities](capabilities/email-delivery.yaml)
- [Vocabulary](vocabulary/resend-vocabulary.yml)

## Capabilities

- [email-delivery.yaml](capabilities/email-delivery.yaml) — Email delivery, domain management, and audience campaign management (REST + MCP, 15 tools)
- [shared/resend.yaml](capabilities/shared/resend.yaml) — Shared per-API definition

## Common Properties

- [GitHubOrganization](https://github.com/resend)
- [ChangeLog](https://resend.com/changelog)
- [Blog](https://resend.com/blog)
- [Migrations](https://resend.com/migrate)
- [Customers](https://resend.com/customers)
- [About](https://resend.com/about)
- [Security](https://resend.com/security)
- [Integrations](https://resend.com/docs/integrations)
- [Examples](https://resend.com/docs/examples)
- [SDKs](https://resend.com/docs/sdks)
- [Pricing](https://resend.com/pricing)
- [Login](https://resend.com/login)
- [SignUp](https://resend.com/signup)
- [Node.js SDK](https://github.com/resend/resend-node)
- [Python SDK](https://github.com/resend/resend-python)
- [Go SDK](https://github.com/resend/resend-go)
- [.NET SDK](https://github.com/resend/resend-dotnet)
- [CLI](https://github.com/resend/resend-cli)
- [MCP Server](https://github.com/resend/resend-mcp)
- [React Email](https://github.com/resend/react-email)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
