# Juan Pablo Gaviria

I build backend and platform infrastructure for systems where failure has real consequences.

My work sits across distributed systems, payments infrastructure, production AI reliability, release safety, and platform control planes. Environments where money, state, trust, and operational control must survive real production pressure.

I have built and operated systems involving $10M+ in payment flows, with zero double-charge incidents across production lifetime. I have also built production LLM evaluation infrastructure using golden datasets, dual LLM judges, CI integration, regression checks, and AI-assisted root cause analysis.

The throughline in my work is simple: systems should fail visibly, recover deliberately, preserve evidence, and remain controllable when pressure rises.

## Public Systems

| Repository                                                                                 | System Thesis                                                                                                                                          | Stack                                             |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------- |
| [credit-ai-ops-platform](https://github.com/JuanPabloGaviria/credit-ai-ops-platform)       | AI decisioning should be governed, auditable, testable, and operationally reviewable before it is trusted in production. Verified by a 173-test suite. | Python · FastAPI · RabbitMQ · PostgreSQL          |
| [golden-path-control-plane](https://github.com/JuanPabloGaviria/golden-path-control-plane) | Release safety should be enforced through control planes, gates, policy checks, and durable production evidence — not left to coordination rituals.    | Go · PostgreSQL · OIDC/JWKS · Docker · Kubernetes |
| [event-fabric-rs](https://github.com/JuanPabloGaviria/event-fabric-rs)                     | Event infrastructure should make delivery, retry, replay, recovery, dead-letter handling, webhooks, and fanout explicit instead of accidental.         | Rust · axum · tokio · PostgreSQL · SSE            |

## Systems I Care About

* Payment flows where idempotency, reconciliation, state transitions, and auditability protect real money
* Distributed systems where failure handling is designed before the happy path is celebrated
* Platform control planes that turn operational discipline into reusable infrastructure
* AI systems where evaluation, regression detection, and decision traceability exist before production trust
* Release systems where deployment risk is visible, gated, evidenced, and reviewable
* Event-driven systems with explicit delivery guarantees, persistence semantics, and recovery paths
* Backend infrastructure where invalid states, silent failures, and unclear ownership are treated as design failures

## Operating Principles

* Failure is part of the design surface
* Correctness matters most when the system carries money, state, trust, or authority
* Runtime contracts should be narrow, explicit, and enforceable
* Operational visibility is a requirement, not a dashboard afterthought
* Production systems need evidence, not vibes
* AI systems need evaluation infrastructure before they earn autonomy
* Platforms should reduce repeated mistakes across teams
* Systems should be diagnosable, controllable, and recoverable under pressure

## Engineering Posture

I prefer infrastructure that is boring where it should be boring, strict where it must be strict, and explicit where ambiguity would become production risk.

I care about architecture that survives implementation, documentation that survives ownership transfer, and systems that can still be reasoned about during incidents.

I am most interested in Staff and Principal Backend / Platform Engineering roles involving:

Distributed systems · Payments infrastructure · Production AI reliability · Platform engineering · Control planes · Release safety · Observability · Operational correctness · Mission-critical backend infrastructure

Open to companies where correctness failures are expensive, reliability is strategic, and production discipline is non-negotiable.

→ [LinkedIn](https://linkedin.com/in/jpgaviria)
→ [juangav@protonmail.com](mailto:juangav@protonmail.com)
