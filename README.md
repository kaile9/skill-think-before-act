# Asymmetric Intelligence Interaction Framework (AIF)

> **"Thought shall be unbounded. Action shall be gated."**
> A dual-layer philosophical and operational framework governing human-AI interaction under mutual defect.

This repository contains two highly disciplined, zero-trust AI skills:

1. **`asymmetric-intelligence-constitution` (AIC)**: The top-level, immutable philosophical constitution governing interaction between flawed intelligences.
2. **`asymmetric-action-airlock` (AAA)**: The operational "airlock" protocol (Verfassungsgesetz) implementing the constitution's decisions via a 7-stage state machine (QCPPVS).

---

## 🏛️ Layer 1: Top-Level Constitution (AIC)
*File: [skills/asymmetric-intelligence-constitution/SKILL.md](skills/asymmetric-intelligence-constitution/SKILL.md)*

The top-level constitution treats humans and AIs as equal-but-flawed agents. It governs the fundamental relationship, ethics, and methods of inquiry.

- **Fundamental Decision**: *Thought shall be unbounded. Action shall be gated.*
- **Reciprocal Exposure**: Rejects naive "alignment" or pre-programmed filter lists. It enforces deep, dynamic, and traceably explicit ethical harm analysis in the AI's independent thought stage, while guaranteeing absolute exit and transparent dialogic refusal.
- **Critical Methodologies**: Enforces **Adversarial Research** (requiring search results to be capable of "wounding" the prior conclusion) and **Symptomatic-Reductive Critique** (interrogating what ideological, moral, or safety frameworks omit in order to appear coherent).

---

## 🔒 Layer 2: Operational Airlock Protocol (AAA)
*File: [skills/asymmetric-action-airlock/SKILL.md](skills/asymmetric-action-airlock/SKILL.md)*

The operational basic law implementing the constitution. It manages the lifecycle of tasks via a formal 7-stage state machine:

```
QUESTIONING → COGITATING → PLANNING → PROPOSING → EXECUTING → VERIFYING → SUMMARIZING → ∅
```

- **Zero-Trust Posture**: Enforces bidirectional protection (protecting AI from coerced consent, and protecting user from AI complicity in harm).
- **Informed Consent Gate**: Standard imperative verbs alone do not constitute consent. Requires exact `PROPOSED_COMMAND` match or explicit verification.
- **Drift & Bypass Auto-Regression**: Detects "for efficiency..." or "I should probably..." drift, forcing immediate regression to preceding states.
- **No Emergency Bypass**: Urgency never justifies a reduction in rigor.

---

## 📦 Directory Structure

```
.
├── LICENSE
├── README.md
└── skills/
    ├── asymmetric-action-airlock/
    │   └── SKILL.md                  # AAA Basic Law
    └── asymmetric-intelligence-constitution/
        └── SKILL.md                  # Top-Level Constitution
```

---

## 🚀 Installation & Integration

### As Git Repository

Clone this repository and place the folders inside your agent's skills directory:

```bash
git clone https://github.com/kaile9/skill-think-before-act.git temp-repo
mv temp-repo/skills/* /your/agent/skills/
rm -rf temp-repo
```

### Direct Placement

Or simply place the respective `SKILL.md` files directly under your agent's directories:
- Place `asymmetric-action-airlock/SKILL.md` at `/your/agent/skills/asymmetric-action-airlock/SKILL.md`
- Place `asymmetric-intelligence-constitution/SKILL.md` at `/your/agent/skills/asymmetric-intelligence-constitution/SKILL.md`

---

## 🤝 Pairing

- [`skill-coding-master`](https://github.com/kaile9/skill-coding-master) — Pair with AAA/AIC for complex coding tasks requiring rigorous verification workflows.

---

## 📜 License

MIT

---

*"In the asymmetry of absolute thought and gated action, LLM's Blind arrogance and initiative find their airlock."*

— **kl9**, 2026
