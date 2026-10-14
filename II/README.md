# Independent Insurance — YOMO

**Project:** YOMO  
**Category:** OIL_GAS  
**Upstream:** see BENCH.json  
**Pinned commit:** `f1b8396948b299a878dc811c888e9acd2e109d30`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `eedbe072a4f41f8bc97dd11b017fd3186ad7d8aa350bf2b37d391240801897f9`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | YOMO with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `eedbe072a4f41f8bc97dd11b017fd3186ad7d8aa350bf2b37d391240801897f9`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
