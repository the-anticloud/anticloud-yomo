# Students — YOMO

**Project:** YOMO  
**Category:** OIL_GAS  
**Upstream:** see BENCH.json  
**Pinned commit:** `f1b8396948b299a878dc811c888e9acd2e109d30`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `eedbe072a4f41f8bc97dd11b017fd3186ad7d8aa350bf2b37d391240801897f9`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `f1b8396948b299a878dc811c888e9acd2e109d30`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `eedbe072a4f41f8bc97dd11b017fd3186ad7d8aa350bf2b37d391240801897f9`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
