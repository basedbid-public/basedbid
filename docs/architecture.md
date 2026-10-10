# Architecture overview

basedbid provides token-launch and fee-routing infrastructure across **Solana, Ethereum, Base, BNB Chain, Arc and Robinhood Chain**.

This is a product-level overview, not the complete production implementation. Contracts, DEX integrations and available settings differ by network.

## Access and partner integration

Creators use the basedbid interface directly. Communities and platforms offer branded launch environments through **Boards**, while developers integrate supported capabilities through **Openbid, API, SDK and ABI**.

Partners use the underlying infrastructure rather than rebuilding the launch contracts and backend.

## Launch infrastructure

Creators choose **Standard or Pro** before selecting their launch type.

- **Standard:** Quick Flash Token launches with minimal configuration.
- **Pro:** The available launch types and advanced settings, including Fee Builder and Rewards Basket options where supported.

The launch types are:

- **Flash Tokens:** Launch directly into DEX trading using virtual liquidity.
- **LBP:** Trade on basedbid until the target market cap is reached, then graduate to a supported DEX.
- **Pre-Launch:** Trade on basedbid before DEX graduation, with a configured time limit, minimum and maximum funding goals, and creator allocation from funds raised.

Boards add branding and partner fee arrangements to launches using the same infrastructure.

## Fee Builder

The Fee Builder configures how trading revenue supports creator income, treasury, liquidity, buybacks, marketing, holder rewards and custom wallets.

Fee routes and receiving wallets can change after launch without redeploying the token, subject to the applicable permissions and supported settings.

Fee Builder distributions do not require selling the launched token.

[Read the Fee Builder overview](./fee-builder.md)

## Rewards Basket

Creators select supported reward assets, configure allocations and set holder eligibility and payout settings.

Baskets can include supported tokens, tokenized stocks and ETFs. Payouts can rotate through individual assets or distribute across the basket simultaneously.

Trading fees fund the rewards without selling the launched token. Basket assets and allocations can evolve after launch without redeploying.

*Assets and functionality vary by network.*

## Network-specific implementation

The shared product experience is backed by network-specific contracts and DEX integrations.

On Solana, basedbid uses custom contracts with **Meteora DAMM v2**, not Meteora DBC. This is one implementation within the wider multichain system.

A supported feature on one network should not be assumed to exist on every other network.

## Example launch flow

1. Select Pro, then Flash Token.
2. Choose the network and enter token details.
3. Configure the supported DEX and quote asset.
4. Set Fee Builder routes and allocations.
5. Configure a Rewards Basket if using holder rewards.
6. Review, confirm in the wallet and launch.

After launch, authorised users can update supported fee routes and basket settings without redeploying the token.

[Explore the complete product flow](../HOWITWORKS.md)

## Public and private components

This repository contains submission materials and product documentation.

The [Openbid repository](https://github.com/basedbid-public/openbid) contains the public, open-source TypeScript SDK.

Production contracts, private backend services, deployment infrastructure and internal tooling are not included here. See [the private-code boundary](./private-code-boundary.md).
