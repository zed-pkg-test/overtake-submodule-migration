# Test plan

- Verify conversion of nested .gitmodules into pinned .zpkg.toml and .zpkg.lock dependencies across the supported happy-path states and canonical fixtures.
- Verify conversion of nested .gitmodules into pinned .zpkg.toml and .zpkg.lock dependencies under retries, interruption, concurrency, offline operation, or partial failure.
- Verify conversion of nested .gitmodules into pinned .zpkg.toml and .zpkg.lock dependencies preserves authorization, idempotency, integrity, observability, and actionable failure classification.

## Classification

- product regression
- blocked dependency
- harness regression
