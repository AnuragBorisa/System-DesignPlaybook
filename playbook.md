# System-Design Playbook: Step-by-Step

0. **Frame the Problem**  
   – State the one-liner, key user journeys, scope & out-of-scope.

1. **Functional Requirements**  
   – List & prioritize all critical user actions.

2. **Non-Functional Requirements & Constraints**  
   – Performance, availability, consistency, security, regulatory, cost.

3. **Capacity & Traffic Estimation**  
   – Users, QPS, data growth, read/write mix, fan-out patterns.

4. **High-Level Architecture (Sketch)**  
   – Draw boxes-and-arrows for services, data stores, sync/async flows.

5. **Data Model (Entities & Relationships)**  
   – Core entities, cardinality, access patterns, transactional boundaries.

6. **API & Contract Design**  
   – Define endpoints, methods, request/response schemas, idempotency.

7. **Deep-Dive Critical Component(s)**  
   – Sequence diagrams, algorithms/data-structures, scaling knobs, failure modes.

8. **Scaling & Evolution Strategies**  
   – Sharding, partitioning, caching layers, stateless vs stateful, migrations.

9. **Reliability, Resiliency & Observability**  
   – Replication, failover, retries, circuit breakers, metrics, tracing, alerts.

10. **Security & Compliance**  
    – AuthN/AuthZ, encryption, PII handling, audit/logging, secrets management.

11. **Cost, Trade-offs & Alternatives**  
    – Capacity vs cost, consistency vs availability, rejected approaches.

12. **Launch, Ops & Future Roadmap**  
    – Rollout plan (canaries, feature flags), runbooks, v2+ improvements.
