# Alchemy (alchemy)

Alchemy is a Web3 developer platform offering blockchain JSON-RPC, Data APIs (NFT, Token, Transfers, Portfolio, Prices, Webhooks/Notify, Simulation), Smart Wallets / Account Abstraction (Bundler, Gas Manager), and dedicated Rollup infrastructure across 50+ chains including Ethereum, Polygon, Arbitrum, Optimism, Base, and Solana.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/alchemy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/alchemy/refs/heads/main/apis.yml)

## Tags

- Web3
- Blockchain
- RPC
- NFT
- Indexing
- Account Abstraction

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-29

## APIs

### Alchemy Node API (JSON-RPC)

Multi-chain JSON-RPC over HTTPS and WebSockets covering standard eth_*, solana, and other chain methods, plus Alchemy-enhanced subscriptions (alchemy_minedTransactions, alchemy_pendingTransactions).

- **Human URL:** [https://www.alchemy.com/docs/reference/api-overview](https://www.alchemy.com/docs/reference/api-overview)
- **Base URL:** `https://{network}.g.alchemy.com/v2/{apiKey}`

#### Tags

- JSON-RPC
- WebSocket
- Multi-chain

#### Properties

- [Documentation](https://www.alchemy.com/docs/reference/api-overview)
- [AsyncAPI](asyncapi/alchemy-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/alchemy-gas-manager-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-gas-manager-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/alchemy-token-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-token-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/alchemy-transfers-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-transfers-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Alchemy NFT API

REST endpoints for NFT ownership, metadata, floor price, sales, contract metadata, and transfers across EVM chains and Solana.

- **Human URL:** [https://www.alchemy.com/docs/reference/nft-api-quickstart](https://www.alchemy.com/docs/reference/nft-api-quickstart)
- **Base URL:** `https://{network}.g.alchemy.com/nft/v3/{apiKey}`

#### Tags

- REST
- NFT

#### Properties

- [Documentation](https://www.alchemy.com/docs/reference/nft-api-quickstart)
- [Postman Collection](collections/alchemy-gas-manager-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-gas-manager-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/alchemy-token-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-token-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/alchemy-transfers-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-transfers-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Alchemy Token API

REST endpoints for ERC-20 token balances, metadata, allowances, prices, and historical transfers.

- **Human URL:** [https://www.alchemy.com/docs/reference/token-api-quickstart](https://www.alchemy.com/docs/reference/token-api-quickstart)
- **Base URL:** `https://{network}.g.alchemy.com/v2/{apiKey}`

#### Tags

- REST
- Token

#### Properties

- [Documentation](https://www.alchemy.com/docs/reference/token-api-quickstart)
- [OpenAPI](openapi/alchemy-token-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/alchemy-token-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-token-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Alchemy Transfers API

REST endpoints for paginated address-level transfer history (external, internal, ERC-20, ERC-721, ERC-1155).

- **Human URL:** [https://www.alchemy.com/docs/reference/transfers-api-quickstart](https://www.alchemy.com/docs/reference/transfers-api-quickstart)
- **Base URL:** `https://{network}.g.alchemy.com/v2/{apiKey}`

#### Tags

- REST
- Transfers

#### Properties

- [Documentation](https://www.alchemy.com/docs/reference/transfers-api-quickstart)
- [OpenAPI](openapi/alchemy-transfers-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/alchemy-transfers-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-transfers-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Alchemy Portfolio API

REST endpoints aggregating multi-chain wallet balances, NFTs, and tokens in a single call.

- **Human URL:** [https://www.alchemy.com/docs/reference/portfolio-api-quickstart](https://www.alchemy.com/docs/reference/portfolio-api-quickstart)
- **Base URL:** `https://api.g.alchemy.com/data/v1/{apiKey}`

#### Tags

- REST
- Portfolio

#### Properties

- [Documentation](https://www.alchemy.com/docs/reference/portfolio-api-quickstart)
- [Postman Collection](collections/alchemy-gas-manager-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-gas-manager-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/alchemy-token-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-token-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/alchemy-transfers-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-transfers-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Alchemy Prices API

REST endpoints for token spot and historical pricing.

- **Human URL:** [https://www.alchemy.com/docs/reference/prices-api-quickstart](https://www.alchemy.com/docs/reference/prices-api-quickstart)
- **Base URL:** `https://api.g.alchemy.com/prices/v1/{apiKey}`

#### Tags

- REST
- Prices

#### Properties

- [Documentation](https://www.alchemy.com/docs/reference/prices-api-quickstart)
- [Postman Collection](collections/alchemy-gas-manager-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-gas-manager-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/alchemy-token-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-token-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/alchemy-transfers-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-transfers-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Alchemy Webhooks (Notify)

REST API for managing webhook subscriptions (mined / dropped transactions, address activity, NFT activity, custom).

- **Human URL:** [https://www.alchemy.com/docs/reference/notify-api-quickstart](https://www.alchemy.com/docs/reference/notify-api-quickstart)
- **Base URL:** `https://dashboard.alchemy.com/api`

#### Tags

- REST
- Webhooks

#### Properties

- [Documentation](https://www.alchemy.com/docs/reference/notify-api-quickstart)
- [Postman Collection](collections/alchemy-gas-manager-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-gas-manager-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/alchemy-token-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-token-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/alchemy-transfers-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-transfers-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Alchemy Bundler API (ERC-4337)

JSON-RPC bundler endpoints for ERC-4337 user operations (eth_sendUserOperation, eth_estimateUserOperationGas, alchemy_*).

- **Human URL:** [https://www.alchemy.com/docs/reference/bundler-api-quickstart](https://www.alchemy.com/docs/reference/bundler-api-quickstart)
- **Base URL:** `https://{network}.g.alchemy.com/v2/{apiKey}`

#### Tags

- JSON-RPC
- ERC-4337
- Account Abstraction

#### Properties

- [Documentation](https://www.alchemy.com/docs/reference/bundler-api-quickstart)
- [Postman Collection](collections/alchemy-gas-manager-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-gas-manager-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/alchemy-token-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-token-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/alchemy-transfers-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-transfers-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Alchemy Gas Manager API

JSON-RPC paymaster API for sponsoring ERC-4337 user operations with policy-based gas funding.

- **Human URL:** [https://www.alchemy.com/docs/reference/gas-manager-api-quickstart](https://www.alchemy.com/docs/reference/gas-manager-api-quickstart)
- **Base URL:** `https://manage.g.alchemy.com/api/gasManager/policy`

#### Tags

- JSON-RPC
- Paymaster
- Account Abstraction

#### Properties

- [Documentation](https://www.alchemy.com/docs/reference/gas-manager-api-quickstart)
- [OpenAPI](openapi/alchemy-gas-manager-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/alchemy-gas-manager-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-gas-manager-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Alchemy Simulation API

REST/JSON-RPC API for simulating transactions and asset changes before broadcasting.

- **Human URL:** [https://www.alchemy.com/docs/reference/transaction-simulation-api-quickstart](https://www.alchemy.com/docs/reference/transaction-simulation-api-quickstart)
- **Base URL:** `https://{network}.g.alchemy.com/v2/{apiKey}`

#### Tags

- JSON-RPC
- Simulation

#### Properties

- [Documentation](https://www.alchemy.com/docs/reference/transaction-simulation-api-quickstart)
- [Postman Collection](collections/alchemy-gas-manager-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-gas-manager-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/alchemy-token-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-token-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/alchemy-transfers-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alchemy-transfers-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/alchemyplatform)
- [LinkedIn](https://www.linkedin.com/company/alchemyinc)
- [Website](https://www.alchemy.com/)
- [Plans](plans/alchemy-plans-pricing.yml)
- [Rate Limits](rate-limits/alchemy-rate-limits.yml)
- [Fin Ops](finops/alchemy-finops.yml)
- [Integrations](https://www.alchemy.com/integrations)
- [L L Ms Txt](https://alchemy.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
