# Scooby DAO seed packages (private)

Contains captured third-party evidence. Do not redistribute, fork publicly, or copy into other repositories.

| File | SHA-256 | Contents |
|---|---|---|
| `scooby-six-reference-seed.zip` | `c9fcbf2a32b7c58142389075511989357431b4d457ae89997ebae2261697b8a0` | Six historical, unreviewed reference case–report pairs (SHIB, FET, SPX, YFI, GRT, METIS). Earlier YFI/FET reports, not the incident supplements. |

Consumed by the backend at boot via `SCOOBY_REFERENCE_SEED_URL` (raw URL, read-only fine-grained token in `SCOOBY_REFERENCE_SEED_AUTH_HEADER`), pinned in code and by `SCOOBY_REFERENCE_SEED_SHA256`. See ScoobyDAO-backend `docs/reference-display-contract.md`.

Never modify bytes under an existing name: a revised package is a new file with a new digest.
