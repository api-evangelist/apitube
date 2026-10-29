# APITube

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

APITube is a news data API providing search and retrieval across news articles, top headlines, trends, companies, journalists, and fact-checks, with taxonomy resolution for entities, topics and locations. The public contract is an OpenAPI 3.1 document of 26 operations served from api.apitube.io, authenticated with an API key by header or query parameter. APITube also operates a first-party MCP server at mcp.apitube.io over streamable HTTP, whose tool list is readable anonymously, and publishes an RFC 9727 api-catalog linkset at the apex that names the specification, the documentation, the llms.txt and the MCP server card.

**Areas:** News · Media Monitoring · News API · Fact Check · Journalists

## APITube on APIs.io

Everything profiled for APITube is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/apitube/](https://apis.io/providers/apitube/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [APITube News API](https://apis.io/apis/apitube/apitube-news-api/) — News search and retrieval — everything, top headlines, trends, companies, journalists, fact-checks and taxonomy suggestion. 26 operations, API key by header…
- [APITube Account API](https://apis.io/apis/apitube/apitube-account-api/) — API key balance and subscription plan information.
- [APITube Fact Check API](https://apis.io/apis/apitube/apitube-fact-check-api/) — Verify factual claims against the live news corpus (retrieval-augmented). Returns per-claim verdicts on an 8-level scale with confidence, explanation, and…
- [APITube Reference API](https://apis.io/apis/apitube/apitube-reference-api/) — The Reference API from APITube — 7 operation(s) for reference.
- [APITube Suggest API](https://apis.io/apis/apitube/apitube-suggest-api/) — Autocomplete and typeahead suggestions for entities.
- [APITube System API](https://apis.io/apis/apitube/apitube-system-api/) — Health checks and service status.
- [APITube Utilities API](https://apis.io/apis/apitube/apitube-utilities-api/) — Helper endpoints for building queries

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Apitube Webhooks](https://apis.io/asyncapis/apitube/apitube-webhooks/)

#### MCP servers (2)

Model Context Protocol servers that expose the API to agents.

- [apitube-mcp-server-card.json](https://apis.io/servers/apitube/apitube-mcp-server-card-json/)
- [APITube News MCP-Server](https://apis.io/servers/apitube/apitube-news-mcp-server/)

#### Overlays (7)

OpenAPI overlays, including conversational phrasing for each operation.

- [Apitube Account Api Overlay](https://apis.io/overlays/apitube/apitube-account-api-overlay/)
- [Apitube Fact Check Api Overlay](https://apis.io/overlays/apitube/apitube-fact-check-api-overlay/)
- [Apitube News Api Overlay](https://apis.io/overlays/apitube/apitube-news-api-overlay/)
- [Apitube Reference Api Overlay](https://apis.io/overlays/apitube/apitube-reference-api-overlay/)
- [Apitube Suggest Api Overlay](https://apis.io/overlays/apitube/apitube-suggest-api-overlay/)
- [Apitube System Api Overlay](https://apis.io/overlays/apitube/apitube-system-api-overlay/)
- [Apitube Utilities Api Overlay](https://apis.io/overlays/apitube/apitube-utilities-api-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Apitube Authentication](https://apis.io/security/apitube/apitube-authentication/)
- [Apitube Domain Security](https://apis.io/security/apitube/apitube-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Apitube Plans Pricing](https://apis.io/plans/apitube/apitube-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Apitube Rate Limits](https://apis.io/rate-limits/apitube/apitube-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://apitube.io)
- [Getting started](https://apitube.io/product/news-api/quick-start)
- [Pricing](https://apitube.io/pricing)
- [Sign up](https://apitube.io/#sign-up)
- [Support](https://apitube.io/contact)
- [Blog](https://apitube.io/blog)
- [Terms of service](https://apitube.io/terms/terms-of-service)
- [Privacy policy](https://apitube.io/terms/privacy-policy)
- [GitHub](https://github.com/apitube)
- [Status](https://status.apitube.io/)

## API Evangelist rating

**Kin Score 62.1** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.7 |
| Contract quality | 60.1 |
| Contract governance | 4.5 |
| Operational transparency | 65.8 |
| Developer ergonomics | 81.0 |
| Access clarity | 69.7 |

**Agent readiness 42.9** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | yes |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | — |

**Regulatory alignment 24.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/apitube/](https://apis.io/providers/apitube/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for APITube: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/apitube/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
