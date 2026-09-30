<div align="center">

### Blockchain Expert · Senior Backend Engineer · Software Architect · Technical Lead

*I design and ship resilient, high-throughput distributed systems — where correctness, low latency, and operational clarity are non-negotiable.*


</div>

---

## 👋 About Me

**11+ years** of professional software engineering — with the last **8+ years** focused on production **Go** backends: fintech ledgers, blockchain infrastructures, wallet gateways, and high-load transaction pipelines on **GCP**. I've been programming since I was **13** *(now 33)* — long before it was my career, and that foundation still shapes how I think about systems. I care about software that stays correct under pressure: idempotent flows, exponential backoff, event-driven architectures, and observability baked in from day one.

Currently architecting a **non-custodial digital-asset wallet gateway** at Matrix.app — multi-chain ledger sync, HSM/MPC signing flows, and enterprise-grade Web3 primitives (Account Abstraction, Gas Sponsorship, EIP-7702).

**Open to:** Blockchain Expert · Senior Backend Engineer · Software Architect · Technical Lead roles — **Remote / Hybrid** *(visa sponsorship required)*

---

## 🎯 Engineering Philosophy

| Principle | In Practice |
|-----------|-------------|
| **Reliability first** | Idempotency keys, retry/recovery paths, graceful shutdown, health-checked deployments |
| **Performance by design** | Worker pools, hot-path caching, pprof-driven optimization, sub-second API targets |
| **Observable systems** | Prometheus, Grafana, OpenTelemetry tracing, structured logging |
| **Clean boundaries** | DDD module isolation, SOLID microservices, auditable event flows |

---

## 🛠 Core Expertise & Tech Stack

<table>
<tr>
<td valign="top" width="50%">

**Core Programming Languages**
<br>
`Golang` (Expert · 8+ Years focused) · `Solidity` (Expert) · `Rust` · `Move` · `TypeScript` · `JavaScript` · `C/C++`

**Cloud Architecture, Edge & Infrastructure**
<br>
`GCP` (Cloud Run, Pub/Sub, Secret Manager) · `AWS Lambda` · `Cloudflare Workers` · `Docker` · `Kubernetes`

**Datastores, Distributed Caching & Graph**
<br>
`Google Cloud Bigtable` · `DynamoDB + DAX` · `Firestore` · `Dgraph` Graph DB · `Redis` · `PostgreSQL` · `MySQL` · Distributed SQL/NoSQL · Time-Series Databases

**Messaging & Distributed Streaming**
<br>
`NATS` (Advanced) · `RabbitMQ` · `GCP Pub/Sub` · `Apache Kafka` · AMQP Topologies & Systems · Event-Driven Architecture & Topologies

**Observability, API Design & Serialization**
<br>
`Prometheus` · `Grafana` · `OpenTelemetry` · Structured Logging · `pprof` Profiling · `gRPC` · `Protobuf` · `REST APIs` · `JSON` · `WebSockets`

</td>
<td valign="top" width="50%">

**Distributed Systems Design**
<br>
Idempotency Design Patterns · Backoff/Retry Strategies · Byzantine Fault Tolerance (BFT) Consensus · Worker Pools · Domain-Driven Design (DDD) · SOLID Principles · Microservices

**Web3 & DLT Ecosystems**
<br>
Smart Contract Auditability · Ethereum & EVM Architecture · Wallet Integration Platforms · Cryptographic Key Management (HSM/MPC) · Stablecoins & Tokenized Asset Infrastructures · MEV/Flashbots Core · Account Abstraction (EIP-4337) · Gas Sponsorship · Diamond Pattern (ERC-2535) · Yield Vaults (ERC-4626) · EIP-7702 Delegation · Cross-Chain Interoperability (`Chainlink CCIP` · `Cosmos IBC` · `Wormhole` · `LayerZero Omnichain`) · `Cosmos SDK` · `Solana` · `Sui` Infrastructure · Crypto Wallets · EVM Integrations · Tokenomics Design

**Leadership & Operations**
<br>
Tech Strategy · Turnaround Management · OKRs/KPIs · Tech Consulting · Operational Excellence · Team Structure & Hiring · CI/CD & SDLC Practices

</td>
</tr>
</table>

---

## 📈 Impact & Achievements

| | |
|---|---|
| 🚀 **50,000+ concurrent users** | Scaled a nationwide SSO & examination platform on a **single server** (24 cores / 16 GB RAM) — resolved deadlocks and contention via custom connection pooling and Redis caching. |
| 🌐 **10,000+ simultaneous sessions** | Led backend architecture for **recoverit.app** US regulated-market launch — cross-platform (Android, iOS, Web) with sub-second API responses under peak load. |
| ⚡ **+35% delivery velocity** | Diagnosed memory and serialization bottlenecks with **Go pprof** at BeStudios; re-engineered multi-DB sync hot paths and migrated static infra to **autoscaling GCP** — cutting recurring cloud spend. |

---

## 🌟 Featured Open Source

### [`vault-guard-7702`](https://github.com/harpy-wings/vault-guard-7702) — Enterprise EIP-7702 Wallet Proxy & Gateway

Production-grade Solidity implementation that injects institutional **multi-sig guards** and compliance controls into standard EOAs via **EIP-7702 persistent delegation** — with a decoupled **Gas Sponsorship Paymaster** for frictionless non-custodial onboarding.

| Stack | Highlight |
|-------|-----------|
| `Solidity` · EIP-7702 · ERC-4337 Paymaster | Institutional-grade wallet security without sacrificing UX — compliance controls baked into delegation, not bolted on. |

---

### [`flashbot`](https://github.com/harpy-wings/flashbot) — Ethereum / MEV Client

Go library for the [Flashbots relay](https://docs.flashbots.net) — bundle simulation, private transaction submission, gas estimation, MEV-Share privacy hints, and EIP-191 request signing.

| Stack | Highlight |
|-------|-----------|
| `Go` · EIP-191 · OpenTelemetry · Mainnet & Sepolia | Built for production MEV workflows with **distributed tracing** and relay-grade request signing out of the box. |

---

### [`signal-flow`](https://github.com/harpy-wings/signal-flow) — AMQP Messaging Library

Generic AMQP client with automatic reconnect, retry strategies, flow control, and pluggable codecs — designed for easy mocking in unit tests.

| Stack | Highlight |
|-------|-----------|
| `Go` · AMQP · JSON/Binary codecs | **Go Report A+** · **84%+ test coverage** · Powers production trading settlement pipelines. |

---

### [`goga`](https://github.com/harpy-wings/goga) — Genetic Algorithms Framework

Configurable genetic algorithm framework in pure Go — custom cost functions, parallel evaluation, and tunable selection/mutation/population strategies.

| Stack | Highlight |
|-------|-----------|
| `Go` · Parallel evaluation · Benchmarks | **Go Report A+** · **95% test coverage** — concurrency-first design for population evaluation at scale. |

---

## 💼 Recent Experience

| Role | Company | Focus |
|------|---------|-------|
| **Principal Software & Gateway Architect** | Matrix.app | Non-custodial wallet gateway, multi-chain sync, HSM/MPC, EIP-4337/7702 |
| **Infrastructure Restructuring Lead** | BeStudios | Architecture turnaround, pprof optimization, GCP autoscaling migration |
| **Principal Software & Smart Contract Architect** | EchoTrade / AxonChain | Go microservices, DDD trade flows, audited Solidity (Diamond Pattern, ERC-4626) |
| **Senior Golang Developer & Tech Lead** | SixSigmaSports | Real-time ledger, chain-of-trust audit layer, shared Go libraries |
| **Principal Cloud Engineer / Backend Lead** | KRM-Venture | recoverit.app US launch, 10K+ concurrent sessions, Redis hot-path caching |


---

<div align="center">

*"Ship systems that survive traffic spikes, audit scrutiny, and 3 AM pages — without trading away developer velocity."*

</div>
