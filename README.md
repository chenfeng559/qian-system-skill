# qian-system-skill

`qian-system-skill` is a Codex Skill for applying Qian Xuesen-inspired systems thinking to complex problems.

It is not a roleplay persona. It does not try to imitate Qian Xuesen’s identity or claim what he would personally say. Instead, it operationalizes a reusable method: classify the system, define boundaries and layers, move from qualitative judgment to quantitative evidence, synthesize through iteration, design an execution apparatus, and keep feedback loops explicit.

## What It Helps With

Use this skill when you need to analyze, plan, decide, execute, or review any complex system, including:

- company strategy
- product and platform systems
- AI agent workflows
- organizational transformation
- research programs
- city, education, health, or policy systems
- personal operating systems and long-term growth plans
- any problem where many actors, variables, layers, feedback loops, and external constraints interact

## Core Method

The skill follows this operating sequence:

1. Clarify the mission.
2. Classify the system.
3. Define boundaries and layers.
4. Move from qualitative judgment to quantitative evidence.
5. Synthesize through expert-data-model-tool iteration.
6. Design the “overall design department” or equivalent execution apparatus.
7. Output a phased decision and feedback mechanism.

The central principle is:

> Do not use a simple-system method on an open complex giant system.

## Skill Structure

```text
qian-system-skill/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── case-index.md
    ├── method-principles.md
    └── output-templates.md
```

## Files

- `SKILL.md`: the main trigger, workflow, behavioral rules, and reference loading guide.
- `references/method-principles.md`: generalized method principles for applying systems thinking to any system object.
- `references/output-templates.md`: reusable templates for analysis, decision memos, execution plans, overall design department plans, and postmortems.
- `references/case-index.md`: self-contained cases and transfer rules. It does not depend on an external PDF or source document.
- `agents/openai.yaml`: UI metadata for Codex skill lists.

## Example Prompts

```text
用钱学森系统工程的方法，分析我们公司的 AI 产品战略。
```

```text
把我的个人成长系统当成开放复杂巨系统，设计一个总体方案。
```

```text
用从定性到定量综合集成的方法，帮我评估这个业务转型方案。
```

```text
按总体设计部的方式，为这个研究项目设计组织结构、数据系统和反馈机制。
```

## Expected Output Style

The skill usually structures work as:

1. 问题性质
2. 系统边界
3. 关键子系统
4. 主要矛盾
5. 定性判断
6. 可量化指标
7. 方案推演
8. 总体设计部 / 执行组织
9. 推荐路径
10. 反馈与修正机制

For smaller tasks, the same logic is compressed.

## Installation

Clone this repository into your Codex skills directory:

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/chenfeng559/qian-system-skill.git ~/.codex/skills/qian-system-skill
```

Then restart Codex or reload available skills.

## Design Notes

This skill deliberately separates three things:

- **Method**: the reusable systems workflow.
- **Cases**: self-contained examples that teach transfer rules.
- **Templates**: practical output structures for execution.

This keeps the skill usable even when the original research materials are not available.

