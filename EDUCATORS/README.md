# Educators — FREQTRADE

**Project:** FREQTRADE  
**Category:** CRYPTOCURRENCY  
**Upstream:** see BENCH.json  
**Pinned commit:** `5da169854b20adfce1e893ddac0f5270fb9b1d2d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c12794704340c4077b79a812722fd86e5a76845dc02202b095b446106ba2df0f`  
**Date:** October 2026

## Teaching with FREQTRADE

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `c12794704340c4077b79a812722fd86e5a76845dc02202b095b446106ba2df0f` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
