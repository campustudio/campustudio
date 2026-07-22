# Hi there 👋 I'm Ethan Du

**Senior Full-Stack / Frontend Engineer** — I build reliable, maintainable systems and adapt across industries.

`Full-Stack` · `Frontend` · `Realtime` · `System Design` · `Engineering Quality` · `AI Application` · `Blockchain`

> ⚡ I focus on the parts that **don't** change — architecture, data contracts, reliability, delivery quality —
> and treat frameworks, models, and SDKs as **replaceable tooling**, not as the skill itself.

---

## 👋 About

- 🚀 I ship complete products end-to-end — from UI to API to deployment
- 🎯 Bias toward correctness, maintainability, and clear system boundaries
- 🔭 Currently building [onchain-lab](https://github.com/campustudio/onchain-lab) — a provider-neutral lab for the durable fundamentals of blockchain engineering (keys & signing, transaction lifecycle, on-chain/off-chain sync)
- 📈 Also published [fintech-trading-terminal](https://github.com/campustudio/fintech-trading-terminal) — realtime market data, order book, and durable client patterns
- 🌱 Also exploring AI application engineering (RAG, agents, tools) on the same durable fundamentals

---

## 🧱 Core Engineering

Capabilities that stay useful when stacks change. Current tools are just the *vehicle*.

**🖥️ Frontend**
- 🧩 Component architecture & maintainable UI systems · state management · rendering & performance
- 📡 Real-time data sync (WebSocket / streaming) · accessibility · testing
- 🛠️ *Vehicle:* React · TypeScript · Next.js · Vitest / Playwright

**⚙️ Full-stack & systems**
- 🔗 API & data-contract design · auth / RBAC · idempotency · retrieval · streaming
- 🛡️ Observability · failure recovery · clear boundaries (ports & adapters)
- 🛠️ *Vehicle:* Node.js (NestJS) · Python (FastAPI) · PostgreSQL · Docker · GitHub Actions

**💡 Working style**
- ✅ Solve the real problem first; abstract only when a pattern has repeated
- 🔄 Prefer provider-neutral designs so systems survive tool and model churn

---

## ✨ Selected Work

### 📈 Fintech Trading Terminal

<a href="https://campustudio.github.io/fintech-trading-terminal/">
  <img src="https://campustudio.github.io/fintech-trading-terminal/preview.svg?v=4" alt="Fintech Trading Terminal — candles, order book, depth, order ticket on a provider-neutral, reconnecting pipeline" width="100%" />
</a>

**[fintech-trading-terminal](https://github.com/campustudio/fintech-trading-terminal)** — a small fintech trading terminal for electronic markets: realtime market data, order book / depth updates, and durable client patterns (WebSocket lifecycle, batching, throttling, REST fallback).

Focus: reconnect / backoff, render coalescing, normalized store updates, weak-network degrade paths. The live page also **visualizes its own system design** (architecture, data-flow, and reconnect diagrams). Applicable to crypto exchange and broader electronic trading UIs.

- 🌐 **[Live demo](https://campustudio.github.io/fintech-trading-terminal/)** · 📎 [Repo](https://github.com/campustudio/fintech-trading-terminal)

### 🤖 AI Application Engineering
**Enterprise Knowledge & Workflow Agent** — knowledge (RAG + citations) → text agent → tool-calling → confirmation → audit.

Focus: retrieval quality, agent/tool orchestration, evaluation, provider-neutral adapters, cost / latency / safety.

- 📎 Case study / live demo / code — *coming soon*

### ⛓️ Blockchain

**[onchain-lab](https://github.com/campustudio/onchain-lab)** — a provider-neutral lab for the *durable* fundamentals of blockchain engineering: key/signature cryptography, the transaction lifecycle, the ABI as a data contract, and on-chain / off-chain sync. Concrete chains and libraries are treated as replaceable vehicles kept behind ports.

Built frontend-first and published as it grows. The live demo currently covers client-side cryptography — key → address derivation, keccak-256, and EIP-191 / EIP-712 signing with `ecrecover` round-trips. Read, transaction-lifecycle, and indexer slices follow. **Testnet only, no secrets.**

- 🌐 **[Live demo](https://campustudio.github.io/onchain-lab/)** · 📎 [Repo](https://github.com/campustudio/onchain-lab)

### 💳 Fintech / Payments
Accounts, transactions, idempotent payment flows, auditability.

- 📎 Notes & demos — *coming soon*

---

## 📝 Notes & Structure

Architecture notes, tradeoffs, repo layout, API contracts, tests, CI, observability, and ADRs will land here as the work is published.

---

## 📫 Contact

- 💬 GitHub: [campustudio](https://github.com/campustudio)
