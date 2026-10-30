# Lemmy

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

Lemmy is a free, open-source, self-hostable federated link aggregator and discussion platform built as a Reddit alternative. It exposes a versioned REST API at /api/v4/ for creating posts, commenting, managing communities, voting, searching, and administering instances. Lemmy federates across the Fediverse using the ActivityPub protocol, allowing users on different Lemmy instances and compatible platforms (Mastodon, PeerTube, Friendica) to interact without a central server. Each instance operator configures their own rate limits; default limits include 50 comments per 10 minutes, 100 searches per 10 minutes, and 5 new registrations per day. Authentication uses JWT bearer tokens obtained via the login endpoint. The software is licensed under AGPL-3.0 and written in Rust with an Actix web framework backend.

**Areas:** Community · Federated · Fediverse · Link Aggregator · Open Source · Social Network

## Lemmy on APIs.io

Everything profiled for Lemmy is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/lemmy/](https://apis.io/providers/lemmy/)** — or go straight to one of the APIs or properties below.

### APIs (14)

- [Lemmy Account API](https://apis.io/apis/lemmy/lemmy-account-api/) — User account management and settings
- [Lemmy Admin API](https://apis.io/apis/lemmy/lemmy-admin-api/) — Administrative actions
- [Lemmy Authentication API](https://apis.io/apis/lemmy/lemmy-authentication-api/) — Account registration, login, and password management
- [Lemmy Comment API](https://apis.io/apis/lemmy/lemmy-comment-api/) — Creating and managing comments
- [Lemmy Community API](https://apis.io/apis/lemmy/lemmy-community-api/) — Community management and discovery
- [Lemmy Federation API](https://apis.io/apis/lemmy/lemmy-federation-api/) — ActivityPub federation and cross-instance operations
- [Lemmy Images API](https://apis.io/apis/lemmy/lemmy-images-api/) — Image upload and retrieval
- [Lemmy Notifications API](https://apis.io/apis/lemmy/lemmy-notifications-api/) — User notifications and alerts
- [Lemmy Person API](https://apis.io/apis/lemmy/lemmy-person-api/) — User profiles and discovery
- [Lemmy Post API](https://apis.io/apis/lemmy/lemmy-post-api/) — Creating and managing posts
- [Lemmy Private Messages API](https://apis.io/apis/lemmy/lemmy-private-messages-api/) — Direct messaging between users
- [Lemmy Reports API](https://apis.io/apis/lemmy/lemmy-reports-api/) — Content reporting and moderation
- [Lemmy Search API](https://apis.io/apis/lemmy/lemmy-search-api/) — Search across posts, comments, communities, and users
- [Lemmy Site API](https://apis.io/apis/lemmy/lemmy-site-api/) — Site-level information and configuration

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Lemmy Agentic Access](https://apis.io/agentic-access/lemmy/lemmy-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [Comment](https://apis.io/schemas/lemmy/comment/)
- [Community](https://apis.io/schemas/lemmy/community/)
- [Post](https://apis.io/schemas/lemmy/post/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Lemmy Context](https://apis.io/jsonld/lemmy/lemmy-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Lemmy REST API Vocabulary](https://apis.io/vocabularies/lemmy/lemmy-vocabulary/)

#### Examples (3)

Example requests and responses.

- [Create Post](https://apis.io/examples/lemmy/create-post/)
- [Login](https://apis.io/examples/lemmy/login/)
- [Search](https://apis.io/examples/lemmy/search/)

#### Collections (14)

Postman and Open Collection request collections.

- [Lemmy REST Account API](https://apis.io/collections/lemmy/open-lemmy-account-api/)
- [Lemmy REST Account Admin API](https://apis.io/collections/lemmy/open-lemmy-admin-api/)
- [Lemmy REST Account Authentication API](https://apis.io/collections/lemmy/open-lemmy-authentication-api/)
- [Lemmy REST Account Comment API](https://apis.io/collections/lemmy/open-lemmy-comment-api/)
- [Lemmy REST Account Community API](https://apis.io/collections/lemmy/open-lemmy-community-api/)
- [Lemmy REST Account Federation API](https://apis.io/collections/lemmy/open-lemmy-federation-api/)
- [Lemmy REST Account Images API](https://apis.io/collections/lemmy/open-lemmy-images-api/)
- [Lemmy REST Account Notifications API](https://apis.io/collections/lemmy/open-lemmy-notifications-api/)
- [Lemmy REST Account Person API](https://apis.io/collections/lemmy/open-lemmy-person-api/)
- [Lemmy REST Account Post API](https://apis.io/collections/lemmy/open-lemmy-post-api/)
- [Lemmy REST Account Private Messages API](https://apis.io/collections/lemmy/open-lemmy-private-messages-api/)
- [Lemmy REST Account Reports API](https://apis.io/collections/lemmy/open-lemmy-reports-api/)
- [Lemmy REST Account Search API](https://apis.io/collections/lemmy/open-lemmy-search-api/)
- [Lemmy REST Account Site API](https://apis.io/collections/lemmy/open-lemmy-site-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Lemmy — jsonschema rules](https://apis.io/rules/lemmy/lemmy-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Lemmy Authentication](https://apis.io/security/lemmy/lemmy-authentication/)
- [Lemmy Domain Security](https://apis.io/security/lemmy/lemmy-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Lemmy Plans Pricing](https://apis.io/plans/lemmy/lemmy-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Lemmy Rate Limits](https://apis.io/rate-limits/lemmy/lemmy-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Lemmy Finops](https://apis.io/finops/lemmy/lemmy-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://join-lemmy.org)
- [Documentation](https://join-lemmy.org/docs/)
- [Getting started](https://join-lemmy.org/docs/client_development/)
- [Blog](https://join-lemmy.org/news/)
- [GitHub](https://github.com/LemmyNet)

## API Evangelist rating

**Kin Score 34.3** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 70.8 |
| Contract governance | 23.5 |
| Operational transparency | 36.8 |
| Developer ergonomics | 11.9 |
| Access clarity | 7.9 |

**Agent readiness 19.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/lemmy/](https://apis.io/providers/lemmy/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Lemmy: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/lemmy/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
