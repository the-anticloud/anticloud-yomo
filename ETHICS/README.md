# Ethics — YOMO

**Project:** YOMO  
**Category:** OIL_GAS  
**Upstream:** see BENCH.json  
**Pinned commit:** `f1b8396948b299a878dc811c888e9acd2e109d30`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `eedbe072a4f41f8bc97dd11b017fd3186ad7d8aa350bf2b37d391240801897f9`  
**Date:** October 2026

## Position

YOMO is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
