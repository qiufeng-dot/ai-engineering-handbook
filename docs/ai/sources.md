# AI 应用：原文与来源

[知识库首页](../../README.md) · [本专题目录](README.md)

> **阅读目标**：按章节查找原始论文与工程材料，并核对版本、日期和图片出处。

本阶段引用的全部一手来源。在线来源均于 2026-10-15 实际打开核对，只使用无需登录的公开页面。厂商文档和价格更新频繁，如与当前版本不一致，以最新官方页面为准。

<a id="section-1"></a>
## 精读论文（原文通过以下链接访问）

| 论文 | 版本 | 用于 |
|---|---|---|
| Liu, Lin, Hewitt, Paranjape, Bevilacqua, Petroni, Liang. *Lost in the Middle: How Language Models Use Long Contexts*. TACL 2024. <https://arxiv.org/abs/2307.03172>；[原文 PDF](https://arxiv.org/pdf/2307.03172v3) | arXiv v3，2023-11-20 | 02、03、精读一 |
| Yao, Zhao, Yu, Du, Shafran, Narasimhan, Cao. *ReAct: Synergizing Reasoning and Acting in Language Models*. ICLR 2023. <https://arxiv.org/abs/2210.03629>；[原文 PDF](https://arxiv.org/pdf/2210.03629v3) | arXiv v3，2023-03-10 | 04、精读二 |
| Zheng, Chiang, Sheng 等. *Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena*. NeurIPS 2023 Datasets and Benchmarks. <https://arxiv.org/abs/2306.05685>；[原文 PDF](https://arxiv.org/pdf/2306.05685v4) | arXiv v4，2023-12-24 | 05、精读三 |
| Kalai, Nachum, Vempala, Zhang. *Why Language Models Hallucinate*. 2025. <https://arxiv.org/abs/2509.04664>；[原文 PDF](https://arxiv.org/pdf/2509.04664v1)；OpenAI 博客 <https://openai.com/index/why-language-models-hallucinate/>（2025-09-05） | arXiv v1，2025-09-04（预印本） | 01、05、精读四 |

<a id="section-2"></a>
## 略读与佐证材料

| 来源 | 类型 | 用于 |
|---|---|---|
| Andrej Karpathy，*Deep Dive into LLMs like ChatGPT*，YouTube，2025-02-05。<https://www.youtube.com/watch?v=7xTGNNLPyMI> | 公开课视频（约三个半小时） | 01 |
| Anthropic，*Prompt caching* 文档。<https://platform.claude.com/docs/en/build-with-claude/prompt-caching> | 官方文档 | 01 |
| OpenAI，*Prompt caching* 文档。<https://developers.openai.com/api/docs/guides/prompt-caching> | 官方文档 | 01 |
| International AI Safety Report 2026，2026-02-03。<https://internationalaisafetyreport.org/> | 国际报告 | 01 |
| Anthropic，*Effective context engineering for AI agents*，2025-09-29。<https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents> | 官方工程博客 | 02 |
| Wei 等，*Chain-of-Thought Prompting Elicits Reasoning in Large Language Models*，NeurIPS 2022。<https://arxiv.org/abs/2201.11903> | 论文（佐证） | 02 |
| Hong、Troynikov、Huber，*Context Rot: How Increasing Input Tokens Impacts LLM Performance*，Chroma 技术报告，2025-07-14。<https://www.trychroma.com/research/context-rot> | 技术报告 | 02 |
| Lewis 等，*Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks*，NeurIPS 2020。<https://arxiv.org/abs/2005.11401> | 论文（略读） | 03 |
| Anthropic，*Introducing Contextual Retrieval*，2024-09-19。<https://www.anthropic.com/news/contextual-retrieval> | 官方博客 | 03 |
| Anthropic（Erik S.、Barry Zhang），*Building effective agents*，2024-12-19。<https://www.anthropic.com/engineering/building-effective-agents> | 官方工程博客 | 04 |
| OpenAI，*A practical guide to building agents*，2025 年 4 月。<https://cdn.openai.com/business-guides-and-resources/a-practical-guide-to-building-agents.pdf> | 官方指南（PDF） | 04 |
| Model Context Protocol 官网 <https://modelcontextprotocol.io/>；Anthropic 发布公告（2024-11-25）<https://www.anthropic.com/news/model-context-protocol>；捐赠公告（2025-12-09）<https://www.anthropic.com/news/donating-the-model-context-protocol-and-establishing-of-the-agentic-ai-foundation> | 官方页面 | 04 |
| Anthropic，*Investigating unintended model actions*，2026-10-09。<https://www.anthropic.com/research/investigating-unintended-model-actions> | 官方研究披露 | 04 |
| Hamel Husain，*Your AI Product Needs Evals*，2024-03-29。<https://hamel.dev/blog/posts/evals/> | 实践文章 | 05 |
| Hamel Husain、Shreya Shankar，*AI Evals FAQ*（2026-09 更新版）。<https://hamel.dev/blog/posts/evals-faq/> | 实践文章 | 05 |
| Shankar 等，*Who Validates the Validators?*，UIST 2024。<https://arxiv.org/abs/2404.12272> | 论文（延伸阅读） | 05 |
| Anthropic（Grace、Hadfield、Olivares、De Jonghe），*Demystifying evals for AI agents*，2026-01-09。<https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents> | 官方工程博客 | 05 |

<a id="section-3"></a>
## 核对与图片说明

- **四篇精读论文**：读了本地 PDF 的正文和相关附录，关键数字与原文表格逐一核对；精读四的附录证明只核对了定理陈述。精读四中发现的一处原文笔误（t = 0.75 时的扣分值）已在该篇“局限”一节说明。
- **略读材料**：依据核对当天的官方页面；视频依据官方页面上的章节目录。
- **论文原图**：按所引论文的原图边界截取，图注中写明了原图编号和页码。
- **示意图**：知识地图、流程图、四篇精读的“论证地图”是本资料绘制的教学示意图，不是原文配图；论证地图中的“隐含假设”和“最弱的一环”是读者的重建与判断。
- **教学数字**：章节中标注为“教学数字”“教学例子”的算例是为讲清概念而设定的，不是真实测量值。
- 没有运行任何论文的实验或代码。

---

[专题目录](README.md) · [知识库首页](../../README.md)
