# Agent 设计：按瓶颈选择机制

[返回知识库首页](../../README.md)

九篇论文不组成一张组件采购表。这里关心新机制怎样改变信息、步骤、时间或反馈。

## 先看问题全貌

### [Agent 设计：读懂九篇论文如何改变推理与行动的过程](00_%E9%98%85%E8%AF%BB%E8%B5%B7%E7%82%B9.md)

用事实、步骤和反馈三个入口读九篇论文，避免把方法名称当成必选组件。

### [九篇 Agent 论文怎么选？按任务的不确定性拆解设计](10_%E7%BB%BC%E5%90%88%E7%A0%94%E7%A9%B6.md)

按任务中的不确定性比较九种方法，设计同预算、同反馈条件下才有解释力的实验。

## 从事实与步骤开始

### [ReAct：为什么让模型边查边想，比只写推理过程更有用](01_ReAct.md)

用原论文的查询轨迹理解行动与观察循环，辨别最终答对和推理可靠之间的差别。

### [Plan-and-Solve：先列计划，究竟减少了哪一种推理错误](02_Plan_and_Solve.md)

从漏步和计算错误区分规划的作用，再用提示消融判断“写得更详细”是否真的有效。

### [Self-Discover：先选推理结构，再解题，为什么可能有效](08_Self_Discover.md)

观察推理模块怎样被选择、改写和组合，区分结构发现的成本与后续解题收益。

## 理解成本与依赖

### [ReWOO：怎样减少重复规划，又保留工具返回的真实证据](03_ReWOO.md)

区分未知结果与未知路线，理解结果引用如何减少重复规划，以及哪些任务仍需重规划。

### [LLMCompiler：Agent 为什么慢，哪些工具调用可以并行](04_LLMCompiler.md)

把工具调用写成依赖关系，找出真正决定完成时间的步骤，并检查并行的前提。

## 比较修改、记忆与搜索

### [Self-Refine：让模型自己改答案，什么反馈才真正有用](05_Self_Refine.md)

拆解“生成—反馈—修改”过程，判断反馈是否提供了能执行的新信息，而非重复鼓励。

### [Reflexion：反思能让 Agent 少犯错吗？关键在反馈与记忆](06_Reflexion.md)

区分修改当前答案和保存尝试间经验，追问反思依据是否可靠、失败诊断是否正确。

### [LATS：让 Agent 比较多条行动路线，收益和代价在哪里](07_LATS.md)

理解候选搜索怎样分配尝试预算，以及状态回退、价值判断和停止规则的代价。

## 调查与长文生成

### [STORM：长文写得全面，为什么仍可能把事实关系写错](09_STORM.md)

追踪从调查视角到成文的全过程，区分资料覆盖充分与引用真正支持结论。

## 原始资料入口

- [ReAct](https://arxiv.org/pdf/2210.03629v3) — arXiv:2210.03629v3。
- [Plan and Solve](https://aclanthology.org/2023.acl-long.147.pdf) — ACL 2023。
- [ReWOO](https://arxiv.org/pdf/2305.18323v1) — arXiv:2305.18323v1。
- [LLMCompiler](https://arxiv.org/pdf/2312.04511v3) — arXiv:2312.04511v3。
- [Self Refine](https://arxiv.org/pdf/2303.17651v2) — arXiv:2303.17651v2。
- [Reflexion](https://arxiv.org/pdf/2303.11366v4) — arXiv:2303.11366v4。
- [LATS](https://arxiv.org/pdf/2310.04406v3) — arXiv:2310.04406v3。
- [Self Discover](https://arxiv.org/pdf/2402.03620v1) — arXiv:2402.03620v1。
- [STORM](https://aclanthology.org/2024.naacl-long.347.pdf) — NAACL 2024。
