<picture>
<img width="512" height="512" alt="emerald basedbid logo with BG container2" src="https://github.com/user-attachments/assets/6deb4b52-c8af-4200-8e8d-61d2bdc96ea5" />
</picture>

[![X (Twitter)](https://img.shields.io/twitter/follow/basedbidx?style=flat&logo=x&label=follow&color=000000)](https://x.com/basedbidx)
[![Telegram](https://img.shields.io/badge/Telegram-join-26A5E4?style=flat&logo=telegram)](https://t.me/ThebasedInc)
[![Website](https://img.shields.io/badge/based.bid-live-00ff00?style=flat)](https://based.bid)
[![Docs](https://img.shields.io/badge/docs-gitbook-blue?style=flat)](https://basedinc.gitbook.io/basedbid)
[![OpenBid SDK](https://img.shields.io/badge/OpenBid-SDK-2ecc71?style=flat&logo=github)](https://github.com/basedbid-public/openbid)

# basedbid

### Programmable economies. Simple launches.

**Colosseum Crypto World's Fair 2026 submission**

**[Watch the pitch](https://youtu.be/F_rXVZ9Ck2E)** | **[Watch the product demo](https://youtu.be/xJ4ocTRwGzg)**

**Tokens launched on basedbid earn more trading fees, with creators choosing how to put them to work without selling the token.**

basedbid is live on mainnet across **Solana, Ethereum, Base, BNB Chain, Arc and Robinhood Chain**, with **300+ token launches, at least $2.5 million in trading volume and over $50,000 in fees generated for projects**.

These are cumulative platform figures, not competition-only activity or basedbid's own revenue.

Its **Fee Builder** lets creators configure trading fees and choose how revenue supports project funding, liquidity, treasury, buybacks, marketing and holder rewards. **Rewards Baskets** distribute supported tokens, tokenized stocks and ETFs to eligible holders, with **no sales of the launched token needed to fund distributions**.

Fee routes and basket settings can change without redeploying the token. Partners use the same infrastructure under their own brand instead of rebuilding the contracts and backend.

## Why we built it

Projects generate trading activity, but often have limited control over the revenue it creates. Some reward models sell project tokens to fund payouts, creating selling pressure. Fixed launch settings can also become a constraint as a project grows.

Teams building launchpads spend months on contracts, backend systems, integrations, testing and maintenance, with no guarantee that the finished technology will meet their needs.

basedbid gives creators configurable economics and gives partners reusable infrastructure.

## Launch your way

- **Flash Tokens:** Launch directly into DEX trading using virtual liquidity.
- **LBP:** Trade on basedbid until the target market cap is reached, then graduate to a supported DEX.
- **Pre-Launch:** Set a time limit, minimum and maximum funding goals, and the share of funds raised allocated to the creator. Tokens trade on basedbid before DEX graduation.

Choose **Standard or Pro** first. Standard is for quick Flash Token launches only. Pro provides the available launch types and deeper configuration, including Fee Builder and Rewards Basket options where supported.

## Put trading fees to work

The **Fee Builder** routes trading revenue to creator income, treasury, liquidity, buybacks, marketing, holder rewards and custom wallets.

Approved routes and receiving wallets can be updated after launch without redeploying the token.

The **Rewards Basket** lets creators choose supported assets, set allocations and configure holder eligibility and payout settings. Distributions can rotate through individual assets or pay across the basket simultaneously.

Trading fees fund distributions, not sales of the launched token.

*Launch types, DEXs, quote assets, reward assets and settings vary by network.*

## Build on basedbid

**Boards** provide branded launch environments for applications, communities and launchpad operators.

**Openbid, API, SDK and ABI** provide integration options for offering supported launch and fee-routing capabilities within an existing product.

Partners earn from launches under their brand according to the configured arrangements. basedbid earns a share of trading fees, including from launches through partner platforms.

[Explore the open-source Openbid SDK](https://github.com/basedbid-public/openbid)

## Traction and release status

We have **13+ backend API integration agreements**, with partners at different implementation stages. [Hooded](https://hooded.club/feed) is using our Openbid SDK, although its integration is still early.

The full release covers all six networks, bringing together a redesigned interface, easier configuration, expanded Rewards Basket options and easier access to our infrastructure.

**At submission on 12 October 2026**, [based.bid](https://www.based.bid/) hosts the existing mainnet beta. The submitted demo shows the updated full release, which is still undergoing final testing and is not yet publicly accessible. It will replace the beta on the same domain once ready. Updated contracts may be redeployed before release.

The team has worked together in crypto launch infrastructure for around five years and has self-funded development for over 15 months.

**Our goal is to become the default choice for launching a token or building a launchpad.**

## Prior work and competition-period development

basedbid and its mainnet beta existed before **14 September 2026**. The **Fee Builder and EVM Rewards Basket** were already built.

During this competition, we:

- Built the **Solana Rewards Basket**.
- Redesigned the **Solana Fee Builder**.
- Developed the **Pre-Launch** launch type.

The complete platform and historical traction should not be treated as work or usage created exclusively during the competition.

## Start here

- [Live platform](https://www.based.bid/)
- [Launch a token](https://www.based.bid/create)
- [Product guides](https://basedinc.gitbook.io/basedbid)
- [Openbid SDK](https://github.com/basedbid-public/openbid)
- [Pitch deck](https://www.based.bid/deck)
- [Contact the team](https://t.me/TheBasedInc)

## Submission materials

| Document | Purpose |
| --- | --- |
| [Submission](./SUBMISSION.md) | Submission overview |
| [How it works](./HOWITWORKS.md) | Product mechanics |
| [Team](./WHY_THIS_TEAM_CAN_WIN.md) | Team background |
| [Traction](./traction.md) | Adoption and progress |
| [Judge review path](./JUDGING.md) | Suggested review order |
| [Documentation](./docs/) | Architecture and product details |
| [Demo](./demo/) | Product walkthrough materials |
| [Metrics](./metrics/) | Supporting metrics |
| [Weekly updates](./Colosseum-Weekly-Updates/) | Build updates |

## Public code and production boundary

This repository contains public submission materials and product documentation. It is **not the complete production codebase**.

The public TypeScript SDK is maintained in [Openbid](https://github.com/basedbid-public/openbid). Full production contracts, private backend services, deployment infrastructure and internal tooling are not included here.

See [DISCLAIMER.md](./DISCLAIMER.md) and [the private-code boundary](./docs/private-code-boundary.md) for details.
