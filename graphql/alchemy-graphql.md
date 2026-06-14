# Alchemy GraphQL Schema

This conceptual GraphQL schema models the Alchemy Web3 developer platform, covering the full surface of Alchemy's blockchain APIs: Node RPC (JSON-RPC over HTTPS/WebSockets), NFT API, Token API, Transfers API, Portfolio API, Prices API, Webhooks/Notify, Transaction Simulation, Bundler (ERC-4337), and Gas Manager.

Alchemy does not currently expose a native GraphQL endpoint. This schema is a conceptual representation derived from Alchemy's REST and JSON-RPC APIs, intended for tooling, federation, and API research purposes.

## Source

- Documentation: https://docs.alchemy.com/
- API Reference: https://www.alchemy.com/docs/reference/api-overview

## Coverage

The schema covers the following Alchemy product areas:

- **Node RPC**: Network, Block, Transaction, Log, Address, GasPrice, Subscription
- **NFT API**: NFT, NFTMetadata, NFTMedia, NFTAttribute, NFTCollection, FloorPrice, Ownership
- **Token API**: Token, TokenBalance, TokenMetadata, TokenTransfer, TokenPrice
- **Transfers API**: Transfer, TransferType, TransferDetails
- **Portfolio API**: Portfolio, WalletAssets
- **Prices API**: PriceData, PriceHistory
- **Webhooks/Notify**: Webhook, WebhookEvent, WebhookType, Notification, Filter
- **Simulation API**: TransactionSimulation, SimulationResult, AssetChange
- **Bundler / ERC-4337**: UserOperation, UserOperationReceipt, PackedUserOperation
- **Gas Manager**: GasPolicy, GasPolicyDetails, Paymaster
- **Auth / Keys**: APIKey, AccessKey

## Type Count

The schema defines 70 named types (scalars, enums, input types, and object types).

## Schema File

See `alchemy-schema.graphql` in this directory for the full schema definition.
