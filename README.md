<div align="center">

# Ghassen Dhaoui

**Software engineer · applied AI & reliable backend systems**  
*Building for correctness-heavy domains — fintech & RegTech*

`Tunis, Tunisia` &nbsp;·&nbsp; `PFE 2026–2027` &nbsp;·&nbsp; Open to PFE / internship opportunities

</div>

---

### What I focus on

I build systems where *“it runs”* isn’t enough — **deterministic behavior, idempotency, auditability, and measured quality** matter.

- **Depth:** Python · FastAPI · PostgreSQL · applied AI/LLM with evaluation · distributed-systems fundamentals  
- **Breadth:** APIs, data modeling, SQL, testing, Docker/CI, and clear engineering docs  
- **Domain lens:** reconciliation, ledgers, evidence & compliance, risk decisioning, payments-grade reliability

---

### Flagship portfolio — design → build

A curated set of **real-product specs** (web UI + API + workers + DB), each defined by hard constraints and *falsifiable proof* — not demos.  
<sub>Building in depth; some repositories may be private while in progress.</sub>

#### 01 · [Recon Ledger Workbench](https://github.com/GhassenD95/01-recon-ledger-workbench)
> Deterministic multi-source reconciliation with explainable matches and a human-review workflow.  
> **Proves:** shuffle-invariant results · precision/recall on labeled sets · safe reruns · 100k+ row benchmarks  
> **Inspired by:** Tradrly (bank reconciliation), Wevioo/Liberrex (data quality & réconciliation), Medius

#### 02 · [Invoice & Spend Control](https://github.com/GhassenD95/02-invoice-spend-control)
> Document intake → extraction & verification (2/3-way match) → approval workflow with guardrails.  
> **Proves:** per-field extraction F1 · confidence & abstention · duplicate prevention · state-machine correctness  
> **Inspired by:** Medius (smart verification, payments/expense ops), Tradrly (invoice extraction), ATS

#### 03 · [Compliance Evidence Copilot](https://github.com/GhassenD95/03-compliance-evidence-copilot)
> Control/evidence room + evidence-grounded Q&A with **citations, refusal, and an eval gate** (CI fails on regressions).  
> **Proves:** faithfulness & citation precision · abstention on unanswerables · cost & p95 per query  
> **Inspired by:** EY Tunisie (ISMS / SWIFT CSP / PCI DSS, AI governance), Wevioo (ConformIA), Olindias

#### 04 · [Risk & Decisioning Console](https://github.com/GhassenD95/04-risk-decisioning-console)
> Leakage-safe, time-correct risk scoring with calibration, reason codes, case review, and drift monitoring.  
> **Proves:** PR-AUC vs baseline · calibration curves · drift-detection demos · p99 serving latency  
> **Inspired by:** Olindias (risk engine), Anypli (payment-delay prediction), Orange, Flexee

#### 05 · [Reliable Event Platform](https://github.com/GhassenD95/05-reliable-event-platform)
> Transactional outbox, idempotent delivery, signed webhooks, bounded safe replay, DLQ, and SLOs.  
> **Proves:** zero-loss/zero-duplicate chaos tests · replay checksums · p99 delivery & throughput  
> **Inspired by:** Singleton (payment infrastructure), Liberrex (integration hub), ODDO BHF (SRE/observability)

---

### How I work

- **Software first, AI as a component** — models/LLMs behind schemas, evals, and confidence thresholds, not the whole system.
- **Evidence over claims** — tests, benchmarks, eval harnesses, and runbooks; tradeoffs and failure modes written down.
- **Domain-aware engineering** — ledgers, idempotency, reconciliation, audit trails, and compliance treated as first-class requirements.

### Toolkit

**Core:** Python · FastAPI · PostgreSQL · SQL/SQLAlchemy · Redis · Docker · GitHub Actions · pytest  
**Frontend:** React · Next.js · TypeScript  
**Applied AI:** RAG & retrieval · evaluation harnesses · extraction & scoring pipelines  
**Also:** exposure to Java/Spring and distributed systems

---

<div align="center">

**Let’s connect**  
[GitHub @GhassenD95](https://github.com/GhassenD95) · open to collaboration on backend, data, and AI-systems problems

</div>
