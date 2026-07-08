# GTM Decision Lab

Most GTM agents write plans.

**GTM Decision Lab tells you which GTM decisions you should not trust yet.**

大多数 GTM AI 工具会帮你写一份看起来完整的市场计划。  
但早期产品真正危险的地方，不是没有计划，而是把没有证据的判断当成战略。

**GTM Decision Lab 是一个面向早期产品的 GTM 决策 Skill。**  
它帮助 founder、独立开发者、AI 产品团队、B2B SaaS 团队、PMM 和增长负责人，把混乱的产品信息、客户反馈和市场假设，整理成一份可以执行、可以质疑、可以验证的 GTM 决策简报。

## What it does

It turns messy product and customer notes into a defensible GTM decision brief, including:

- beachhead segment
- GTM motion
- positioning hypothesis
- channel bets
- validation experiments
- evidence, assumption, and risk ledger

## 它解决什么问题

早期 GTM 最大的问题通常不是“不知道怎么营销”，而是：

- 不知道第一个客户群到底是谁
- 把大市场误认为好市场
- 把创始人的直觉误认为客户证据
- 选了热门渠道，却不知道买家是否真的在那里
- 写了漂亮定位，但没有任何 proof point
- 把 PLG、outbound、content、community 当成流行词，而不是决策
- 在没有验证前，就开始做完整 campaign

GTM Decision Lab 的目标不是生成一份漂亮方案，而是帮你回答：

> 这个 GTM 判断，现在到底能不能信？

## Core principle

Most GTM agents generate plans.  
**This skill generates GTM decisions with confidence levels, assumption flags, and validation gates.**

多数 GTM agent 生成计划。  
**这个 Skill 生成带置信度、假设标记和验证门槛的 GTM 判断。**

## When to use

Use this skill when you need to:

- choose a first beachhead segment
- pressure-test a GTM idea
- select a GTM motion
- design early validation experiments
- separate evidence from assumptions
- turn product notes into a decision-ready GTM brief
- identify which GTM claims are still unsafe to make

## 适合谁用

- 早期 founder
- 独立开发者
- AI 产品构建者
- B2B SaaS 团队
- developer tool 团队
- PMM / growth operator
- 孵化器、顾问、投资分析场景

如果你已经有成熟销售团队、完整 CRM、历史 campaign 数据和明确市场预算，这个 Skill 不是替代你的 GTM ops 系统。  
它更适合在早期帮你做第一版市场进入判断。

## What makes it different

Instead of only asking:

> What is the GTM plan?

It asks:

> What evidence supports this GTM plan?  
> Which assumptions could break it?  
> What should we validate before scaling?

它不会默认“你说的目标客户就是目标客户”。  
它会检查：

- 这个 segment 是否具体
- pain 是否真实
- urgency 是否存在
- buyer 是否可触达
- 是否有付费能力
- 当前替代方案是什么
- 这个渠道为什么能触达买家
- 哪些定位 claim 还没有证据

## Structure

```text
gtm-decision-lab/
  SKILL.md
  agents/
    openai.yaml
  references/
    evidence-standards.md
    gtm-motions.md
    scoring-rubric.md
    source-map.md
    validation-experiments.md
  assets/
    gtm-decision-brief-template.md
    experiment-plan-template.md
```

## Installation

Download or clone this repository, then place the `gtm-decision-lab` folder into your local skills directory.

Then invoke it with:

```text
Use $gtm-decision-lab to analyze this product and create a GTM decision brief.
```

Example input:

```text
We are building an AI tool for small B2B SaaS teams that summarizes sales calls and identifies churn risks. We have 20 waitlist signups, 3 user interviews, and no revenue yet. Help us choose a beachhead segment and validation plan.
```
