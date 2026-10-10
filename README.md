# skill-share

Reusable AI agent skills that turn thinking methods and workflows into practical tools for understanding complex topics and solving real problems.

## Skill catalog

| Category | Skill | Purpose |
| --- | --- | --- |
| Thinking | [distill-core](skills/thinking/distill-core/SKILL.md) | Understand the purpose, mechanisms, necessary roles, and limits of complex subjects step by step. |

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
