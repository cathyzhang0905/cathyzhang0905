# Product Company Analysis

A reusable Codex skill for deep product and company analysis.

It turns a product, startup, competitor, launch, or business idea into a structured strategy report: target users, customer pain, before/after workflow, substitutes, core capability, monetization, distribution, retention, moat, risks, and verification questions.

[中文说明](./README.zh-CN.md) · [Example: StoreClaw analysis](./examples/storeclaw.md) · [Promotion & submission notes](./DISTRIBUTION.md)

## Why this exists

Most product analysis stops at "what does it do?" This skill pushes further:

- Who is the real user?
- What painful workflow exists before this product?
- What changes after using it?
- What alternatives already solve part of the job?
- Why might this become a durable company instead of a feature, demo, or wrapper?

It is intentionally not limited to AI products. It works for SaaS, marketplaces, developer tools, consumer apps, platform businesses, ecommerce products, services, and startup ideas.

## Install

In Codex, install from the GitHub directory URL:

```text
$skill-installer install https://github.com/cathyzhang0905/cathyzhang0905/tree/main/skills/product-company-analysis
```

Restart Codex after installation so the skill is picked up.

## Use it

Example prompts:

```text
Use $product-company-analysis to analyze this Product Hunt launch: <url>
```

```text
Use $product-company-analysis to compare this startup against platform-native alternatives.
```

```text
Use $product-company-analysis to produce a deep-dive analysis of <company/product>.
```

## Output structure

The default output is a deep-dive report, not a short summary:

1. One-line judgment
2. Target users
3. Core problem
4. Previous workflow
5. Workflow after using the product
6. Competitors and substitutes
7. Core capability
8. Efficiency improvement or structural change
9. Monetization
10. Distribution and growth
11. Retention
12. Moat
13. Biggest risks
14. Strategic judgment
15. Questions to verify

Before writing, the skill also pressure-tests claim vs reality, workflow delta, substitution pressure, structural change, business durability, and the strongest counter-position.

## Good fit for

- Product managers building market judgment
- Founders evaluating startup ideas or competitors
- Investors and scouts doing first-pass company analysis
- Builders tracking Product Hunt, Hacker News, GitHub, App Store, or vertical SaaS launches
- AI product researchers who want to separate real workflow change from surface-level AI features

## Files

- [`SKILL.md`](./SKILL.md) — the skill instructions
- [`agents/openai.yaml`](./agents/openai.yaml) — Codex UI metadata
- [`examples/storeclaw.md`](./examples/storeclaw.md) — complete example output
- [`DISTRIBUTION.md`](./DISTRIBUTION.md) — where to submit or promote this skill
