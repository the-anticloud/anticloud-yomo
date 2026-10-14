# Educators — YOMO

**Project:** YOMO  
**Category:** OIL_GAS  
**Upstream:** see BENCH.json  
**Pinned commit:** `f1b8396948b299a878dc811c888e9acd2e109d30`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `eedbe072a4f41f8bc97dd11b017fd3186ad7d8aa350bf2b37d391240801897f9`  
**Date:** October 2026

## Teaching with YOMO

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `eedbe072a4f41f8bc97dd11b017fd3186ad7d8aa350bf2b37d391240801897f9` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
