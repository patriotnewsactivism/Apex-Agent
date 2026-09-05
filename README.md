# Apex-Agent — DEPRECATED

> **This repository is not maintained and should not be used as a source of
> current capability.** Its last commit (2026-07-12) documents that the
> deployed Railway instance was crash-looping continuously and had never once
> completed initialization; no later commit confirms a fix. There have been
> zero commits since. Railway is also a retired APEX hosting path in the
> live system (see `patriotnewsactivism/apex`, ADR-001 in
> `docs/ARCHITECTURE_DECISIONS.md`).
>
> **Current development happens in [`patriotnewsactivism/apex`](https://github.com/patriotnewsactivism/apex).**
> That repository independently re-implements and substantially extends every
> design idea in this one (hierarchical agents, per-tool approval gating,
> durable task queue, memory) against Postgres/Cloud Run/OpenRouter, with
> real tests, CI, and production deploy provenance that this repository never
> had. See `docs/APEX_SYSTEM_AUDIT.md` and `docs/APEX_ARCHITECTURE.md` in
> that repository for the full comparison and disposition rationale.
>
> This repository is kept for history, not deleted, and is not receiving
> further development. Do not port work out of it without checking whether
> Apex has already re-implemented it more completely — in every case checked
> during the 2026-09-05 audit, it had.

---

# Apex-Agent — Autonomous AI Workforce (historical)

Persistent hierarchical multi-agent platform deploying on Railway.
Built: Sat Jul 11 12:34:20 UTC 2026
