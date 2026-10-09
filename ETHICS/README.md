# Ethics — FREQTRADE

**Project:** FREQTRADE  
**Category:** CRYPTOCURRENCY  
**Upstream:** see BENCH.json  
**Pinned commit:** `5da169854b20adfce1e893ddac0f5270fb9b1d2d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c12794704340c4077b79a812722fd86e5a76845dc02202b095b446106ba2df0f`  
**Date:** October 2026

## Position

FREQTRADE is packaged for offline deployment with a verifiable audit trail. The
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
