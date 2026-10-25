---
title: "Dooplicatoor: Real-Time Multi-Broker Trade Replication"
excerpt: "Replicates orders from one parent trading account to 10+ downstream accounts across three brokers in real time, at >99% replication and sub-250 ms end-to-end latency."
collection: portfolio
---

*Sep 2024 – Feb 2025. Joint project between registered broker Tradejini and a three-person team.*

**Stack:** TypeScript, Express, WebSockets, Redis, PostgreSQL (Prisma), AWS EC2

**Links:** [GitHub](https://github.com/parik-shit/Dooplicatoor) · [Demo video](https://www.youtube.com/watch?v=JGB86EK6fZY)

Dooplicatoor is a broker-agnostic trade replicator for Indian retail traders. Orders placed on a parent account are mirrored to many downstream accounts in real time.

* Replicated orders from one parent account to 10+ concurrent downstream accounts over persistent WebSocket connections, at >99% replication and sub-250 ms end-to-end latency.
* Abstracted three independent broker SDKs (AngelOne, CubePlus, Tradejini) behind one interface, handling divergent rate limits, reconnection behaviour and partial-failure modes.

<iframe style="width: 100%; aspect-ratio: 16 / 9; border: 0;" src="https://www.youtube-nocookie.com/embed/JGB86EK6fZY" title="Dooplicatoor demo" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
