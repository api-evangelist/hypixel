# Hypixel (hypixel)

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

Hypixel Public API — the official REST API of the Hypixel Minecraft server network, the largest Minecraft minigame server. The API exposes player profiles and stats, guilds, friends, recent games, online status, server-wide counts, network boosters, punishment statistics, leaderboards, housing, and the full SkyBlock economy (auctions, bazaar, profiles, museum, garden, bingo, fire sales). All endpoints are read-only HTTP GET requests returning JSON, authenticated with a per-application API key issued via the Hypixel Developer Dashboard.

**APIs.json:** [https://api.hypixel.net/](https://api.hypixel.net/)

## Tags

- Games And Comics
- Gaming
- Minecraft
- Player Stats
- Leaderboards
- SkyBlock
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Hypixel Public API

Read-only REST API exposing player, guild, recent games, online status, server counts, boosters, leaderboards, punishment statistics, housing, and the full SkyBlock economy (auctions, bazaar, profiles, museum, garden, bingo, fire sales) for the Hypixel Minecraft network. All endpoints are HTTP GET, JSON, and authenticated with an API key issued via the Hypixel Developer Dashboard.

- **Human URL:** [https://api.hypixel.net/](https://api.hypixel.net/)
- **Base URL:** `https://api.hypixel.net/v2`

#### Tags

- Games And Comics
- Gaming
- Minecraft
- Player Stats
- SkyBlock

#### Properties

- [Documentation](https://api.hypixel.net/)
- [Developer Portal](https://developer.hypixel.net/)
- [Policies](https://developer.hypixel.net/policies)
- [OpenAPI](openapi/hypixel-public-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hypixel-public-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hypixel-public-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [SDK](https://github.com/HypixelDev/PublicAPI)
- [Code Examples](https://github.com/HypixelDev/PublicAPI/tree/master/hypixel-api-example)

## Common Properties

- [Website](https://hypixel.net/)
- [Developer Portal](https://developer.hypixel.net/)
- [Api Help Forum](https://hypixel.net/forums/api-help.111/)
- [Terms of Service](https://hypixel.net/tos)
- [Policies](https://developer.hypixel.net/policies)
- [GitHub Organization](https://github.com/HypixelDev)
- [Source Code](https://github.com/HypixelDev/PublicAPI)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Plans](plans/hypixel-plans-pricing.yml)
- [Rate Limits](rate-limits/hypixel-rate-limits.yml)
- [Fin Ops](finops/hypixel-finops.yml)
- [Spectral Rules](rules/hypixel-spectral-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [Vocabulary](vocabulary/hypixel-vocabulary.yml)
- [Json Ld](json-ld/hypixel-public-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
