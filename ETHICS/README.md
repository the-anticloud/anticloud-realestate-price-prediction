# Ethics — REALESTATE_PRICE_PREDICTION

**Project:** REALESTATE_PRICE_PREDICTION  
**Category:** REAL_ESTATE  
**Upstream:** see BENCH.json  
**Pinned commit:** `14c61ee1d5b901ad173ebc030edcfa733df6c954`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `fc3174d467a8a082da9a282bdfcbd7597cf87ef649e2e2bb21d5dd241412861e`  
**Date:** October 2026

## Position

REALESTATE_PRICE_PREDICTION is packaged for offline deployment with a verifiable audit trail. The
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
