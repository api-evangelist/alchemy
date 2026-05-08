# Alchemy (alchemy)

Alchemy is a Web3 developer platform offering blockchain JSON-RPC, Data APIs (NFT, Token, Transfers, Portfolio, Prices, Webhooks/Notify, Simulation), Smart Wallets / Account Abstraction (Bundler, Gas Manager), and dedicated Rollup infrastructure across 50+ chains including Ethereum, Polygon, Arbitrum, Optimism, Base, and Solana.

OpenAPI specs for Token API, Transfers API, and Gas Manager API are captured in [`openapi/`](openapi/).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/alchemy/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=alchemy-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## APIs
- **Alchemy Node API (JSON-RPC)** - Multi-chain JSON-RPC over HTTPS and WebSockets covering standard eth_*, solana, and other chain methods, plus Alchemy-enhanced subscriptions (alchemy_minedTransactions, alchemy_pendingTransactions).
- **Alchemy NFT API** - REST endpoints for NFT ownership, metadata, floor price, sales, contract metadata, and transfers across EVM chains and Solana.
- **Alchemy Token API** - REST endpoints for ERC-20 token balances, metadata, allowances, prices, and historical transfers.
- **Alchemy Transfers API** - REST endpoints for paginated address-level transfer history (external, internal, ERC-20, ERC-721, ERC-1155).
- **Alchemy Portfolio API** - REST endpoints aggregating multi-chain wallet balances, NFTs, and tokens in a single call.
- **Alchemy Prices API** - REST endpoints for token spot and historical pricing.
- **Alchemy Webhooks (Notify)** - REST API for managing webhook subscriptions (mined / dropped transactions, address activity, NFT activity, custom).
- **Alchemy Bundler API (ERC-4337)** - JSON-RPC bundler endpoints for ERC-4337 user operations (eth_sendUserOperation, eth_estimateUserOperationGas, alchemy_*).
- **Alchemy Gas Manager API** - JSON-RPC paymaster API for sponsoring ERC-4337 user operations with policy-based gas funding.
- **Alchemy Simulation API** - REST/JSON-RPC API for simulating transactions and asset changes before broadcasting.

## Tags
 - Web3, Blockchain, RPC, NFT, Indexing, Account Abstraction

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://www.alchemy.com/)
- [Plans](plans/alchemy-plans-pricing.yml)
- [RateLimits](rate-limits/alchemy-rate-limits.yml)
- [FinOps](finops/alchemy-finops.yml)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
