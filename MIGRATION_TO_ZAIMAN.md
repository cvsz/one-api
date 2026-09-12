# one-api -> Zaiman Migration

Status: DEPRECATION_CANDIDATE
Canonical destination: cvsz/zaiman
Date: 2026-09-12

## Preserve

- API input-validation tests
- CORS/robustness tests
- health endpoint contract
- lightweight compatibility behavior where an active client still depends on it

## Do not add

- new provider registries
- multi-account routing
- quota/fallback logic
- a second ZeaZ model-control plane

Those capabilities belong in cvsz/zaiman.

## Retirement gates

This repository may be archived only after:
1. all active clients point to Zaiman or an explicitly approved compatibility facade;
2. useful tests are ported;
3. parity is recorded;
4. no production deployment references this repository;
5. rollback evidence exists.

No deletion is authorized by this document.
