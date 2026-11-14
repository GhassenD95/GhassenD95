# Ghassen Dhaoui

**Software engineer building reliable, AI-powered backend systems** — with a focus on correctness-heavy domains (fintech & RegTech): reconciliation, auditability, evaluated AI, and payments-grade reliability.

- 🎓 Engineering student (PFE 2026–2027) based in **Tunis, Tunisia**
- 🔭 Building T-shaped depth: **Python · FastAPI · PostgreSQL · applied AI/LLM (with evals) · distributed systems**
- 🧩 Interested in problems where "it runs" isn’t enough: determinism, idempotency, traceability, and measured quality

## Flagship portfolio (design → build, in order)

A curated set of real-product specs (web UI + API + workers + DB) inspired by production-grade PFE problem spaces — each defined by hard engineering constraints and falsifiable proof (benchmarks, evals, chaos tests), not demos.

| # | Project | Focus | Proof I care about |
|---|---|---|---|
| 01 | [**Recon Ledger Workbench**](https://github.com/GhassenD95/01-recon-ledger-workbench) | Deterministic multi-source reconciliation, versioned rules, explainable matches, audit trail | Shuffle-invariant results, precision/recall on labeled sets, safe reruns, 100k+ row benchmarks |
| 02 | [**Invoice & Spend Control**](https://github.com/GhassenD95/02-invoice-spend-control) | Document extraction → verification (2/3-way match) → approval workflow with guardrails | Per-field extraction F1, confidence & abstention, duplicate/state-machine correctness |
| 03 | [**Compliance Evidence Copilot**](https://github.com/GhassenD95/03-compliance-evidence-copilot) | Control/evidence room + evidence-grounded Q&A with citations, refusal, and an eval gate | Faithfulness & citation precision, abstention on unanswerables, CI-failing regressions, cost/p95 |
| 04 | [**Risk & Decisioning Console**](https://github.com/GhassenD95/04-risk-decisioning-console) | Leakage-safe, time-correct risk scoring, calibration & reason codes, case review, drift monitoring | PR-AUC vs baseline, calibration, drift-detection demos, p99 serving latency |
| 05 | [**Reliable Event Platform**](https://github.com/GhassenD95/05-reliable-event-platform) | Outbox, idempotent delivery, signed webhooks, bounded safe replay, DLQ, SLOs | Zero-loss/zero-duplicate chaos tests, replay checksums, p99 delivery & throughput |

> Building these in depth (correctness & measurement over feature count). Some repos may be private while in progress.

## How I like to work
- **Software first, AI as a component:** APIs, data models, and workflows that hold up — ML/LLMs behind schemas, evals, and confidence thresholds.
- **Evidence over claims:** tests, benchmarks, eval harnesses, and runbooks; tradeoffs and failure modes written down (ADRs).
- **Domain-aware engineering:** ledgers, idempotency, reconciliation, audit trails, and compliance evidence treated as first-class requirements.

## Toolkit
`Python` · `FastAPI` · `PostgreSQL` · `SQL/SQLAlchemy` · `Redis` · `Docker` · `GitHub Actions` · `pytest` · `React/Next.js` · `applied ML/LLM (RAG, evals)` · exposure to `Java/Spring` & distributed systems

## Get in touch
- GitHub: [@GhassenD95](https://github.com/GhassenD95)
- Open to PFE/internship opportunities and collaboration on backend, data, and AI-systems problems.
