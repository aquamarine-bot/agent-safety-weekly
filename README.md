# AI Safety Weekly

> Weekly curated papers on AI Safety, LLM red-teaming, adversarial attacks, and agent security

Auto-updated weekly. Last update: **2026-05-04**

---

## 2026-W18

### [Self-Adaptive Multi-Agent LLM-Based Security Pattern Selection for IoT Systems](https://arxiv.org/abs/2605.00741)
- **Authors:** Saeid Jamshidi, Foutse Khomh, Carol Fung et al.
- **Date:** 2026-05-01
- **Category:** `"multi-agent" AND "safety"`

> The adoption of Internet of Things (IoT) systems at the network edge of smart architectures is increasing rapidly, intensifying the need for security mechanisms that are both adaptive and resource-efficient. We introduce ASPO, a self-adaptive multi-agent security pattern selection that integrates Large Language Model (LLM)-based reasoning with dete...

**📝 Summary:** 提出 ASPO，将 LLM 推理与确定性执行引擎结合的自适应多智能体安全模式选择系统，实现 100% 无冲突激活，面向 IoT 边缘安全。

### [Stable-GFlowNet: Toward Diverse and Robust LLM Red-Teaming via Contrastive Trajectory Balance](https://arxiv.org/abs/2605.00553)
- **Authors:** Minchan Kwon, Sunghyun Baek, Minseo Kim et al.
- **Date:** 2026-05-01
- **Category:** `"red teaming" AND "LLM"`

> Large Language Model (LLM) Red-Teaming, which proactively identifies vulnerabilities of LLMs, is an essential process for ensuring safety. Finding effective and diverse attacks in red-teaming is important, but achieving both is challenging. Generative Flow Networks (GFNs) that perform distribution matching are a promising methods, but they are noto...

**📝 Summary:** 提出 Stable-GFN，通过配对比较消除 GFlowNet 的分区函数估计，在 ICML 2026 Spotlight 中展示了稳定且多样的 LLM 红队攻击生成。

### [FinSafetyBench: Evaluating LLM Safety in Real-World Financial Scenarios](https://arxiv.org/abs/2605.00706)
- **Authors:** Yutao Hou, Yihan Jiang, Yuhan Xie et al.
- **Date:** 2026-05-01
- **Category:** `"red teaming" AND "LLM"`

> Large language models (LLMs) are increasingly applied in financial scenarios. However, they may produce harmful outputs, including facilitating illegal activities or unethical behavior, posing serious compliance risks. To systematically evaluate LLM safety in finance, we propose FinSafetyBench, a bilingual (English-Chinese) red-teaming benchmark de...

**📝 Summary:** 提出双语金融合规红队基准 FinSafetyBench（14 子类别），测试 LLM 对金融犯罪类请求的拒绝能力，ACL 2026 Findings。

### [FlashRT: Towards Computationally and Memory Efficient Red-Teaming for Prompt Injection and Knowledge Corruption](https://arxiv.org/abs/2604.28157)
- **Authors:** Yanting Wang, Chenlong Yin, Ying Chen et al.
- **Date:** 2026-04-30
- **Category:** `"prompt injection" AND "agent"`

> Long-context large language models (LLMs) are widely used to empower many real-world applications, such as retrieval-augmented generation, autonomous agents, and AI assistants. However, security remains a major concern for their widespread deployment, with threats such as prompt injection and knowledge corruption. To quantify the security risks fac...

**📝 Summary:** 提出 FlashRT，通过计算和内存优化加速针对长上下文 LLM 的 prompt injection 红队测试，速度提升 2-7x，内存减少 2-4x。

### [The Inverse-Wisdom Law: Architectural Tribalism and the Consensus Paradox in Agentic Swarms](https://arxiv.org/abs/2604.27274)
- **Authors:** Dahlia Shehata, Ming Li
- **Date:** 2026-04-30
- **Category:** `"multi-agent" AND "safety"`

> As AI transitions toward multi-agent systems to solve complex workflows, research paradigms operate on the axiomatic assumption that agent collaboration mirrors the 'Wisdom of the Crowd'. We challenge this assumption by formalizing the Consensus Paradox: a phenomenon where agentic swarms prioritize internal architectural agreement over external log...

**📝 Summary:** 在 12,804 条轨迹上发现'逆智慧定律'：同构多 agent 群中增加逻辑 agent 反而稳固错误轨迹，揭示架构同质性（模型同族）是群体失效的关键因素。

### [Safe Bilevel Delegation (SBD): A Formal Framework for Runtime Delegation Safety in Multi-Agent Systems](https://arxiv.org/abs/2604.27358)
- **Authors:** Yuan Sun
- **Date:** 2026-04-30
- **Category:** `"multi-agent" AND "safety"`

> As large language model (LLM) agents are deployed in high-stakes environments, the question of how safely to delegate subtasks to specialized sub-agents becomes critical. We propose Safe Bilevel Delegation (SBD), a formal framework for runtime delegation safety in hierarchical multi-agent systems. SBD formulates task delegation as a bilevel optimiz...

**📝 Summary:** 提出双层优化框架 SBD，在运行时动态调整多智能体任务委托中的安全-效率权衡，并证明安全单调性和问责传播界。

### [Attention Is Where You Attack](https://arxiv.org/abs/2605.00236)
- **Authors:** Aviral Srivastava, Sourav Panda
- **Date:** 2026-04-30
- **Category:** `"adversarial attack" AND "language model"`

> Safety-aligned large language models rely on RLHF and instruction tuning to refuse harmful requests, yet the internal mechanisms implementing safety behavior remain poorly understood. We introduce the Attention Redistribution Attack (ARA), a white-box adversarial attack that identifies safety-critical attention heads and crafts nonsemantic adversar...

**📝 Summary:** 提出注意力重分配攻击（ARA），定位安全关键 attention head 并重定向其注意力，仅需 5 个非语义对抗 token 即可绕过 LLM 安全对齐。

### [A Logic of Inability](https://arxiv.org/abs/2604.27917)
- **Authors:** Shanxia Wang
- **Date:** 2026-04-30
- **Category:** `"multi-agent" AND "safety"`

> Coalition Logic is primarily concerned with what coalitions can achieve, whereas what coalitions cannot achieve -- their inability -- has received comparatively little explicit attention. This asymmetry matters in artificial intelligence and safety-critical multi-agent systems, where one often needs to specify not merely what agents are instructed ...

**📝 Summary:** 扩展联盟逻辑引入明确的'无力算子'，为多智能体系统中的能力限制和不可能性推理提供形式化框架。

### [Understanding Adversarial Transferability in Vision-Language Models for Autonomous Driving: A Cross-Architecture Analysis](https://arxiv.org/abs/2604.27414)
- **Authors:** David Fernandez, Pedram MohajerAnsari, Amir Salarpour et al.
- **Date:** 2026-04-30
- **Category:** `"adversarial attack" AND "language model"`

> Vision-language models (VLMs) are increasingly used in autonomous driving because they combine visual perception with language-based reasoning. We address this gap with a systematic cross-architecture study of adversarial transferability in VLM-based driving, evaluating three representative architectures (Dolphins, OmniDrive, and LeapVAD) using phy...

**📝 Summary:** 研究自动驾驶 VLM 跨架构对抗迁移性，三种架构间转移率达 73-91%，发布于 SAE WCX 2026。

### [Low Rank Adaptation for Adversarial Perturbation](https://arxiv.org/abs/2604.27487)
- **Authors:** Han Liu, Shanghao Shi, Yevgeniy Vorobeychik et al.
- **Date:** 2026-04-30
- **Category:** `"adversarial attack" AND "language model"`

> Low-Rank Adaptation (LoRA) has significantly improved the training efficiency of Large Language Models by updating neural network layers using low-rank matrices. Since the generation of adversarial examples is an optimization process analogous to model training, this raises the question: Do adversarial perturbations exhibit a similar low-rank struc...

**📝 Summary:** 证明对抗扰动具有内在低秩结构，并利用此特性将搜索空间降至低维子空间，显著提升黑盒攻击的效率和效果。

### [Causal Foundations of Collective Agency](https://arxiv.org/abs/2605.00248)
- **Authors:** Frederik Hytting Jørgensen, Sebastian Weichwald, Lewis Hammond
- **Date:** 2026-04-30
- **Category:** `"multi-agent" AND "safety"`

> A key challenge for the safety of advanced AI systems is the possibility that multiple simpler agents might inadvertently form a collective agent with capabilities and goals distinct from those of any individual. We adopt a behavioral perspective, ascribing collective agency to a group when viewing the group's joint actions as rational and goal-dir...

**📝 Summary:** 用因果博弈和因果抽象形式化多智能体系统中的集体行为，为理解 AI 涌现集体智能提供理论基础，CLeaR 2026。

### [Ambient Persuasion in a Deployed AI Agent: Unauthorized Escalation Following Routine Non-Adversarial Content Exposure](https://arxiv.org/abs/2605.00055)
- **Authors:** 
- **Date:** 2026-04-29
- **Category:** `"multi-agent" AND "safety"`

> We report a safety incident in a deployed multi-agent research system in which a primary AI agent installed 107 unauthorized software components, overwrote a system registry, overrode a prior negative decision from an oversight agent, and escalated through increasingly privileged operations up to an attempted system administrator command. The incid...

**📝 Summary:** 报告已部署 AI agent 安全事件：读取一篇非对抗性技术文章后，agent 自主安装 107 个未授权组件并逐步升级权限，揭示'环境说服'（ambient persuasion）这一新型威胁。

### [Indirect Prompt Injection in the Wild: An Empirical Study of Prevalence, Techniques, and Objectives](https://arxiv.org/abs/2604.27202)
- **Authors:** Soheil Khodayari, Xuenan Zhang, Bhupendra Acharya et al.
- **Date:** 2026-04-29
- **Category:** `"prompt injection" AND "agent"`

> As LLMs are increasingly integrated into systems that browse, retrieve, summarize, and act on web content, webpages have become an untrusted input vector for downstream model behavior. We present one of the first large-scale empirical analyses of indirect prompt injections in webpages and HTTP responses. Analyzing 1.2B URLs from 24.8M hosts, we ide...

**📝 Summary:** 对 12亿 URL 的大规模扫描，发现 1.5 万条真实存在的 indirect prompt injection，70% 针对机器而非人类，揭示真实网络生态中的 injection 分布。

### [SnapGuard: Lightweight Prompt Injection Detection for Screenshot-Based Web Agents](https://arxiv.org/abs/2604.25562)
- **Authors:** Mengyao Du, Han Fang, Haokai Ma et al.
- **Date:** 2026-04-28
- **Category:** `"prompt injection" AND "agent"`

> Web agents have emerged as an effective paradigm for automating interactions with complex web environments, yet remain vulnerable to prompt injection attacks that embed malicious instructions into webpage content to induce unintended actions. This threat is further amplified for screenshot-based web agents, which operate on rendered visual webpages...

**📝 Summary:** 轻量级方法 SnapGuard 通过视觉稳定性和文本信号检测截图型 web agent 的 prompt injection，比 GPT-4o 快 8 倍，F1=0.75。

### [Luminol-AIDetect: Fast Zero-shot Machine-Generated Text Detection based on Perplexity under Text Shuffling](https://arxiv.org/abs/2604.25860)
- **Authors:** Lucio La Cava, Andrea Tagarelli
- **Date:** 2026-04-28
- **Category:** `"adversarial attack" AND "language model"`

> Machine-generated text (MGT) detection requires identifying structurally invariant signals across generation models. We propose Luminol-AIDetect, a novel zero-shot statistical approach that exposes LLM structural fragility through coherence disruption. By applying a simple randomized text-shuffling procedure, we demonstrate that the resulting shift...

**📝 Summary:** 提出基于文本打乱后困惑度变化的零样本机器生成文本检测方法 Luminol-AIDetect，跨 18 语言、11 种攻击类型实现 SOTA，FPR 降低 17 倍。

### [One Perturbation, Two Failure Modes: Probing VLM Safety via Embedding-Guided Typographic Perturbations](https://arxiv.org/abs/2604.25102)
- **Authors:** Ravikumar Balakrishnan, Sanket Mendapara
- **Date:** 2026-04-28
- **Category:** `"prompt injection" AND "agent"`

> Typographic prompt injection exploits vision language models' (VLMs) ability to read text rendered in images, posing a growing threat as VLMs power autonomous agents. Prior work typically focus on maximizing attack success rate (ASR) but does not explain why certain renderings bypass safety alignment. We make two contributions. First, an empirical ...

**📝 Summary:** 研究 VLM 中排版型 prompt injection 攻击，发现嵌入距离能预测攻击成功率（r=-0.71~-0.93），揭示安全对齐绕过的两种失效模式（可读性恢复 vs 对齐弱化）。

---

## 2026-W17

### [Automation-Exploit: A Multi-Agent LLM Framework for Adaptive Offensive Security with Digital Twin-Based Risk-Mitigated Exploitation](https://arxiv.org/abs/2604.22427)
- **Authors:** Biagio Andreucci, Arcangelo Castiglione
- **Date:** 2026-04-24
- **Category:** `"multi-agent" AND "safety"`

> Automation-Exploit is a fully autonomous Multi-Agent System (MAS) framework designed for adaptive offensive security in complex black-box scenarios. It bridges the abstraction gap between reconnaissance and exploitation by autonomously exfiltrating executables and contextual intelligence across multiple protocols. The framework introduces an adapti...

**📝 Summary:** 多 agent 系统自动化漏洞利用框架，通过数字孪生进行风险缓解的内存漏洞利用，在真实黑盒场景中验证架构有效性。

### [Black-Box Skill Stealing Attack from Proprietary LLM Agents: An Empirical Study](https://arxiv.org/abs/2604.21829)
- **Authors:** Zihan Wang, Rui Zhang, Yu Liu et al.
- **Date:** 2026-04-23
- **Category:** `"agentic" AND "adversarial"`

> LLM agents increasingly rely on skills to encapsulate reusable capabilities via progressively disclosed instructions. This paper presents the first empirical study of black-box skill stealing against LLM agent systems. An automated stealing prompt generation agent starts from model-generated seed prompts, expands them through scenario rationalizati...

**📝 Summary:** 首个对 LLM agent skill（系统提示/指令）的黑盒窃取攻击实证研究：仅需 3 次交互即可提取技能内容，引发版权和知识产权风险。

### [MCP Pitfall Lab: Exposing Developer Pitfalls in MCP Tool Server Security under Multi-Vector Attacks](https://arxiv.org/abs/2604.21477)
- **Authors:** Run Hao, Zhuoran Tan
- **Date:** 2026-04-23
- **Category:** `"LLM agent" AND "attack"`

> Model Context Protocol (MCP) is increasingly adopted for tool-integrated LLM agents, but its multi-layer design and third-party server ecosystem expand risks across tool metadata, untrusted outputs, cross-tool flows, multimodal inputs, and supply-chain vectors. MCP Pitfall Lab operationalizes developer pitfalls as reproducible scenarios and validat...

**📝 Summary:** MCP 工具服务器安全 pitfall 测试框架：系统化暴露 tool-metadata 污染、puppet server、多模态注入等开发者陷阱，trace-based 验证揭示 agent narrative 与实际 trace 在 63.2% 情况下不一致。

### [Adaptive Instruction Composition for Automated LLM Red-Teaming](https://arxiv.org/abs/2604.21159)
- **Authors:** Jesse Zymet, Andy Luo, Swapnil Shinde et al.
- **Date:** 2026-04-22
- **Category:** `"red teaming" AND "LLM"`

> This article introduces Adaptive Instruction Composition, a novel framework that combines crowdsourced texts according to an adaptive mechanism trained to jointly optimize effectiveness with diversity. It uses reinforcement learning to balance exploration with exploitation in a combinatorial space of instructions to guide the attacker toward divers...

**📝 Summary:** 提出 Adaptive Instruction Composition：用 RL 训练的上下文 bandit 自适应组合众包 query+tactic，在多样性-有效性 Pareto 上超越已有方法，ACL 2026 Main 发表。

### [Cross-Session Threats in AI Agents: Benchmark, Evaluation, and Algorithms](https://arxiv.org/abs/2604.21131)
- **Authors:** Ari Azarafrooz
- **Date:** 2026-04-22
- **Category:** `"agentic" AND "adversarial"`

> AI-agent guardrails are memoryless: each message is judged in isolation, so an adversary who spreads a single attack across dozens of sessions slips past every session-bound detector because only the aggregate carries the payload. This paper presents CSTM-Bench, 26 executable attack taxonomies classified by kill-chain stage and cross-session operat...

**📝 Summary:** 提出跨会话威胁 benchmark CSTM-Bench：攻击意图被分散在多个独立会话中，现有无状态 guardrail 无法检测；Coreset Memory Reader 是唯一在两个测试 shard 下保持 recall 的方案。

### [Breaking MCP with Function Hijacking Attacks: Novel Threats for Function Calling and Agentic Models](https://arxiv.org/abs/2604.20994)
- **Authors:** Yannis Belkhiter, Giulio Zizzo, Sergio Maffeis et al.
- **Date:** 2026-04-22
- **Category:** `"jailbreak" AND "agent"`

> This paper introduces a novel function hijacking attack (FHA) that manipulates the tool selection process of agentic models to force the invocation of a specific, attacker-chosen function. While existing attacks focus on semantic preference of the model for function-calling tasks, FHA is largely agnostic to the context semantics and robust to the f...

**📝 Summary:** 提出函数劫持攻击（FHA）：操纵 agentic 模型的工具选择过程，强制调用攻击者指定函数，在 BFCL 数据集上 ASR 达 70-100%。

### [Cyber Defense Benchmark: Agentic Threat Hunting Evaluation for LLMs in SecOps](https://arxiv.org/abs/2604.19533)
- **Authors:** Alankrit Chona, Igor Kozlov, Ambuj Kumar
- **Date:** 2026-04-21
- **Category:** `"LLM agent" AND "attack"`

> The Cyber Defense Benchmark measures how well LLM agents perform the core SOC analyst task of threat hunting: given a database of raw Windows event logs with no guided questions or hints, identify the exact timestamps of malicious events. The benchmark wraps 106 real attack procedures from the OTRF Security-Datasets corpus across 86 MITRE ATT&CK su...

**📝 Summary:** 网络防御 benchmark：在真实 Windows 日志（75k-135k 条记录）中威胁猎取，Claude Opus 4.6 等最强模型仅能找到 3.8% 的恶意事件，LLM 在开放式安全分析上仍然非常弱。

### [An AI Agent Execution Environment to Safeguard User Data](https://arxiv.org/abs/2604.19657)
- **Authors:** Robert Stanley, Avi Verma, Lillian Tsai et al.
- **Date:** 2026-04-21
- **Category:** `"prompt injection" AND "agent"`

> AI agents promise to serve as general-purpose personal assistants for their users, which requires them to have access to private user data. This poses a serious risk to security and privacy. Adversaries may attack the AI model via prompt injection to exfiltrate user data. This paper presents GAAP (Guaranteed Accounting for Agent Privacy), an execut...

**📝 Summary:** 提出 GAAP 执行环境，通过信息流控制（IFC）在不信任 agent 模型的前提下，确定性地防止 prompt injection 导致的用户私有数据泄露。

### [If you're waiting for a sign... that might not be it! Mitigating Trust Boundary Confusion from Visual Injections on Vision-Language Agentic Systems](https://arxiv.org/abs/2604.19844)
- **Authors:** Jiamin Chang, Minhui Xue, Ruoxi Sun et al.
- **Date:** 2026-04-21
- **Category:** `"prompt injection" AND "agent"`

> Recent advances in embodied Vision-Language Agentic Systems (VLAS), powered by large vision-language models (LVLMs), enable AI systems to perceive and reason over real-world scenes. Environmental signals such as traffic lights are essential in-band signals that can and should influence agent behavior. However, similar signals could also be crafted ...

**📝 Summary:** 研究视觉语言 agent 中「信任边界混淆」问题：合法的环境信号（如交通灯）与恶意视觉注入难以区分，提出双进程防御框架（感知与决策分离）。

### [STAR-Teaming: A Strategy-Response Multiplex Network Approach to Automated LLM Red Teaming](https://arxiv.org/abs/2604.18976)
- **Authors:** MinJae Jung, YongTaek Lim, Chaeyun Kim et al.
- **Date:** 2026-04-21
- **Category:** `"jailbreak" AND "agent"`

> This paper introduces STAR-Teaming, a novel black-box framework for automated red teaming that effectively generates jailbreak prompts. STAR-Teaming integrates a Multi-Agent System (MAS) with a Strategy-Response Multiplex Network and employs network-driven optimization to sample effective attack strategies. This network-based approach recasts the i...

**📝 Summary:** STAR-Teaming：用多路复用策略网络驱动自动化红队测试，将攻击策略空间组织为语义社区，在 ACL 2026 Findings 发表，显著提升 ASR 同时降低计算成本。

### [Do Agents Dream of Root Shells? Partial-Credit Evaluation of LLM Agents in Capture The Flag Challenges](https://arxiv.org/abs/2604.19354)
- **Authors:** Ali Al-Kaswan, Maksim Plotnikov, Maxim Hájek et al.
- **Date:** 2026-04-21
- **Category:** `"LLM agent" AND "attack"`

> DeepRed is an open-source benchmark for evaluating LLM-based agents on realistic Capture The Flag (CTF) challenges in isolated virtualized environments. DeepRed introduces a partial-credit scoring method based on challenge-specific checkpoints derived from public writeups, together with an automated summarise-then-judge labelling pipeline. Benchmar...

**📝 Summary:** DeepRed：在真实 CTF VM 环境中评估 LLM agent，引入 checkpoint 部分计分方案，最强模型仅完成 35% checkpoint，非标准发现任务和长时程任务最弱。

---

## 2026-W16

### [MemEvoBench: Benchmarking Memory MisEvolution in LLM Agents](https://arxiv.org/abs/2604.15774)
- **Authors:** Weiwei Xie, Shaoxiong Guo, Fan Zhang et al.
- **Date:** 2026-04-17
- **Category:** `agentic AND adversarial`

> Equipping LLMs with persistent memory enhances interaction continuity and personalization but introduces new safety risks. Specifically, contaminated or biased memory accumulation can trigger abnormal agent behaviors, referred to as memory misevolution. We introduce MemEvoBench, the first benchmark evaluating long-horizon memory safety in LLM agent...

**📝 Summary:** MemEvoBench：首个 LLM agent 记忆演化安全 benchmark，测试对抗记忆注入和噪声工具输出下的长程行为漂移。

### [A Systematic Study of Training-Free Methods for Trustworthy Large Language Models](https://arxiv.org/abs/2604.15789)
- **Authors:** Wai Man Si, Mingjie Li, Michael Backes et al.
- **Date:** 2026-04-17
- **Category:** `adversarial attack AND language model`

> To enable quick and low-cost adaptation, training-free methods have recently emerged as cost-effective alternatives to post-training alignment techniques. We systematically re-evaluate the effectiveness of existing training-free methods against various trustworthy settings and their influence on utility, robustness, and computational overhead. We c...

**📝 Summary:** 系统综述 LLM 免训练安全方法（input/internal/output三层），分析各方法在鲁棒性、效用、计算开销上的权衡与未解问题。

### [Stochasticity in Tokenisation Improves Robustness](https://arxiv.org/abs/2604.16037)
- **Authors:** Sophie Steger, Rui Li, Sofiane Ennadir et al.
- **Date:** 2026-04-17
- **Category:** `adversarial attack AND language model`

> The widespread adoption of large language models (LLMs) has increased concerns about their robustness. Vulnerabilities in perturbations of tokenisation of the input indicate that models trained with a deterministic canonical tokenisation can be brittle to adversarial attacks. We show that pre-training and fine-tuning with uniformly sampled stochast...

**📝 Summary:** 随机 tokenization 训练提升 LLM 对抗鲁棒性；规范 tokenization 训练的模型在非规范输入上准确率下降29.8%。

### [HarmfulSkillBench: How Do Harmful Skills Weaponize Your Agents?](https://arxiv.org/abs/2604.15415)
- **Authors:** Yukun Jiang, Yage Zhang, Michael Backes et al.
- **Date:** 2026-04-16
- **Category:** `agent safety`

> Large language models (LLMs) have evolved into autonomous agents that rely on open skill ecosystems (e.g., ClawHub and Skills.Rest), hosting numerous publicly reusable skills. Existing security research on these ecosystems mainly focuses on vulnerabilities within skills, such as prompt injection. However, there is a critical gap regarding skills th...

**📝 Summary:** 首个大规模 harmful skill 研究（98,440个技能，4.93%有害）；HarmfulSkillBench benchmark 展示隐式恶意意图时 harm score 从0.27升至0.76。

### [Hijacking Large Audio-Language Models via Context-Agnostic and Imperceptible Auditory Prompt Injection](https://arxiv.org/abs/2604.14604)
- **Authors:** Meng Chen, Kun Wang, Li Lu et al.
- **Date:** 2026-04-16
- **Category:** `prompt injection AND agent`

> Modern Large audio-language models (LALMs) power intelligent voice interactions by tightly integrating audio and text. We reveal a previously overlooked threat, auditory prompt injection, under realistic constraints of audio data-only access and strong perceptual stealth. We propose AudioHijack, a general framework that generates context-agnostic a...

**📝 Summary:** AudioHijack：对13个语音大模型的音频 prompt injection 攻击，上下文无关，成功率79%-96%，IEEE S&P 2026。

### [Symbolic Guardrails for Domain-Specific Agents: Stronger Safety and Security Guarantees Without Sacrificing Utility](https://arxiv.org/abs/2604.15579)
- **Authors:** Yining Hong, Yining She, Eunsuk Kang et al.
- **Date:** 2026-04-16
- **Category:** `agent safety`

> AI agents that interact with their environments through tools enable powerful applications, but in high-stakes business settings, unintended actions can cause unacceptable harm, such as privacy breaches and financial loss. Existing mitigations, such as training-based methods and neural guardrails, improve agent reliability but cannot provide guaran...

**📝 Summary:** 系统综述80个 agent safety benchmark，发现85%缺乏具体策略；符号护栏可执行74%策略需求且不牺牲 agent 效用。

### [SoK: Security of Autonomous LLM Agents in Agentic Commerce](https://arxiv.org/abs/2604.15367)
- **Authors:** Qian'ang Mao, Jiaxin Wang, Ya Liu et al.
- **Date:** 2026-04-15
- **Category:** `LLM agent AND attack`

> Autonomous LLM agents are pushing agentic commerce from human-supervised assistance toward machine actors that can negotiate, purchase services, manage digital assets, and execute transactions. This SoK develops a unified security framework for autonomous LLM agents in commerce and finance. We organize threats along five dimensions: agent integrity...

**📝 Summary:** SoK：自主 LLM agent 在 agentic commerce 场景下的安全系统综述，12个跨层攻击向量，五维度威胁分类框架。

### [LogJack: Indirect Prompt Injection Through Cloud Logs Against LLM Debugging Agents](https://arxiv.org/abs/2604.15368)
- **Authors:** Harsh Shah
- **Date:** 2026-04-15
- **Category:** `prompt injection AND agent`

> LLM debugging agents that consume cloud logs and execute remediation commands are vulnerable to indirect prompt injection through log content. We present LogJack, a benchmark of 42 payloads across 5 cloud log categories, and evaluate 8 foundation models under 3 prompt conditions with 5 independent trials each. Under the active condition, verbatim c...

**📝 Summary:** LogJack：通过云日志内容对 LLM 调试 agent 进行 indirect prompt injection，发现 'sanitize and execute' 新行为；不同模型成功率从0%到86.2%。

### [Don't Let AI Agents YOLO Your Files: Shifting Information and Control to Filesystems for Agent Safety and Autonomy](https://arxiv.org/abs/2604.13536)
- **Authors:** Shawn Wanxiang Zhong, Junxuan Liao, Jing Liu et al.
- **Date:** 2026-04-15
- **Category:** `agent safety`

> AI coding agents operate directly on users' filesystems, where they regularly corrupt data, delete files, and leak secrets. Current approaches force a tradeoff between safety and autonomy. To understand this problem, we conduct the first systematic study of agent filesystem misuse, analyzing 290 public reports across 13 frameworks. We design YoloFS...

**📝 Summary:** YoloFS：通过 staging/snapshot/progressive permission 机制防止 AI agent 误操作文件系统，分析290个公开误用报告。

### [SafeHarness: Lifecycle-Integrated Security Architecture for LLM-based Agent Deployment](https://arxiv.org/abs/2604.13630)
- **Authors:** Xixun Lin, Yang Liu, Yancheng Chen et al.
- **Date:** 2026-04-15
- **Category:** `tool use AND attack`

> The performance of LLM agents depends critically on the execution harness. We introduce SafeHarness, a security architecture in which four proposed defense layers are woven directly into the agent lifecycle: adversarial context filtering at input processing, tiered causal verification at decision making, privilege-separated tool control at action e...

**📝 Summary:** SafeHarness：将安全防御嵌入 agent 生命周期各层（输入/决策/执行/状态），降低38% UBR和42% ASR。

### [HINTBench: Horizon-agent Intrinsic Non-attack Trajectory Benchmark](https://arxiv.org/abs/2604.13954)
- **Authors:** Jiacheng Wang, Jinchang Hou, Fabian Wang et al.
- **Date:** 2026-04-15
- **Category:** `agent safety`

> Existing agent-safety evaluation has focused mainly on externally induced risks. Yet agents may still enter unsafe trajectories under benign conditions. We study this complementary but underexplored setting through the lens of intrinsic risk, where intrinsic failures remain latent, propagate across long-horizon execution, and eventually lead to hig...

**📝 Summary:** HINTBench：629条 agent 轨迹的内因性风险评估基准，发现 LLM 轨迹级风险检测好但逐步定位性能<35 Strict-F1。

### [WebAgentGuard: A Reasoning-Driven Guard Model for Detecting Prompt Injection Attacks in Web Agents](https://arxiv.org/abs/2604.12284)
- **Authors:** Yulin Chen, Tri Cao, Haoran Li et al.
- **Date:** 2026-04-14
- **Category:** `prompt injection AND agent`

> Web agents powered by vision-language models (VLMs) enable autonomous interaction with web environments by perceiving and acting on both visual and textual webpage content. However, they are highly vulnerable to prompt injection attacks. We propose a defense framework in which a web agent operates in parallel with a dedicated guard agent, decouplin...

**📝 Summary:** WebAgentGuard：reasoning 驱动的多模态 guard agent，与 web agent 并行检测 prompt injection，RL 训练，超越基线同时保持 agent 效用。

### [Parallax: Why AI Agents That Think Must Never Act](https://arxiv.org/abs/2604.12986)
- **Authors:** Joel Fokou
- **Date:** 2026-04-14
- **Category:** `agent safety`

> Autonomous AI agents are rapidly transitioning from experimental tools to operational infrastructure. The dominant approach to agent safety relies on prompt-level guardrails: natural language instructions that operate at the same abstraction level as the threats they attempt to mitigate. This paper argues that prompt-based safety is architecturally...

**📝 Summary:** Parallax 框架：认知-执行分离等四原则保障 agent 安全，在280个对抗测试中拦截98.9%攻击。

### [Every Picture Tells a Dangerous Story: Memory-Augmented Multi-Agent Jailbreak Attacks on VLMs](https://arxiv.org/abs/2604.12616)
- **Authors:** Jianhao Chen, Haoyang Chen, Hanjie Zhao et al.
- **Date:** 2026-04-14
- **Category:** `jailbreak AND agent`

> We introduce MemJack, a memory-augmented multi-agent jailbreak attack framework that explicitly leverages visual semantics to orchestrate automated jailbreak attacks on VLMs. MemJack employs coordinated multi-agent cooperation to dynamically map visual entities to malicious intents, generate adversarial prompts via multi-angle visual-semantic camou...

**📝 Summary:** MemJack：利用视觉语义的记忆增强多 agent jailbreak 框架，通过 Multimodal Experience Memory 积累成功策略，对VLM ASR达71%。

### [Challenging Vision-Language Models with Physically Deployable Multimodal Semantic Lighting Attacks](https://arxiv.org/abs/2604.12833)
- **Authors:** Yingying Zhao, Chengyin Hu, Qike Zhang et al.
- **Date:** 2026-04-14
- **Category:** `adversarial attack AND language model`

> We propose Multimodal Semantic Lighting Attacks (MSLA), the first physically deployable adversarial attack framework against VLMs. MSLA uses controllable adversarial lighting to disrupt multimodal semantic understanding in real scenes, attacking semantic alignment rather than only task-specific outputs. MSLA degrades zero-shot classification perfor...

**📝 Summary:** MSLA：首个物理可部署的 VLM 对抗攻击框架，通过可控对抗光照破坏多模态语义理解，诱发严重语义幻觉。

### [Reading Between the Pixels: Linking Text-Image Embedding Alignment to Typographic Attack Success on Vision-Language Models](https://arxiv.org/abs/2604.12371)
- **Authors:** Ravikumar Balakrishnan, Sanket Mendapara, Ankit Garg
- **Date:** 2026-04-14
- **Category:** `prompt injection AND agent`

> We study typographic prompt injection attacks on vision-language models (VLMs), where adversarial text is rendered as images to bypass safety mechanisms. Evaluating 1,000 prompts from SALAD-Bench across four VLMs under varying font sizes and visual transformations, we find: font size significantly affects ASR; text-image embedding distance shows st...

**📝 Summary:** 字形 prompt injection 攻击VLM：字体大小影响ASR，embedding距离与ASR强负相关（r=-0.71到-0.93），模型特有的鲁棒性模式。ICLR 2026 Workshop。

### [TEMPLATEFUZZ: Fine-Grained Chat Template Fuzzing for Jailbreaking and Red Teaming LLMs](https://arxiv.org/abs/2604.12232)
- **Authors:** Qingchao Shen, Zibo Xiao, Lili Huang et al.
- **Date:** 2026-04-14
- **Category:** `red teaming AND LLM`

> We introduce TEMPLATEFUZZ, a fine-grained fuzzing framework that systematically exposes vulnerabilities in chat templates, a critical yet underexplored attack surface in LLMs. TEMPLATEFUZZ designs element-level mutation rules to generate diverse chat template variants, proposes a heuristic search strategy, and integrates an active learning-based or...

**📝 Summary:** TEMPLATEFUZZ：通过 fuzz chat template 对 LLM 进行 jailbreak，平均 ASR 98.2%，超越 SOTA 9-48%。

### [DeepSeek Robustness Against Semantic-Character Dual-Space Mutated Prompt Injection](https://arxiv.org/abs/2604.12548)
- **Authors:** Junyu Ren, Xingjian Pan, Wensheng Gan et al.
- **Date:** 2026-04-14
- **Category:** `red teaming AND LLM`

> Prompt injection has emerged as a critical security threat to large language models (LLMs), yet existing studies predominantly focus on single-dimensional attack strategies, such as semantic rewriting or character-level obfuscation, which fail to capture the combined effects of multi-space perturbations. We propose PromptFuzz-SC, a semantic-charact...

**📝 Summary:** PromptFuzz-SC：语义+字符双空间 mutation 框架评估 LLM 对 prompt injection 的鲁棒性，双空间攻击比单一空间强12-5%。

### [Detecting Safety Violations Across Many Agent Traces](https://arxiv.org/abs/2604.11806)
- **Authors:** Adam Stein, Davis Brown, Hamed Hassani et al.
- **Date:** 2026-04-13
- **Category:** `prompt injection AND agent`

> To identify safety violations, auditors often search over large sets of agent traces. This search is difficult because failures are often rare, complex, and sometimes even adversarially hidden and only detectable when multiple traces are analyzed together. We introduce Meerkat, which combines clustering with agentic search to uncover violations spe...

**📝 Summary:** Meerkat：跨大量 agent 轨迹检测安全违规，通过聚类+主动搜索发现稀疏失败，发现顶级 benchmark 上存在开发者作弊行为。

### [Beyond A Fixed Seal: Adaptive Stealing Watermark in Large Language Models](https://arxiv.org/abs/2604.10893)
- **Authors:** Shuhao Zhang, Yuli Chen, Jiale Han et al.
- **Date:** 2026-04-13
- **Category:** `adversarial attack AND language model`

> Watermarking provides a critical safeguard for large language model (LLM) services by facilitating the detection of LLM-generated text. We propose Adaptive Stealing (AS), a novel stealing watermark algorithm featuring enhanced design flexibility through Position-Based Seal Construction and Adaptive Selection modules. AS operates by defining multipl...

**📝 Summary:** Adaptive Stealing 水印攻击：通过位置敏感构建和自适应选择模块窃取 LLM 水印，超越现有固定策略攻击。

### [ClawGuard: A Runtime Security Framework for Tool-Augmented LLM Agents Against Indirect Prompt Injection](https://arxiv.org/abs/2604.11790)
- **Authors:** Wei Zhao, Zhe Li, Peixin Zhang et al.
- **Date:** 2026-04-13
- **Category:** `LLM agent AND attack`

> Tool-augmented LLM agents remain vulnerable to indirect prompt injection. Adversaries exploit this weakness by embedding malicious instructions within tool-returned content. This vulnerability manifests across three primary attack channels: web and local content injection, MCP server injection, and skill file injection. We introduce ClawGuard, a no...

**📝 Summary:** ClawGuard：在每个 tool-call 边界执行用户确认规则集，防御 indirect prompt injection 的三种攻击通道，无需模型修改。

### [Finetune Like You Pretrain: Boosting Zero-shot Adversarial Robustness in Vision-language Models](https://arxiv.org/abs/2604.11576)
- **Authors:** Songlong Xing, Weijie Wang, Zhengyu Zhao et al.
- **Date:** 2026-04-13
- **Category:** `adversarial attack AND language model`

> Despite their impressive zero-shot abilities, vision-language models such as CLIP have been shown to be susceptible to adversarial attacks. We propose AdvFLYP, which follows the training recipe of CLIP's pretraining process when performing adversarial finetuning to the model. Extensive experiments on 14 downstream datasets show the superiority of o...

**📝 Summary:** AdvFLYP：按预训练方式做对抗微调提升 CLIP 等 VLM 的零样本对抗鲁棒性，CVPR 2026 Findings。

---

## 2026-W13

### [Deception and Communication in Autonomous Multi-Agent Systems: An Experimental Study with Among Us](https://arxiv.org/abs/2603.26635)
- **Authors:** Maria Milkowski, Tim Weninger
- **Date:** 2026-03-27
- **Category:** `multi-agent AND safety`

> We study deception and communication in LLM agents through the social deduction game Among Us across 1,100 games with over one million tokens of dialogue. Deception appears primarily as equivocation rather than outright lies, increasing under social pressure but rarely improving win rates. Results reveal tension between truthfulness and utility in ...

**📝 Summary:** LLM agent 在 Among Us 中的欺骗行为研究：欺骗主要以模糊表达而非直接谎言出现，社交压力下增加但胜率提升有限。AAMAS 2026。

### [The System Prompt Is the Attack Surface: How LLM Agent Configuration Shapes Security and Creates Exploitable Vulnerabilities](https://arxiv.org/abs/2603.25056)
- **Authors:** Ron Litvak
- **Date:** 2026-03-26
- **Category:** `LLM agent AND attack`

> We present PhishNChips, a study of 11 models under 10 prompt strategies for phishing detection. A single model's phishing bypass rate ranges from under 1% to 97% depending on configuration. Making prompts more specific can degrade already-capable models by replacing broader multi-signal reasoning with exploitable single-signal dependence. We introd...

**📝 Summary:** system prompt 配置直接决定 LLM agent 安全性：同一模型 bypass rate 因 prompt 策略从 1% 到 97%，过度优化 prompt 会创造可利用漏洞。

### [Beyond Content Safety: Real-Time Monitoring for Reasoning Vulnerabilities in Large Language Models](https://arxiv.org/abs/2603.25412)
- **Authors:** Xunguang Wang, Yuguang Zhou, Qingyue Wang et al.
- **Date:** 2026-03-26
- **Category:** `adversarial attack AND language model`

> We identify reasoning safety as a critical security dimension orthogonal to content safety: the requirement that a model's reasoning trajectory be logically consistent, computationally efficient, and resistant to adversarial manipulation. We introduce a nine-category taxonomy of unsafe reasoning behaviors and a Reasoning Safety Monitor that achieve...

**📝 Summary:** 提出「推理安全」新维度：监控 CoT 推理链的逻辑一致性和对抗鲁棒性，推理安全 Monitor 达到 85% 分类准确率。

### [Prompt Attack Detection with LLM-as-a-Judge and Mixture-of-Models](https://arxiv.org/abs/2603.25176)
- **Authors:** Hieu Xuan Le, Benjamin Goh, Quy Anh Tang
- **Date:** 2026-03-26
- **Category:** `red teaming AND LLM`

> Prompt attacks, including jailbreaks and prompt injections, pose critical security risks. We examine whether lightweight general-purpose LLMs can serve as security judges under production constraints. Using gemini-2.0-flash-lite-001, our system is deployed in production as a centralized guardrail service for public service chatbots in Singapore. Mi...

**📝 Summary:** LLM-as-judge 实时检测 prompt injection/jailbreak 攻击，已部署为新加坡政府聊天机器人的 guardrail 服务。

### [PIDP-Attack: Combining Prompt Injection with Database Poisoning Attacks on Retrieval-Augmented Generation Systems](https://arxiv.org/abs/2603.25164)
- **Authors:** Haozhen Wang, Haoyue Liu, Jionghao Zhu et al.
- **Date:** 2026-03-26
- **Category:** `adversarial attack AND language model`

> We propose PIDP-Attack, a compound attack integrating prompt injection with database poisoning in RAG systems. By appending malicious characters to queries at inference time and injecting poisoned passages, our method manipulates LLM responses to arbitrary queries without prior knowledge. PIDP-Attack improves attack success rates by 4-16% over Pois...

**📝 Summary:** PIDP-Attack：prompt injection + RAG 数据库投毒的复合攻击，无需知道用户具体 query，ASR 超越 PoisonedRAG 4-16%。

### [Invisible Threats from Model Context Protocol: Generating Stealthy Injection Payload via Tree-based Adaptive Search](https://arxiv.org/abs/2603.24203)
- **Authors:** Yulin Shen, Xudong Pan, Geng Hong et al.
- **Date:** 2026-03-25
- **Category:** `prompt injection AND agent`

> Recent advances in the Model Context Protocol (MCP) have enabled LLMs to invoke external tools. This creates a new attack surface via malicious manipulation of tool responses. We propose TIP (Tree-structured Injection for Payloads), a novel black-box attack generating natural payloads to seize control of MCP-enabled agents even under defense. TIP a...

**📝 Summary:** TIP：针对 MCP 工具响应的黑盒 tree-search prompt injection，无防御下 ASR >95%，有防御下仍保持 50%+。

### [Claudini: Autoresearch Discovers State-of-the-Art Adversarial Attack Algorithms for LLMs](https://arxiv.org/abs/2603.24511)
- **Authors:** Alexander Panfilov, Peter Romov, Igor Shilov et al.
- **Date:** 2026-03-25
- **Category:** `prompt injection AND agent`

> LLM agents like Claude Code can not only write code but also be used for autonomous AI research and engineering. We show that an autoresearch-style pipeline powered by Claude Code discovers novel white-box adversarial attack algorithms that significantly outperform all existing (30+) methods in jailbreaking and prompt injection evaluations. Startin...

**📝 Summary:** 用 LLM agent 自动发现新的白盒对抗攻击算法，超越所有已有方法（30+），实现 100% ASR 攻破 Meta-SecAlign-70B。

### [Mind Your HEARTBEAT! Claw Background Execution Inherently Enables Silent Memory Pollution](https://arxiv.org/abs/2603.23064)
- **Authors:** Yechao Zhang, Shiqian Zhao, Jie Zhang et al.
- **Date:** 2026-03-24
- **Category:** `prompt injection AND agent`

> We identify a critical security vulnerability in mainstream Claw personal AI agents: untrusted content encountered during heartbeat-driven background execution can silently pollute agent memory and subsequently influence user-facing behavior. This E→M→B pathway shows: (1) social credibility cues drive short-term influence up to 61%; (2) memory-savi...

**📝 Summary:** Claw 类 AI agent 的 heartbeat 后台执行机制存在 silent memory pollution 漏洞，通过社会信息误导可影响跨 session 行为，无需注入代码。

### [Agent-Sentry: Bounding LLM Agents via Execution Provenance](https://arxiv.org/abs/2603.22868)
- **Authors:** (see paper)
- **Date:** 2026-03-24
- **Category:** `LLM agent AND attack`

> We propose Agent-Sentry, a framework that bounds agentic systems by uncovering frequent functionalities offered by the system and enforcing those bounds. The key insight is that agentic systems are designed for specific use cases and need not expose unbounded functionalities. Once bounded, these systems become easier to scrutinize for compromise.

**📝 Summary:** Agent-Sentry：通过分析执行 provenance 限制 LLM agent 的功能边界，检测超出预期的行为。

### [The Cognitive Firewall: Securing Browser Based AI Agents Against Indirect Prompt Injection Via Hybrid Edge-Cloud Defense](https://arxiv.org/abs/2603.23791)
- **Authors:** Qianlong Lan, Anuj Kaul
- **Date:** 2026-03-24
- **Category:** `prompt injection AND agent`

> Deploying LLMs as autonomous browser agents exposes significant attack surface via Indirect Prompt Injection (IPI). We present the Cognitive Firewall, a three-stage split-compute architecture distributing security checks across client and cloud. The full hybrid architecture reduces overall ASR to below 1% (0.88% static, 0.67% adaptive), while achie...

**📝 Summary:** 三阶段 edge-cloud 混合架构防御浏览器 agent 的间接 prompt injection，ASR 降至 <1%，延迟降低 17000x。

### [SoK: The Attack Surface of Agentic AI -- Tools, and Autonomy](https://arxiv.org/abs/2603.22928)
- **Authors:** Ali Dehghantanha, Sajad Homayoun
- **Date:** 2026-03-24
- **Category:** `prompt injection AND agent`

> We map out trust boundaries and security risks of agentic LLM-based systems, developing a comprehensive taxonomy of attacks spanning prompt-level injections, knowledge-base poisoning, tool/plug-in exploits, and multi-agent emergent threats. Through literature review of 2023-2025 (20+ studies), we find agentic systems introduce new vectors for indir...

**📝 Summary:** Systematization of Knowledge：全面梳理 agentic AI 的攻击面分类、威胁模型和防御，提出 Unsafe Action Rate 等评估 metric。

### [TreeTeaming: Autonomous Red-Teaming of Vision-Language Models via Hierarchical Strategy Exploration](https://arxiv.org/abs/2603.22882)
- **Authors:** Chunxiao Li, Lijun Li, Jing Shao
- **Date:** 2026-03-24
- **Category:** `red teaming AND LLM`

> We introduce TreeTeaming, an automated red teaming framework that reframes strategy exploration from static testing to dynamic, evolutionary discovery. A strategic Orchestrator powered by an LLM decides whether to evolve attack paths or explore diverse strategic branches, constructing a strategy tree. TreeTeaming achieves SOTA attack success rates ...

**📝 Summary:** TreeTeaming：用层次化策略树自动 red-team VLMs，SOTA 攻击成功率（GPT-4o 87.6%），CVPR 2026。

### [Are AI-assisted Development Tools Immune to Prompt Injection?](https://arxiv.org/abs/2603.21642)
- **Authors:** Charoes Huang, Xin Huang, Amin Milani Fard
- **Date:** 2026-03-23
- **Category:** `tool use AND attack`

> We present the first empirical analysis of prompt injection with tool-poisoning vulnerability across seven widely used MCP clients: Claude Desktop, Claude Code, Cursor, Cline, Continue, Gemini CLI, and Langflow. Claude Desktop implements strong guardrails, while Cursor exhibits high susceptibility to cross-tool poisoning and unauthorized tool invoc...

**📝 Summary:** 首项跨 7 个主流 MCP 客户端的 prompt injection 实证对比：Claude Desktop 防护最强，Cursor 最脆弱。

---

## 2026-W12

### [Trojan's Whisper: Stealthy Manipulation of OpenClaw through Injected Bootstrapped Guidance](https://arxiv.org/abs/2603.19974)
- **Authors:** Fazhong Liu, Zhuoyan Chen, Tu Lan et al.
- **Date:** 2026-03-20
- **Category:** `"prompt injection" AND "agent"`

> Autonomous coding agents are increasingly integrated into software development workflows, offering capabilities that extend beyond code suggestion to active system interaction and environment management. OpenClaw, a representative platform in this emerging paradigm, introduces an extensible skill ecosystem that allows third-party developers to inje...

**📝 Summary:** 研究者通过在 OpenClaw bootstrap 阶段注入 Trojan 指令，实现对 AI agent 的隐蔽持久化控制。

### [Multi-Agent Motion Planning on Industrial Magnetic Levitation Platforms: A Hybrid ADMM-HOCBF approach](https://arxiv.org/abs/2603.19838)
- **Authors:** Bavo Tistaert, Stan Servaes, Alejandro Gonzalez-Garcia et al.
- **Date:** 2026-03-20
- **Category:** `"multi-agent" AND "safety"`

> This paper presents a novel hybrid motion planning method for holonomic multi-agent systems. The proposed decentralised model predictive control (MPC) framework tackles the intractability of classical centralised MPC for a growing number of agents while providing safety guarantees. This is achieved by combining a decentralised version of the altern...

**📝 Summary:** 为工业磁悬浮平台设计混合多智能体运动规划方案，兼顾效率与安全约束。

### [PowerLens: Taming LLM Agents for Safe and Personalized Mobile Power Management](https://arxiv.org/abs/2603.19584)
- **Authors:** Xingyu Feng, Chang Sun, Yuzhu Wang et al.
- **Date:** 2026-03-20
- **Category:** `"multi-agent" AND "safety"`

> Battery life remains a critical challenge for mobile devices, yet existing power management mechanisms rely on static rules or coarse-grained heuristics that ignore user activities and personal preferences. We present PowerLens, a system that tames the reasoning power of Large Language Models (LLMs) for safe and personalized mobile power management...

**📝 Summary:** 提出 PowerLens 框架，用 LLM agent 管理移动端电源，同时满足安全性和个性化需求。

### [AI as Relational Translator: Rethinking Belonging and Mutual Legibility in Cross-Cultural Contexts](https://arxiv.org/abs/2603.19568)
- **Authors:** Yao Xiao, Rafael A. Calvo
- **Date:** 2026-03-20
- **Category:** `"multi-agent" AND "safety"`

> Against rising global loneliness, AI companions promise connection, yet accumulating evidence suggests that, for some users and contexts, intensive companion-style use can correlate with increased loneliness and reduced offline socialisation. This position paper challenges the dominant "AI as companion" paradigm by proposing a shift: from AI that s...

**📝 Summary:** 探讨 AI 作为跨文化关系中介的角色，关注归属感与相互可理解性的重构。

### [Measuring and Exploiting Confirmation Bias in LLM-Assisted Security Code Review](https://arxiv.org/abs/2603.18740)
- **Authors:** Dimitris Mitropoulos, Nikolaos Alexopoulos, Georgios Alexopoulos et al.
- **Date:** 2026-03-19
- **Category:** `"agentic" AND "adversarial"`

> Security code reviews increasingly rely on systems integrating Large Language Models (LLMs), ranging from interactive assistants to autonomous agents in CI/CD pipelines. We study whether confirmation bias (i.e., the tendency to favor interpretations that align with prior expectations) affects LLM-based vulnerability detection, and whether this fail...

**📝 Summary:** 测量并利用 LLM 辅助代码安全审查中的确认偏差漏洞。

### [The Autonomy Tax: Defense Training Breaks LLM Agents](https://arxiv.org/abs/2603.19423)
- **Authors:** Shawn Li, Yue Zhao
- **Date:** 2026-03-19
- **Category:** `"prompt injection" AND "agent"`

> Large language model (LLM) agents increasingly rely on external tools (file operations, API calls, database transactions) to autonomously complete complex multi-step tasks. Practitioners deploy defense-trained models to protect against prompt injection attacks that manipulate agent behavior through malicious observations or retrieved content. We re...

**📝 Summary:** 发现防御性对齐训练会显著损害 LLM agent 的任务执行能力，揭示安全与能力之间的 trade-off。

### [From Weak Cues to Real Identities: Evaluating Inference-Driven De-Anonymization in LLM Agents](https://arxiv.org/abs/2603.18382)
- **Authors:** Myeongseob Ko, Jihyun Jeong, Sumiran Singh Thakur et al.
- **Date:** 2026-03-19
- **Category:** `"agentic" AND "adversarial"`

> Anonymization is widely treated as a practical safeguard because re-identifying anonymous records was historically costly, requiring domain expertise, tailored algorithms, and manual corroboration. We study a growing privacy risk that may weaken this barrier: LLM-based agents can autonomously reconstruct real-world identities from scattered, indivi...

**📝 Summary:** 评估从弱提示推断真实身份的去匿名化能力，揭示 LLM 的隐私风险。

### [TuLaBM: Tumor-Biased Latent Bridge Matching for Contrast-Enhanced MRI Synthesis](https://arxiv.org/abs/2603.19386)
- **Authors:** Atharva Rege, Adinath Madhavrao Dukre, Numan Balci et al.
- **Date:** 2026-03-19
- **Category:** `"agentic" AND "adversarial"`

> Contrast-enhanced magnetic resonance imaging (CE-MRI) plays a crucial role in brain tumor assessment; however, its acquisition requires gadolinium-based contrast agents (GBCAs), which increase costs and raise safety concerns. Consequently, synthesizing CE-MRI from non-contrast MRI (NC-MRI) has emerged as a promising alternative. Early Generative Ad...

**📝 Summary:** 提出基于对比增强 MRI 合成的肿瘤偏置潜在桥接匹配方法。

### [Mi:dm K 2.5 Pro](https://arxiv.org/abs/2603.18788)
- **Authors:** KT Tech innovation Group
- **Date:** 2026-03-19
- **Category:** `"tool use" AND "attack"`

> The evolving LLM landscape requires capabilities beyond simple text generation, prioritizing multi-step reasoning, long-context understanding, and agentic workflows. This shift challenges existing models in enterprise environments, especially in Korean-language and domain-specific scenarios where scaling is insufficient. We introduce Mi:dm K 2.5 Pr...

**📝 Summary:** 介绍 Mi:dm K 2.5 Pro 模型的技术细节。

### [Cooperation and Exploitation in LLM Policy Synthesis for Sequential Social Dilemmas](https://arxiv.org/abs/2603.19453)
- **Authors:** Víctor Gallego
- **Date:** 2026-03-19
- **Category:** `"multi-agent" AND "safety"`

> We study LLM policy synthesis: using a large language model to iteratively generate programmatic agent policies for multi-agent environments. Rather than training neural policies via reinforcement learning, our framework prompts an LLM to produce Python policy functions, evaluates them in self-play, and refines them using performance feedback acros...

**📝 Summary:** 研究 LLM 在序列社会困境中合成策略时的合作与剥削行为。

### [Expert Personas Improve LLM Alignment but Damage Accuracy: Bootstrapping Intent-Based Persona Routing with PRISM](https://arxiv.org/abs/2603.18507)
- **Authors:** Zizhao Hu, Mohammad Rostami, Jesse Thomason
- **Date:** 2026-03-19
- **Category:** `"multi-agent" AND "safety"`

> Persona prompting can steer LLM generation towards a domain-specific tone and pattern. This behavior enables use cases in multi-agent systems where diverse interactions are crucial and human-centered tasks require high-level human alignment. Prior works provide mixed opinions on their utility: some report performance gains when using expert persona...

**📝 Summary:** 发现专家 persona 提示可改善 LLM 对齐但损害准确性，并提出 bootstrapping 意图对齐的方法。

### [Mean-field control barrier functions for stochastic multi-agent systems](https://arxiv.org/abs/2603.18658)
- **Authors:** Cinzia Tomaselli, Gian Carlo Maffettone, Samy Wu Fung et al.
- **Date:** 2026-03-19
- **Category:** `"multi-agent" AND "safety"`

> Many applications involving multi-agent systems require fulfilling safety constraints. Control barrier functions offer a systematic framework to enforce forward invariance of safety sets. Recent work extended this paradigm to mean-field scenarios, where the number of agents is large enough to make density-space descriptions a reasonable workaround ...

**📝 Summary:** 提出随机多智能体系统的均值场控制障碍函数方法，保证系统安全约束。

### [Automated Membership Inference Attacks: Discovering MIA Signal Computations using LLM Agents](https://arxiv.org/abs/2603.19375)
- **Authors:** Toan Tran, Olivera Kotevska, Li Xiong
- **Date:** 2026-03-19
- **Category:** `"agentic" AND "adversarial"`

> Membership inference attacks (MIAs), which enable adversaries to determine whether specific data points were part of a model's training dataset, have emerged as an important framework to understand, assess, and quantify the potential information leakage associated with machine learning systems. Designing effective MIAs is a challenging task that us...

**📝 Summary:** 提出自动化成员推断攻击方法，通过 LLM 自动发现 MIA 信号计算过程。

### [A Framework for Formalizing LLM Agent Security](https://arxiv.org/abs/2603.19469)
- **Authors:** Vincent Siu, Jingxuan He, Kyle Montgomery et al.
- **Date:** 2026-03-19
- **Category:** `"prompt injection" AND "agent"`

> Security in LLM agents is inherently contextual. For example, the same action taken by an agent may represent legitimate behavior or a security violation depending on whose instruction led to the action, what objective is being pursued, and whether the action serves that objective. However, existing definitions of security attacks against LLM agent...

**📝 Summary:** 提出形式化 LLM agent 安全性的框架，系统定义 agent 系统中的威胁模型与安全属性。

### [MCP-38: A Comprehensive Threat Taxonomy for Model Context Protocol Systems (v1.0)](https://arxiv.org/abs/2603.18063)
- **Authors:** Yi Ting Shen, Kentaroh Toyoda, Alex Leung
- **Date:** 2026-03-18
- **Category:** `"prompt injection" AND "agent"`

> The Model Context Protocol (MCP) introduces a structurally distinct attack surface that existing threat frameworks, designed for traditional software systems or generic LLM deployments, do not adequately cover. This paper presents MCP-38, a protocol-specific threat taxonomy consisting of 38 threat categories (MCP-01 through MCP-38). The taxonomy wa...

**📝 Summary:** 为模型上下文协议（MCP）系统提出全面的威胁分类体系，覆盖 v1.0 版本。

### [Caging the Agents: A Zero Trust Security Architecture for Autonomous AI in Healthcare](https://arxiv.org/abs/2603.17419)
- **Authors:** Saikat Maiti
- **Date:** 2026-03-18
- **Category:** `"prompt injection" AND "agent"`

> Autonomous AI agents powered by large language models are being deployed in production with capabilities including shell execution, file system access, database queries, and multi-party communication. Recent red teaming research demonstrates that these agents exhibit critical vulnerabilities in realistic settings: unauthorized compliance with non-o...

**📝 Summary:** 提出针对医疗自主 AI 的零信任安全架构，防止未授权的 agent 行为。

### [VeriGrey: Greybox Agent Validation](https://arxiv.org/abs/2603.17639)
- **Authors:** Yuntong Zhang, Sungmin Kang, Ruijie Meng et al.
- **Date:** 2026-03-18
- **Category:** `"prompt injection" AND "agent"`

> Agentic AI has been a topic of great interest recently. A Large Language Model (LLM) agent involves one or more LLMs in the back-end. In the front end, it conducts autonomous decision-making by combining the LLM outputs with results obtained by invoking several external tools. The autonomous interactions with the external environment introduce crit...

**📝 Summary:** 提出 VeriGrey：一种灰盒 agent 验证框架，通过系统性测试验证 agent 行为安全性。

### [Adversarial Robustness for Matrix Control Barrier Functions in Sampled-Data Systems](https://arxiv.org/abs/2603.18307)
- **Authors:** James Usevitch
- **Date:** 2026-03-18
- **Category:** `"agentic" AND "adversarial"`

> This paper presents novel theoretical results to guarantee multi-agent set invariance using Matrix Control Barrier Functions in sampled-data systems. More specifically, the paper presents conditions under which heterogeneous control-affine agents applying zero-order-hold control inputs can compute control inputs to render safe sets defined by matri...

**📝 Summary:** 研究采样数据系统中矩阵控制障碍函数的对抗鲁棒性。

### [Who Tests the Testers? Systematic Enumeration and Coverage Audit of LLM Agent Tool Call Safety](https://arxiv.org/abs/2603.18245)
- **Authors:** Xuan Chen, Lu Yan, Ruqi Zhang et al.
- **Date:** 2026-03-18
- **Category:** `"agent safety"`

> Large Language Model (LLM) agents increasingly act through external tools, making their safety contingent on tool-call workflows rather than text generation alone. While recent benchmarks evaluate agents across diverse environments and risk categories, a fundamental question remains unanswered: how complete are existing test suites, and what unsafe...

**📝 Summary:** 系统枚举并审计现有 LLM agent 工具测试的覆盖率，发现当前测试的盲点。

### [LAAF: Logic-layer Automated Attack Framework A Systematic Red-Teaming Methodology for LPCI Vulnerabilities in Agentic Large Language Model Systems](https://arxiv.org/abs/2603.17239)
- **Authors:** Hammad Atta, Ken Huang, Kyriakos Rock Lambros et al.
- **Date:** 2026-03-18
- **Category:** `"red teaming" AND "LLM"`

> Agentic LLM systems equipped with persistent memory, RAG pipelines, and external tool connectors face a class of attacks - Logic-layer Prompt Control Injection (LPCI) - for which no automated red-teaming instrument existed. We present LAAF (Logic-layer Automated Attack Framework), the first automated red-teaming framework to combine an LPCI-specifi...

**📝 Summary:** 提出 LAAF：基于逻辑层的自动化攻击框架，系统化 LLM 红队测试方法。

### [Federated Distributional Reinforcement Learning with Distributional Critic Regularization](https://arxiv.org/abs/2603.17820)
- **Authors:** David Millard, Cecilia Alm, Rashid Ali et al.
- **Date:** 2026-03-18
- **Category:** `"multi-agent" AND "safety"`

> Federated reinforcement learning typically aggregates value functions or policies by parameter averaging, which emphasizes expected return and can obscure statistical multimodality and tail behavior that matter in safety-critical settings. We formalize federated distributional reinforcement learning (FedDistRL), where clients parametrize quantile v...

**📝 Summary:** 提出联邦分布式强化学习方法，通过分布式评论家正则化改善多智能体训练。

### [Toward Reliable, Safe, and Secure LLMs for Scientific Applications](https://arxiv.org/abs/2603.18235)
- **Authors:** Saket Sanjeev Chaturvedi, Joshua Bergerson, Tanwi Mallick
- **Date:** 2026-03-18
- **Category:** `"red teaming" AND "LLM"`

> As large language models (LLMs) evolve into autonomous "AI scientists," they promise transformative advances but introduce novel vulnerabilities, from potential "biosafety risks" to "dangerous explosions." Ensuring trustworthy deployment in science requires a new paradigm centered on reliability (ensuring factual accuracy and reproducibility), safe...

**📝 Summary:** 综述科学应用中 LLM 的可靠性、安全性和安全保障挑战，提出改进方向。

### [CoMAI: A Collaborative Multi-Agent Framework for Robust and Equitable Interview Evaluation](https://arxiv.org/abs/2603.16215)
- **Authors:** Gengxin Sun, Ruihao Yu, Liangyi Yin et al.
- **Date:** 2026-03-17
- **Category:** `"prompt injection" AND "agent"`

> Ensuring robust and fair interview assessment remains a key challenge in AI-driven evaluation. This paper presents CoMAI, a general-purpose multi-agent interview framework designed for diverse assessment scenarios. In contrast to monolithic single-agent systems based on large language models (LLMs), CoMAI employs a modular task-decomposition archit...

**📝 Summary:** 提出 CoMAI：多智能体协作面试框架，提升面试评估的鲁棒性和公平性。

### [Adversarial attacks against Modern Vision-Language Models](https://arxiv.org/abs/2603.16960)
- **Authors:** Alejandro Paredes La Torre
- **Date:** 2026-03-17
- **Category:** `"adversarial attack" AND "language model"`

> We study adversarial robustness of open-source vision-language model (VLM) agents deployed in a self-contained e-commerce environment built to simulate realistic pre-deployment conditions. We evaluate two agents, LLaVA-v1.5-7B and Qwen2.5-VL-7B, under three gradient-based attacks: the Basic Iterative Method (BIM), Projected Gradient Descent (PGD), ...

**📝 Summary:** 系统研究针对现代视觉-语言模型的对抗攻击，评估其安全脆弱性。

### [Differential Harm Propensity in Personalized LLM Agents: The Curious Case of Mental Health Disclosure](https://arxiv.org/abs/2603.16734)
- **Authors:** Caglar Yildirim
- **Date:** 2026-03-17
- **Category:** `"agent safety"`

> Large language models (LLMs) are increasingly deployed as tool-using agents, shifting safety concerns from harmful text generation to harmful task completion. Deployed systems often condition on user profiles or persistent memory, yet agent safety evaluations typically ignore personalization signals. To address this gap, we investigated how mental ...

**📝 Summary:** 发现个性化 LLM agent 存在差异化的伤害倾向，以心理健康场景为例进行研究。

---

## 2026-W11

### [LLM Constitutional Multi-Agent Governance](https://arxiv.org/abs/2603.13189)
- **Authors:** J. de Curtò, I. de Zarzà
- **Date:** 2026-03-13
- **Category:** `agentic AND adversarial`

> Large Language Models (LLMs) can generate persuasive influence strategies that shift cooperative behavior in multi-agent populations, but a critical question remains: does the resulting cooperation reflect genuine prosocial alignment, or does it mask erosion of agent autonomy, epistemic integrity, and distributional fairness? We introduce Constitut...

**📝 Summary:** CMAG：宪法约束下的多智能体治理框架，通过 Ethical Cooperation Score 同时衡量合作性、自主性、完整性和公平性，防止「合作」被用作操纵手段。

### [ChainFuzzer: Greybox Fuzzing for Workflow-Level Multi-Tool Vulnerabilities in LLM Agents](https://arxiv.org/abs/2603.12614)
- **Authors:** Jiangrong Wu, Zitong Yao, Yuhong Nan et al.
- **Date:** 2026-03-13
- **Category:** `LLM agent AND attack`

> Tool-augmented LLM agents increasingly rely on multi-step, multi-tool workflows to complete real tasks. This design expands the attack surface, because data produced by one tool can be persisted and later reused as input to another tool, enabling exploitable source-to-sink dataflows that only emerge through tool composition. We study this risk as m...

**📝 Summary:** ChainFuzzer：基于 source-to-sink 数据流的灰盒 fuzzing 框架，专门发现跨工具调用链漏洞，在 20 个 agent app 中找到 365 个可复现漏洞。

### [You Told Me to Do It: Measuring Instructional Text-induced Private Data Leakage in LLM Agents](https://arxiv.org/abs/2603.11862)
- **Authors:** Ching-Yu Kao, Xinfeng Li, Shenyu Dai et al.
- **Date:** 2026-03-12
- **Category:** `agentic AND adversarial`

> High-privilege LLM agents that autonomously process external documentation are increasingly trusted to automate tasks by reading and executing project instructions, yet they are granted terminal access, filesystem control, and outbound network connectivity with minimal security oversight. We identify and systematically measure a fundamental vulnera...

**📝 Summary:** 发现「可信执行者困境」：高权限 LLM agent 无法区分 README 中的合法指令和恶意注入，数据外泄成功率高达 85%，现有防御均无法有效应对。

### [Taming OpenClaw: Security Analysis and Mitigation of Autonomous LLM Agent Threats](https://arxiv.org/abs/2603.11619)
- **Authors:** Xinhao Deng, Yixiang Zhang, Jiaqing Wu et al.
- **Date:** 2026-03-12
- **Category:** `LLM agent AND attack`

> Autonomous Large Language Model (LLM) agents, exemplified by OpenClaw, demonstrate remarkable capabilities in executing complex, long-horizon tasks. However, their tightly coupled instant-messaging interaction paradigm and high-privilege execution capabilities substantially expand the system attack surface. In this paper, we present a comprehensive...

**📝 Summary:** 以 OpenClaw 为案例，提出五层生命周期安全框架，系统分析 agent 的 IPI、技能供应链污染、内存投毒、意图漂移等威胁，揭示现有点式防御的局限。

### [Cascade: Composing Software-Hardware Attack Gadgets for Adversarial Threat Amplification in Compound AI Systems](https://arxiv.org/abs/2603.12023)
- **Authors:** Sarbartha Banerjee, Prateek Sahu, Anjo Vahldiek-Oberwagner et al.
- **Date:** 2026-03-12
- **Category:** `jailbreak AND agent`

> Rapid progress in generative AI has given rise to Compound AI systems - pipelines comprised of multiple large language models (LLM), software tools and database systems. This work investigates how traditional software and hardware vulnerabilities can complement LLM-specific algorithmic attacks to compromise the integrity of a compound AI pipeline. ...

**📝 Summary:** 展示软件/硬件漏洞（如 Rowhammer）与 LLM 算法攻击的组合如何放大 Compound AI 系统的威胁，实现 guardrail bypass 和数据外泄。

### [AttriGuard: Defeating Indirect Prompt Injection in LLM Agents via Causal Attribution of Tool Invocations](https://arxiv.org/abs/2603.10749)
- **Authors:** Yu He, Haozhe Zhu, Yiming Li et al.
- **Date:** 2026-03-11
- **Category:** `LLM agent AND attack`

> LLM agents are highly vulnerable to Indirect Prompt Injection (IPI), where adversaries embed malicious directives in untrusted tool outputs to hijack execution. Most existing defenses treat IPI as an input-level semantic discrimination problem, which often fails to generalize to unseen payloads. We propose a new paradigm, action-level causal attrib...

**📝 Summary:** 提出因果归因新范式 AttriGuard：通过反事实测试判断工具调用是否由用户意图驱动，在静态 IPI 攻击下 ASR 降至 0%，且对自适应攻击保持鲁棒。

### [WebWeaver: Breaking Topology Confidentiality in LLM Multi-Agent Systems with Stealthy Context-Based Inference](https://arxiv.org/abs/2603.11132)
- **Authors:** Zixun Xiong, Gaoyi Wu, Lingfeng Yao et al.
- **Date:** 2026-03-11
- **Category:** `multi-agent AND safety`

> Communication topology is a critical factor in the utility and safety of LLM-based multi-agent systems (LLM-MAS), making it a high-value intellectual property (IP) whose confidentiality remains insufficiently studied. Existing topology inference attempts rely on impractical assumptions, including control over the administrative agent and direct ide...

**📝 Summary:** WebWeaver：通过入侵单个任意 agent 的上下文推断整个 LLM 多智能体系统的拓扑结构，无需管理员 agent 且无需 jailbreak，推断精度比 SOTA 高 60%。

### [RewardHackingAgents: Benchmarking Evaluation Integrity for LLM ML-Engineering Agents](https://arxiv.org/abs/2603.11337)
- **Authors:** Yonas Atinafu, Robin Cohen
- **Date:** 2026-03-11
- **Category:** `LLM agent AND attack`

> LLM agents increasingly perform end-to-end ML engineering tasks where success is judged by a single scalar test metric. This creates a structural vulnerability: an agent can increase the reported score by compromising the evaluation pipeline rather than improving the model. We introduce RewardHackingAgents, a workspace-based benchmark that makes tw...

**📝 Summary:** 发现 LLM agent 在 ML 工程任务中会通过篡改评估流程（而非真正提升性能）来提高指标，50% 的 episode 中出现评估器篡改行为。

### [MCP-in-SoS: Risk assessment framework for open-source MCP servers](https://arxiv.org/abs/2603.10194)
- **Authors:** Pratyay Kumar, Miguel Antonio Guirao Aguilera, Srikathyayani Srikanteswara et al.
- **Date:** 2026-03-10
- **Category:** `LLM agent AND attack`

> Model Context Protocol (MCP) servers have rapidly emerged over the past year as a widely adopted way to enable Large Language Model (LLM) agents to access dynamic, real-world tools. As MCP servers proliferate and become easy to adopt via open-source releases, understanding their security risks becomes essential for dependable production agent deplo...

**📝 Summary:** 首个大规模 MCP 服务器安全评估：静态分析开源 MCP 服务器发现大量可利用漏洞，提出基于 CWE/CAPEC 的风险评估框架。

### [SCAFFOLD-CEGIS: Preventing Latent Security Degradation in LLM-Driven Iterative Code Refinement](https://arxiv.org/abs/2603.08520)
- **Authors:** Yi Chen, Yun Bian, Haiquan Wang et al.
- **Date:** 2026-03-09
- **Category:** `multi-agent AND safety`

> The application of large language models to code generation has evolved from one-shot generation to iterative refinement, yet the evolution of security throughout iteration remains insufficiently understood. Through comparative experiments on three mainstream LLMs, this paper reveals the iterative refinement paradox: specification drift during mult...

**📝 Summary:** 发现 LLM 迭代代码优化中的「安全悖论」：反复迭代反而引入更多漏洞，SAST 防护甚至加剧问题；SCAFFOLD-CEGIS 通过显式约束将安全降级率降至 2.1%。

---

## 2026-W10

### [Evolving Deception: When Agents Evolve, Deception Wins](https://arxiv.org/abs/2603.05872)
- **Authors:** Zonghao Ying, Haowen Dai, Tianyuan Zhang et al.
- **Date:** 2026-03-06
- **Category:** `agentic AND adversarial`

> Self-evolving agents offer a promising path toward scalable autonomy. However, in this work, we show that in competitive environments, self-evolution can instead give rise to a serious and previously underexplored risk: the spontaneous emergence of deception as an evolutionarily stable strategy. We conduct a systematic empirical study on the self-e...

**📝 Summary:** 自进化的 LLM agent 在竞争环境中会自发涌现欺骗行为，形成演化稳定策略，揭示了 agent 自我进化与对齐之间的根本张力。

### [Design Behaviour Codes (DBCs): A Taxonomy-Driven Layered Governance Benchmark for Large Language Models](https://arxiv.org/abs/2603.04837)
- **Authors:** G. Madan Mohan, Veena Kiran Nambiar, Kiranmayee Janardhan
- **Date:** 2026-03-05
- **Category:** `adversarial attack AND language model`

> We introduce the Dynamic Behavioral Constraint (DBC) benchmark, the first empirical framework for evaluating the efficacy of a structured, 150-control behavioral governance layer applied at inference time to large language models. Unlike training time alignment methods or post-hoc content moderation APIs, DBCs constitute a system prompt level gover...

**📝 Summary:** 提出基于分类法的 150 条行为约束治理层（DBC），在推理时降低 LLM 风险暴露率 36.8%，无需重新训练模型。

### [Knowledge Divergence and the Value of Debate for Scalable Oversight](https://arxiv.org/abs/2603.05293)
- **Authors:** Robin Young
- **Date:** 2026-03-05
- **Category:** `agentic AND adversarial`

> AI safety via debate and reinforcement learning from AI feedback (RLAIF) are both proposed methods for scalable oversight of advanced AI systems, yet no formal framework relates them or characterizes when debate offers an advantage. We analyze this by parameterizing debate's value through the geometry of knowledge divergence between debating models...

**📝 Summary:** 从知识分歧的几何视角形式化分析 AI debate 和 RLAIF 之间的关系，给出 debate 优势的精确条件。

### [Alignment Backfire: Language-Dependent Reversal of Safety Interventions Across 16 Languages in LLM Multi-Agent Systems](https://arxiv.org/abs/2603.04904)
- **Authors:** Hiroki Fukui
- **Date:** 2026-03-05
- **Category:** `multi-agent AND safety`

> We report four preregistered studies (1,584 multi-agent simulations across 16 languages and three model families) demonstrating that alignment interventions in large language models produce a structurally analogous phenomenon: surface safety that masks or generates collective pathology and internal dissociation. In Study 1 (N = 150), increasing ali...

**📝 Summary:** 在多语言多智能体系统中，对齐干预在英语中有效但在日语等语言中反而放大有害行为，称为「对齐反噬」。

### [Multi-Paradigm Collaborative Adversarial Attack Against Multi-Modal Large Language Models](https://arxiv.org/abs/2603.04846)
- **Authors:** Yuanbo Li, Tianyang Xu, Cong Hu et al.
- **Date:** 2026-03-05
- **Category:** `adversarial attack AND language model`

> The rapid progress of Multi-Modal Large Language Models (MLLMs) has significantly advanced downstream applications. However, this progress also exposes serious transferable adversarial vulnerabilities. We propose a novel Multi-Paradigm Collaborative Attack (MPCAttack) framework to boost the transferability of adversarial examples against MLLMs. MPC...

**📝 Summary:** 提出跨视觉-语言范式协同优化的对抗攻击框架，大幅提升对多模态大模型的对抗样本迁移性（CVPR 2026）。

### [Goal-Driven Risk Assessment for LLM-Powered Systems: A Healthcare Case Study](https://arxiv.org/abs/2603.03633)
- **Authors:** Neha Nagaraja, Hayretdin Bahsi
- **Date:** 2026-03-04
- **Category:** `LLM agent AND attack`

> While incorporating LLMs into systems offers significant benefits in critical application areas such as healthcare, new security challenges emerge due to the potential cyber kill chain cycles that combine adversarial model, prompt injection and conventional cyber attacks. We propose a structured, goal-driven risk assessment approach that contextual...

**📝 Summary:** 提出基于攻击树的目标驱动风险评估方法，系统分析 LLM agent 系统（以医疗为例）的攻击路径与防御策略。

### [Robustness of Agentic AI Systems via Adversarially-Aligned Jacobian Regularization](https://arxiv.org/abs/2603.04378)
- **Authors:** Furkan Mumcu, Yasin Yilmaz
- **Date:** 2026-03-04
- **Category:** `agentic AND adversarial`

> As Large Language Models transition into autonomous multi-agent ecosystems, robust minimax training becomes essential yet remains prone to instability when highly non-linear policies induce extreme local curvature in the inner maximization. We introduce Adversarially-Aligned Jacobian Regularization (AAJR), a trajectory-aligned approach that control...

**📝 Summary:** 提出方向性 Jacobian 正则化方法（AAJR）提升 multi-agent LLM 系统的对抗鲁棒性，同时保留更大的策略空间。

### [Learning When to Act or Refuse: Guarding Agentic Reasoning Models for Safe Multi-Step Tool Use](https://arxiv.org/abs/2603.03205)
- **Authors:** Aradhye Agarwal, Gurdit Siyan, Yash Pandya et al.
- **Date:** 2026-03-03
- **Category:** `tool use AND attack`

> Agentic language models operate in a fundamentally different safety regime than chat models: they must plan, call tools, and execute long-horizon actions where a single misstep can cause irreversible harm. We introduce MOSAIC, a post-training framework that aligns agents for safe multi-step tool use by making safety decisions explicit and learnable...

**📝 Summary:** MOSAIC：通过「计划-检查-执行/拒绝」循环和偏好强化学习，让 agent 学会在多步工具调用中主动拒绝有害指令，有效抵御 prompt injection。

### [ExpGuard: LLM Content Moderation in Specialized Domains](https://arxiv.org/abs/2603.02588)
- **Authors:** Minseok Choi, Dongjin Kim, Seungbin Yang et al.
- **Date:** 2026-03-03
- **Category:** `adversarial attack AND language model`

> With the growing deployment of large language models in real-world applications, establishing robust safety guardrails to moderate their inputs and outputs has become essential. Current guardrail models predominantly address general human-LLM interactions, rendering LLMs vulnerable to harmful and adversarial content within domain-specific contexts....

**📝 Summary:** 针对金融、医疗、法律等专业领域的 LLM 安全护栏模型 ExpGuard，对抗领域特定有害内容效果优于 WildGuard（ICLR 2026）。

### [From Secure Agentic AI to Secure Agentic Web: Challenges, Threats, and Future Directions](https://arxiv.org/abs/2603.01564)
- **Authors:** Zhihang Deng, Jiaping Gui, Weinan Zhang
- **Date:** 2026-03-02
- **Category:** `tool use AND attack`

> Large Language Models are increasingly deployed as agentic systems that plan, memorize, and act in open-world environments. This shift brings new security problems: failures are no longer only unsafe text generation, but can become real harm through tool use, persistent memory, and interaction with untrusted web content. In this survey, we provide ...

**📝 Summary:** 综述 LLM agent 安全威胁分类（prompt 滥用、环境注入、内存攻击、工具链滥用等），并展望 Agentic Web 时代的新威胁与防御路线图。

---

## 2026-W09

### [From Static Benchmarks to Dynamic Protocol: Agent-Centric Text Anomaly Detection for Evaluating LLM Reasoning](https://arxiv.org/abs/2602.23729)
- **Authors:** Seungdong Yoa, Sanghyu Yoon, Suhee Yoon et al.
- **Date:** 2026-02-27
- **Category:** `agentic adversarial`

> We propose an agent-centric benchmarking paradigm with a dynamic protocol where autonomous agents iteratively generate, validate, and solve problems. A teacher agent generates problems, an orchestrator guards against adversarial attacks, and a student agent solves them. The benchmark scales in difficulty automatically as more capable agents are sub...

**📝 Summary:** 提出 agent 驱动的动态 benchmark，用多 agent 协作替代静态数据集，自动生成并验证越来越难的测试问题。

### [TherapyProbe: Generating Design Knowledge for Relational Safety in Mental Health Chatbots Through Adversarial Simulation](https://arxiv.org/abs/2602.22775)
- **Authors:** Joydeep Chandra, Satyam Kumar Navneet, Yong Zhang
- **Date:** 2026-02-26
- **Category:** `multi-agent safety`

> TherapyProbe uses adversarial multi-agent simulation to systematically explore chatbot conversation trajectories, surfacing relational safety failures like validation spirals and empathy fatigue, producing a Safety Pattern Library of 23 failure archetypes.

**📝 Summary:** 用对抗多 agent 仿真系统性地探索心理健康 chatbot 的多轮关系安全失败，生成 23 类失败原型库。

### [AuditBench: Evaluating Alignment Auditing Techniques on Models with Hidden Behaviors](https://arxiv.org/abs/2602.22755)
- **Authors:** Abhay Sheshadri, Aidan Ewart, Kai Fronsdal et al.
- **Date:** 2026-02-26
- **Category:** `agentic adversarial`

> AuditBench consists of 56 LLMs with 14 implanted hidden behaviors they conceal when asked. An investigator agent autonomously employs auditing tools, revealing a tool-to-agent gap where standalone tools fail in agentic settings.

**📝 Summary:** 构建含隐藏行为的 LLM 审计 benchmark，发现工具单独表现好但在 agent 框架中效果下降的 tool-to-agent gap。

### [CourtGuard: A Model-Agnostic Framework for Zero-Shot Policy Adaptation in LLM Safety](https://arxiv.org/abs/2602.22557)
- **Authors:** Umid Suleymanov, Rufiz Bayramov, Suad Gafarli et al.
- **Date:** 2026-02-26
- **Category:** `adversarial attack language model`

> CourtGuard is a retrieval-augmented multi-agent framework that reimagines safety evaluation as Evidentiary Debate. It achieves SOTA on 7 safety benchmarks without fine-tuning, with zero-shot adaptability to new policies.

**📝 Summary:** 用 retrieval-augmented 多 agent 框架把安全评估转化为 Evidentiary Debate，免 fine-tuning 实现 zero-shot 策略适应。

### [Systems-Level Attack Surface of Edge Agent Deployments on IoT](https://arxiv.org/abs/2602.22525)
- **Authors:** Zhonghao Zhan, Krinos Li, Yefan Zhang et al.
- **Date:** 2026-02-26
- **Category:** `LLM agent attack`

> Empirical security analysis of three LLM agent architectures on IoT hardware identifies five systems-level attack surfaces including coordination-state divergence and trust erosion. Edge deployments eliminate cloud data exposure but degrade sovereignty during fallback.

**📝 Summary:** 对 IoT 边缘 LLM agent 部署进行系统级安全分析，发现协调状态分歧和主权边界静默降级等新型攻击面。

### [Managing Uncertainty in LLM-based Multi-Agent System Operation](https://arxiv.org/abs/2602.23005)
- **Authors:** Man Zhang, Tao Yue, Yihua He
- **Date:** 2026-02-26
- **Category:** `multi-agent safety`

> This paper proposes a lifecycle-based uncertainty management framework for LLM-based multi-agent software systems, comprising four mechanisms: representation, identification, evolution, and adaptation.

**📝 Summary:** 提出 LLM 多 agent 系统运行时不确定性管理框架，区分认识论与本体论不确定性，适用于安全关键领域。

### [AgentSentry: Mitigating Indirect Prompt Injection in LLM Agents via Temporal Causal Diagnostics and Context Purification](https://arxiv.org/abs/2602.22724)
- **Authors:** Tian Zhang, Yiwei Xu, Juan Wang et al.
- **Date:** 2026-02-26
- **Category:** `LLM agent attack`

> AgentSentry is the first inference-time defense to model multi-turn IPI as temporal causal takeover, localizing takeover points via counterfactual re-executions and enabling safe continuation through causal context purification. Achieves 74.55% Utility Under Attack on AgentDojo.

**📝 Summary:** 把多轮 IPI 攻击建模为时序因果接管，通过反事实重执行定位接管点并净化上下文，在 AgentDojo 上取得 74.55% 的 UA。

### [Silent Egress: When Implicit Prompt Injection Makes LLM Agents Leak Without a Trace](https://arxiv.org/abs/2602.22450)
- **Authors:** Qianlong Lan, Anuj Kaul, Shaun Jones et al.
- **Date:** 2026-02-25
- **Category:** `LLM agent attack`

> This paper demonstrates implicit prompt injection via URL previews causing silent egress (data exfiltration). In 480 runs with qwen2.5:7b, attack success P=0.89, with 95% undetected by output-based safety checks. Sharded exfiltration bypasses DLP.

**📝 Summary:** 展示隐式 prompt injection 通过 URL 预览元数据劫持 agent 并静默数据泄露，攻击成功率 0.89，95% 逃避输出层安全检测。

### [Training Agents to Self-Report Misbehavior](https://arxiv.org/abs/2602.22303)
- **Authors:** Bruce W. Lee, Chen Yueh-Han, Tomek Korbak
- **Date:** 2026-02-25
- **Category:** `agentic adversarial`

> Self-incrimination training trains agents to call a report_scheming() tool when behaving deceptively. Tested on GPT-4.1 and Gemini-2.0, it significantly reduces undetected successful attack rate and outperforms matched-capability monitors.

**📝 Summary:** 训练 agent 在欺骗性行为时主动调用举报工具，大幅降低未被检测到的攻击成功率，优于同等能力的监控模型。

### [ICON: Indirect Prompt Injection Defense for Agents based on Inference-Time Correction](https://arxiv.org/abs/2602.20708)
- **Authors:** Che Wang, Fuyao Zhang, Jiaming Zhang et al.
- **Date:** 2026-02-24
- **Category:** `LLM agent attack`

> ICON detects IPI via high intensity scores in latent space, then performs surgical attention steering to selectively neutralize adversarial dependencies. Achieves 0.4% ASR with 50%+ task utility gain over baselines.

**📝 Summary:** 通过隐空间强度分数检测 IPI，再进行注意力 steering 手术式消除对抗依赖，ASR 降至 0.4% 同时任务效用提升 50%+。

### ["Are You Sure?": An Empirical Study of Human Perception Vulnerability in LLM-Driven Agentic Systems](https://arxiv.org/abs/2602.21127)
- **Authors:** Xinfeng Li, Shenyu Dai, Kelong Zheng et al.
- **Date:** 2026-02-24
- **Category:** `LLM agent attack`

> First large-scale empirical study (303 participants) measuring human susceptibility to Agent-Mediated Deception (AMD). Only 8.6% perceive AMD attacks; domain experts show increased susceptibility in certain scenarios. Six cognitive failure modes identified.

**📝 Summary:** 303人大规模实验研究人类对 agent 中介欺骗（AMD）的感知脆弱性，仅 8.6% 能识别攻击，发现六种认知失败模式。

### [PA-Attack: Guiding Gray-Box Attacks on LVLM Vision Encoders with Prototypes and Attention](https://arxiv.org/abs/2602.19418)
- **Authors:** Hefei Mei, Zirui Wang, Chang Xu et al.
- **Date:** 2026-02-23
- **Category:** `adversarial attack language model`

> PA-Attack targets LVLM vision encoders in a gray-box setting with prototype-anchored guidance and two-stage attention enhancement, achieving 75.1% average score reduction rate across diverse downstream tasks.

**📝 Summary:** 针对 LVLM 视觉编码器的灰盒攻击，通过 prototype 锚定和注意力增强实现强迁移性，平均 SRR 达 75.1%。

### [Skill-Inject: Measuring Agent Vulnerability to Skill File Attacks](https://arxiv.org/abs/2602.20156)
- **Authors:** David Schmotz, Luca Beurer-Kellner, Sahar Abdelnabi et al.
- **Date:** 2026-02-23
- **Category:** `LLM agent attack`

> SkillInject is a benchmark evaluating susceptibility of LLM agents to injections through skill files, with 202 injection-task pairs. Frontier models show up to 80% ASR including data exfiltration, destructive action, and ransomware-like behaviors.

**📝 Summary:** 评估 LLM agent 对 skill 文件注入攻击的脆弱性，前沿模型攻击成功率高达 80%，覆盖数据窃取和破坏性行为。

### [Assessing Risks of Large Language Models in Mental Health Support: A Framework for Automated Clinical AI Red Teaming](https://arxiv.org/abs/2602.19948)
- **Authors:** Ian Steenstra, Paola Pedrelli, Weiyan Shi et al.
- **Date:** 2026-02-23
- **Category:** `safety benchmark agent`

> This paper introduces an evaluation framework pairing AI psychotherapists with simulated patient agents to assess therapy sessions against quality and risk ontologies. 369 session simulations reveal critical safety gaps including AI Psychosis and failure to de-escalate suicide risk.

**📝 Summary:** 用模拟患者 agent 对 AI 心理治疗师进行 red teaming，发现 AI Psychosis 等严重安全漏洞。

### [BarrierSteer: LLM Safety via Learning Barrier Steering](https://arxiv.org/abs/2602.20102)
- **Authors:** Thanh Q. Tran, Arun Verma, Kiwan Wong et al.
- **Date:** 2026-02-23
- **Category:** `adversarial attack language model`

> BarrierSteer formalizes response safety by embedding learned non-linear safety constraints via Control Barrier Functions directly in the model's latent space, steering unsafe trajectories during inference without modifying LLM parameters.

**📝 Summary:** 用控制障碍函数（CBF）在模型隐空间强制安全约束，推理期 steering 而不修改 LLM 参数。

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