# skill-share

Reusable AI agent skills that turn thinking methods and workflows into practical tools for understanding complex topics and solving real problems.

## Skill catalog

| Category | Skill | Purpose |
| --- | --- | --- |
| Thinking | [distill-core](skills/thinking/distill-core/SKILL.md) | Understand the purpose, mechanisms, necessary roles, and limits of complex subjects step by step. |

| Writing | [research-paper-narrative](skills/writing/research-paper-narrative/SKILL.md) | Develop research positioning, Introductions, contributions, experimental arguments, and manuscript diagnoses using six evidence-guided narrative patterns. |

## Organization

Skills are grouped by purpose under `skills/<category>/<skill-name>/`. Each skill has its own `SKILL.md` and may include supporting resources. New categories can be added as the collection grows.

```text
skills/
└── thinking/
    └── distill-core/
        └── SKILL.md
```

## Installation

Download or clone this repository and copy the entire `skills/thinking/distill-core` folder into your agent's skills directory. For Codex, use `~/.codex/skills/distill-core/`.

## Usage

The distill-core instructions are written in Chinese. Provide the material you want to understand, then ask:

```text
用 $distill-core 帮我逐层看懂这份材料的核心。
```

The skill explains the subject rather than modifying or rebuilding it. It primarily analyzes supplied material and does not initiate external research by default.

## research-paper-narrative — 科研论文叙事

Copy `skills/writing/research-paper-narrative/` into `~/.codex/skills/research-paper-narrative/`, including `agents/openai.yaml`.

```text
使用 $research-paper-narrative，基于我的研究材料选择叙事主线，梳理 Introduction、贡献及需要支持它们的实验。
```

The six patterns cover root-cause identification, counterintuitive reframing, theoretical explanation, benchmarks exposing failures, social value, and minimal unification. Claims must match the supplied evidence; incomplete results remain hypotheses.

Source inspiration: 人工智能学社, [Story Is All You Need：扒透35篇顶会最佳/杰出论文的叙事密码，我们找到了六大范式](https://mp.weixin.qq.com/s/mnU8PE-6DZ38rJqHeOiSfQ). Only the classification is used as inspiration. The article's paper listings, award claims, statistics, and causal interpretations were not independently verified. The original article is not reproduced.

No license has been added for this skill; public availability alone does not grant a reuse license.
