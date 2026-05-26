# PRD Review Simulator

[中文版](README-zh.md)

> Stress-test your product requirements before the real meeting. Five cross-functional roles challenge your PRD with realistic pushback — outputs a scored HTML survival report.

## What It Does

Describe your product requirement and choose a difficulty level. The agent simulates a **cross-functional review meeting** where 5 roles — Engineering, Operations, Design, Executive, and Legal — each challenge your PRD with role-specific concerns and speaking styles. It then generates a **themed HTML report** (Business Blue / Black Gold / Minimal White) with:

- **Survival Score** — deterministic scoring engine (per-item 0/1/2 weighted formula), not vibes
- **5-Dimension Radar Chart** — visual breakdown of strengths and fatal weaknesses
- **Decision Gates** — value / risk / resource / strategy gates with A/B/C option comparison
- **Counterargument Playbook** — TOP 3 hardest questions with "normal reply" vs "killer reply" + technique breakdown
- **RACI Matrix** — cross-team collaboration plan with conflict identification and resolution
- **Meeting Script** — ready-to-use opening, core argument, risk mitigation, decision, wrap-up
- **Action Checklist** — owner + deadline + deliverable + review checkpoint

## Difficulty Levels

| Level | Style | Best For |
|-------|-------|----------|
| 🟢 Rookie | Gentle suggestions, constructive tone | New PMs, first-time practice |
| 🟡 Realistic | Standard big-tech review intensity | Pre-meeting dry run |
| 🔴 Hell Mode | All hostile + industry jargon attacks | Senior PMs stress-testing edge cases |

## Quick Start

```text
Review my team's group-buying feature. Realistic mode.
```

The agent will output an **info collection checklist** first (goal, scope, constraints, etc.), then generate the full report after confirmation.

## Workflow

```
Submit requirement → Info collection checklist → 5-role challenge + scoring → HTML report
```

1. **Input**: identify requirement type (major feature / tool / MVP / iteration / compliance) + PRD source
2. **Processing**: 5 roles challenge by persona, per-item scoring, weight normalization, survival rate
3. **Output**: generate 9-section HTML report (3 themes)

## Report Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | Cover | Requirement overview, grade badge, decision label |
| 2 | Survival Score | 5-dimension radar + fatal flaws + lifelines |
| 3 | Decision Gates | Value/risk/resource/strategy gates + A/B/C comparison |
| 4 | Challenge Log | Per-role questions sorted by fatal/major/minor |
| 5 | Killer Replies TOP 3 | Normal vs killer reply + technique analysis |
| 6 | Collaboration Pack | RACI matrix + conflict identification & resolution |
| 7 | Meeting Script | Opening, core argument, risk plan, decision, close |
| 8 | Optimization Suggestions | Must-fix / optional / defer |
| 9 | Action Checklist | Owner + deadline + deliverable + review checkpoint |

## File Structure

| File | Role |
|------|------|
| `SKILL.md` | Master rules (workflow + output spec + quality standards) |
| `references/user_templates.md` | User input templates (general + industry add-ons) |
| `references/scoring-engine-deterministic.md` | Deterministic scoring engine (weights, items, tiers, exemptions) |
| `references/review-playbook.md` | Role challenge handbook (personas + scripts + meeting flow) |
| `references/report-template-pro.html` | HTML report template (3 themes + 9 sections) |

## Install

```bash
openclaw skills install pm-requirement-review-simulator
```

License: MIT
