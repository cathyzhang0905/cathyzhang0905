# 产品 / 公司分析 Skill

一个用于深度分析产品和公司的 Codex skill。

它可以把一个产品、创业公司、竞品、发布页或商业想法，转化成一份结构化战略分析报告：目标用户、核心痛点、使用前后的 workflow、替代方案、核心能力、商业化、分发、留存、护城河、风险和后续验证问题。

[English README](./README.md) · [范例：StoreClaw 分析](./examples/storeclaw.md) · [分发 / 投稿清单](./DISTRIBUTION.md)

## 为什么需要这个 skill

很多产品分析只停在“它做了什么”。这个 skill 会继续往下问：

- 真实用户是谁？
- 用户原来痛苦的 workflow 是什么？
- 使用这个产品之后，workflow 到底发生了什么变化？
- 已有替代方案为什么不够好？
- 它为什么可能成为一个可持续的公司，而不只是一个功能、demo 或 wrapper？

它不局限于 AI 产品，也适用于 SaaS、marketplace、开发者工具、消费产品、平台型业务、电商产品、服务型业务和创业想法。

## 安装

在 Codex 里用 GitHub 目录链接安装：

```text
$skill-installer install https://github.com/cathyzhang0905/cathyzhang0905/tree/main/skills/product-company-analysis
```

安装后重启 Codex，让新 skill 生效。

## 使用方式

示例 prompt：

```text
Use $product-company-analysis to analyze this Product Hunt launch: <url>
```

```text
Use $product-company-analysis to compare this startup against platform-native alternatives.
```

```text
Use $product-company-analysis to produce a deep-dive analysis of <company/product>.
```

中文也可以直接说：

```text
用 product-company-analysis 深度分析一下这个产品：<url 或产品名>
```

## 默认输出结构

默认输出是 deep-dive report，不是短评：

1. 一句话判断
2. 目标用户群体
3. 解决的核心问题
4. 原来的 workflow
5. 使用后的 workflow
6. 竞品 / 替代方案
7. 功能与服务
8. 核心能力
9. 效率提升还是结构性改变
10. 商业化模式
11. 分发与增长
12. 留存机制
13. 护城河
14. 最大风险
15. 综合判断
16. 后续需要验证的问题

## 内置压力测试

在写最终报告之前，skill 会强制做一轮内部压力测试：

- Claim vs reality：产品声称自己是什么，实际 workflow 更像什么？
- Workflow delta：哪些步骤消失了，哪些只是变快，哪些仍然要用户自己做？
- Substitution pressure：用户为什么不用现有工具、平台官方工具、人工服务、顾问、表格、ChatGPT/Claude 或内部自建？
- Structural change test：它是否改变了谁来判断、协调、执行、验证？
- Business durability test：最脆弱的一环是用户、痛点、分发、留存、商业化、护城河、经济模型、平台依赖、信任，还是执行质量？
- Counter-position：反对这个产品最强的论点是什么？什么证据会改变这个判断？

## 适合谁用

- 想训练产品判断力的 PM
- 在看创业方向、竞品或市场机会的 founder
- 做早期项目判断的投资人、scout、研究者
- 每天看 Product Hunt、GitHub、HN、App Store 或垂直 SaaS 新产品的 builder
- 想判断 AI 产品到底是效率工具还是结构性改变的人

## 文件

- [`SKILL.md`](./SKILL.md) — skill 主体说明
- [`agents/openai.yaml`](./agents/openai.yaml) — Codex UI 元数据
- [`examples/storeclaw.md`](./examples/storeclaw.md) — 完整范例
- [`DISTRIBUTION.md`](./DISTRIBUTION.md) — 可投稿 / 可宣传的位置和文案
