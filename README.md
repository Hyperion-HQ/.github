# Hyperion

Enterprise-grade AI infrastructure for teams who can't afford to be slow.

[Website](https://hyperionhq.co) | [Documentation](https://docs.hyperionhq.co) | [Discord](https://discord.gg/hyperion) | [X/Twitter](https://x.com/hyperionhq)

---

## The Mission

Hyperion is building the backbone for the next generation of AI-native applications. Our mission is to provide the performance, observability, and cost-control infrastructure that developers need to move from prompt-to-production at scale.

We believe that as LLM usage grows, the infrastructure sitting between your application and your providers shouldn't just be a proxy—it should be an intelligent layer that optimizes for latency, cost, and reliability automatically.

## Core Projects

### [Hyperion Gateway](https://github.com/hyperionhq/hyperion)
The flagship intelligent LLM orchestrator. A high-performance proxy capable of 20,000+ RPS with 5µs median overhead. Features include:
*   Multi-Tier Caching: L1 (Exact) and L2 (Semantic) caching for microsecond responses.
*   Smart Routing: Automated model selection based on query complexity and budget.
*   Governance: Hard budget enforcement, PII filtering, and per-key rate limiting.
*   Observability: Real-time cost and performance analytics powered by ClickHouse.

### [Hyperion SDKs](https://github.com/hyperionhq/sdks)
Lightweight, typed clients for Go, Python, and TypeScript that make integrating Hyperion's advanced features seamless.

## Tech Stack

Our stack is built for extreme performance and scalability:
*   Gateway: High-concurrency Go
*   Intelligence: Python (FastAPI/Scikit-Learn/PyTorch)
*   Databases: Redis (L1/Auth), Qdrant (L2/Vector), Postgres (Metadata), ClickHouse (Analytics)
*   Dashboard: Tailwind + React + Framer Motion

## Community and Contributing

We are an open-core organization. While we offer enterprise features and hosted solutions, our core gateway is open-source under AGPL-3.0. We welcome contributions from the community!

- Looking for help? Check our Discussions.
- Found a bug? Open an Issue.
- Want to contribute? See our Contributing Guide.

---

(c) 2026 Hyperion AI Infrastructure. Built for the future of AI.
