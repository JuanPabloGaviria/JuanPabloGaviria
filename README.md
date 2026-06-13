# Juan Pablo Gaviria

Backend and platform engineer focused on distributed systems, payments infrastructure, platform control planes, and production AI reliability.

I build production systems where correctness, failure handling, auditability, and operational visibility are treated as runtime requirements and not afterthoughts.

Over 7+ years, I have worked on systems involving $10M+ in payment flows, zero double-charge incidents across production lifetime, and production LLM evaluation infrastructure built around golden datasets, dual LLM judges, CI integration, and AI-assisted root cause analysis.

My public work is designed to demonstrate the same engineering principles I care about in production: explicit contracts, durable state, controlled failure modes, release discipline, auditability, and systems that remain understandable under pressure.

## Flagship Repositories

| Repository                                                                                 | What it demonstrates                                                                                                                                                                              | Stack                                             |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------- |
| [credit-ai-ops-platform](https://github.com/JuanPabloGaviria/credit-ai-ops-platform)       | Governed AI decisioning with auditability, asynchronous orchestration, production-facing controls, and operational boundaries rather than demo-layer model serving. Verified by a 173-test suite. | Python · FastAPI · RabbitMQ · PostgreSQL          |
| [golden-path-control-plane](https://github.com/JuanPabloGaviria/golden-path-control-plane) | Platform control plane for release readiness, deployment gating, policy enforcement, and durable evidence around production safety.                                                               | Go · PostgreSQL · OIDC/JWKS · Docker · Kubernetes |
| [event-fabric-rs](https://github.com/JuanPabloGaviria/event-fabric-rs)                     | Event infrastructure with explicit delivery semantics for ingest, retries, replay, dead-letter recovery, webhooks, and real-time fanout.                                                          | Rust · axum · tokio · PostgreSQL · SSE            |

## Engineering Focus

* Distributed systems designed around failure handling, recovery paths, and operational correctness
* Payments infrastructure where idempotency, state transitions, reconciliation, and audit trails matter
* Platform control planes that reduce repeated engineering mistakes across teams
* Production AI infrastructure with evaluation, regression detection, and traceable decision quality
* Release discipline, deployment gates, runtime evidence, and observability
* Explicit contracts, persistence semantics, and defensible system boundaries
* Backend systems that remain understandable during incidents, reviews, and high-pressure execution

## What I Optimize For

* Correctness before cleverness
* Clear runtime contracts
* Controlled failure modes
* Durable operational evidence
* Narrow, enforceable system boundaries
* Evaluation infrastructure before production AI rollout
* Engineering leverage across teams, not just local implementation speed

## Working Style

* Make tradeoffs explicit before they become production incidents
* Design narrow contracts and enforceable boundaries
* Treat invalid assumptions as failure modes, not edge cases
* Build systems that can be reasoned about during pressure
* Prefer boring reliability over fragile novelty
* Document decisions in a way that holds up against implementation review

## Currently Interested In

Staff and Senior Backend / Platform Engineering roles involving:

Distributed systems · Payments infrastructure · Production AI reliability · Platform engineering · Control planes · Release safety · Observability · Operational correctness

Open to companies where correctness, reliability, and production discipline actually matter.

→ [LinkedIn](https://linkedin.com/in/jpgaviria)
→ [juangav@protonmail.com](mailto:juangav@protonmail.com)
