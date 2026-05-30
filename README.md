# Hypixel (hypixel)

Hypixel Public API — the official REST API of the Hypixel Minecraft server network, the largest Minecraft minigame server. The API exposes player profiles and stats, guilds, friends, recent games, online status, server-wide counts, network boosters, punishment statistics, leaderboards, housing, and the full SkyBlock economy (auctions, bazaar, profiles, museum, garden, bingo, fire sales). All endpoints are read-only HTTP GET requests returning JSON, authenticated with a per-application API key issued via the Hypixel Developer Dashboard.

**URL:** [https://api.hypixel.net/](https://api.hypixel.net/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Games And Comics, Gaming, Minecraft, Player Stats, Leaderboards, SkyBlock, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Hypixel Public API

Read-only REST API exposing player, guild, recent games, online status, server counts, boosters, leaderboards, punishment statistics, housing, and the full SkyBlock economy (auctions, bazaar, profiles, museum, garden, bingo, fire sales) for the Hypixel Minecraft network. All endpoints are HTTP GET, JSON, and authenticated with an API key issued via the Hypixel Developer Dashboard.

**Human URL:** [https://api.hypixel.net/](https://api.hypixel.net/)

**Base URL:** `https://api.hypixel.net/v2`

**Version:** `v2`

#### Tags

 - Games And Comics, Gaming, Minecraft, Player Stats, SkyBlock

#### Properties

- [Documentation](https://api.hypixel.net/)
- [DeveloperPortal](https://developer.hypixel.net/)
- [Policies](https://developer.hypixel.net/policies)
- [OpenAPI](openapi/hypixel-public-api-openapi.yml)
- [Java SDK](https://github.com/HypixelDev/PublicAPI)
- [Java Examples](https://github.com/HypixelDev/PublicAPI/tree/master/hypixel-api-example)
- [NaftikoCapability](capabilities/hypixel-public-api-player-data.yaml)
- [NaftikoCapability](capabilities/hypixel-public-api-resources.yaml)
- [NaftikoCapability](capabilities/hypixel-public-api-skyblock.yaml)
- [NaftikoCapability](capabilities/hypixel-public-api-housing.yaml)
- [NaftikoCapability](capabilities/hypixel-public-api-other.yaml)

## Common Properties

- [Website](https://hypixel.net/)
- [DeveloperPortal](https://developer.hypixel.net/)
- [ApiHelpForum](https://hypixel.net/forums/api-help.111/)
- [TermsOfService](https://hypixel.net/tos)
- [Policies](https://developer.hypixel.net/policies)
- [GitHubOrganization](https://github.com/HypixelDev)
- [SourceCode](https://github.com/HypixelDev/PublicAPI)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- [Plans](plans/hypixel-plans-pricing.yml)
- [RateLimits](rate-limits/hypixel-rate-limits.yml)
- [FinOps](finops/hypixel-finops.yml)
- [Spectral](rules/hypixel-spectral-rules.yml)
- [Vocabulary](vocabulary/hypixel-vocabulary.yml)
- [JsonLd](json-ld/hypixel-public-api-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Player Data | Retrieve a player's full profile and per-game statistics by Minecraft UUID, including their recent games and current online status. |
| Guild Lookup | Resolve a Hypixel guild by guild id, player UUID, or guild name and return its members, ranks, level, and per-game experience. |
| Network Boosters | Read the list of active in-network coin/XP boosters and the queue waiting to activate per game. |
| Server Counts and Leaderboards | Get real-time player counts per game and lobby plus the official network leaderboards across every supported Hypixel game. |
| Punishment Statistics | Read network-wide moderation statistics including watchdog/staff bans today and historical totals. |
| SkyBlock Economy | Full access to the SkyBlock economy — active auctions (paged), recently ended auctions, the live bazaar, fire sales, plus per-profile data (profile, profiles, museum, garden, bingo). |
| SkyBlock Resources | Static SkyBlock resource catalogs — collections, skills, items, current election and mayor, and the current bingo event. |
| Game Resources | Static reference data for the network — game types, achievements, challenges, quests, guild achievements, and vanity pets / companions. |
| Housing | Active public houses across the network, the public houses owned by a given player, and the full data of a single house. |

## Use Cases

| Name | Description |
|------|-------------|
| Public Stats Sites | Build a third-party stats website (e.g. plancke.io style) that resolves a Minecraft username to UUID and renders the player's full Hypixel profile, recent games, guild, and per-game stats. |
| SkyBlock Flipping and Arbitrage Tools | Subscribe to active SkyBlock auctions and bazaar order books to power flipping calculators, arbitrage scanners, and craft-cost analyzers. |
| Guild Dashboards and Bots | Power Discord bots and guild dashboards that resolve guild membership, track per-game contribution, and rank guild members on the network leaderboards. |
| Network Status Widgets | Build status widgets and lobby-finder tools using the live /counts and /status endpoints. |
| Watchdog and Moderation Reporting | Surface daily and historical watchdog/staff ban counts from /punishmentstats for community moderation transparency reports. |

## Integrations

| Name | Description |
|------|-------------|
| Minecraft / Mojang UUID Resolution | Players are addressed by Minecraft UUID; consumers typically resolve usernames via the Mojang API first, then query Hypixel by UUID. |
| Hypixel ModAPI (Forge / Fabric) | The Hypixel ModAPI lets Minecraft mods request a subset of Hypixel data via the Minecraft plugin-message system in-game, complementing this REST API. |

## Solutions

| Name | Description |
|------|-------------|
| SkyBlock Tooling Ecosystem | The Hypixel API underpins a large ecosystem of community SkyBlock tools — auction flippers, museum / collection trackers, bazaar arbitrage bots, and profile viewers. |
| Network Telemetry | Counts, leaderboards, boosters, and punishment statistics together form a public telemetry surface for the entire Hypixel network. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [hypixel-public-api-openapi.json](openapi/hypixel-public-api-openapi.json)
- [hypixel-public-api-openapi.yml](openapi/hypixel-public-api-openapi.yml)

### JSON Schema

- [hypixel-public-api-active-booster-schema.json](json-schema/hypixel-public-api-active-booster-schema.json)
- [hypixel-public-api-booster-schema.json](json-schema/hypixel-public-api-booster-schema.json)
- [hypixel-public-api-game-schema.json](json-schema/hypixel-public-api-game-schema.json)
- [hypixel-public-api-housing-house-schema.json](json-schema/hypixel-public-api-housing-house-schema.json)
- [hypixel-public-api-queued-booster-schema.json](json-schema/hypixel-public-api-queued-booster-schema.json)
- [hypixel-public-api-sky-block-auction-schema.json](json-schema/hypixel-public-api-sky-block-auction-schema.json)
- [hypixel-public-api-sky-block-fire-sale-schema.json](json-schema/hypixel-public-api-sky-block-fire-sale-schema.json)
- [hypixel-public-api-sky-block-garden-schema.json](json-schema/hypixel-public-api-sky-block-garden-schema.json)
- [hypixel-public-api-sky-block-item-schema.json](json-schema/hypixel-public-api-sky-block-item-schema.json)
- [hypixel-public-api-sky-block-museum-schema.json](json-schema/hypixel-public-api-sky-block-museum-schema.json)
- [hypixel-public-api-sky-block-profile-schema.json](json-schema/hypixel-public-api-sky-block-profile-schema.json)

### JSON Structure

- [hypixel-public-api-active-booster-structure.json](json-structure/hypixel-public-api-active-booster-structure.json)
- [hypixel-public-api-booster-structure.json](json-structure/hypixel-public-api-booster-structure.json)
- [hypixel-public-api-game-structure.json](json-structure/hypixel-public-api-game-structure.json)
- [hypixel-public-api-housing-house-structure.json](json-structure/hypixel-public-api-housing-house-structure.json)
- [hypixel-public-api-queued-booster-structure.json](json-structure/hypixel-public-api-queued-booster-structure.json)
- [hypixel-public-api-sky-block-auction-structure.json](json-structure/hypixel-public-api-sky-block-auction-structure.json)
- [hypixel-public-api-sky-block-fire-sale-structure.json](json-structure/hypixel-public-api-sky-block-fire-sale-structure.json)
- [hypixel-public-api-sky-block-garden-structure.json](json-structure/hypixel-public-api-sky-block-garden-structure.json)
- [hypixel-public-api-sky-block-item-structure.json](json-structure/hypixel-public-api-sky-block-item-structure.json)
- [hypixel-public-api-sky-block-museum-structure.json](json-structure/hypixel-public-api-sky-block-museum-structure.json)
- [hypixel-public-api-sky-block-profile-structure.json](json-structure/hypixel-public-api-sky-block-profile-structure.json)

### JSON-LD

- [hypixel-public-api-context.jsonld](json-ld/hypixel-public-api-context.jsonld)

### Examples

- [hypixel-public-api-active-booster-example.json](examples/hypixel-public-api-active-booster-example.json)
- [hypixel-public-api-booster-example.json](examples/hypixel-public-api-booster-example.json)
- [hypixel-public-api-game-example.json](examples/hypixel-public-api-game-example.json)
- [hypixel-public-api-housing-house-example.json](examples/hypixel-public-api-housing-house-example.json)
- [hypixel-public-api-queued-booster-example.json](examples/hypixel-public-api-queued-booster-example.json)
- [hypixel-public-api-sky-block-auction-example.json](examples/hypixel-public-api-sky-block-auction-example.json)
- [hypixel-public-api-sky-block-fire-sale-example.json](examples/hypixel-public-api-sky-block-fire-sale-example.json)
- [hypixel-public-api-sky-block-garden-example.json](examples/hypixel-public-api-sky-block-garden-example.json)
- [hypixel-public-api-sky-block-item-example.json](examples/hypixel-public-api-sky-block-item-example.json)
- [hypixel-public-api-sky-block-museum-example.json](examples/hypixel-public-api-sky-block-museum-example.json)
- [hypixel-public-api-sky-block-profile-example.json](examples/hypixel-public-api-sky-block-profile-example.json)

## Capabilities

Naftiko capability files — one per business surface (OpenAPI tag). Each file is self-contained, with inline `consumes`, a REST exposer, and an MCP exposer.

| Capability | Operations | MCP Tools | File |
|------------|-----------:|----------:|------|
| Hypixel Public API — Housing | 3 | 3 | [hypixel-public-api-housing.yaml](capabilities/hypixel-public-api-housing.yaml) |
| Hypixel Public API — Other | 4 | 4 | [hypixel-public-api-other.yaml](capabilities/hypixel-public-api-other.yaml) |
| Hypixel Public API — Player Data | 4 | 4 | [hypixel-public-api-player-data.yaml](capabilities/hypixel-public-api-player-data.yaml) |
| Hypixel Public API — Resources | 7 | 7 | [hypixel-public-api-resources.yaml](capabilities/hypixel-public-api-resources.yaml) |
| Hypixel Public API — SkyBlock | 16 | 16 | [hypixel-public-api-skyblock.yaml](capabilities/hypixel-public-api-skyblock.yaml) |

## Vocabulary

- [Hypixel Vocabulary](vocabulary/hypixel-vocabulary.yml) — Unified taxonomy mapping 34 resources, 2 actions, 5 workflows, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [hypixel-spectral-rules.yml](rules/hypixel-spectral-rules.yml) — 36 Spectral rules enforcing Hypixel Public API conventions.

## Plans / Pricing

- [hypixel-plans-pricing.yml](plans/hypixel-plans-pricing.yml)

## Rate Limits

- [hypixel-rate-limits.yml](rate-limits/hypixel-rate-limits.yml)

## FinOps

- [hypixel-finops.yml](finops/hypixel-finops.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
