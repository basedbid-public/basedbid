# Judge review guide

A short guide to our **Colosseum Crypto World's Fair 2026 submission**.

basedbid powers token launches and branded launchpads across **Solana, Ethereum, Base, BNB Chain, Arc and Robinhood Chain**.

**Start with the development disclosure in [SUBMISSION.md](./SUBMISSION.md).** The existing platform predates the competition. Competition-period work comprises the Solana Rewards Basket, a redesign of the Solana Fee Builder and Pre-Launch.

## Suggested review order

1. [Product overview](./README.md): What basedbid does and who it serves.
2. [Submission summary](./SUBMISSION.md): Prior work, competition-period development, product and release scope.
3. [Product demo](./demo/Live-Product-walkthrough.md): The walkthrough and demo materials.
4. [Traction](./traction.md): Cumulative platform usage, infrastructure demand and integrations.
5. [Team](./WHY_THIS_TEAM_CAN_WIN.md): Our experience, roles and execution.
6. [How it works](./HOWITWORKS.md): Launch types, Fee Builder, Rewards Baskets and partner infrastructure.

## What makes basedbid different

- **Economics that can evolve:** Fee routes and Rewards Basket settings can change after launch without redeploying the token.
- **Rewards funded by trading fees:** No sales of the launched token are needed to fund distributions.
- **Infrastructure for other platforms:** Partners offer our capabilities through branded Boards or integrate them into existing products.
- **Multichain reach:** The full release covers all six supported networks.

## Technical review

[Openbid SDK](https://github.com/basedbid-public/openbid) is our public, open-source TypeScript SDK for developers integrating basedbid.

[Technical documentation](./docs/) explains the architecture and product components. [Weekly updates](./Colosseum-Weekly-Updates/) record project progress.

This repository contains submission materials and documentation, not the complete production codebase. Production contracts, private backend services and deployment infrastructure are not included here.

See [the private-code boundary](./docs/private-code-boundary.md) and [disclaimer](./DISCLAIMER.md) for details.

## Try the product

At submission, the primary domain hosts the existing mainnet beta. The submitted demo shows the updated full release, which is still undergoing final testing and is not yet publicly accessible. It will replace the beta on the same domain once ready. Updated contracts may be redeployed before release.

- [Live platform](https://www.based.bid/)
- [Launch interface](https://www.based.bid/create)
- [Product guides](https://basedinc.gitbook.io/basedbid)
