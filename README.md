# Sana (sana-labs)

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
