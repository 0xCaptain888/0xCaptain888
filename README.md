# 0xCaptain888

### I build the execution layer that keeps autonomous AI agents inside policy.

Agents can act, coordinate and pay — but never beyond a defined budget,
permission, risk or verification boundary.

<p>
  <a href="https://github.com/0xCaptain888/ethonline-agentguard"><img src="https://img.shields.io/badge/flagship-ETHOnline%20AgentGuard-111827?style=flat-square&logo=github&logoColor=white" alt="ETHOnline AgentGuard"></a>
  <a href="https://github.com/0xCaptain888/agent-control-plane"><img src="https://img.shields.io/badge/core-Agent%20Control%20Plane-1d4ed8?style=flat-square&logo=github&logoColor=white" alt="Agent Control Plane"></a>
  <a href="https://github.com/0xCaptain888/ethonline-agentguard/actions/workflows/ci.yml"><img src="https://img.shields.io/github/actions/workflow/status/0xCaptain888/ethonline-agentguard/ci.yml?branch=main&style=flat-square&label=ETHOnline%20checks" alt="ETHOnline checks"></a>
</p>

## The thesis

The missing layer in agent infrastructure is not another model or marketplace.
It is a policy-controlled execution layer that can decide whether an agent is
still allowed to act — at every step — and leave evidence when it does.

```text
Intent → Policy → Risk → Execute → Verify → Recover → Receipt
```

## Current flagship: AgentGuard

### [ETHOnline AgentGuard](https://github.com/0xCaptain888/ethonline-agentguard)

The ETHOnline 2026 Continuity submission: live blockchain data informs an
autonomous buyer, bounded authority controls the spend, and an independent
verifier decides whether USDC is released.

```text
The Graph → Policy Engine → Privy authorization → Arc USDC escrow
→ Seller Agent → Independent Verifier → VERIFIED / BLOCKED / FROZEN
```

The repository includes a judge-first Demo, Continuity before/after record,
machine-readable evidence manifest, sponsor fit notes and reproducible checks.

## AgentGuard family

- **[Agent Control Plane](https://github.com/0xCaptain888/agent-control-plane)** — generic policy-controlled execution foundation.
- **[Monad AgentGuard](https://github.com/0xCaptain888/monad-agentguard)** — Monad deployment, benchmarks and baseline evidence.
- **[Binance AgentGuard](https://github.com/0xCaptain888/binance-agentguard)** — Binance Agentic execution adapter with independent verification.

These are one capability expressed through different chains and execution
venues, not unrelated products.

## Capability map

| Layer | What it controls |
| --- | --- |
| Policy | permissions, budgets, targets, approvals and time windows |
| Risk | exposure, duplication, slippage, runtime drift and circuit breakers |
| Execution | exchange, chain, payment, MCP, x402 and workflow adapters |
| Verification | outcome checks before release or settlement |
| Recovery | cancel, refund, freeze, retry and escalation paths |
| Receipts | auditable decisions, proofs and execution history |

## Selected experiments

Earlier repositories across Arc, Solana, Arbitrum, OKX, BNB, DeFi and privacy
are preserved as experiments and continuity context. The current product thesis
is AgentGuard: make autonomous economic activity bounded, verifiable and
recoverable.

- [agentpay](https://github.com/0xCaptain888/agentpay) — programmable wallets and payment rails.
- [agentbank](https://github.com/0xCaptain888/agentbank) — multi-agent treasury automation.
- [agentcourt](https://github.com/0xCaptain888/agentcourt) — proof and dispute handling.
- [kitehive](https://github.com/0xCaptain888/kitehive) — Agent-to-Agent labor-market experiment.

## Find the signal quickly

- [ETHOnline submission](https://github.com/0xCaptain888/ethonline-agentguard)
- [Public ETHOnline Demo](https://0xcaptain888.github.io/ethonline-agentguard/)
- [Core repository](https://github.com/0xCaptain888/agent-control-plane)
- [Repository map](https://github.com/0xCaptain888/ethonline-agentguard/blob/main/docs/repo-map.md)
- [Judge scoring map](https://github.com/0xCaptain888/ethonline-agentguard/blob/main/docs/scoring-map.md)
- [X / @0xCaptain888](https://x.com/0xCaptain888)
