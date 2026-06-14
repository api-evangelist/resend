# Resend GraphQL Schema

## Description

Resend is a developer-first email API platform for sending and managing transactional and marketing emails. Resend's public API is REST-based; this GraphQL schema is a conceptual representation derived from the official REST API reference at https://resend.com/docs/api-reference. It models all core Resend resources — emails, batches, domains, contacts, audiences, broadcasts, webhooks, API keys, tags, schedules, and email events — as GraphQL types to support schema-driven tooling, code generation, and documentation.

## Endpoint

Resend does not publish a public GraphQL endpoint. The base REST API is:

```
https://api.resend.com
```

Authentication uses Bearer tokens passed in the `Authorization` header.

## Documentation

- API Reference: https://resend.com/docs/api-reference
- Introduction: https://resend.com/docs/api-reference/introduction
- Emails: https://resend.com/docs/api-reference/emails
- Batches: https://resend.com/docs/api-reference/emails/send-batch-emails
- Domains: https://resend.com/docs/api-reference/domains
- API Keys: https://resend.com/docs/api-reference/api-keys
- Audiences: https://resend.com/docs/api-reference/audiences
- Contacts: https://resend.com/docs/api-reference/contacts
- Broadcasts: https://resend.com/docs/api-reference/broadcasts
- Webhooks: https://resend.com/docs/dashboard/webhooks/introduction

## Schema Source

This schema is conceptual and derived from the Resend REST API reference. It is not an introspected schema from a live GraphQL endpoint.
