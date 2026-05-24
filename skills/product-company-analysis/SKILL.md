---
name: product-company-analysis
description: Structured product and company analysis for startups, SaaS, marketplaces, developer tools, consumer apps, platform businesses, AI products, ecommerce products, services, and business ideas. Use when the user asks to analyze a product, company, startup, competitor, launch, market opportunity, business model, positioning, target users, customer pain, workflow change, differentiation, monetization, distribution, retention, moat, risks, or whether a product/company is promising.
---

# Product and Company Analysis

## Core Principle

Analyze whether the product or company solves a real user problem and can become a durable business, not whether it is merely interesting.

Anchor every report on four questions:

1. Who is the real user?
2. What painful workflow exists before this product?
3. What changes after using it?
4. Why can this become a sustainable company instead of a feature, demo, or wrapper?

Use the user's language by default. If the user writes in Chinese, output in Chinese.

## Research Standard

For current products or companies, browse before making claims. Prefer:

- Official website, docs, pricing, changelog, blog, launch page.
- Launch page, app store, marketplace listing, Product Hunt page, or directory listing when relevant.
- Company announcement, founder announcement, launch press release, demo video, public docs.
- Competitor official pages for direct comparison.

Separate public facts from inference. Use phrases like "从公开信息看" or "我的推断是" when evidence is incomplete.

Do not over-trust marketing language. Compare the claimed positioning with the actual workflow the product asks users to perform.

## Report Structure

Default to a deep-dive report, not a short summary. Use the full structure unless the user explicitly asks for a brief, quick, short, or lightweight analysis.

Before writing the final report, perform this analysis pass internally and make sure the report reflects the answers:

1. Claim vs reality: What does the product/company claim to be, and what does the actual user workflow suggest it really is?
2. Workflow delta: Which steps disappear, which steps become faster, and which steps still require the user?
3. Substitution pressure: Why would the user not use existing tools, platform-native tools, manual services, consultants, spreadsheets, ChatGPT/Claude, or internal builds?
4. Structural change test: Does the product change who judges, coordinates, executes, and verifies the work?
5. Business durability test: Which part is weakest: target user, pain intensity, distribution, retention, monetization, moat, unit economics, platform dependency, trust, or execution quality?
6. Counter-position: What is the strongest argument against the product/company, and what evidence would change that view?

Depth requirements for the default report:

- Write enough detail for the report to be saved as a durable reference note.
- Each major section should contain concrete reasoning, not just a label or one-line answer.
- Include explicit before / after workflow steps.
- Include direct comparison with competitors, platform-native tools, or realistic substitutes.
- Explain the judgment, not only the conclusion.
- Include at least one meaningful counterargument or pressure-test, especially around incumbents, platforms, substitutes, or user willingness to pay.
- End with specific questions to verify through product trial, user interviews, pricing, retention, or case studies.
- If public evidence is thin, write a deeper uncertainty analysis instead of shortening the report.

```markdown
**产品 / 公司：<name>**

**0. 一句话判断**
<一句话说清：是否看好、为什么、最大不确定性是什么。>

**1. 目标用户群体**
<真实用户是谁，不只是官网写的用户。区分 early adopter、付费用户、长期理想用户。>

**2. 解决的核心问题**
<它解决哪类用户的什么问题。说明痛点强度、高频程度、是否影响收入/成本/风险。>

**3. 原来的 workflow**
<用户不用这个产品时怎么完成任务。写成具体步骤。>

**4. 使用后的 workflow**
<用户用了产品后流程如何变化。指出哪些步骤被压缩、自动化、重组或消失。>

**5. 竞品 / 替代方案**
<传统工具、平台官方工具、人工服务、内部自建、ChatGPT/Claude 等替代品分别怎么解决。>

**6. 功能与服务**
<列出核心功能，但不要停留在功能清单；解释每个功能服务于哪个 workflow 环节。>

**7. 核心能力**
<分析它真正依赖的核心能力：技术、数据、供应链、网络效应、分发、品牌、运营、社区、生态位、服务能力等。如果是 AI 产品，再判断 AI 是装饰层、效率层、工作流层，还是执行层。>

**8. 效率提升还是结构性改变**
<判断它是让原流程更快，还是改变谁来判断、协调、执行、复盘。>

**9. 商业化模式**
<谁付费、为什么付费、定价是否匹配价值、是否能扩展到高阶收入。>

**10. 分发与增长**
<用户如何发现它。分析 SEO、平台生态、社区、销售、内容、合作伙伴、线下渠道、口碑、viral loop、Product Hunt 等 launch 渠道。>

**11. 留存机制**
<为什么用户会反复使用。是否进入核心 workflow，是否有数据/历史/自动监控带来的持续价值。>

**12. 护城河**
<数据、workflow、集成、分发、品牌、社区、合规、切换成本、网络效应等。避免把“用了大模型”当护城河。>

**13. 最大风险**
<列出 3-5 个最关键风险。优先写会杀死公司的风险，而不是普通缺点。>

**14. 综合判断**
<这个产品/公司是否值得关注；如果要继续做，应该怎么收窄切入点、验证 PMF、避开平台/竞品压力。>

**15. 后续需要验证的问题**
<列出下一步要看官网、试用、访谈、数据或案例验证的问题。>
```

## Analysis Heuristics

### User and Pain

Identify the smallest sharp user segment. Avoid "everyone who needs productivity" style answers.

Ask:

- Is the pain urgent, frequent, expensive, or risky?
- Does solving it affect revenue, cost, risk, or status?
- What are users already paying for?
- What workaround do they use today?

### Workflow Change

Distinguish efficiency improvement from structural change:

- Efficiency improvement: the same workflow becomes faster or cheaper.
- Structural change: the workflow is reorganized; the user's role changes from executor to reviewer, coordinator, or goal-setter.

Use this test:

- Who decides the next step before and after?
- Who coordinates across tools?
- Who executes?
- Who verifies the result?
- Does the product close the loop from input to outcome?

### Core Capability

First analyze the product's core capability. Depending on the company, this may be:

- Technology or product execution.
- Proprietary data.
- Distribution.
- Marketplace liquidity.
- Supply chain.
- Workflow depth.
- Brand or community.
- Operational excellence.
- Technical infrastructure.
- Regulatory or compliance capability.
- Partnerships or ecosystem position.

For AI products, additionally classify AI's role:

- AI decoration layer: AI is mostly marketing, chat, or copy polish.
- AI assistance layer: AI helps generate, summarize, search, or draft.
- AI workflow layer: AI connects multiple steps and reduces coordination.
- AI execution layer: AI calls tools, acts in external systems, tracks results, and asks for approval at key moments.

Do not call something a structural AI product unless AI changes the workflow, not just the interface.

### Platform and Incumbent Pressure

Always ask whether a platform owner can absorb the feature.

For products built around major platforms such as Shopify, Amazon, Google, Slack, Notion, GitHub, Salesforce, browser, email, calendar, social platforms, app stores, or operating systems, compare against native platform tools and likely platform expansion.

Third-party products need one of these advantages:

- Cross-platform view.
- Platform-neutral optimization.
- Deeper vertical workflow.
- Better execution layer.
- Proprietary data or feedback loop.
- Distribution outside the platform owner's control.

### Business Quality

Evaluate:

- Market size and willingness to pay.
- CAC and likely acquisition channels.
- Retention loop and usage frequency.
- Expansion revenue path.
- Gross margin and onboarding cost.
- Whether it is SaaS or a service business disguised as SaaS.

## Writing Style

Be direct and specific. Avoid generic praise.

Use concrete workflow examples. Prefer "before / after" over abstract claims.

When evidence is weak, say what needs verification instead of overstating certainty.

End with a clear strategic judgment: worth watching, not compelling, strong wedge but weak moat, good market but risky execution, etc.
