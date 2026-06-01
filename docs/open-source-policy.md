# Open Source Policy

This repository keeps public package surfaces documented so contributors can understand what is stable, what is shared, and where to look for canonical interfaces.

## Package Documentation Rules

- Every workspace package should have a README that explains its purpose, ownership, and expected surface area.
- Shared contract-facing packages must be documented in the architecture map before they are referenced as stable dependencies elsewhere.
- When a package becomes the canonical source of truth for a shared interface, the README and architecture docs must point to each other for discoverability.

## ABI Registry

The `@orbital/abi-registry` package is the canonical source of ABI descriptors and typed contract interfaces for the monorepo.

- Architecture overview: [docs/ARCHITECTURE.md](./ARCHITECTURE.md)
- Package README: [packages/abi-registry/README.md](../packages/abi-registry/README.md)

Use this package as the shared contract surface instead of duplicating ABI definitions across application code.
