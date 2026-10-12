# Submission review notes

This page connects our submission to the questions raised in the draft review. It is our explanation of the evidence, not an official Colosseum score or endorsement.

## What existed before the competition

basedbid and its mainnet beta existed before **14 September 2026**. The Fee Builder and EVM Rewards Basket were already built.

During the competition, we built the **Solana Rewards Basket**, redesigned the **Solana Fee Builder** and developed **Pre-Launch**.

[Development disclosure and release status](../SUBMISSION.md)

## Usage and demand

Our cumulative platform milestones are **300+ token launches**, **at least $2.5 million in trading volume** and **over $50,000 in fees generated for projects**.

We have **13+ backend API integration agreements**, at different implementation stages. Hooded is using our Openbid SDK in an early integration.

These are distinct signals. Agreements are not completed deployments, and project fees are not basedbid's revenue.

[Traction](../traction.md) | [Metric definitions](../metrics/README.md)

## Why partners use the infrastructure

Partners can offer launches through Boards or integrate supported capabilities through Openbid instead of rebuilding the contracts, backend and DEX integrations.

Others could build similar functionality, but replicating and maintaining it across six networks could take months of engineering, integration and testing. Our Uniswap and PancakeSwap hook whitelisting reflects integration work beyond the interface.

Hooded provides an early SDK-adoption example, not proof of established partner revenue.

[Boards](./boards.md) | [Public SDK](https://github.com/basedbid-public/openbid)

## Business model

basedbid earns protocol fees from direct launches and partner launchpads, including ongoing trading activity. Current rates vary by launch type and network and will change for the full release.

We do not publish a platform-revenue total here. The project-fee milestone should not be used as a substitute.

[Current fee schedule](https://basedinc.gitbook.io/basedbid/fees)

## Team and execution

Redrum leads engineering, Michael leads partnerships, Seth leads growth and strategy, and Dante works on the SDK and integration tooling.

Our core team has around five years of shared launch-infrastructure experience. We have self-funded basedbid's development for over 15 months.

[Team background](../WHY_THIS_TEAM_CAN_WIN.md)

## How to review the product

At submission, the primary domain hosts the existing mainnet beta. The submitted demo shows the updated full release, still undergoing final testing. Updated contracts may be redeployed before release.

This repository contains documentation and submission materials, not the complete production implementation. The open-source SDK is maintained separately.

[Judge review guide](../JUDGING.md) | [Demo materials](../demo/) | [Architecture](./architecture.md) | [Code boundary](./private-code-boundary.md)
