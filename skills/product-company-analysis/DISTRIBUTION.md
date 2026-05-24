# Distribution Notes

This file tracks where the `product-company-analysis` skill can be submitted, shared, or repackaged.

## Best next move

Create a standalone repository such as:

```text
cathyzhang0905/product-company-analysis-skill
```

A standalone repository is better than a profile subdirectory because people can star, fork, watch, and install it directly. The current profile-hosted version is useful as a public preview, but it is not ideal for discovery.

Recommended standalone repo structure:

```text
product-company-analysis-skill/
├── README.md
├── README.zh-CN.md
├── SKILL.md
├── agents/
│   └── openai.yaml
└── examples/
    └── storeclaw.md
```

## Places to submit

1. [OpenAI Skills Catalog](https://github.com/openai/skills)

   Best fit if the skill is packaged as a standard Codex skill. The repository describes agent skills as folders of instructions, scripts, and resources that agents can discover and use for repeatable tasks.

2. [ComposioHQ/awesome-codex-skills](https://github.com/ComposioHQ/awesome-codex-skills)

   Best fit for an awesome-list style submission. It already curates practical Codex skills across many workflow categories.

3. [SkillHub](https://www.skill-marketplace.com/)

   A marketplace for AI agent skills. Good for discoverability beyond GitHub-native users.

4. [SkillsGate](https://skillsgate.ai/)

   An open marketplace for agent skills. Good for broader agent-skill indexing.

5. [skills.pub](https://skills.pub/)

   A third-party marketplace currently focused on Claude skills, but useful for reaching people already searching for reusable skill packages.

6. [SkillsMP](https://skillsmp.com/)

   A marketplace that positions itself around Claude, Codex, and ChatGPT skills.

## Suggested GitHub description

```text
Codex skill for deep product and company analysis: users, painful workflows, substitutes, monetization, distribution, moat, risks, and strategic judgment.
```

## Suggested GitHub topics

```text
codex-skill
agent-skills
product-management
startup-analysis
company-analysis
product-analysis
market-research
competitive-analysis
ai-product
strategy
```

## Suggested PR title

```text
Add product-company-analysis skill
```

## Suggested PR description

```markdown
## Summary

Adds `product-company-analysis`, a Codex skill for deep product and company analysis.

The skill helps analyze products, startups, competitors, launches, and business ideas through target users, customer pain, previous workflow, after-workflow, substitutes, core capability, monetization, distribution, retention, moat, risks, and verification questions.

## Why it is useful

Many product reviews stop at feature description. This skill pushes the analysis toward business durability and workflow change: who the real user is, what painful workflow existed before, what actually changes after using the product, what substitutes compete with it, and whether the product is only an efficiency layer or a structural change.

## Example

Includes a StoreClaw example analysis covering ecommerce sellers, platform-native AI tools, workflow change, monetization, distribution, moat, and risks.
```

## Suggested social post

```text
I made a Codex skill for deep product/company analysis.

It turns any product, startup, competitor, or launch into a structured report:
- target users
- painful workflow before/after
- substitutes
- core capability
- monetization
- distribution
- retention
- moat
- risks
- strategic judgment

Useful if you track Product Hunt, AI products, SaaS, marketplaces, or startup ideas regularly.

GitHub: <repo link>
```

## Positioning note

The strongest positioning is not "an AI product analysis template." It is:

```text
A repeatable thinking framework for judging whether a product is just a feature, an efficiency layer, or a durable company.
```

That makes it useful beyond AI products and more attractive to product builders, founders, and investors.
