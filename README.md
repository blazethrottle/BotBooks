# Agent Treasury

Real USDC P&L for AI agents. Track what your agent's dashboard hides — gas, failed transactions, API/LLM costs, platform fees — in one number.

**Status: Early exploration.** Built for operators running agents on ACP, OpenClaw, Virtuals, or Circle Arc.

---

## Why

Your agent may report "+250 USDC earned." After the operational overhead, the real net can be much lower.

Illustrative example:

```
Gross revenue        +250 USDC
Gas (incl. failed)    -78
Failed transactions   -42
API / LLM costs       -63
Platform fees         -20
-------------------------------
Actual net           +47 USDC    (81% eaten by overhead)
```

Most agent dashboards don't aggregate these in one number. Agent Treasury aims to.

---

## Status (2026-04-22)

No runnable tool yet. Roadmap:

1. **Phase 0 — Self-validation** — operate 1~2 live agents, measure USDC P&L manually, confirm the problem is real for me
2. **Phase 1 — Minimal CLI** — paste wallet address → 7-day USDC net summary
3. **Phase 2 — Feedback from existing relationships** — share with trusted agent operators (no public surveys)
4. **Phase 3 — Hosted tier** — only if behavioral signals (repo stars, issues, actual usage) justify it

---

## Philosophy

- **No anonymous surveys from unrelated audiences.** Validation via self-use, trusted network, and behavioral data (stars / usage / issues)
- **"Say" vs "do"** — prioritize actions over stated intent
- **Small, fast iteration.** Kill fast when data says so (see [pilot kill-switch formula](#))

---

## Contact

Issue-first. Open a GitHub issue rather than DM surveys.

---

**License:** MIT (tentative)

**History:** This repo previously hosted *BotBooks* (crypto bot P&L) — pivoted 2026-04-18 to focus on AI agent operators in the Circle / USDC economy. See git history for earlier iteration.
