# 软件测试：从选输入到判断对错

[返回知识库首页](../../README.md)

用同一条业务规则连接测试方法。输入、结构和答案依据分别提供证据，不能互相冒充。

## 从一个完整例子进入

### [黑盒与白盒测试：从选输入到判断证据](00_%E9%98%85%E8%AF%BB%E8%B5%B7%E7%82%B9.md)

沿着选输入、看结构、判断结果的顺序学习测试，并明确每类证据能够支持多强的结论。

### [用一条折扣规则，串起黑盒、白盒、符号执行与结果判断](09_%E8%B4%AF%E9%80%9A%E7%BB%83%E4%B9%A0.md)

用同一条折扣规则串起边界、组合、条件覆盖和预期答案，检验能否读懂一份测试结论。

## 有理由地选择输入

### [黑盒测试怎么选用例？从等价类、边界到状态变化](01_ISTQB.md)

从一条业务规则构造等价类、边界、决策表和状态变化，交代每种覆盖的分母。

### [组合太多测不完怎么办？NIST 组合测试的原理与分母](02_NIST.md)

用小表格理解组合覆盖为什么能节省测试，以及约束和高阶交互如何留下空白。

## 检查结构与生成方法

### [分支都跑过，还会漏什么？读懂 NASA 的 MC/DC 教程](03_NASA.md)

为每个条件找出独立改变最终决策的证据对，区分条件出现过与条件起过作用。

### [覆盖率多高才算测够？测试充分性的机制与边界](04_Zhu.md)

把覆盖率看成定义明确的观察标准，理解“结构要求更强”为什么不自动等于检错更多。

### [符号执行是什么？让一次分析代表一整类程序输入](05_King.md)

用符号状态和路径条件代表多组输入，逐步推导可达分支及方法的边界。

### [KLEE 怎样自动生成测试？从路径搜索到真实系统的限制](06_KLEE.md)

从小程序走向真实系统，理解搜索、约束查询和外部环境模型怎样共同限制自动测试。

## 判断证据是否充分

### [覆盖率高，为什么未必更能找出错误？读懂 ICSE 2014 实验](07_Coverage_Effectiveness.md)

控制测试数量后重新看覆盖率与检错效果，区分相关关系、代理指标和因果结论。

### [程序跑完之后，谁来判断对错？测试判定依据的完整问题](08_Oracle.md)

找到正确答案的依据，比较规格、差分、性质和人工判断，并检查它们会怎样共同出错。

## 原始资料入口

- [ISTQB CTFL 基础级大纲](https://istqb.org/?download_id=3345&sdm_process_download=1) — v4.0.1，2024。
- [NIST Practical Combinatorial Testing](https://nvlpubs.nist.gov/nistpubs/legacy/sp/nistspecialpublication800-142.pdf) — SP 800-142，2010。
- [NASA MC/DC 教程](https://ntrs.nasa.gov/api/citations/20010057789/downloads/20010057789.pdf) — NASA/TM-2001-210876，2001。
- [Zhu 等：测试覆盖与充分性综述](https://userweb.cs.txstate.edu/~rp31/papers/ZhuHallMay.pdf) — ACM Computing Surveys，1997。
- [King：符号执行与程序测试](https://lim.univ-reunion.fr/staff/fred/Enseignement/Verif-M2/Articles/Autres/Symbolic-execution-and-Program-Testing-King-1976.pdf) — Communications of the ACM，1976。
- [KLEE：高覆盖测试自动生成](https://www.usenix.org/events/osdi08/tech/full_papers/cadar/cadar.pdf) — OSDI，2008。
- [覆盖率与测试检错效果](https://www.cs.ubc.ca/~rtholmes/papers/icse_2014_inozemtseva.pdf) — ICSE，2014；作者稿。
- [测试 Oracle 问题综述](https://philmcminn.com/publications/barr2015.pdf) — IEEE TSE，2015；作者稿。
