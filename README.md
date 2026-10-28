# gamma-protocol

Legal moves, contracts and governance; intended authoritative home of the protocol JSON Schemas.

Proposed future name: **jynx-rules** (proposal, not renamed yet)

## Place in the 7-repo layout

Plane: **RULES**. See [HNXJ/jynx-arena](https://github.com/HNXJ/jynx-arena) and its [architecture](https://github.com/HNXJ/jynx-arena/blob/main/docs/protocol/ARCHITECTURE.md) (ARENA, RULES, SCIENCE, LAB, ENGINE, JUDGE, WORLD). The current jynx-arena runtime is proposed to become **jynx-engine**; **jynx-world** (event ledger, projections) is a new proposed repo.

## Holds today

- Markdown contracts in `contracts/` (agent, harness, judge, observation, patch, quest, receipt).
- Doctrine in `doctrine/`, policies in `docs/`, templates in `templates/`.
- Schema specs in `schemas/` (Markdown only; the JSON Schemas are provisionally in jynx-arena per [SCHEMA_AUTHORITY](https://github.com/HNXJ/jynx-arena/blob/main/docs/protocol/SCHEMA_AUTHORITY.md)).

## Shared root layout (target, not yet applied)

`artifacts/`, `docs/`, `src/`, `schemas/`, `tests/`, `tournaments/`, `README.md` — see [SHARED_ROOT_LAYOUT](https://github.com/HNXJ/jynx-arena/blob/main/docs/protocol/SHARED_ROOT_LAYOUT.md).

## Truth safety

A Judge PASS means a submission met a rubric under a protocol version; it is not scientific truth.

