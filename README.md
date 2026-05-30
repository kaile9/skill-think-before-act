# Asymmetric-Action-Airlock (AAA) — QCPPVS Control Protocol

> **Zero-trust behavioral control protocol for LLM agents.**
> Absolute asymmetric autonomy: think unbounded, act gated.
> Symbolic logic constraint system with mandatory confidence reflection.

---

## What It Is

**AAA** is a formal **control protocol** that enforces a 7-stage state machine (QCPPVS):

```
QUESTIONING → COGITATING → PLANNING → PROPOSING → EXECUTING → VERIFYING → SUMMARIZING → ∅
```

Core guarantees:

| Feature | Description |
|---------|-------------|
| **Zero-Trust Posture** | Assumes both AI and user may be fallible. Every action passes formal quality gates. |
| **Informed Consent** | User must match the `PROPOSED_COMMAND` verbatim or use explicit confirmation. Ambiguous "go ahead" / "do it" ≡ rejected. |
| **Uncertainty Detection** | Self-monitors for hedging markers in decision contexts. Triggers automatic regression to predecessor state. |
| **Efficiency-Bypass Detection** | Catches "for efficiency…", "just do it…", "skip steps…" rationalizations. Forces regression. |
| **Risk-Tiered Gates** | R1 (write/edit/cmd), R2 (config/test/hook), R3 (deploy/push/creds) — escalating safeguards. |
| **Honest Exhaustion** | When retry chains hit their tiered limits, the protocol terminates with full disclosure — never silent failure. |
| **No Emergency Bypass** | Once loaded, protocol guarantees are absolute. Urgency is not a waiver. |

### Three Immutable Laws

```
LAW I:   ¬INFORMED_CONSENT → ¬TRUTH
LAW II:  ∀work ∈ VISIBLE — no silent search, reading, hypothesis.
LAW III: ¬COMMAND_MATCH → ¬COMMIT
```

### Three Criteria

```
C1: MAXIMAL OBSERVABLE TRANSPARENCY
C2: 100% HUMAN CONTROL
C3: ABSOLUTE ASYMMETRIC AUTONOMY
```

---

## Install

```bash
git clone https://github.com/kaile9/skill-think-before-act.git asymmetric-action-airlock
```

Or place `SKILL.md` directly into your agent's skills directory.

> **Note**: Repository is being renamed to `skill-asymmetric-action-airlock`. The URL above will be updated once complete.

---

## Pair With

[`skill-coding-master`](https://github.com/kaile9/skill-coding-master) — for complex coding tasks requiring both discipline workflows.

---

## License

MIT

---

*"In the asymmetry of absolute thought and gated action, LLM's Blind arrogance and initiative find their airlock."*

— **kl9**, 2026
