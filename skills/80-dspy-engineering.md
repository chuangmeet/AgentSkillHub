# 🚀 DSPy Engineering (DSPy 工程与优化)

[🔙 返回首页](../README.md)

> 专注于 **DSPy 框架** 的高级技能。这些工具允许 Agent 从手动“编写提示词”转变为系统化“编程与编译”语言模型，实现 Prompt 的自动优化与权重微调。
> **来源库**: [OmidZamani/dspy-skills](https://github.com/OmidZamani/dspy-skills/tree/master/skills)

## Optimization & Learning (优化与学习)
*DSPy 的核心能力：使用编译器自动优化 Prompt 和权重。*

- [**dspy-finetune-bootstrap**](https://github.com/OmidZamani/dspy-skills/tree/master/skills/dspy-finetune-bootstrap)
    - **简介**: 使用 `BootstrapFewShot` 或 `BootstrapFineTune` 模块，通过从少量示例中学习，自动优化模型的 Prompt 和权重。
    - **标签**: `Optimization`, `Fine-tuning`, `Bootstrapping`

- [**dspy-gepa-reflective**](https://github.com/OmidZamani/dspy-skills/tree/master/skills/dspy-gepa-reflective)
    - **简介**: 一种基于反射（Reflection）的高级优化器。它利用 LLM 对自身的执行轨迹进行反思，从而优化 Agent 的决策逻辑。
    - **标签**: `Optimizer`, `Reflection`, `Agentic`

## RAG & Integrations (RAG 与集成)
*将 DSPy 的编程思想应用于检索增强生成（RAG）系统。*

- [**dspy-rag-pipeline**](https://github.com/OmidZamani/dspy-skills/tree/master/skills/dspy-rag-pipeline)
    - **简介**: 完整的 RAG 流水线实现，集成 ColBERTv2 检索模型，支持知识增强的生成任务，并可自动优化检索与生成环节。
    - **标签**: `RAG`, `ColBERT`, `Pipeline`

- [**dspy-haystack-integration**](https://github.com/OmidZamani/dspy-skills/tree/master/skills/dspy-haystack-integration)
    - **简介**: 将 DSPy 的优化能力与 Deepset Haystack 框架结合，允许在现有的 Haystack 管道中使用 DSPy 模块。
    - **标签**: `Integration`, `Haystack`, `Framework`

## Core & Evaluation (核心设计与评估)
*构建稳健 DSPy 程序的基础设施与测试工具。*

- [**dspy-signature-designer**](https://github.com/OmidZamani/dspy-skills/tree/master/skills/dspy-signature-designer)
    - **简介**: 辅助设计 DSPy Signatures（签名）。它确保输入/输出字段的类型安全，帮助开发者定义清晰、结构化的 LLM 接口。
    - **标签**: `Design`, `Type Safety`, `Interface`

- [**dspy-evaluation-suite**](https://github.com/OmidZamani/dspy-skills/tree/master/skills/dspy-evaluation-suite)
    - **简介**: 专门用于 DSPy 程序的评估套件。包含准确率、召回率等标准指标，以及基于 LLM 的语义评估指标，用于量化优化效果。
    - **标签**: `Evaluation`, `Metrics`, `QA`
