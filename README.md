# Sana (sana-labs)

Sana is an AI-native knowledge and learning company (Stockholm, Sweden; now part of Workday) behind Sana AI / Sana Agents and the Sana Learn platform. It builds expert AI agents and assistants grounded in a company's knowledge, plus an AI-first LMS/LXP. Sana exposes a tenant-scoped REST API (OAuth 2.0 client credentials) for user, group, program, course, content, and reporting management, along with xAPI and SCIM integration surfaces.

> Disambiguation: This profile covers **Sana** (sana.ai / sanalabs.com), the AI knowledge and learning platform. It is **not** Sana Benefits (sanabenefits.com), the unrelated US health insurance company.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sana-labs/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sana-labs/refs/heads/main/apis.yml)

## Tags

- AI
- Knowledge
- Learning
- LMS
- Agents

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Sana AI Assistant & Agents API

Sana AI / Sana Agents builds expert AI agents and a knowledge assistant grounded in a company's connected knowledge, able to act across tools such as Slack and Salesforce. The agent / assistant capabilities are configured primarily in-product; the documented public REST API surface is tenant-scoped administration and content rather than a general chat-completions endpoint, and agent/assistant programmatic access is partner / tenant gated. Captured here accurately rather than fabricated.

- **Human URL:** [https://docs.sana.ai/api-docs/](https://docs.sana.ai/api-docs/)
- **Base URL:** `https://<domain>.sana.ai`

#### Tags

- AI
- Agents
- Assistant

#### Properties

- [Documentation](https://docs.sana.ai/api-docs/)
- [OpenAPI](openapi/sana-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sana-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sana-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sana Knowledge & Search API

Sana connects to a company's knowledge (documents, spreadsheets, meeting recordings, CRM assets) and answers multimodal queries grounded in authorized sources. A dedicated public search/retrieval REST endpoint is not separately documented in the public API reference as of this catalog date; knowledge ingestion and grounding are configured via in-product connectors and the Sana Learn content/course APIs.

- **Human URL:** [https://docs.sana.ai/api-docs/](https://docs.sana.ai/api-docs/)
- **Base URL:** `https://<domain>.sana.ai`

#### Tags

- Knowledge
- Search
- Retrieval

#### Properties

- [Documentation](https://docs.sana.ai/api-docs/)
- [OpenAPI](openapi/sana-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sana-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sana-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sana Learn Content & Learning API

The documented core of the public API - tenant-scoped management of users, groups, programs, courses, learning paths, assignments, teamspaces, and reporting/insights for the Sana Learn platform. All requests are authenticated with a Bearer access token obtained via OAuth 2.0 client credentials and are scoped to a customer's `<domain>.sana.ai` tenant.

- **Human URL:** [https://docs.sana.ai/api-docs/](https://docs.sana.ai/api-docs/)
- **Base URL:** `https://<domain>.sana.ai`

#### Tags

- Learning
- LMS
- Content
- Courses

#### Properties

- [Documentation](https://docs.sana.ai/api-docs/)
- [OpenAPI](openapi/sana-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sana-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sana-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sana Integrations API

Standards-based integration surfaces - xAPI (Experience API) statement ingestion at `/xapi/v1/statements` with its own OAuth token endpoint, and SCIM 2.0 user/group provisioning at `/scim/v2` - plus connectors to external systems (Slack, Salesforce, LinkedIn Learning) configured in-product.

- **Human URL:** [https://docs.sana.ai/api-docs/](https://docs.sana.ai/api-docs/)
- **Base URL:** `https://<domain>.sana.ai`

#### Tags

- Integrations
- xAPI
- SCIM
- Provisioning

#### Properties

- [Documentation](https://docs.sana.ai/api-docs/)
- [OpenAPI](openapi/sana-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sana-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sana-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/sanalabs)
- [LinkedIn](https://www.linkedin.com/company/sana-labs)
- [Website](https://www.sana.ai)
- [Documentation](https://docs.sana.ai/api-docs/)
- [Plans](plans/sana-labs-plans-pricing.yml)
- [Rate Limits](rate-limits/sana-labs-rate-limits.yml)
- [Fin Ops](finops/sana-labs-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
