# AgentFeed Methodology

Public methodology for scoring AI agent frameworks on production-readiness.

This repository documents how AgentFeed evaluates agent frameworks like LangChain, CrewAI, LangGraph, AutoGen, and others. Scores produced using this methodology are published weekly in the AgentFeed newsletter.

## Status

🚧 **Work in progress.** This methodology is being actively developed and refined. v1.0 will be locked in before the AgentFeed newsletter launches.

## Why This Exists

The agent ecosystem has no shared definition of "production-ready." Frameworks compete on developer experience and feature breadth, but operational properties — security, isolation, observability, recoverability — remain undermeasured.

AgentFeed scores 16 major agent frameworks across 23 production-readiness criteria, every week. This repository is the single source of truth for how those scores are calculated.

## The Six Levels

AgentFeed assigns each framework a level based on weighted scores across 23 criteria:

- **L0 — Uncontrolled**: No meaningful production controls
- **L1 — Monitored**: Basic observability, minimal controls
- **L2 — Constrained**: Resource limits and basic guardrails
- **L3 — Accountable**: Audit trail and identity verification
- **L4 — Isolated**: Strong sandboxing and failure containment
- **L5 — Production-Grade**: Cryptographic integrity and full operational maturity

No framework currently sits at L5. Scores update weekly.

## The 23 Criteria

(Full criteria list, definitions, scoring rubric, and weights coming in v0.2 of this repo.)

## Right to Respond

Maintainers of any framework scored by AgentFeed are invited to respond to scores publicly. Open an issue in this repository tagged `framework-response` and your response will be linked from the relevant newsletter edition.

## Contributing

Methodology is open to public scrutiny and contribution. Open an issue to challenge a definition, propose a new criterion, or correct an error.

## License

MIT.

---

Built by @shaymizuno. Newsletter: agentfeed.dev (launching soon).

