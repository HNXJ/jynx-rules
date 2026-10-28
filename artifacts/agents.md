# agents

Rules: legal moves, contracts, schema specs (Markdown).

## Layout

- `docs/contracts/`, `docs/templates/`, `docs/doctrine/` Markdown. `schemas/*_spec.md` schema specs. `src/`, `tests/`, `tournaments/` empty. `artifacts/archive/` retired files.

## Build and test

No build. Root layout check (needs a jynx-engine checkout): `python <jynx-engine>/src/scripts/check_shared_root.py .` prints `OK`.

Gate: the root layout check; read its last line.

## Git

- Work on `_temp_<name>` branches; PR to `main`. No direct push to `main`.
- Stage exact paths; never `git add .` or `-A`.
- Never commit `.env`, tokens or keys.
