# Software Engineer / AI Systems — Reliability, Distributed Systems, Agentic AI

**Proof**
- Delivered **3× throughput** while holding **p95 ≤ 3.8s** by pairing guardrailed agent flows with regression gates + evidence bundles.
- Tuned platform schedulers for **~50% less swap thrash** and **~$40K/year infra savings** via idempotent queues, retries/backoff, and DLQ hygiene.
- Cut **38% inference cost** yet kept **60fps UI at 100k+ rows** through caching/batching, virtualization, and observability-led tuning.

**Background**: NYU MS CS (May 2026) • Samsung Research • Veach AI • Research Assistant • ES 2026 full paper accepted.

## Featured Projects
- **Event-driven workflow orchestrator** — [workflow-orchestrator-sandbox](https://github.com/Karan-05/workflow-orchestrator-sandbox). FastAPI + Redis + Postgres engine with idempotency keys, retries/backoff, DLQ, reconciliation sweeps, and audit-ready metrics.
- **RAG evaluation + latency/cost harness** — [rag-eval-harness](https://github.com/Karan-05/rag-eval-harness). Deterministic dataset loader, caching vector store, async runners, and hit-rate/latency dashboards that drove the 38% cost win.
- **High-volume analytics UI** — [Portfolio](https://github.com/Karan-05/Portfolio) + production code: virtualized tables, workerized transforms, and motion budgets that keep 60fps at 100k+ rows.
- **Low-latency C++ prototyping** — internal Samsung/Veach efforts (not open-sourced) for near-metal profiling of agent loops, SIMD batching, and pipeline hazard detection.
- **Cloud automation agent** — [Cloud_Automation_Agent-](https://github.com/Karan-05/Cloud_Automation_Agent-). Electron + Django + browser automation with audit logs, plan review, and evidence capture.

## Reliability patterns I reach for
<p align="center">
  <picture>
    <source srcset="assets/reliability.svg" type="image/svg+xml">
    <img src="assets/reliability.png" width="1000" alt="Reliability patterns diagram" />
  </picture>
</p>

## Tech
**Languages**: Python, Java (Spring), TypeScript, C++17/20, Go, SQL, Bash  
**Backend**: REST APIs, microservices, validation/pagination, rate limiting, Redis caching, Kafka queues/streams, background workers  
**Infra**: Docker, Kubernetes, GitHub Actions, Linux, observability (logs/metrics/traces), runbooks & on-call guides

## Writing / Research
- **ES 2026 accepted full paper** – *Agentic Decomposition for Reliable Long-Horizon AI Planning* (public preprint coming soon).

## What I’m looking for
Staff/Senior roles across backend platforms, reliability engineering, or AI systems (NYC hybrid or remote). Let’s collaborate on idempotent, observable, impact-driven systems.

📫 [ka3527@nyu.edu](mailto:ka3527@nyu.edu) • [LinkedIn](https://linkedin.com/in/karan-allagh) • [Portfolio](https://karan-allagh.vercel.app) • [GitHub](https://github.com/Karan-05)

## Pinned repos recommendation
1. `workflow-orchestrator-sandbox` — shows idempotency, retries/backoff, DLQ, reconciliation.
2. `rag-eval-harness` — demonstrates latency/cost benchmarking and async evaluation.
3. `Cloud_Automation_Agent-` — agentic automation with plan reviews + audit logs.
4. `Portfolio` — high-volume UI + recruiter-ready story.
5. `office-submission` — reliability patterns inside Office add-ins.
