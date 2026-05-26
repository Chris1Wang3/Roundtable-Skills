---
name: jiaye-skills
description: >-
  AI agent skill collection: OPC Board (one-person company feasibility stress-test),
  competitive product research, and PRD review simulation. All output professional,
  execution-oriented reports (Markdown + HTML).
  AI 技能合集：一人董事会（一人公司可行性压测）、竞品调研、需求评审模拟。
  均输出专业、面向执行的报告。
---

# Jiaye-Skills

本目录是 AI 技能合集，当前包含 3 个子技能：

1. `opc-board/`（一人董事会）
2. `competitive-product-research/`（竞品调研）
3. `requirement-review-simulator/`（需求评审模拟器）

## 技能列表

| 技能 | 目录 | 主要能力 |
|---|---|---|
| 一人董事会 | `opc-board/` | 5 位专业顾问五维压测一人公司想法，输出带评分的专业评估报告 + Go/No-Go 决策 |
| 竞品调研 | `competitive-product-research/` | 双轨分析（体验对标 + 战略诊断），输出竞品调研 HTML 报告 |
| 需求评审模拟器 | `requirement-review-simulator/` | 五方攻防推演、确定性评分，输出需求评审 HTML 报告 |

## 最短启动

- `帮我评审一下我做的 AI 周报 SaaS，实战模式。`（一人董事会）
- `请按竞品调研模式，对标 A/B 产品，输出对标总览、战略诊断、关键发现和落地动作清单。`（竞品调研）
- `请评审这个需求：会员体系2.0，实战模式，先给信息采集清单，再生成完整评审报告。`（需求评审）

## 目录约定

每个子技能目录应包含：

- `SKILL.md`：主规则与执行流程
- `README.md` / `README-zh.md`：对外说明（英文 + 中文）
- `claw.json`：上架元数据
- `references/`：模板与方法附录
