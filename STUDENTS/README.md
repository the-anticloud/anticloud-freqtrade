# Students — FREQTRADE

**Project:** FREQTRADE  
**Category:** CRYPTOCURRENCY  
**Upstream:** see BENCH.json  
**Pinned commit:** `5da169854b20adfce1e893ddac0f5270fb9b1d2d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c12794704340c4077b79a812722fd86e5a76845dc02202b095b446106ba2df0f`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `5da169854b20adfce1e893ddac0f5270fb9b1d2d`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `c12794704340c4077b79a812722fd86e5a76845dc02202b095b446106ba2df0f`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
