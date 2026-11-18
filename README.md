# Alexis Perdomo

Backend engineer. I build product backends, and the guardrails that keep AI agents from breaking
them.

Python · TypeScript · Go · PostgreSQL · Azure & GCP

---

## What I work on

**Product backends with real domain weight.** Revenue and rebate engines, multi-tenant APIs with
capability-based access, document ingestion and versioning. The kind of system where a wrong number
is a business problem, not a bug.

**AI systems that have to be right.** Retrieval-backed product backends (Postgres/pgvector,
document ingestion and versioning), MCP servers, and agent workflows where deterministic scripts
own the facts and models only own the judgment.

**Delivery governance.** An execution harness for AI-assisted delivery: the project board is the
single source of truth, and the harness covers technical discovery, issue breakdown, plan gates,
evidence-backed builds, fresh-session review and release verification.

## How I work

1. **Correctness is enforced, not assumed.** Schema, types, architecture rules and tests make the
   wrong state hard to reach.
2. **Failure is explicit.** A missing guard blocks the action instead of degrading quietly.
3. **Boundaries first.** Domain, transport and persistence are separated before the first feature,
   because that is when it is cheap.
4. **Decisions are written.** Assumptions get IDs, scope changes get history, and the next person
   should not need archaeology.
5. **Subtraction is part of the design.** The most recent change to the harness was removing
   planning, estimation and reporting from its scope.

## Currently

Rebuilding the agent harness around the project board: technical discovery only, no planning and no
estimation. Pruning the base of anything not tied to a stage and a caller.

## Selected work

| Project | What it is | Why it matters |
| --- | --- | --- |
| [redix](https://github.com/AlexisPerdomoD/redix) | Redis-compatible datastore in Go, zero dependencies | RESP2/RESP3, AOF/RDB, expiration semantics — protocol and persistence from the inside |
| [deterministic-executor](https://github.com/AlexisPerdomoD/deterministic-executor) | Stack VM library in Rust | Either the resulting state or an error, never a partial result |
| [local-ia](https://github.com/AlexisPerdomoD/local-ia) | Local inference workstation (Arch, Ollama/Vulkan) | Reproducible profiles for long-context agents and millisecond completions, fully offline |
| [ownned](https://github.com/AlexisPerdomoD/ownned) | Self-hosted cloud storage, Go + SolidJS | Hierarchical permissions with ltree, vector search with pgvector, JWT + Argon2 |

## At work (private)

- **Revenue & rebates platform** — Python/FastAPI, PostgreSQL, Azure AD. Rebates, markups,
  FT0–FT12 forecasts, provider homologation over 600+ brands and 1,500+ media providers.
- **Education AI platform** — NestJS, Postgres + pgvector, GCP. Curriculum domain,
  capability-based RBAC, document versioning.
- **Agent execution harness** — board-centered execution, fail-closed guards, fresh-session review.
  Design notes: [agent-harness-notes](https://github.com/AlexisPerdomoD/agent-harness-notes).

## Stack

Python (FastAPI) · TypeScript (Node.js, NestJS) · Go · PostgreSQL · Redis · SQL Server · Docker ·
Terraform · GitHub Actions · Azure · GCP

## Contact

[LinkedIn](https://www.linkedin.com/in/alexisperdomod) ·
[Email](mailto:alexisjperdomod@gmail.com)
