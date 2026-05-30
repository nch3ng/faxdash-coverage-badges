# faxdash-coverage-badges

Public mirror of coverage-badge JSON for the **private** [`aldero-io/faxdash`](https://github.com/aldero-io/faxdash) repo.

shields.io reads these unauthenticated; a private repo's raw files can't be read by shields, so the
badge data lives here. Files are written automatically by faxdash's `backend.yml` / `app.yml` via a
write-scoped, **non-expiring deploy key** (no PAT, no human step — see faxdash ALD-44).

Machine-managed — do not edit by hand.

- `faxdash-backend-coverage.json` — backend statement coverage
- `faxdash-app-coverage.json` — Flutter app line coverage
