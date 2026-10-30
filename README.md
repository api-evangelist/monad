# Monad

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

Monad is a high-performance EVM-compatible Layer 1 blockchain designed for parallel execution and pipelined consensus, targeting 10,000 TPS with 1-second block time and single-slot finality while remaining fully Ethereum bytecode-compatible. Mainnet (chain ID 143, native token MON) launched on November 24, 2025 alongside a long-running public testnet. Developer surfaces include public JSON-RPC endpoints (rpc.monad.xyz, testnet-rpc.monad.xyz), an Ethereum-compatible JSON-RPC plus Monad-specific extensions, MonadVision, Monadscan, and Socialscan explorers, native EVM tooling (Foundry, Hardhat, Remix), indexers (GhostGraph, QuickNode Streams, Envio HyperIndex), and a Staking API and Machine Payments Protocol.

**Areas:** Blockchain · Layer 1 · EVM · High Performance · Parallel Execution · JSON-RPC · MonadBFT · Monad

## Monad on APIs.io

Everything profiled for Monad is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/monad/](https://apis.io/providers/monad/)** — or go straight to one of the APIs or properties below.

### APIs (13)

- [Monad Mainnet JSON-RPC](https://apis.io/apis/monad/mainnet-rpc/) — Public Ethereum-compatible JSON-RPC endpoint for Monad mainnet (chain ID 143, native token MON). Hosted on QuickNode infrastructure with a 25 requests/sec…
- [Monad Testnet JSON-RPC](https://apis.io/apis/monad/testnet-rpc/) — Public JSON-RPC endpoint for the Monad public testnet, used for application development, integration testing, and validator software validation before…
- [Monad JSON-RPC API](https://apis.io/apis/monad/json-rpc-api/) — Full JSON-RPC method reference — standard Ethereum eth_*, net_*, web3_*, debug_*, and trace_* methods plus Monad-specific extensions and notes on method…
- [Monad Staking API](https://apis.io/apis/monad/staking-api/) — API for delegating MON to validators, querying validator stats, undelegating, and reading rewards. Backs delegation UI and external staking integrations.
- [Monad Machine Payments Protocol](https://apis.io/apis/monad/machine-payments-protocol/) — Protocol specification for programmable machine-to-machine payments on Monad, including account, channel, and settlement primitives.
- [MonadVision Block Explorer](https://apis.io/apis/monad/monadvision-explorer/) — Block explorer for Monad mainnet — transaction, block, contract, and token lookup with Solidity source verification.
- [Monadscan Block Explorer](https://apis.io/apis/monad/monadscan-explorer/) — Etherscan-style Monadscan block explorer covering Monad mainnet, with transaction, address, contract, and token analytics.
- [Socialscan Monad Explorer](https://apis.io/apis/monad/socialscan-explorer/) — Socialscan instance for Monad, offering an alternative explorer view with social and on-chain identity overlays.
- [Monad Foundry Toolkit](https://apis.io/apis/monad/foundry-toolkit/) — Monad-flavored Foundry toolkit (forge, cast, anvil) for compiling, deploying, scripting, and testing Solidity against Monad mainnet and testnet.
- [Monad RPC Providers](https://apis.io/apis/monad/rpc-providers/) — Registry of third-party RPC providers supporting Monad — QuickNode, Alchemy, Goldsky Edge, Ankr, MonadInfra — with rate-limit and method-availability…
- [Monad Indexers](https://apis.io/apis/monad/indexers/) — Indexing options for Monad data — GhostGraph (Graph-style subgraphs), QuickNode Streams, and Envio HyperIndex — for building data backends and analytics on…
- [Monad Bridges](https://apis.io/apis/monad/bridges/) — Token bridges and cross-chain messaging integrations for moving assets between Ethereum, other chains, and Monad.
- [Monad JSON RPC API](https://apis.io/apis/monad/monad-monad-json-rpc-api-api/) — The Monad JSON RPC API API from Monad — 1 operation(s) for monad json rpc api.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### GraphQL (1)

GraphQL schemas.

- [Monad GraphQL API](https://apis.io/graphqls/monad/monad-graphql/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Moved to /providers/monad/](https://apis.io/servers/monad/monad/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Monad Agentic Access](https://apis.io/agentic-access/monad/monad-agentic-access/)

#### Collections (2)

Postman and Open Collection request collections.

- [Monad JSON-RPC API](https://apis.io/collections/monad/open-monad/)
- [Monad JSON-RPC Monad JSON RPC API API](https://apis.io/collections/monad/open-monad-monad-json-rpc-api-api/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Monad Domain Security](https://apis.io/security/monad/monad-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Monad Plans Pricing](https://apis.io/plans/monad/monad-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Monad Rate Limits](https://apis.io/rate-limits/monad/monad-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Monad Finops](https://apis.io/finops/monad/monad-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.monad.xyz)
- [Documentation](https://docs.monad.xyz)
- [Getting started](https://docs.monad.xyz/developer-essentials/network-information)
- [API reference](https://docs.monad.xyz/reference/json-rpc/api)
- [Blog](https://www.monad.xyz/blog)
- [Terms of service](https://www.monad.xyz/terms)
- [Privacy policy](https://www.monad.xyz/privacy)

## API Evangelist rating

**Kin Score 28.1** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 49.6 |
| Contract governance | 0.0 |
| Operational transparency | 10.5 |
| Developer ergonomics | 39.3 |
| Access clarity | 5.3 |

**Agent readiness 29.0** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
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
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 5.9** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/monad/](https://apis.io/providers/monad/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Monad: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/monad/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
