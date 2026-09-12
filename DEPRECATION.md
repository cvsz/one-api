# Deprecation / Migration Plan

Canonical AI gateway: **`cvsz/zaiman`**

`one-api` is retained temporarily as a small compatibility and robustness-test reference.

Migration:
1. inventory health/CORS/OpenAI-compatible robustness tests
2. port useful tests/contracts to Zaiman
3. migrate clients to Zaiman
4. optionally retain a thin compatibility facade during transition
5. deprecate/archive only after parity and client migration

Do not build an independent second provider-routing platform here.

Explicit exclusion: `cvsz/zsme` is not part of this program.
