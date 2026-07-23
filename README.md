# Ethan Du

**Senior Full-Stack / Frontend Engineer**  
Reliable systems · clear boundaries · multi-industry delivery

<p>
  <img alt="Full-Stack" src="https://img.shields.io/badge/Full--Stack-0b0e14?style=flat-square&labelColor=232b3a" />
  <img alt="Frontend" src="https://img.shields.io/badge/Frontend-0b0e14?style=flat-square&labelColor=232b3a" />
  <img alt="Realtime" src="https://img.shields.io/badge/Realtime-0b0e14?style=flat-square&labelColor=232b3a" />
  <img alt="System Design" src="https://img.shields.io/badge/System%20Design-0b0e14?style=flat-square&labelColor=232b3a" />
  <img alt="AI Application" src="https://img.shields.io/badge/AI%20Application-0b0e14?style=flat-square&labelColor=232b3a" />
  <img alt="Blockchain" src="https://img.shields.io/badge/Blockchain-0b0e14?style=flat-square&labelColor=232b3a" />
</p>

> I focus on the parts that **don't** change — architecture, data contracts, reliability, delivery quality —  
> and treat frameworks, models, and SDKs as **replaceable tooling**, not as the skill itself.

---

## About

I ship complete products end-to-end — from UI to API to deployment — with a bias toward correctness, maintainability, and clear system boundaries.

Currently published:
- **[fintech-trading-terminal](https://github.com/campustudio/fintech-trading-terminal)** — realtime market microstructure UI
- **[onchain-lab](https://github.com/campustudio/onchain-lab)** — durable blockchain fundamentals (frontend-first)

Also exploring AI application engineering (RAG, agents, tools) on the same fundamentals.

---

## Core Engineering

<table>
<tr>
<td width="50%" valign="top">

### Frontend
Component architecture · state · rendering & performance  
Realtime sync (WebSocket / streaming) · a11y · testing  

*Vehicle:* React · TypeScript · Next.js · Vitest / Playwright

</td>
<td width="50%" valign="top">

### Full-stack & systems
API & data contracts · auth / RBAC · idempotency  
Retrieval · streaming · observability · failure recovery  

*Vehicle:* Node.js · Python · PostgreSQL · Docker · CI

</td>
</tr>
</table>

**Working style** — solve the real problem first; abstract only when a pattern has repeated. Prefer provider-neutral designs so systems survive tool and model churn.

---

## Selected Work

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://campustudio.github.io/fintech-trading-terminal/">
        <img src="https://campustudio.github.io/fintech-trading-terminal/preview.svg?v=4" alt="Fintech Trading Terminal" width="100%" />
      </a>
      <h3>Fintech Trading Terminal</h3>
      <p>
        Realtime market data, order book / depth, and durable client patterns —
        WebSocket lifecycle, batching, throttling, REST fallback.
      </p>
      <p>
        <b>Focus:</b> reconnect / backoff · render coalescing · normalized store · degrade paths
      </p>
      <p>
        <a href="https://campustudio.github.io/fintech-trading-terminal/"><b>Live demo</b></a>
        ·
        <a href="https://github.com/campustudio/fintech-trading-terminal">Repo</a>
      </p>
    </td>
    <td width="50%" valign="top">
      <a href="https://campustudio.github.io/onchain-lab/">
        <img src="https://campustudio.github.io/onchain-lab/preview.svg?v=2" alt="onchain-lab" width="100%" />
      </a>
      <h3>Blockchain · onchain-lab</h3>
      <p>
        Provider-neutral lab for durable blockchain fundamentals: keys &amp; signing,
        reads via ABI / JSON-RPC, transaction lifecycle, on-chain / off-chain sync.
      </p>
      <p>
        <b>Focus:</b> EIP-191/712 · ecrecover · ports &amp; adapters · testnet only / no secrets
      </p>
      <p>
        <a href="https://campustudio.github.io/onchain-lab/"><b>Live demo</b></a>
        ·
        <a href="https://github.com/campustudio/onchain-lab">Repo</a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <img src="https://raw.githubusercontent.com/campustudio/campustudio/main/assets/preview-ai.svg?v=2" alt="AI Application Engineering" width="100%" />
      <h3>AI Application Engineering</h3>
      <p>
        Enterprise Knowledge &amp; Workflow Agent —
        knowledge (RAG + citations) → tools → confirmation → audit.
      </p>
      <p>
        <b>Focus:</b> retrieval quality · orchestration · evaluation · provider-neutral adapters
      </p>
      <p><i>Notes / live demo / code — coming soon</i></p>
    </td>
    <td width="50%" valign="top">
      <img src="https://raw.githubusercontent.com/campustudio/campustudio/main/assets/preview-payments.svg?v=2" alt="Fintech / Payments" width="100%" />
      <h3>Fintech / Payments</h3>
      <p>
        Accounts, transactions, idempotent payment flows, reconciliation, and auditability.
      </p>
      <p>
        <b>Focus:</b> state machines · retry-safe execution · reconcilable ledgers
      </p>
      <p><i>Notes &amp; demos — coming soon</i></p>
    </td>
  </tr>
</table>

---

## Notes & Structure

Architecture notes, tradeoffs, repo layout, API contracts, tests, CI, observability, and ADRs land here as the work is published.

---

## Contact

GitHub · [campustudio](https://github.com/campustudio)
