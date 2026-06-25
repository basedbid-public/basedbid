<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/1cded765-3fb0-4599-af25-6396b4434319" />
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/bd8ca2a7-8ee8-4970-8150-8b074b7bb751" />
  <img src="https://github.com/user-attachments/assets/1cded765-3fb0-4599-af25-6396b4434319" alt="basedbid logo" width="601" height="331" />
</picture>

[![X (Twitter)](https://img.shields.io/twitter/follow/basedbidx?style=flat&logo=x&label=follow&color=000000)](https://x.com/basedbidx)
[![Telegram](https://img.shields.io/badge/Telegram-join-26A5E4?style=flat&logo=telegram)](https://t.me/ThebasedInc)
[![Website](https://img.shields.io/badge/based.bid-live-00ff00?style=flat)](https://based.bid)
[![Docs](https://img.shields.io/badge/docs-gitbook-blue?style=flat)](https://basedinc.gitbook.io/basedbid)
[![OpenBid SDK](https://img.shields.io/badge/OpenBid-SDK-2ecc71?style=flat&logo=github)](https://github.com/basedbid-public/openbid)

# basedbid

> Programmable token launch infrastructure for instant launches, Liquidity Bonding Pools, and creator-owned Boards.

**Colosseum Frontier Hackathon 2026 submission**

**BNB Ecosystem:** basedbid supports BNB Chain, also known as BNB Smart Chain or BSC, with native BNB fee routing for token launches, Pools, Flash Tokens, and Boards.

---

## Summary

basedbid lets builders, creators, KOLs, communities, and incubators launch tokens or Liquidity Bonding Pools while defining how trading fees are routed across creators, communities, KOLs, rewards, buybacks, marketing, liquidity, and treasury destinations.

Launches should not be one-time extraction events. They should become programmable economic infrastructure for the people who create, distribute, and support them.

boards, pools, token launches, and OpenBid support are live on mainnet.

---

## The problem

Token launch infrastructure is structurally misaligned.

Creators launch tokens, graduate to DEXs, and are often left with little or no sustainable post-launch revenue.

Common problems include:

- platforms capturing most of the economics;
- creators lacking recurring revenue;
- KOLs being paid in tokens and forced to sell;
- tax-token models accumulating supply and creating batch-selling pressure;
- static launch contracts that are hard to evolve after deployment.

basedbid is designed to address these problems through programmable launch infrastructure, configurable fee routing, and Board-based distribution ownership.

---

## What basedbid provides

### Pools

Liquidity Bonding Pools with configurable launch parameters, custom market caps, fee routing, and project-controlled economics.

### Flash Tokens

Instant token launches using virtual liquidity, designed to reduce capital requirements and time-to-market.

### Boards

White-label launch environments for KOLs, communities, agencies, incubators, and builder groups.

A Board can define launch rules, branding, permissions, fee defaults, market cap parameters, DEX preferences, and revenue structures.

### Fee Builder

Programmable fee routing across multiple recipients, including creators, KOLs, marketing wallets, rewards, buybacks, liquidity, and treasuries.

---

## Fee Builder flow

Fee Builder lets projects define how trading fees are routed across multiple recipients such as creators, KOLs, rewards, marketing, buybacks, liquidity, and treasuries.

<p align="center">
  <img width="1440" height="896" alt="basedbid Fee Builder flow" src="https://github.com/user-attachments/assets/271ed1d4-ac74-48ff-8d7f-e5e2e75e010f" />
</p>

Instead of treating launch fees as a single protocol-owned revenue stream, basedbid is designed around programmable fee allocation. Multiple stakeholders can earn from the same launch according to the rules configured by the creator, Board, or future governance structure.

---

## Why Boards matter

Boards turn distribution into infrastructure.

Instead of a KOL, community, or agency promoting launches for one-time payments, they can own a programmable launch environment and earn recurring on-chain revenue from projects launched through that Board.

This creates a new model for:

- KOLs;
- incubators;
- launch agencies;
- communities;
- DAOs;
- builder groups.

---

## Open-source technical companion

The open-source SDK lives in a separate repository for cleanliness:

**OpenBid SDK:** https://github.com/basedbid-public/openbid

OpenBid is the public TypeScript SDK and developer tooling for interacting with basedbid.

This repository is the public Colosseum submission hub. OpenBid is the fully open-source technical companion.

---

## Repository map

| Path | Purpose |
|---|---|
| [`SUBMISSION.md`](./SUBMISSION.md) | Colosseum submission summary |
| [`WHY_THIS_TEAM_CAN_WIN.md`](./WHY_THIS_TEAM_CAN_WIN.md) | Team background, GemPad execution history, and why we can compete |
| [`JUDGING.md`](./JUDGING.md) | Suggested judge review path |
| [`DISCLAIMER.md`](./DISCLAIMER.md) | Public repo boundary and verification notice |
| [`HOWITWORKS.md`](./HOWITWORKS.md) | Product mechanics and feature explanation |
| [`docs/`](./docs) | Deeper documentation and architecture notes |
| [`demo/`](./demo) | Demo materials |
| [`metrics/`](./metrics) | Metrics and supporting data |
| [`partnerships/`](./partnerships) | Partnership notes |
| [`traction.md`](./traction.md) | Traction and progress |
| [`Colosseum-Weekly-Updates/`](./Colosseum-Weekly-Updates) | Weekly hackathon build updates |

---

## What is public here

This repository includes:

- product documentation;
- submission materials;
- demo information;
- traction summaries;
- partnership notes;
- weekly updates;
- architecture explanations;
- links to the open-source SDK.

---

## What is private

The complete production basedbid implementation is live but private, and is not included in this repository.

This repository does not include:

- full production smart contracts;
- private backend services;
- deployment infrastructure;
- private admin tooling;
- complete production ABIs;
- security-sensitive internal routing logic.

For more detail, see:

- [`DISCLAIMER.md`](./DISCLAIMER.md)
- [`docs/private-code-boundary.md`](./docs/private-code-boundary.md)

---

## Suggested judge review path

1. Read [`SUBMISSION.md`](./SUBMISSION.md)
2. Read [`WHY_THIS_TEAM_CAN_WIN.md`](./WHY_THIS_TEAM_CAN_WIN.md)
3. Read [`HOWITWORKS.md`](./HOWITWORKS.md)
4. Read [`JUDGING.md`](./JUDGING.md)
5. Review [`docs/`](./docs)
6. Review [`demo/`](./demo)
7. Review [`traction.md`](./traction.md)
8. Review the open-source [`OpenBid SDK`](https://github.com/basedbid-public/openbid)

---

## Current focus

basedbid is focused on making token launch infrastructure more sustainable, programmable, and creator-aligned.

The core thesis:

> the protocol does not eat first. the builder eats first.

---

## Status

This repository is maintained as the public Colosseum Frontier Hackathon 2026 submission hub for basedbid.

boards, pools, token launches, and OpenBid support are live on mainnet.

The full production basedbid implementation is private and is not fully represented in this repository. The open-source SDK is maintained separately in the OpenBid repository.
