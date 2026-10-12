# Public and private code boundary

## What is in this repository

This repository contains basedbid's public submission materials and product documentation:

- Product and launch mechanics.
- Competition-period development disclosure.
- High-level architecture and fee-routing explanations.
- Traction summaries and demo materials.
- Links to public developer tooling.

It does not expose the complete production implementation. The architecture documentation explains the system but is not a substitute for production-source review.

## Public developer tooling

The [Openbid repository](https://github.com/basedbid-public/openbid) contains our public, open-source TypeScript SDK.

Partners can use the SDK and supported API and ABI integration surfaces to interact with basedbid. Publishing that tooling does not make the underlying private backend and full production contracts part of this repository.

## Components not included

- Full production smart-contract source.
- Private backend services and internal routing implementation.
- Deployment infrastructure and operational tooling.
- Private keys and credentials.

## Existing product versus updated release

The existing mainnet beta is accessible at [based.bid](https://www.based.bid/).

At submission, the updated full release shown in the demo is still in final testing and is not publicly accessible. Updated contracts may be redeployed; testing addresses should not be treated as final production addresses.

See [SUBMISSION.md](../SUBMISSION.md) for the distinction between pre-existing work and competition-period development, and [architecture.md](./architecture.md) for the product-level system overview.
