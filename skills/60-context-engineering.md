# 🧬 Context & Agent Engineering (上下文与架构工程)

[🔙 返回首页](../README.md)

> 专注于 Agent 系统的核心架构设计、上下文管理与性能评估。这是构建生产级 Agent 的理论基石。
> **来源库**: [muratcankoylan/Agent-Skills-for-Context-Engineering](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering)

## Fundamentals & Patterns (基础与失效模式)
*理解上下文的解剖结构以及它为何会失效。*

- [**context-fundamentals**](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/context-fundamentals)
    - **简介**: 深入理解 Agent 系统中上下文的组成部分（Anatomy）及其重要性，是进行任何优化的前提。
    - **标签**: `Theory`, `Fundamentals`

- [**context-degradation**](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/context-degradation)
    - **简介**: 识别上下文失效的常见模式，如“中间迷失”（Lost-in-Middle）、上下文中毒（Poisoning）、干扰与冲突。
    - **标签**: `Debugging`, `Failure Analysis`

## Optimization & Memory (优化与内存管理)
*在有限的 Token 预算下最大化信息密度。*

- [**context-optimization**](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/context-optimization)
    - **简介**: 应用压缩（Compaction）、掩码（Masking）和缓存（Caching）策略来优化上下文使用效率。
    - **标签**: `Optimization`, `Token Efficiency`

- [**context-compression**](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/context-compression)
    - **简介**: 针对长会话（Long-running sessions）设计和评估上下文压缩策略，防止上下文溢出。
    - **标签**: `Compression`, `Long-context`

- [**memory-systems**](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/memory-systems)
    - **简介**: 构建 Agent 的记忆体系，管理短期工作记忆与长期知识库的检索与存储。
    - **标签**: `Memory`, `RAG`

## Architecture & Tools (架构与工具设计)
*如何设计宏观的多智能体系统与微观的工具交互。*

- [**multi-agent-patterns**](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/multi-agent-patterns)
    - **简介**: 掌握主流的多智能体架构模式，包括编排器（Orchestrator）、点对点（P2P）和层级结构（Hierarchical）。
    - **标签**: `Multi-Agent`, `Architecture`

- [**tool-design**](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/tool-design)
    - **简介**: 学习工具定义（Tool Definitions）如何与上下文交互，设计对模型友好的工具接口。
    - **标签**: `Tooling`, `Interface Design`

- [**project-development**](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/project-development)
    - **简介**: 构建 Agent 项目的工程方法论，从原型设计到生产部署的完整流程。
    - **标签**: `Methodology`, `Engineering`

## Evaluation & QA (评估与测试)
*确保 Agent 行为符合预期的测试框架。*

- [**evaluation**](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/evaluation)
    - **简介**: 构建 Agent 系统的基础评估框架，定义成功指标与测试集。
    - **标签**: `Testing`, `QA`

- [**advanced-evaluation**](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/advanced-evaluation)
    - **简介**: 掌握 LLM-as-a-Judge 高级技术，包括直接评分、成对比较（Pairwise Comparison）、评分标准生成（Rubric Generation）及偏见缓解。
    - **标签**: `LLM-as-a-Judge`, `Metrics`
