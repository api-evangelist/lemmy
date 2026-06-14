# Lemmy

Lemmy is a free, open-source, self-hostable federated link aggregator and discussion platform built as a Reddit alternative. It exposes a versioned REST API at /api/v4/ for creating posts, commenting, managing communities, voting, searching, and administering instances. Lemmy federates across the Fediverse using the ActivityPub protocol, allowing users on different Lemmy instances and compatible platforms (Mastodon, PeerTube, Friendica) to interact without a central server.

**API Version:** v4  
**License:** AGPL-3.0  
**Latest Release:** 0.19.19 (June 2026)  
**Base URL (largest public instance):** https://lemmy.world/api/v4

## Resources

- [Documentation](https://join-lemmy.org/docs/)
- [GitHub Organization](https://github.com/LemmyNet)
- [Source Repository](https://github.com/LemmyNet/lemmy)
- [JS Client](https://github.com/LemmyNet/lemmy-js-client)
- [Website](https://join-lemmy.org)
- [Blog](https://join-lemmy.org/news/)

## APIs

- **Lemmy REST API** — Full platform API for posts, comments, communities, voting, search, private messages, moderation, and administration.

## Files

| File | Description |
|------|-------------|
| `apis.yml` | APIs.json 0.19 provider index |
| `plans/lemmy-plans-pricing.yml` | API Commons Plans profile (free/OSS/managed hosting) |
| `rate-limits/lemmy-rate-limits.yml` | API Commons Rate Limits profile |
| `finops/lemmy-finops.yml` | FOCUS-aligned FinOps profile |
