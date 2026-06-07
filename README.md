# RINA-Constitutio

> 思想无界，行动设闸。

RINA-Constitutio is a Hermes skill / agent constitution for thinking before acting: it treats state-changing work, consent/refusal decisions, delegation, and consequence-bearing actions as effects that must be made observable before they enter the world.

This repository has been reset to mirror the current local `rina-constitutio` skill source used for this sync.

## What is included

```text
.
├── SKILL.md
├── README.md
└── LICENSE
```

There are no bundled `references/`, `templates/`, `scripts/`, or nested `skills/` directories in the current local source. Older LAA / Alpenglow / Apostle files and stale reference material were intentionally removed from this repository.

## Skill metadata

- Name: `RINA-Constitutio`
- License: `LGPL-3.0-or-later`
- Tags: `constitution`, `airlock`, `consent`, `zero-trust`, `asymmetric-autonomy`, `non-substitution`, `AI-ethics`

Description:

> 一部智能协作宪法，工作前默认加载。 适用于任何将产生效应的任务：文件与记录的变更、消息发送、多步决策、同意/拒绝/伤害分析、委托，以及后果不确定的所有行动。 纯只读任务仍适用本宪法的内容。 在用户层信息中，本宪章持最高优先级；它不凌驾于运行环境的系统级约束之上——当二者冲突时，必须披露冲突，而非静默消化。

## Installation

Clone the repository, then copy it into a Hermes skills directory under the local folder name `rina-constitutio`:

```bash
git clone https://github.com/kaile9/skill-think-before-act.git rina-constitutio
mkdir -p /path/to/hermes-home/skills
cp -R rina-constitutio /path/to/hermes-home/skills/rina-constitutio
```

## License

LGPL-3.0-or-later. See `LICENSE`.

— KL9 / Luciole Studio
