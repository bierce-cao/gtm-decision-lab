[README.md](https://github.com/user-attachments/files/29791544/README.md)
# GTM Decision Lab

**Stop asking AI for GTM plans. Start asking which market assumptions are still unsafe.**

GTM Decision Lab is a market and demand reality-check skill for AI builders, early-stage founders, indie hackers, B2B SaaS teams, developer tool builders, PMMs, growth operators, incubators, and advisors.

It does not help you make an unvalidated idea sound more investable. It helps you decide whether the target customer, market demand, adoption path, and GTM assumptions are real enough to **build, validate, or hold**.

---

## 介绍

现在 AI 让“做东西”变便宜了，但没有让“有人需要、愿意信、愿意买、愿意采用”变便宜。

很多 AI 工具会默认你的想法是对的，然后帮你写市场计划、包装定位、生成 campaign。GTM Decision Lab 反过来做：

它不负责鼓励创始人自嗨，只负责检查市场和需求是否真实。

这个 skill 专门服务于早期项目的市场和需求判断：

- 谁真的需要这个东西？
- 这个问题现在痛不痛、急不急？
- 用户现在用什么替代方案？
- 用户是否愿意换、愿意试、愿意付费？
- 这个项目是不是只是“AI 能做”，但市场并不需要？
- 创始人是否真的接触得到目标用户？
- 当前应该 build、validate，还是 hold？

它不决定产品最终应该做成什么形态，也不负责写功能路线图。除非某个功能是为了验证需求、信任、采用或付费意愿，否则它不会讨论产品功能。

---

## What It Does

GTM Decision Lab turns messy product notes, customer feedback, market assumptions, and early traction signals into a defensible market reality and GTM decision brief.

It helps you:

- check whether demand is real enough to continue
- choose or audit a first beachhead segment
- separate customer evidence from founder assumptions
- identify AI hype risk and demo-novelty risk
- test whether the builder has access, credibility, and feedback paths
- select an early GTM motion
- pressure-test positioning claims
- design 14-day or 30-day validation experiments
- decide whether to **Build / Validate / Hold**

---

## Core Principle

Most GTM agents generate plans.

**GTM Decision Lab generates market decisions with evidence levels, assumption flags, risk gates, and validation actions.**

This skill does not validate the user's ego. It validates market reality.

---

## When To Use

Use this skill when you need to:

- evaluate an AI product idea before building
- decide whether a target customer is specific enough
- choose a first beachhead segment
- audit a GTM idea before launching
- check whether a pain point is real or imagined
- compare possible customer segments
- design demand validation experiments
- turn scattered notes into a decision-ready brief
- identify which claims are still unsafe to make
- decide whether to build, validate first, or hold

---

## When Not To Use

This skill is not designed for:

- mature enterprise campaign calendars
- generic marketing copywriting
- feature roadmaps
- product design
- technical architecture
- investor pitch polishing without market evidence
- post-repeatability GTM ops
- making an idea sound better when the evidence is weak

If you already have a mature sales team, CRM history, repeatable pipeline, campaign data, and clear budget, this skill may still help with a focused decision audit, but it is not a replacement for your GTM ops system.

---

## What Makes It Different

Instead of only asking:

> What is the GTM plan?

It asks:

> What evidence supports this GTM decision?  
> Which assumptions could break it?  
> What should be validated before building or scaling?  
> What should not be claimed yet?  
> Should this be built, validated, or paused?

It explicitly checks:

- whether the segment is concrete
- whether the pain is real
- whether urgency exists
- whether the buyer or user is reachable
- whether willingness to pay has any evidence
- what current alternative already exists
- why the customer would switch
- whether AI is necessary or just a novelty layer
- whether the builder has access to the market
- which positioning claims lack proof

---

## Main Outputs

A typical output includes:

- Product snapshot
- Input completeness audit
- Market reality check
- Founder / builder reality check
- Beachhead segment scorecard
- Rejected or deferred segments
- Recommended GTM motion
- Positioning hypothesis
- AI project market risk table
- Channel bets
- Validation plan
- Build / Validate / Hold decision
- Decision gates
- Evidence, assumption, and risk ledger
- Next actions

---

## Build / Validate / Hold

The skill does not force every idea into a plan.

It can return:

### Build

Use when there is direct evidence of real demand, a clear target customer, reachable users, manageable trust/adoption risk, and a practical path to first delivery.

### Validate

Use when the opportunity may be real, but key assumptions still need evidence: buyer, urgency, willingness to pay, trust, adoption path, or repeat usage.

### Hold

Use when the idea is mostly AI capability, a vague audience, weak pain, unclear delivery, no credible access to users, or no evidence that the market wants the result.

The skill is allowed to say:

> Hold. Do not build yet. Validate the demand before designing the product.

---

## Example Prompt

```text
Use $gtm-decision-lab to analyze this product idea.

We are building an AI tool for small B2B SaaS teams that summarizes sales calls and identifies churn risks.
We have 20 waitlist signups, 3 user interviews, and no revenue yet.
Help us decide whether demand is real enough to continue, choose a beachhead segment, and design a 14-day validation plan.
```

---

## Example Use Cases

### AI product idea

Check whether the project is solving a real customer problem or just starting from what AI can automate.

### Early founder GTM

Choose the first customer segment before wasting time on a broad launch.

### B2B SaaS validation

Separate waitlist interest from willingness to pay.

### Developer tool GTM

Decide whether usage from free users can become a paid motion.

### PMM / advisor work

Turn scattered customer notes into a structured decision brief with evidence and risk gates.

---

## Repository Structure

```text
gtm-decision-lab/
  SKILL.md
  agents/
    openai.yaml
  assets/
    experiment-plan-template.md
    gtm-decision-brief-template.md
    intake-template.md
  evals/
    golden-cases.md
  examples/
    sample-input-ai-sales-risk.md
    sample-output-ai-sales-risk.md
    sample-input-devtool-analytics.md
    sample-output-devtool-analytics.md
  references/
    ai-project-market-risks.md
    evidence-standards.md
    gtm-motions.md
    scoring-rubric.md
    source-map.md
    validation-experiments.md
```

---

## Installation

Download or clone this repository, then place the `gtm-decision-lab` folder into your local Codex skills directory.

Then invoke it with:

```text
Use $gtm-decision-lab to check whether this product has real market demand and create a GTM decision brief.
```

---

## Suggested First Input

For best results, provide:

- what the product does
- who you think the target customer is
- current stage
- evidence you already have
- current traction or usage
- whether anyone has paid or committed
- candidate customer segments
- constraints around time, budget, trust, data, compliance, or distribution
- what decision you need to make now

If you do not have all of this, the skill can still work. It will label weak evidence and missing assumptions instead of pretending the answer is certain.

---

## License

MIT License.
