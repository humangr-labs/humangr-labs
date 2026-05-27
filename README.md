# humangr-labs

Building **infrastructure for compliance-aware engineering teams** — production-grade tooling for build pipelines, governance, and data residency.

## What we ship

**[CoreLink](https://github.com/humangr-labs/corelink-server)** — multi-tenant content-addressable build cache. REAPI v2 compatible, per-tenant BYOK (AWS/GCP/Azure/Vault), audit-chain native. Five GB free.

**[corelink-cli](https://github.com/humangr-labs/corelink-cli)** — install: `curl -fsSL https://corelink-get.humangr.com | sh -s -- --token=<PAT>`

## Trust

- Cargo workspace under `#![forbid(unsafe_code)]`
- TLA+ proved critical invariants on cross-tenant isolation
- RFC-6962-style audit chain (BLAKE3)
- cargo-deny lockdown on supply chain
- DPA available (Common Paper template)

## Solo founder

Built and maintained by [Gustavo Schneiter](https://twitter.com/gschneiter). Pre-PMF; pre-revenue. Build-in-public.

-> [Docs](https://corelink-docs.humangr.com) · [Pricing](https://corelink-docs.humangr.com/pricing) · [Trust](https://corelink-docs.humangr.com/trust)
