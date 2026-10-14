# Ethics — MPPT_ALGORITHMS

**Project:** MPPT_ALGORITHMS  
**Category:** SOLAR  
**Upstream:** https://github.com/ej-jp/perovskino.git  
**Pinned commit:** `e1a9efe3536609413e712af3c81a502d640cbdc1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `eed48a6698a3fc223068d52791ecc5c9e5e8dbcfab6cda9869bfe1b34dc04808`  
**Date:** October 2026

## Position

MPPT_ALGORITHMS is packaged for offline deployment with a verifiable audit trail. The
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
