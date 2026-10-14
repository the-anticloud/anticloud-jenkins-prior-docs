# Students — JENKINS_PRIOR_DOCS

**Project:** JENKINS_PRIOR_DOCS  
**Category:** SOFTWARE_DEVELOPMENT  
**Upstream:** https://github.com/jenkinsci/jenkins  
**Pinned commit:** `e2ba107d13304978b338eb19f31fad5a53a858cc`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `0f199537ce536de51d35c5e7e34c175e8a33acc8b742c47df5228899dcc4b8ef`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `e2ba107d13304978b338eb19f31fad5a53a858cc`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `0f199537ce536de51d35c5e7e34c175e8a33acc8b742c47df5228899dcc4b8ef`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
