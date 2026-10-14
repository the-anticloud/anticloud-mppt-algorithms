# Students — MPPT_ALGORITHMS

**Project:** MPPT_ALGORITHMS  
**Category:** SOLAR  
**Upstream:** https://github.com/ej-jp/perovskino.git  
**Pinned commit:** `e1a9efe3536609413e712af3c81a502d640cbdc1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `eed48a6698a3fc223068d52791ecc5c9e5e8dbcfab6cda9869bfe1b34dc04808`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `e1a9efe3536609413e712af3c81a502d640cbdc1`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `eed48a6698a3fc223068d52791ecc5c9e5e8dbcfab6cda9869bfe1b34dc04808`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
