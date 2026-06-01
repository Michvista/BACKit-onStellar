# BACKit — Stellar Architecture

This docs entry point mirrors the repository architecture reference in the root [`ARCHITECTURE.md`](../ARCHITECTURE.md) file.

## 3.5 ABI Registry (`@orbital/abi-registry`)

The ABI Registry is the shared contract surface for the monorepo.

- It centralizes ABI descriptors and typed contract interfaces.
- It keeps frontend, backend, and tooling aligned on one package surface.
- It acts as the review boundary for ABI changes before they are consumed elsewhere.
- It provides the documentation anchor used by the package README and open-source policy.
