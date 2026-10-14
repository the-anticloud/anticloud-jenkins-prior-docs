# Educators — JENKINS_PRIOR_DOCS

**Project:** JENKINS_PRIOR_DOCS  
**Category:** SOFTWARE_DEVELOPMENT  
**Upstream:** https://github.com/jenkinsci/jenkins  
**Pinned commit:** `e2ba107d13304978b338eb19f31fad5a53a858cc`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `0f199537ce536de51d35c5e7e34c175e8a33acc8b742c47df5228899dcc4b8ef`  
**Date:** October 2026

## Teaching with JENKINS_PRIOR_DOCS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `0f199537ce536de51d35c5e7e34c175e8a33acc8b742c47df5228899dcc4b8ef` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
