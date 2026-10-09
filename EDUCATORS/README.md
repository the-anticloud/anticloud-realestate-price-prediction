# Educators — REALESTATE_PRICE_PREDICTION

**Project:** REALESTATE_PRICE_PREDICTION  
**Category:** REAL_ESTATE  
**Upstream:** see BENCH.json  
**Pinned commit:** `14c61ee1d5b901ad173ebc030edcfa733df6c954`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `fc3174d467a8a082da9a282bdfcbd7597cf87ef649e2e2bb21d5dd241412861e`  
**Date:** October 2026

## Teaching with REALESTATE_PRICE_PREDICTION

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `fc3174d467a8a082da9a282bdfcbd7597cf87ef649e2e2bb21d5dd241412861e` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
