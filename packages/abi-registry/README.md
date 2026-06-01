# @orbital/abi-registry

Shared ABI registry for the Orbital Stellar monorepo.

This package is the canonical home for contract ABI descriptors, typed interface exports, and other shared contract-facing metadata. Other packages should depend on it instead of inlining or duplicating contract signatures.

## Why it exists

- Keeps contract interfaces consistent across frontend, backend, and tooling.
- Gives ABI changes a single review point.
- Reduces drift between deployed contracts and client-side assumptions.

## Package Surface

- ABI manifests and descriptors
- Typed contract interface definitions
- Shared constants used by consumers of contract ABIs

## References

- Architecture map: [../../docs/ARCHITECTURE.md](../../docs/ARCHITECTURE.md)
- Open source policy: [../../docs/open-source-policy.md](../../docs/open-source-policy.md)
