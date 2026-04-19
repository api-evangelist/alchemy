# Alchemy (alchemy)
Alchemy is a Web3 developer platform providing powerful APIs, SDKs, and infrastructure tools to build and scale blockchain applications. Supporting Ethereum, Polygon, and other EVM-compatible networks, Alchemy powers production dApps with reliable node infrastructure, enhanced APIs for token data, asset transfers, NFTs, and ERC-4337 Account Abstraction tools including gas sponsorship (Gas Manager) and smart account bundling.

**URL:** [https://raw.githubusercontent.com/api-evangelist/alchemy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/alchemy/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Blockchain, Cryptocurrency, Web3, Account Abstraction, Ethereum

## Timestamps

- **Created:** 2024-11-07T00:00:00.000Z
- **Modified:** 2026-04-19

## APIs

### Alchemy Gas Manager API
The Alchemy Gas Manager API enables developers to sponsor gas fees for end users via the ERC-4337 Account Abstraction standard. Manage sponsorship policies with per-user spend limits, total caps, allowlisted contracts, and time-based expiry, enabling gasless transactions for dApp users.

**Human URL:** [https://www.alchemy.com/gas-manager](https://www.alchemy.com/gas-manager)

#### Tags:

 - Gas Manager, Account Abstraction, ERC-4337

#### Properties

- [OpenAPI](openapi/alchemy-gas-manager-api-openapi.yml)
- [JSONSchema](json-schema/alchemy-gas-manager-api-policy-schema.json)
- [JSONSchema](json-schema/alchemy-gas-manager-api-policy-list-response-schema.json)
- [JSONSchema](json-schema/alchemy-gas-manager-api-create-policy-request-schema.json)
- [JSONSchema](json-schema/alchemy-gas-manager-api-sponsor-user-operation-request-schema.json)
- [JSONSchema](json-schema/alchemy-gas-manager-api-sponsor-user-operation-result-schema.json)
- [JSONSchema](json-schema/alchemy-gas-manager-api-sponsor-user-operation-response-schema.json)
- [JSONStructure](json-structure/alchemy-gas-manager-api-policy-structure.json)
- [JSONStructure](json-structure/alchemy-gas-manager-api-policy-list-response-structure.json)
- [JSONStructure](json-structure/alchemy-gas-manager-api-create-policy-request-structure.json)
- [JSONStructure](json-structure/alchemy-gas-manager-api-sponsor-user-operation-request-structure.json)
- [JSONStructure](json-structure/alchemy-gas-manager-api-sponsor-user-operation-result-structure.json)
- [JSONStructure](json-structure/alchemy-gas-manager-api-sponsor-user-operation-response-structure.json)
- [JSON-LD](json-ld/alchemy-gas-manager-api-context.jsonld)
- [Example](examples/alchemy-gas-manager-api-policy-example.json)
- [Example](examples/alchemy-gas-manager-api-policy-list-response-example.json)
- [Example](examples/alchemy-gas-manager-api-create-policy-request-example.json)
- [Example](examples/alchemy-gas-manager-api-sponsor-user-operation-request-example.json)
- [Example](examples/alchemy-gas-manager-api-sponsor-user-operation-result-example.json)
- [Example](examples/alchemy-gas-manager-api-sponsor-user-operation-response-example.json)

### Alchemy Token API
The Alchemy Token API provides comprehensive access to ERC-20 token data across EVM-compatible networks. Retrieve token balances by wallet address, token metadata (name, symbol, decimals, logo), and real-time pricing data. Supports multi-chain queries for wallets, portfolio trackers, and DeFi applications.

**Human URL:** [https://www.alchemy.com/token-api](https://www.alchemy.com/token-api)

#### Tags:

 - Tokens, ERC-20, DeFi

#### Properties

- [OpenAPI](openapi/alchemy-token-api-openapi.yml)
- [JSONSchema](json-schema/alchemy-token-api-token-balance-schema.json)
- [JSONSchema](json-schema/alchemy-token-api-token-balances-result-schema.json)
- [JSONSchema](json-schema/alchemy-token-api-token-balances-response-schema.json)
- [JSONSchema](json-schema/alchemy-token-api-token-metadata-schema.json)
- [JSONSchema](json-schema/alchemy-token-api-token-metadata-response-schema.json)
- [JSONStructure](json-structure/alchemy-token-api-token-balance-structure.json)
- [JSONStructure](json-structure/alchemy-token-api-token-balances-result-structure.json)
- [JSONStructure](json-structure/alchemy-token-api-token-balances-response-structure.json)
- [JSONStructure](json-structure/alchemy-token-api-token-metadata-structure.json)
- [JSONStructure](json-structure/alchemy-token-api-token-metadata-response-structure.json)
- [JSON-LD](json-ld/alchemy-token-api-context.jsonld)
- [Example](examples/alchemy-token-api-token-balance-example.json)
- [Example](examples/alchemy-token-api-token-balances-result-example.json)
- [Example](examples/alchemy-token-api-token-balances-response-example.json)
- [Example](examples/alchemy-token-api-token-metadata-example.json)
- [Example](examples/alchemy-token-api-token-metadata-response-example.json)

### Alchemy Transfers API
The Alchemy Transfers API provides access to historical on-chain transfer data across EVM-compatible networks. Query asset transfers by address, block range, and transfer category (ETH, ERC-20, ERC-721, ERC-1155, and internal transfers), enabling wallet activity tracking, portfolio history, and transaction auditing.

**Human URL:** [https://www.alchemy.com/transfers-api](https://www.alchemy.com/transfers-api)

#### Tags:

 - Transfers, NFTs, Transaction History

#### Properties

- [OpenAPI](openapi/alchemy-transfers-api-openapi.yml)
- [JSONSchema](json-schema/alchemy-transfers-api-asset-transfer-schema.json)
- [JSONSchema](json-schema/alchemy-transfers-api-transfer-metadata-schema.json)
- [JSONSchema](json-schema/alchemy-transfers-api-asset-transfers-result-schema.json)
- [JSONSchema](json-schema/alchemy-transfers-api-asset-transfers-response-schema.json)
- [JSONStructure](json-structure/alchemy-transfers-api-asset-transfer-structure.json)
- [JSONStructure](json-structure/alchemy-transfers-api-transfer-metadata-structure.json)
- [JSONStructure](json-structure/alchemy-transfers-api-asset-transfers-result-structure.json)
- [JSONStructure](json-structure/alchemy-transfers-api-asset-transfers-response-structure.json)
- [JSON-LD](json-ld/alchemy-transfers-api-context.jsonld)
- [Example](examples/alchemy-transfers-api-asset-transfer-example.json)
- [Example](examples/alchemy-transfers-api-transfer-metadata-example.json)
- [Example](examples/alchemy-transfers-api-asset-transfers-result-example.json)
- [Example](examples/alchemy-transfers-api-asset-transfers-response-example.json)

### Alchemy Bundler API
The Alchemy Bundler API implements the ERC-4337 Account Abstraction bundler standard, allowing UserOperations to be submitted to the blockchain.

**Human URL:** [https://www.alchemy.com/bundler](https://www.alchemy.com/bundler)

#### Tags:

 - Bundler, Account Abstraction, ERC-4337

## Common Properties

- [Pricing](https://www.alchemy.com/pricing)
- [Sandbox](https://www.alchemy.com/sandbox)
- [Webhooks](https://www.alchemy.com/webhooks)
- [SDKs](https://www.alchemy.com/sdk)
- [Blog](https://www.alchemy.com/blog)
- [PostmanWorkspace](https://www.postman.com/alchemyapi/alchemy-platforms/overview)
- [Documentation](https://docs.alchemy.com)
- [Support](https://www.alchemy.com/support)
- [SignUp](https://dashboard.alchemy.com/signup)
- [StatusPage](https://status.alchemy.com)
- [GitHubOrganization](https://github.com/alchemyplatform)

## Features

| Name | Description |
|------|-------------|
| Multi-Chain Support | Query token data and transfers across Ethereum, Polygon, and other EVM-compatible networks. |
| ERC-4337 Account Abstraction | Full support for ERC-4337 with bundler, paymaster (Gas Manager), and smart account APIs. |
| Gasless Transactions | Sponsor gas fees for end users via Gas Manager policies with spend limits and network rules. |
| Token Data | Real-time ERC-20 token balances and metadata including name, symbol, decimals, and logo. |
| Transfer History | Historical on-chain transfer data for ETH, ERC-20, ERC-721, and ERC-1155 assets. |
| JSON-RPC Compatibility | Standard Ethereum JSON-RPC interface with Alchemy-enhanced methods for additional data. |
| Webhook Notifications | Real-time blockchain event notifications via webhooks for address activity and mined transactions. |

## Use Cases

| Name | Description |
|------|-------------|
| Wallet Application Development | Build EVM wallets with real-time token balances, transaction history, and NFT support. |
| DeFi Portfolio Tracking | Track multi-asset portfolios across EVM networks with accurate token pricing and balances. |
| Gasless dApp UX | Abstract gas fees from end users so they can interact with dApps without holding ETH. |
| NFT Marketplace Integration | Query ERC-721 and ERC-1155 transfer history for NFT ownership tracking and provenance. |
| Blockchain Analytics | Analyze on-chain transfer patterns, wallet activity, and token flow across EVM networks. |

## Integrations

| Name | Description |
|------|-------------|
| Ethereum | Native support for Ethereum mainnet and testnets. |
| Polygon | Full API support for Polygon (MATIC) mainnet and Mumbai testnet. |
| ERC-4337 Bundlers | Works with any ERC-4337 compatible bundler for UserOperation submission. |
| MetaMask | Integration with MetaMask wallet for Web3 connection management. |
| Hardhat and Foundry | Developer toolchain integration for local testing and deployment. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Alchemy Gas Manager API](openapi/alchemy-gas-manager-api-openapi.yml)
- [Alchemy Token API](openapi/alchemy-token-api-openapi.yml)
- [Alchemy Transfers API](openapi/alchemy-transfers-api-openapi.yml)

### JSON Schema

- [Gas Manager Policy](json-schema/alchemy-gas-manager-api-policy-schema.json)
- [Gas Manager Policy List Response](json-schema/alchemy-gas-manager-api-policy-list-response-schema.json)
- [Gas Manager Create Policy Request](json-schema/alchemy-gas-manager-api-create-policy-request-schema.json)
- [Gas Manager Sponsor User Operation Request](json-schema/alchemy-gas-manager-api-sponsor-user-operation-request-schema.json)
- [Gas Manager Sponsor User Operation Result](json-schema/alchemy-gas-manager-api-sponsor-user-operation-result-schema.json)
- [Gas Manager Sponsor User Operation Response](json-schema/alchemy-gas-manager-api-sponsor-user-operation-response-schema.json)
- [Token Balance](json-schema/alchemy-token-api-token-balance-schema.json)
- [Token Balances Result](json-schema/alchemy-token-api-token-balances-result-schema.json)
- [Token Balances Response](json-schema/alchemy-token-api-token-balances-response-schema.json)
- [Token Metadata](json-schema/alchemy-token-api-token-metadata-schema.json)
- [Token Metadata Response](json-schema/alchemy-token-api-token-metadata-response-schema.json)
- [Asset Transfer](json-schema/alchemy-transfers-api-asset-transfer-schema.json)
- [Transfer Metadata](json-schema/alchemy-transfers-api-transfer-metadata-schema.json)
- [Asset Transfers Result](json-schema/alchemy-transfers-api-asset-transfers-result-schema.json)
- [Asset Transfers Response](json-schema/alchemy-transfers-api-asset-transfers-response-schema.json)

### JSON Structure

- [Gas Manager Policy](json-structure/alchemy-gas-manager-api-policy-structure.json)
- [Gas Manager Policy List Response](json-structure/alchemy-gas-manager-api-policy-list-response-structure.json)
- [Gas Manager Create Policy Request](json-structure/alchemy-gas-manager-api-create-policy-request-structure.json)
- [Gas Manager Sponsor User Operation Request](json-structure/alchemy-gas-manager-api-sponsor-user-operation-request-structure.json)
- [Gas Manager Sponsor User Operation Result](json-structure/alchemy-gas-manager-api-sponsor-user-operation-result-structure.json)
- [Gas Manager Sponsor User Operation Response](json-structure/alchemy-gas-manager-api-sponsor-user-operation-response-structure.json)
- [Token Balance](json-structure/alchemy-token-api-token-balance-structure.json)
- [Token Balances Result](json-structure/alchemy-token-api-token-balances-result-structure.json)
- [Token Balances Response](json-structure/alchemy-token-api-token-balances-response-structure.json)
- [Token Metadata](json-structure/alchemy-token-api-token-metadata-structure.json)
- [Token Metadata Response](json-structure/alchemy-token-api-token-metadata-response-structure.json)
- [Asset Transfer](json-structure/alchemy-transfers-api-asset-transfer-structure.json)
- [Transfer Metadata](json-structure/alchemy-transfers-api-transfer-metadata-structure.json)
- [Asset Transfers Result](json-structure/alchemy-transfers-api-asset-transfers-result-structure.json)
- [Asset Transfers Response](json-structure/alchemy-transfers-api-asset-transfers-response-structure.json)

### JSON-LD

- [Gas Manager API Context](json-ld/alchemy-gas-manager-api-context.jsonld)
- [Token API Context](json-ld/alchemy-token-api-context.jsonld)
- [Transfers API Context](json-ld/alchemy-transfers-api-context.jsonld)

### Examples

- [Gas Manager Policy Example](examples/alchemy-gas-manager-api-policy-example.json)
- [Gas Manager Policy List Response Example](examples/alchemy-gas-manager-api-policy-list-response-example.json)
- [Gas Manager Create Policy Request Example](examples/alchemy-gas-manager-api-create-policy-request-example.json)
- [Gas Manager Sponsor User Operation Request Example](examples/alchemy-gas-manager-api-sponsor-user-operation-request-example.json)
- [Gas Manager Sponsor User Operation Result Example](examples/alchemy-gas-manager-api-sponsor-user-operation-result-example.json)
- [Gas Manager Sponsor User Operation Response Example](examples/alchemy-gas-manager-api-sponsor-user-operation-response-example.json)
- [Token Balance Example](examples/alchemy-token-api-token-balance-example.json)
- [Token Balances Result Example](examples/alchemy-token-api-token-balances-result-example.json)
- [Token Balances Response Example](examples/alchemy-token-api-token-balances-response-example.json)
- [Token Metadata Example](examples/alchemy-token-api-token-metadata-example.json)
- [Token Metadata Response Example](examples/alchemy-token-api-token-metadata-response-example.json)
- [Asset Transfer Example](examples/alchemy-transfers-api-asset-transfer-example.json)
- [Transfer Metadata Example](examples/alchemy-transfers-api-transfer-metadata-example.json)
- [Asset Transfers Result Example](examples/alchemy-transfers-api-asset-transfers-result-example.json)
- [Asset Transfers Response Example](examples/alchemy-transfers-api-asset-transfers-response-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Alchemy Gas Manager API](capabilities/shared/gas-manager-api.yaml) — 4 operations for gas sponsorship policy management and ERC-4337 paymaster
- [Alchemy Token API](capabilities/shared/token-api.yaml) — 2 operations for ERC-20 token balance and metadata queries
- [Alchemy Transfers API](capabilities/shared/transfers-api.yaml) — 1 operation for historical on-chain transfer data

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Web3 Wallet Portfolio](capabilities/web3-wallet-portfolio.yaml) | Token API, Transfers API | 3 | Wallet Developer, DeFi Builder |
| [Gasless Transaction Management](capabilities/gasless-transaction-management.yaml) | Gas Manager API | 4 | dApp Developer, Web3 Platform Engineer |

## Vocabulary

- [Alchemy Vocabulary](vocabulary/alchemy-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 4 actions, 2 workflows, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Alchemy Spectral Rules](rules/alchemy-spectral-rules.yml) — 35 rules across 13 categories enforcing Alchemy API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
