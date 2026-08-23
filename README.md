# 0xCaptain888

### I build the execution layer that keeps autonomous AI agents inside policy.

Agents can act — but never beyond a defined budget, permission, risk boundary, or verification rule.

<p>
  <a href="https://github.com/0xCaptain888/agent-control-plane"><img src="https://img.shields.io/badge/core-agent--control--plane-111827?style=flat-square&logo=github&logoColor=white" alt="Agent Control Plane"></a>
  <a href="https://github.com/0xCaptain888/agent-control-plane/actions/workflows/ci.yml"><img src="https://img.shields.io/github/actions/workflow/status/0xCaptain888/agent-control-plane/ci.yml?branch=main&style=flat-square&label=checks" alt="CI checks"></a>
  <a href="https://github.com/0xCaptain888/agent-control-plane"><img src="https://img.shields.io/badge/Node-22-3c873a?style=flat-square&logo=node.js&logoColor=white" alt="Node 22"></a>
  <a href="https://github.com/0xCaptain888/agent-control-plane/blob/main/SECURITY.md"><img src="https://img.shields.io/badge/security-policy-0f766e?style=flat-square" alt="Security policy"></a>
</p>

## The thesis

The missing layer in agent infrastructure is not another model or marketplace. It is a **policy-controlled execution layer** that can decide whether an agent is still allowed to act — at every step — and leave evidence when it does.

```text
Intent → Policy → Risk → Execute → Verify → Recover → Receipt
```

## Core project

### [Agent Control Plane](https://github.com/0xCaptain888/agent-control-plane)

Policy-controlled, verifiable execution infrastructure for autonomous AI agents.

It gives agents bounded capabilities to trade, pay, call APIs, use MCP tools, manage assets, and execute workflows without turning an LLM into an unchecked custodian.

| Layer | What it guarantees |
| --- | --- |
| Policy | permissions, budgets, targets, approvals, time windows |
| Risk | simulation, exposure, duplication, slippage, runtime drift |
| Execution | exchange, chain, payment, MCP, x402, and workflow adapters |
| Verification | outcome checks before release or settlement |
| Recovery | cancel, refund, freeze, retry, and circuit-breaker paths |
| Receipts | auditable decisions, proofs, and execution history |

## Judge-first proof

The repository is organized around reference applications rather than disconnected demos:

- **[Safe Trade](https://github.com/0xCaptain888/agent-control-plane/tree/main/examples/safe-trade)** — bounded trading with approved and frozen outcomes.
- **[Agent Commerce](https://github.com/0xCaptain888/agent-control-plane/tree/main/examples/agent-commerce)** — quote, escrow, verification, release, and recovery.
- **[API Procurement](https://github.com/0xCaptain888/agent-control-plane/tree/main/examples/api-procurement)** — pay only after the purchased result is verified.
- **[OKX Trade](https://github.com/0xCaptain888/agent-control-plane/tree/main/examples/okx-trade)** — judge-ready exchange flow with explicit blocked and frozen paths.
- **[Solana Devnet](https://github.com/0xCaptain888/agent-control-plane/tree/main/examples/solana-devnet)** — resilient RPC, external signing, confirmation, and auditable failure handling.

## What I am building next

Reusable adapters and proof-oriented workflows for exchanges, chains, MCP, x402, and agent-to-agent execution — while keeping the control plane domain-neutral.

## Find the signal quickly

- [Core repository](https://github.com/0xCaptain888/agent-control-plane)
- [Architecture](https://github.com/0xCaptain888/agent-control-plane/blob/main/docs/architecture.md)
- [Hackathon guide](https://github.com/0xCaptain888/agent-control-plane/blob/main/docs/hackathon-guide.md)
- [Local integration safety](https://github.com/0xCaptain888/agent-control-plane/blob/main/docs/local-development.md)

<details>
<summary>Selected experiments</summary>

- [agentpay](https://github.com/0xCaptain888/agentpay) — programmable wallets and payment rails for agents.
- [agentbank](https://github.com/0xCaptain888/agentbank) — policy-controlled treasury automation.
- [agentcourt](https://github.com/0xCaptain888/agentcourt) — evidence, proof, and dispute handling.
- [kitehive](https://github.com/0xCaptain888/kitehive) — an agent-to-agent labor market and settlement experiment.

</details>
