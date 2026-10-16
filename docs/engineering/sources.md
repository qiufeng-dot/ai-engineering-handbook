# 原文与来源

[知识库首页](../../README.md) · [本专题目录](README.md)

> **阅读目标**：按主题回到论文、官方文档和教学图的来源，识别研究结论与自建案例。

<details>
<summary>本文目录</summary>

- [A 线：AI 编程代理](#section-1)
- [测试与代码基础](#section-2)
- [B 线：开发流程](#section-3)
- [核对范围说明](#section-4)
- [图片说明](#section-5)

</details>

本资料引用的全部一手来源。所有在线来源均于 2026-10-07 实际打开核对；两篇 ETH Zurich 论文另有本地 PDF。只使用了无需登录的公开页面。工具文档（OpenAI、Anthropic）更新频繁，如与当前版本不一致，以最新官方文档为准。

“类型”一栏说明证据的性质：**论文**经过同行评审或为预印本；**报告**是机构调研或评测记录；**官方文档**是厂商说明；**行业经典**是被广泛采用的实践文章或标准。

<a id="section-1"></a>
## A 线：AI 编程代理

### 研究论文与报告

| 来源 | 类型 | 用于章节 |
|---|---|---|
| Jimenez 等，*SWE-bench: Can Language Models Resolve Real-World GitHub Issues?*，ICLR 2024。<https://arxiv.org/abs/2310.06770> | 论文 | 04 |
| METR，*Measuring the Impact of Early-2025 AI on Experienced Open-Source Developer Productivity*，2025-07-10（本地为 v2，2025-07-25）。<https://arxiv.org/abs/2507.09089>；[原文 PDF](https://arxiv.org/pdf/2507.09089v2)；博客 <https://metr.org/blog/2025-07-10-early-2025-ai-experienced-os-dev-study/> | 论文（随机对照实验） | 04、09、11 |
| Gloaguen、Mündler、Müller、Raychev、Vechev，*Evaluating AGENTS.md: Are Repository-Level Context Files Helpful for Coding Agents?*，ICLR 2026，arXiv:2602.11988v2。<https://arxiv.org/abs/2602.11988>；[原文 PDF](https://arxiv.org/pdf/2602.11988v2) | 论文 | 03、04 |
| Gloaguen、Mündler、Müller、Raychev、Vechev，*Coding Agents Don't Know When to Act*，arXiv:2605.07769v1，2026-05-08（审稿中预印本）。<https://arxiv.org/abs/2605.07769>；[原文 PDF](https://arxiv.org/pdf/2605.07769v1) | 论文（预印本） | 04、05 |
| Zhong、Raghunathan、Carlini，*ImpossibleBench: Measuring LLMs' Propensity of Exploiting Test Cases*，arXiv:2510.20270，2025-10；ICLR 2026。<https://arxiv.org/abs/2510.20270>；[原文 PDF](https://arxiv.org/pdf/2510.20270) | 论文 | 04、05 |
| METR，*Recent Frontier Models Are Reward Hacking*，2025-06-05。<https://metr.org/blog/2025-06-05-recent-reward-hacking> | 报告 | 04 |
| Stack Overflow，*2025 Developer Survey: AI*。<https://survey.stackoverflow.co/2025/ai> | 调查 | 04 |
| Google DORA，*2025 State of AI-assisted Software Development*，2025-09-23。<https://dora.dev/research/2025/dora-report/>；Google 博客摘要 <https://blog.google/technology/developers/dora-report-2025/> | 报告（调查） | 04、10、11 |
| Google Cloud，*Introducing DORA's inaugural AI Capabilities Model*，2025-09-23。<https://cloud.google.com/blog/products/ai-machine-learning/introducing-doras-inaugural-ai-capabilities-model> | 报告摘要 | 11 |

### 官方文档与实践文章

| 来源 | 类型 | 用于章节 |
|---|---|---|
| OpenAI，Codex *Best practices*。<https://developers.openai.com/codex/learn/best-practices> | 官方文档 | 03、05 |
| OpenAI，Codex *AGENTS.md* 指南。<https://developers.openai.com/codex/guides/agents-md> | 官方文档 | 03 |
| OpenAI，Codex *Sandboxing*。<https://developers.openai.com/codex/concepts/sandboxing> | 官方文档 | 03 |
| OpenAI，*How OpenAI uses Codex*。<https://openai.com/business/guides-and-resources/how-openai-uses-codex/> | 官方指南 | 07、11 |
| OpenAI，*Evaluation best practices*。<https://developers.openai.com/api/docs/guides/evaluation-best-practices> | 官方文档 | 10 |
| OpenAI，Codex 应用 *Review*（审查面板、`/review`、PR 审查）。<https://developers.openai.com/codex/app/review>（核对时跳转至 <https://learn.chatgpt.com/docs/code-review?surface=app>，2026-10-10） | 官方文档 | 06B |
| OpenAI，*Use Codex in GitHub*（`@codex review`、自动审查、AGENTS.md 审查规则）。<https://learn.chatgpt.com/codex/third-party/github>（2026-10-10） | 官方文档 | 06B |
| Anthropic，*Best practices for Claude Code*。<https://code.claude.com/docs/en/best-practices> | 官方文档（同类工具） | 02、03、05、06 |
| Kent Beck，*Augmented Coding: Beyond the Vibes*，2025-06-25。<https://newsletter.kentbeck.com/p/augmented-coding-beyond-the-vibes> | 实践文章 | 02、06、11 |
| Simon Willison，*Vibe engineering*，2025-10-07。<https://simonwillison.net/2025/Oct/7/vibe-engineering/> | 实践文章 | 06、09、11 |
| Den Delimarsky（GitHub），*Spec-driven development with AI*，2025-09-02。<https://github.blog/ai-and-ml/generative-ai/spec-driven-development-with-ai-get-started-with-a-new-open-source-toolkit/> | 实践文章 | 11 |

<a id="section-2"></a>
## 测试与代码基础

| 来源 | 类型 | 用于章节 |
|---|---|---|
| Scott Chacon、Ben Straub，《Pro Git》第 2 版，官方免费在线，含简体中文版。<https://git-scm.com/book/zh/v2> | 行业经典（书） | 01、12 |
| Ham Vocke，*The Practical Test Pyramid*，martinfowler.com，2018-02-26。<https://martinfowler.com/articles/practical-test-pyramid.html> | 行业经典 | 02 |
| Alex Eagle，*Change-Detector Tests Considered Harmful*，Google Testing Blog，2015-01-27。<https://testing.googleblog.com/2015/01/testing-on-toilet-change-detector-tests.html> | 行业经典 | 02 |
| Winters、Manshreck、Wright 编，《Software Engineering at Google》，2020，官方免费在线。<https://abseil.io/resources/swe-book>；第 9 章代码审查 <https://abseil.io/resources/swe-book/html/ch09.html>；第 11 章测试概览 <https://abseil.io/resources/swe-book/html/ch11.html> | 行业经典（书） | 02、08 |
| Inozemtseva、Holmes，*Coverage Is Not Strongly Correlated with Test Suite Effectiveness*，ICSE 2014。本系列已有精读：[覆盖率与测试有效性](../testing/07_Coverage_Effectiveness.md) | 论文 | 02 |

<a id="section-3"></a>
## B 线：开发流程

| 来源 | 类型 | 用于章节 |
|---|---|---|
| Google Engineering Practices：*The Standard of Code Review*、*What to look for in a code review*、*Small CLs*、*Speed of Code Reviews*。<https://google.github.io/eng-practices/> | 行业经典 | 05、06、08 |
| GitHub Docs，*Reviewing proposed changes in a pull request*。<https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/reviewing-proposed-changes-in-a-pull-request>（2026-10-10） | 官方文档 | 06B |
| VS Code Docs，*Source Control overview*、*Staging, commits & undo*（差异编辑器）。<https://code.visualstudio.com/docs/sourcecontrol/overview>；<https://code.visualstudio.com/docs/sourcecontrol/staging-commits>（2026-10-10） | 官方文档 | 06B |
| Google Engineering Practices：*Navigating a CL in review*、*How to write code review comments*。<https://google.github.io/eng-practices/review/reviewer/navigate.html>；<https://google.github.io/eng-practices/review/reviewer/comments.html>（2026-10-10） | 行业经典 | 06B |
| GitHub Docs，*GitHub flow*。<https://docs.github.com/en/get-started/using-github/github-flow> | 官方文档 | 08 |
| DORA，*Trunk-based development*。<https://dora.dev/capabilities/trunk-based-development/> | 研究型指南 | 08 |
| DORA，*DORA's software delivery metrics*。<https://dora.dev/guides/dora-metrics/> | 研究型指南 | 10 |
| Martin Fowler，*Continuous Integration*，2024-01-18 更新。<https://martinfowler.com/articles/continuousIntegration.html> | 行业经典 | 07、08 |
| Martin Fowler，*Patterns for Managing Source Code Branches*，2020-05-28。<https://martinfowler.com/articles/branching-patterns.html> | 行业经典 | 08 |
| Vincent Driessen，*A successful Git branching model*，2010-01-05（2020 年补充反思）。<https://nvie.com/posts/a-successful-git-branching-model/> | 行业经典 | 08 |
| Ken Schwaber、Jeff Sutherland，《Scrum 指南》，2020 年 11 月版。<https://scrumguides.org/scrum-guide.html> | 标准 | 09 |
| 《看板指南》（The Kanban Guide），2025 年 5 月版。<https://kanbanguides.org/english/> | 标准 | 09 |
| 《敏捷软件开发宣言》，2001。<https://agilemanifesto.org/> | 标准 | 09 |
| Bill Wake，*INVEST in Good Stories, and SMART Tasks*，2003-08-17。<https://xp123.com/invest-in-good-stories-and-smart-tasks/> | 行业经典 | 09 |
| Dan North，*Introducing BDD*，2006。<https://dannorth.net/blog/introducing-bdd/> | 行业经典 | 05、09 |
| Michael Nygard，*Documenting Architecture Decisions*，2011-11-15。<https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions> | 行业经典 | 07 |
| *Semantic Versioning 2.0.0*。<https://semver.org/> | 标准 | 07 |
| Melvin Conway，*How Do Committees Invent?*，Datamation，1968。<https://www.melconway.com/Home/Committees_Paper.html> | 经典论文 | 07 |
| Frederick P. Brooks，《人月神话》（*The Mythical Man-Month*），1975 | 经典著作（未在线核对） | 07 |
| Pete Hodgson，*Feature Toggles (aka Feature Flags)*，martinfowler.com，2017-10-09。<https://martinfowler.com/articles/feature-toggles.html> | 行业经典 | 10 |
| Martin Fowler，*Technical Debt Quadrant*，2009-10-14。<https://martinfowler.com/bliki/TechnicalDebtQuadrant.html> | 行业经典 | 10 |
| Lunney、Lueder，*Postmortem Culture: Learning from Failure*，《Site Reliability Engineering》第 15 章。<https://sre.google/sre-book/postmortem-culture/> | 行业经典（书） | 10 |

<a id="section-4"></a>
## 核对范围说明

- 四篇精读论文（METR 实验、AGENTS.md 评测、FixedBench、ImpossibleBench）读了本地 PDF 的正文和相关附录，关键数字、图表与原文逐一核对。
- SWE-bench 与 METR 奖励投机报告只作佐证，依据 arXiv 摘要页和报告网页。
- 官方文档和实践文章依据核对当天的在线版本。
- 没有运行任何论文的实验，也没有在真实项目中验证文中的 Codex 设置效果。

<a id="section-5"></a>
## 图片说明

- **论文原图**：第 04 章和四篇精读中的论文图表，全部从 `高质量论文` 文件夹中的本地 PDF（编号 13、14、21、22）按原图边界截取，图注里写明了原图编号和页码。
- **重绘图**：只有 SWE-bench 一张。它在本资料中只作佐证，没有下载原文，图依据论文文字描述重绘，图注中已标明。
- **06B 的 diff 图**：由本资料自建的示例仓库（Python 聊天应用后端）用 `git diff` 真实生成，再渲染成接近 GitHub 的样式；审查意见是教学标注。Codex 的改动按 AI 代理的常见问题刻意构造，不是某次真实运行的输出。测试结果和导出 bug 的复现在本机实际运行过（markdownify 1.2.3；沙盒中没有 pytest，用等价的最小运行器执行同一批测试函数）。
- **06B 的界面示意图**：Codex 应用、GitHub、VS Code 三张图是依据官方文档绘制的示意图，不是截图。
- **概念示意图**：测试金字塔、代理循环、分支、GitHub Flow、Scrum 等图是本资料依据所引来源绘制的教学示意图，不是原文配图。

---

[专题目录](README.md) · [知识库首页](../../README.md)
