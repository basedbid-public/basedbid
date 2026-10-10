# How basedbid works

basedbid combines **token launches, programmable trading-fee routing and multi-asset holder rewards** with infrastructure that partners can use under their own brand.

It supports **Solana, Ethereum, Base, BNB Chain, Arc and Robinhood Chain**. Available launch types, DEXs, assets and settings vary by network.

## 1. Choose Standard or Pro

Choose the interface mode before choosing your launch type.

**Standard** is for Flash Tokens only. It keeps the launch quick, with minimum settings and token details such as name, symbol and logo.

**Pro** provides access to the available launch types and deeper configuration, including supported quote assets, DEX settings, Fee Builder routes, Rewards Baskets and initial-buy options.

A Standard quick launch is not the same as a Pro launch with the Fee Builder configured. The walkthrough below describes the Pro Fee Builder flow.

## 2. Choose a launch type

### Flash Tokens

Flash Tokens launch directly into DEX trading using virtual liquidity. They do not require a bonding-curve graduation stage.

Creators select the supported network and launch configuration. In Pro, they can configure trading fees and supported Fee Builder routes before launching.

### Liquidity Bonding Pools

Liquidity Bonding Pools trade on basedbid before graduating to a supported DEX.

Creators configure the available launch parameters and graduation target. Once the applicable graduation conditions are met, liquidity migrates to the selected DEX.

### Pre-Launch

Pre-Launch tokens also trade on basedbid before DEX graduation. Creators configure:

- A time limit.
- A minimum funding goal.
- A maximum funding goal.
- The share of funds raised allocated to the creator.

This provides a launch-stage funding option alongside the trading-fee settings available for the configuration.

*The time limit and funding goals are distinct from an LBP's market-cap graduation target. Exact graduation, migration and unsuccessful-launch handling must follow the applicable deployed configuration.*

## 3. Configure the Fee Builder

The Fee Builder determines how trading revenue is allocated. Creators choose which routes to enable and how much goes to each.

| Route | Purpose |
| --- | --- |
| Creator income | Revenue sent to the creator's receiving wallet |
| Treasury | Funding for project operations or reserves |
| Liquidity | Revenue allocated to liquidity support |
| Buybacks | Revenue used to buy back the launched token |
| Holder rewards | Funding for eligible holders, including supported Rewards Basket configurations |
| Marketing | Funding sent to a designated marketing wallet |
| Custom wallets | Allocations to other selected recipients |

Allocations must fit within the fee budget shown in the interface. Network and DEX configurations can differ, so the trading-fee total, platform share and project allocations should not be treated as one universal fee schedule.

**No sales of the launched token are needed to fund Fee Builder or Rewards Basket distributions.** This describes the source of distribution funding; it does not prevent ordinary trading, guarantee price performance or eliminate all selling pressure.

## 4. Configure a Rewards Basket

The Rewards Basket is a holder-reward route within the Fee Builder.

Creators allocate trading fees to rewards, then select supported assets. Depending on the network, these can include tokens, tokenized stocks, ETFs and other available assets.

The configuration includes:

- **Assets:** Which supported assets holders receive.
- **Allocations:** The share assigned to each asset, using custom weights or an equal split.
- **Holder eligibility:** The minimum holding requirement for participation.
- **Payout mode:** Rotate through individual assets or distribute across the basket simultaneously.
- **Distribution settings:** Configure the available payout options and collected-fee trigger.

Holder eligibility and the distribution trigger are different settings: one determines who qualifies, while the other determines when collected fees are distributed.

A basket shown in the interface demonstrates its configuration, not proof that a payout has occurred. A completed distribution should be verified through its onchain transaction.

## 5. Review and launch

For a Flash Token launch using the Fee Builder:

1. Select Pro, then choose the Flash Token launch type.
2. Select the network and enter the token details.
3. Choose the supported quote asset, DEX and trading-fee settings.
4. Enable Fee Builder routes and set their allocations.
5. Configure Rewards Basket assets, eligibility and payouts if using holder rewards.
6. Review the settings and displayed costs.
7. Confirm the launch in the wallet.
8. Open the basedbid token-detail page and verify the launch transaction.

Trading activity then generates fees under the configured rules. Distribution follows the applicable routing and payout settings.

[Open the launch interface](https://www.based.bid/create)

## 6. Update the configuration after launch

Authorised creators can update supported fee routes, receiving wallets and Rewards Basket settings **without redeploying the token**.

For example, a project can change its revenue allocations as its priorities develop or update the assets used for holder rewards.

This does not mean every launch parameter is editable. Changes remain subject to the permissions and options supported by the deployed contracts.

## 7. Offer the same technology under your own brand

### Boards

Boards provide branded launch environments for applications, communities and launchpad operators.

Board owners can configure branding, permissions and available fee arrangements. Projects launch under the Board's brand, with creator and Board revenue determined by the configured arrangements.

### Openbid integrations

External products can use **Openbid, API, SDK and ABI** to integrate supported launch and fee-routing functionality into their own interface.

Partners do not need to rebuild the complete contracts and backend. basedbid earns a share of trading fees, including from launches through partner platforms.

[Explore the public Openbid SDK](https://github.com/basedbid-public/openbid)

## Network-specific implementation

The user-facing configuration brings together different execution environments. Contracts, DEX integrations, supported assets and fee behaviour depend on the selected network.

On Solana, basedbid uses custom contracts and **Meteora DAMM v2**, not Meteora DBC. This is a Solana implementation detail, not a description of the full multichain system.

Use the current interface and [GitBook guides](https://basedinc.gitbook.io/basedbid) for the options available to a particular launch.

## Deployment and source-code scope

The existing platform is live on mainnet. Updated release features may be in final testing before they are available on the primary domain. See [SUBMISSION.md](./SUBMISSION.md) for the dated deployment status.

This document explains product mechanics; it is not the full contract specification or a security audit. The complete production implementation is private, while the public TypeScript SDK is available in Openbid.

See [DISCLAIMER.md](./DISCLAIMER.md) and [the private-code boundary](./docs/private-code-boundary.md).
