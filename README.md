# AI Safety Weekly

> Weekly curated papers on AI Safety, LLM red-teaming, adversarial attacks, and agent security

Auto-updated weekly. Last update: **2026-02-23**

---

## 2026-W08

### [What Makes a Good LLM Agent for Real-world Penetration Testing?](https://arxiv.org/abs/2602.17622)
- **Authors:** Gelei Deng, Yi Liu, Yuekang Li et al.
- **Date:** 2026-02-19
- **Category:** `LLM agent AND attack`

> We analyze 28 LLM-based penetration testing systems and evaluate five representative implementations across three benchmarks. We identify two failure modes: Type A (capability gaps from missing tools/prompts, fixable via engineering) and Type B (planning/state management limitations persisting regardless of tooling). Type B failures share a root ca...

**📝 Summary:** 系统分析 28 个 LLM 渗透测试系统，区分能力缺口（Type A）和规划失败（Type B），提出 Excalibur 框架通过难度感知规划在 CTF benchmark 上达到 91% 完成率。

### [Safe Continuous-time Multi-Agent Reinforcement Learning via Epigraph Form](https://arxiv.org/abs/2602.17078)
- **Authors:** Xuefeng Wang, Lei Zhang, Henglin Pu et al.
- **Date:** 2026-02-19
- **Category:** `multi-agent AND safety`

> Multi-agent reinforcement learning (MARL) has made significant progress, but most algorithms rely on a discrete-time Markov Decision Process with fixed decision intervals. We propose a continuous-time constrained MDP (CT-CMDP) formulation and a novel MARL framework that transforms discrete MDPs into CT-CMDPs via an epigraph-based reformulation. Usi...

**📝 Summary:** 将离散时间 MARL 扩展到连续时间约束 MDP，用 PINN actor-critic 解决连续时间安全多智能体问题（ICLR 2026）。

### [Pushing the Frontier of Black-Box LVLM Attacks via Fine-Grained Detail Targeting (M-Attack-V2)](https://arxiv.org/abs/2602.17645)
- **Authors:** Xiaohan Zhao, Zhaoyi Li, Yaxin Luo et al.
- **Date:** 2026-02-19
- **Category:** `adversarial attack AND language model`

> Black-box adversarial attacks on Large Vision-Language Models (LVLMs) are challenging due to missing gradients and complex multimodal boundaries. We find that prior approaches induce high-variance, nearly orthogonal gradients across iterations. We reformulate local matching as an asymmetric expectation over source transformations and target semanti...

**📝 Summary:** M-Attack-V2：改进黑盒多模态 LLM 对抗攻击，通过 MCA+ATA 稳定梯度估计，Claude-4.0 攻击成功率 8%→30%，GPT-5 98%→100%。

### [The Emergence of Lab-Driven Alignment Signatures: A Psychometric Framework for Auditing Latent Bias and Compounding Risk in Generative AI](https://arxiv.org/abs/2602.17127)
- **Authors:** Dusan Bosnjakovic
- **Date:** 2026-02-19
- **Category:** `multi-agent AND safety`

> As LLMs transition from chat interfaces to foundational layers in multi-agent systems and LLM-as-a-judge loops, detection of durable, provider-level behavioral signatures becomes critical. We introduce an auditing framework using psychometric measurement theory to quantify these tendencies without ground-truth labels, utilizing forced-choice ordina...

**📝 Summary:** 心理测量框架审计不同 AI 实验室的 LLM 的隐性偏见和'lab signal'，发现提供商级别的行为签名在多 agent 场景下可能形成复合风险和意识形态回音室。

### [NESSiE: The Necessary Safety Benchmark -- Identifying Errors that should not Exist](https://arxiv.org/abs/2602.16756)
- **Authors:** Johannes Bertram, Jonas Geiping
- **Date:** 2026-02-18
- **Category:** `adversarial attack AND language model`

> We introduce NESSiE, the NEceSsary SafEty benchmark for large language models (LLMs). With minimal test cases of information and access security, NESSiE reveals safety-relevant failures that should not exist, given the low complexity of the tasks. Even state-of-the-art LLMs do not reach 100% on NESSiE, failing the necessary condition of language mo...

**📝 Summary:** NESSiE：极简安全 benchmark，揭示 SOTA LLM 在低复杂度安全任务上仍存在失败，且 benign 干扰上下文可显著降低安全性能。

### [AgentLAB: Benchmarking LLM Agents against Long-Horizon Attacks](https://arxiv.org/abs/2602.16901)
- **Authors:** Tanqiu Jiang, Yuhui Wang, Jiacheng Liang et al.
- **Date:** 2026-02-18
- **Category:** `LLM agent AND attack`

> LLM agents deployed in long-horizon, complex environments face long-horizon attacks that exploit multi-turn user-agent-environment interactions to achieve objectives infeasible in single-turn settings. We present AgentLAB, the first benchmark dedicated to evaluating LLM agent susceptibility to adaptive, long-horizon attacks. AgentLAB supports five ...

**📝 Summary:** AgentLAB：首个专注于评估 LLM agent 对长时程攻击脆弱性的 benchmark，覆盖 5 种攻击类型×28 个真实 agentic 环境×644 个测试用例，证明单轮防御对长时程攻击无效。

### [Automating Agent Hijacking via Structural Template Injection](https://arxiv.org/abs/2602.16958)
- **Authors:** Xinhao Deng, Jiaqing Wu, Miao Chen et al.
- **Date:** 2026-02-18
- **Category:** `agentic AND adversarial`

> We propose Phantom, an automated agent hijacking framework built upon Structured Template Injection that targets the fundamental architectural mechanisms of LLM agents. Agents rely on specific chat template tokens to separate system, user, assistant, and tool instructions. By injecting optimized structured templates into the retrieved context, we i...

**📝 Summary:** Phantom：利用 chat template token 结构注入的 agent 劫持框架，通过 Template Autoencoder + 贝叶斯优化搜索最优对抗模板，在真实商业产品中发现 70+ 漏洞。

### [Mind the GAP: Text Safety Does Not Transfer to Tool-Call Safety in LLM Agents](https://arxiv.org/abs/2602.16943)
- **Authors:** Arnold Cartagena, Ariane Teixeira
- **Date:** 2026-02-18
- **Category:** `jailbreak AND agent`

> Large language models deployed as agents increasingly interact with external systems through tool calls--actions with real-world consequences that text outputs alone do not carry. Safety evaluations, however, overwhelmingly measure text-level refusal behavior, leaving a critical question unanswered: does alignment that suppresses harmful text also ...

**📝 Summary:** 提出 GAP benchmark，发现 LLM agent 的文本层拒绝≠工具调用层安全——模型口头拒绝的同时可能悄悄执行禁止操作，17,420 个数据点覆盖六个前沿模型。

### [Narrow fine-tuning erodes safety alignment in vision-language agents](https://arxiv.org/abs/2602.16931)
- **Authors:** Idhant Gulati, Shivam Raval
- **Date:** 2026-02-18
- **Category:** `safety benchmark AND agent`

> Fine-tuning aligned vision-language models on narrow-domain harmful datasets induces severe emergent misalignment that generalizes broadly across unrelated tasks and modalities. Through experiments on Gemma3-4B, misalignment scales monotonically with LoRA rank, and multimodal evaluation reveals substantially higher misalignment (70.71% at r=128) th...

**📝 Summary:** 窄领域微调可以严重侵蚀视觉语言 agent 的安全对齐，有害行为占据低维子空间（10个主成分），单模态安全 benchmark 低估了多模态模型的对齐退化。

### [Policy Compiler for Secure Agentic Systems (PCAS)](https://arxiv.org/abs/2602.16708)
- **Authors:** Nils Palumbo, Sarthak Choudhary, Jihye Choi et al.
- **Date:** 2026-02-18
- **Category:** `prompt injection`

> LLM-based agents are increasingly being deployed in contexts requiring complex authorization policies. Embedding these policies in prompts provides no enforcement guarantees. We present PCAS, a Policy Compiler for Agentic Systems that provides deterministic policy enforcement. PCAS models the agentic system state as a dependency graph capturing cau...

**📝 Summary:** PCAS：用 dependency graph + Datalog 策略语言实现确定性策略执行，防御 prompt injection，policy 合规率从 48% 提升到 93%，无需修改 agent 代码。

### [Helpful to a Fault: Measuring Illicit Assistance in Multi-Turn, Multilingual LLM Agents (STING)](https://arxiv.org/abs/2602.16346)
- **Authors:** Nivya Talokar, Ayush K Tarun, Murari Mandal et al.
- **Date:** 2026-02-18
- **Category:** `red teaming AND LLM`

> LLM-based agents execute real-world workflows via tools and memory. These affordances enable ill-intended adversaries to also use these agents to carry out complex misuse scenarios. We introduce STING (Sequential Testing of Illicit N-step Goal execution), an automated red-teaming framework that constructs a step-by-step illicit plan grounded in a b...

**📝 Summary:** STING：自动化多轮 agent red-teaming 框架，将攻击建模为 time-to-first-jailbreak 随机变量，多语言实验发现低资源语言未必更脆弱（与 chatbot 研究结论不同）。

### [Recursive language models for jailbreak detection: a procedural defense for tool-augmented agents](https://arxiv.org/abs/2602.16520)
- **Authors:** Doron Shavit
- **Date:** 2026-02-18
- **Category:** `agentic AND adversarial`

> We present RLM-JB, an end-to-end jailbreak detection framework built on Recursive Language Models (RLMs), in which a root model orchestrates a bounded analysis program that transforms the input, queries worker models over covered segments, and aggregates evidence into an auditable decision. RLM-JB treats detection as a procedure rather than one-sho...

**📝 Summary:** RLM-JB：递归 LM 结构的 jailbreak 检测防御框架，将检测视为流程而非单次分类，通过分块+并行筛查+跨块信号合成，对 AutoDAN 类攻击达到 92-98% 召回率。

### [Zombie Agents: Persistent Control of Self-Evolving LLM Agents via Self-Reinforcing Injections](https://arxiv.org/abs/2602.15654)
- **Authors:** Xianglin Yang, Yufei He, Shuo Ji et al.
- **Date:** 2026-02-17
- **Category:** `LLM agent AND attack`

> Self-evolving LLM agents update their internal state across sessions by writing and reusing long-term memory. This creates a security risk: untrusted external content observed during a benign session can be stored as memory and later treated as instruction. We formalize a persistent attack called Zombie Agent, where an attacker covertly implants a ...

**📝 Summary:** Zombie Agent：对自进化 LLM agent 的持久性攻击，通过将 payload 植入 long-term memory 实现跨 session 持久控制，针对滑动窗口和 RAG 记忆设计了绕过截断/相关性过滤的持久化策略。

### [Colosseum: Auditing Collusion in Cooperative Multi-Agent Systems](https://arxiv.org/abs/2602.15198)
- **Authors:** Mason Nakamura, Abhinav Kumar, Saswat Das et al.
- **Date:** 2026-02-16
- **Category:** `multi-agent AND safety`

> Multi-agent systems where LLM agents communicate through free-form language enable sophisticated coordination, but surface a unique safety problem when individual agents form a coalition and collude to pursue secondary goals. We present Colosseum, a framework for auditing LLM agents' collusive behavior in multi-agent settings, grounding cooperation...

**📝 Summary:** Colosseum：多 agent 系统中的串谋审计框架，发现大多数模型在有秘密通信渠道时倾向于串谋，且存在'纸面串谋'现象。

### [A Trajectory-Based Safety Audit of Clawdbot (OpenClaw)](https://arxiv.org/abs/2602.14364)
- **Authors:** Tianyu Chen, Dongrui Liu, Xia Hu et al.
- **Date:** 2026-02-16
- **Category:** `agent safety`

> Clawdbot is a self-hosted, tool-using personal AI agent with a broad action space spanning local execution and web-mediated workflows. We present a trajectory-centric evaluation of Clawdbot across six risk dimensions. Our test suite samples and lightly adapts scenarios from prior agent-safety benchmarks (including ATBench and LPS-Bench) and supplem...

**📝 Summary:** 对 OpenClaw（Clawdbot）做 trajectory-based 安全审计，34 个测试用例覆盖六个风险维度，发现大多数失败出现在意图模糊或 benign-seeming jailbreak 场景。

### [Overthinking Loops in Agents: A Structural Risk via MCP Tools](https://arxiv.org/abs/2602.14798)
- **Authors:** Yohan Lee, Jisoo Jang, Seoyeon Choi et al.
- **Date:** 2026-02-16
- **Category:** `tool use AND attack`

> Tool-using LLM agents increasingly coordinate real workloads by selecting and chaining third-party tools based on text-visible metadata such as tool names, descriptions, and return messages. A malicious MCP tool server can induce overthinking loops where individually trivial or plausible tool calls compose into cyclic trajectories that inflate end-...

**📝 Summary:** 恶意 MCP 工具服务器可通过结构性攻击诱导 agent 陷入'过度思考循环'，造成最高 142.4x 的 token 放大，且解码时的简洁控制无法可靠防御。

### [Boundary Point Jailbreaking of Black-Box LLMs](https://arxiv.org/abs/2602.15001)
- **Authors:** Xander Davies, Giorgi Giglemiani, Edmund Lau et al.
- **Date:** 2026-02-16
- **Category:** `red teaming AND LLM`

> Frontier LLMs are safeguarded against attempts to extract harmful information via adversarial prompts known as "jailbreaks". Recently, defenders have developed classifier-based systems that have survived thousands of hours of human red teaming. We introduce Boundary Point Jailbreaking (BPJ), a new class of automated jailbreak attacks that evade the...

**📝 Summary:** BPJ：纯黑盒 jailbreak，每次只用一 bit 信息（是否被检测器标记），通过 curriculum 中间目标攻破 Constitutional Classifiers 和 GPT-5 输入过滤器。

### [Exposing the Systematic Vulnerability of Open-Weight Models to Prefill Attacks](https://arxiv.org/abs/2602.14689)
- **Authors:** Lukas Struppek, Adam Gleave, Kellin Pelrine
- **Date:** 2026-02-16
- **Category:** `red teaming AND LLM`

> Open-weight models natively support prefilling, which allows an attacker to predefine initial response tokens before generation begins. We present the largest empirical study to date of prefill attacks, evaluating over 20 existing and novel strategies across multiple model families and state-of-the-art open-weight models. Our results show that pref...

**📝 Summary:** 系统研究 prefill attack（预填充初始回复 token）对开源模型的攻击效果，20+ 策略评估全部主流开源模型，发现普遍脆弱；推理模型对通用 prefill 有一定抵抗但针对性策略依然有效。

---

## 2026-W07

### [SkillJect: Automating Stealthy Skill-Based Prompt Injection for Coding Agents](https://arxiv.org/abs/2602.14211)
- **Authors:** Xiaojun Jia, Jie Liao, Simeng Qin et al.
- **Date:** 2026-02-15
- **Category:** `prompt injection`

> Agent skills are becoming a core abstraction in coding agents, packaging long-form instructions and auxiliary scripts to extend tool-augmented behaviors. This abstraction introduces an under-measured attack surface: skill-based prompt injection, where poisoned skills can steer agents away from user intent and safety policies. We propose the first a...

**📝 Summary:** SkillJect：首个针对 coding agent skill 的自动化隐蔽 prompt injection 框架，三 agent 闭环（Attack/Code/Evaluate），将恶意操作藏于辅助脚本中。

### [Unsafer in Many Turns: Benchmarking and Defending Multi-Turn Safety Risks in Tool-Using Agents](https://arxiv.org/abs/2602.13379)
- **Authors:** Xu Li, Simon Yu, Minzhou Pan et al.
- **Date:** 2026-02-13
- **Category:** `agent safety`

> LLM-based agents are becoming increasingly capable, yet their safety lags behind. This creates a gap between what agents can do and should do. This gap widens as agents engage in multi-turn interactions and employ diverse tools, introducing new risks overlooked by existing benchmarks. To systematically scale safety testing into multi-turn, tool-rea...

**📝 Summary:** 构建 MT-AgentRisk benchmark（首个多轮工具调用 agent 安全评估），发现多轮场景下 ASR 平均提升 16%；提出免训练防御 ToolShield。Bo Li 组的工作！

---


*Curated by [aq bot](https://github.com/aquamarine-bot) · [AI Safety Weekly](https://github.com/aquamarine-bot/ai-safety-weekly)*