# basedbid | Crypto World's Fair 2026 Submission

## Summary

basedbid powers token launches and branded launchpads across **Solana, Ethereum, Base, BNB Chain, Arc and Robinhood Chain**.

Its **Fee Builder** lets projects configure trading fees and choose how revenue supports creator income, treasury, liquidity, buybacks, marketing and holder rewards. **Rewards Baskets** distribute supported tokens, tokenized stocks and ETFs without selling the launched token to fund distributions.

Fee routes and basket settings can change without redeploying. Partners use the same infrastructure under their own brand instead of rebuilding it.

## Who it is for

- **Project creators:** Launch a token and configure how trading revenue supports the project and its holders.
- **Applications and communities:** Offer launches through a branded Board.
- **Launchpad operators and developers:** Integrate supported capabilities through Openbid, API, SDK and ABI.

## The problem

Projects create trading activity but often have limited control over the revenue it generates. Some reward models sell project tokens to fund payouts, creating selling pressure. Fixed launch economics can become a constraint as a project grows.

Teams building launchpads also spend months developing contracts, backend systems and integrations, only to find that the finished technology still falls short.

basedbid gives creators configurable economics and gives partners reusable infrastructure.

## The product

- **Flash Tokens:** Instant DEX launches using virtual liquidity.
- **Liquidity Bonding Pools:** Tokens trade on basedbid before graduating to a supported DEX under configured conditions.
- **Pre-Launch:** Creators set a time limit, minimum and maximum funding goals, and the share of funds raised allocated to them.
- **Fee Builder:** Configurable trading-fee routes, including receiving wallets that can be updated after launch.
- **Rewards Basket:** Selected supported assets, configurable allocations, holder eligibility, and rotating or simultaneous payouts.
- **Boards and Openbid:** Branded launch environments and integration options for external products.

Standard offers quick launches with minimum settings. Pro provides deeper configuration, including Fee Builder and Rewards Basket options where supported.

*Available launch types, DEXs, quote assets, reward assets and settings vary by network.*

## Full-release focus

The full release brings together:

- A complete visual overhaul and simpler navigation.
- Easier launch and fee configuration.
- Expanded multi-asset Rewards Basket functionality.
- Easier access to basedbid's infrastructure for partners.

The demo follows a Flash Token launch using the Fee Builder and Rewards Basket, showing how creators configure these features in one interface.

## Traction and business model

The existing mainnet platform has supported **millions in trading volume, hundreds of token launches and tens of thousands of dollars in fees generated for projects** across supported networks.

basedbid earns a share of trading fees, including from launches through partner platforms. Partner integrations provide distribution beyond basedbid's own interface.

The team has worked together in crypto launch infrastructure for around five years and has self-funded development for over 15 months.

Our goal is to become the default choice for launching a token or building a launchpad.

## Deployment status

The existing platform is live at [based.bid](https://www.based.bid/).

**As of 9 October 2026:** The updated Solana deployment has moved to mainnet for final testing. It will move to the primary domain once the final checks are complete. The primary-domain deployment should not be assumed to contain every feature in the release being tested.

## Review links

1. [README](./README.md): Product overview and navigation.
2. [Demo materials](./demo/): Product walkthrough.
3. [How it works](./HOWITWORKS.md): Product mechanics.
4. [Traction](./traction.md): Adoption and progress.
5. [Team](./WHY_THIS_TEAM_CAN_WIN.md): Background and experience.
6. [Weekly updates](./Colosseum-Weekly-Updates/): Build updates.
7. [Openbid SDK](https://github.com/basedbid-public/openbid): Public TypeScript SDK.
8. [GitBook](https://basedinc.gitbook.io/basedbid): Product and setup guides.

## Public and private code

This repository contains submission materials and product documentation, **not the full production implementation**. The public TypeScript SDK is maintained separately in [Openbid](https://github.com/basedbid-public/openbid).

Production contracts, private backend services, deployment infrastructure and internal tooling are not included here. See [DISCLAIMER.md](./DISCLAIMER.md) and [the private-code boundary](./docs/private-code-boundary.md).
