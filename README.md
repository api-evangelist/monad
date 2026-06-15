# Monad (monad)

Monad is a high-performance EVM-compatible Layer 1 blockchain designed for parallel execution and pipelined consensus, targeting 10,000 TPS with 1-second block time and single-slot finality while remaining fully Ethereum bytecode-compatible. Mainnet (chain ID 143, native token MON) launched on November 24, 2025 alongside a long-running public testnet. Developer surfaces include public JSON-RPC endpoints (rpc.monad.xyz, testnet-rpc.monad.xyz), an Ethereum-compatible JSON-RPC plus Monad-specific extensions, MonadVision, Monadscan, and Socialscan explorers, native EVM tooling (Foundry, Hardhat, Remix), indexers (GhostGraph, QuickNode Streams, Envio HyperIndex), and a Staking API and Machine Payments Protocol.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/monad/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/monad/refs/heads/main/apis.yml)

## Tags

- Blockchain
- Layer 1
- EVM
- High Performance
- Parallel Execution
- JSON-RPC
- MonadBFT

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Monad Mainnet JSON-RPC

Public Ethereum-compatible JSON-RPC endpoint for Monad mainnet (chain ID 143, native token MON). Hosted on QuickNode infrastructure with a 25 requests/sec default rate limit; alternative public endpoints are published in the docs.

- **Human URL:** [https://docs.monad.xyz/developer-essentials/network-information](https://docs.monad.xyz/developer-essentials/network-information)
- **Base URL:** `https://rpc.monad.xyz`

#### Tags

- JSON-RPC
- Mainnet
- EVM

#### Properties

- [Documentation](https://docs.monad.xyz/developer-essentials/network-information)
- [API Reference](https://docs.monad.xyz/reference/json-rpc/api)
- [Postman Collection](collections/monad.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/monad.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Monad Testnet JSON-RPC

Public JSON-RPC endpoint for the Monad public testnet, used for application development, integration testing, and validator software validation before deploying to mainnet.

- **Human URL:** [https://docs.monad.xyz/developer-essentials/testnets](https://docs.monad.xyz/developer-essentials/testnets)
- **Base URL:** `https://testnet-rpc.monad.xyz`

#### Tags

- JSON-RPC
- Testnet
- EVM

#### Properties

- [Documentation](https://docs.monad.xyz/developer-essentials/testnets)
- [API Reference](https://docs.monad.xyz/reference/json-rpc/api)
- [Postman Collection](collections/monad.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/monad.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Monad JSON-RPC API

Full JSON-RPC method reference — standard Ethereum eth_*, net_*, web3_*, debug_*, and trace_* methods plus Monad-specific extensions and notes on method differences, rate limits, and error codes.

- **Human URL:** [https://docs.monad.xyz/reference/json-rpc/api](https://docs.monad.xyz/reference/json-rpc/api)
- **Base URL:** `https://docs.monad.xyz/reference/json-rpc/api`

#### Tags

- JSON-RPC
- Reference
- EVM

#### Properties

- [Documentation](https://docs.monad.xyz/reference/json-rpc/overview)
- [API Reference](https://docs.monad.xyz/reference/json-rpc/api)
- [Playground](https://docs.monad.xyz/reference/json-rpc/playground)
- [Postman Collection](collections/monad.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/monad.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Monad Staking API

API for delegating MON to validators, querying validator stats, undelegating, and reading rewards. Backs delegation UI and external staking integrations.

- **Human URL:** [https://docs.monad.xyz/reference/staking/api](https://docs.monad.xyz/reference/staking/api)
- **Base URL:** `https://docs.monad.xyz/reference/staking/api`

#### Tags

- Staking
- Validators
- Rewards

#### Properties

- [Documentation](https://docs.monad.xyz/reference/staking/api)
- [Postman Collection](collections/monad.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/monad.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Monad Machine Payments Protocol

Protocol specification for programmable machine-to-machine payments on Monad, including account, channel, and settlement primitives.

- **Human URL:** [https://docs.monad.xyz/reference/mpp/overview](https://docs.monad.xyz/reference/mpp/overview)
- **Base URL:** `https://docs.monad.xyz/reference/mpp/overview`

#### Tags

- MPP
- Machine Payments
- Protocol

#### Properties

- [Documentation](https://docs.monad.xyz/reference/mpp/overview)
- [Postman Collection](collections/monad.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/monad.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MonadVision Block Explorer

Block explorer for Monad mainnet — transaction, block, contract, and token lookup with Solidity source verification.

- **Human URL:** [https://monadvision.com](https://monadvision.com)
- **Base URL:** `https://monadvision.com`

#### Tags

- Explorer
- MonadVision
- Mainnet

#### Properties

- [Documentation](https://monadvision.com)
- [Postman Collection](collections/monad.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/monad.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Monadscan Block Explorer

Etherscan-style Monadscan block explorer covering Monad mainnet, with transaction, address, contract, and token analytics.

- **Human URL:** [https://monadscan.com](https://monadscan.com)
- **Base URL:** `https://monadscan.com`

#### Tags

- Explorer
- Monadscan
- Mainnet

#### Properties

- [Documentation](https://monadscan.com)
- [Postman Collection](collections/monad.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/monad.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Socialscan Monad Explorer

Socialscan instance for Monad, offering an alternative explorer view with social and on-chain identity overlays.

- **Human URL:** [https://monad.socialscan.io](https://monad.socialscan.io)
- **Base URL:** `https://monad.socialscan.io`

#### Tags

- Explorer
- Socialscan

#### Properties

- [Documentation](https://monad.socialscan.io)
- [Postman Collection](collections/monad.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/monad.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Monad Foundry Toolkit

Monad-flavored Foundry toolkit (forge, cast, anvil) for compiling, deploying, scripting, and testing Solidity against Monad mainnet and testnet.

- **Human URL:** [https://docs.monad.xyz/tooling-and-infra/toolkits/monad-foundry](https://docs.monad.xyz/tooling-and-infra/toolkits/monad-foundry)
- **Base URL:** `https://docs.monad.xyz/tooling-and-infra/toolkits/monad-foundry`

#### Tags

- Foundry
- Tooling
- Solidity

#### Properties

- [Documentation](https://docs.monad.xyz/tooling-and-infra/toolkits/monad-foundry)
- [Postman Collection](collections/monad.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/monad.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Monad RPC Providers

Registry of third-party RPC providers supporting Monad — QuickNode, Alchemy, Goldsky Edge, Ankr, MonadInfra — with rate-limit and method-availability differences documented.

- **Human URL:** [https://docs.monad.xyz/tooling-and-infra/rpc-providers](https://docs.monad.xyz/tooling-and-infra/rpc-providers)
- **Base URL:** `https://docs.monad.xyz/tooling-and-infra/rpc-providers`

#### Tags

- RPC
- Providers
- Infrastructure

#### Properties

- [Documentation](https://docs.monad.xyz/tooling-and-infra/rpc-providers)
- [Postman Collection](collections/monad.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/monad.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Monad Indexers

Indexing options for Monad data — GhostGraph (Graph-style subgraphs), QuickNode Streams, and Envio HyperIndex — for building data backends and analytics on top of Monad.

- **Human URL:** [https://docs.monad.xyz/tooling-and-infra/indexers](https://docs.monad.xyz/tooling-and-infra/indexers)
- **Base URL:** `https://docs.monad.xyz/tooling-and-infra/indexers`

#### Tags

- Indexers
- GraphQL
- Data

#### Properties

- [Documentation](https://docs.monad.xyz/tooling-and-infra/indexers)
- [Postman Collection](collections/monad.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/monad.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Monad Bridges

Token bridges and cross-chain messaging integrations for moving assets between Ethereum, other chains, and Monad.

- **Human URL:** [https://docs.monad.xyz/developer-essentials/network-information/tokens-and-bridges](https://docs.monad.xyz/developer-essentials/network-information/tokens-and-bridges)
- **Base URL:** `https://docs.monad.xyz/developer-essentials/network-information/tokens-and-bridges`

#### Tags

- Bridge
- Cross-Chain
- Tokens

#### Properties

- [Documentation](https://docs.monad.xyz/developer-essentials/network-information/tokens-and-bridges)
- [Postman Collection](collections/monad.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/monad.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.monad.xyz)
- [Documentation](https://docs.monad.xyz)
- [Getting Started](https://docs.monad.xyz/developer-essentials/network-information)
- [API Reference](https://docs.monad.xyz/reference/json-rpc/api)
- [Playground](https://docs.monad.xyz/reference/json-rpc/playground)
- [App](https://app.monad.xyz)
- [Visualization](https://gmonads.com)
- [Explorer](https://monadvision.com)
- [Git Hub](https://github.com/monad-crypto)
- [Blog](https://www.monad.xyz/blog)
- [Twitter](https://x.com/monad)
- [Discord](https://discord.gg/monad)
- [Telegram](https://t.me/monad_xyz)
- [Privacy Policy](https://www.monad.xyz/privacy)
- [Terms of Service](https://www.monad.xyz/terms)
- [L L Ms Txt](https://docs.monad.xyz/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
