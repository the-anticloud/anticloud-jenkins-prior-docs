# Ethics — JENKINS_PRIOR_DOCS

**Project:** JENKINS_PRIOR_DOCS  
**Category:** SOFTWARE_DEVELOPMENT  
**Upstream:** https://github.com/jenkinsci/jenkins  
**Pinned commit:** `e2ba107d13304978b338eb19f31fad5a53a858cc`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `0f199537ce536de51d35c5e7e34c175e8a33acc8b742c47df5228899dcc4b8ef`  
**Date:** October 2026

## Position

JENKINS_PRIOR_DOCS is packaged for offline deployment with a verifiable audit trail. The
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
