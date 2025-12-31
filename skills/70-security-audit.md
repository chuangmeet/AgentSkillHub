# 🛡️ Security & Audit (安全与审计)

[🔙 返回首页](../README.md)

> 专注于 AI Agent 生态系统的安全评估。这些 Skill 充当“看门人”，用于扫描其他的 Skill 或 MCP Server 是否存在恶意代码、Prompt 注入风险及隐私漏洞。
> **来源库**: [JeredBlu/eval-marketplace](https://github.com/JeredBlu/eval-marketplace/tree/main/evaluator-tools/skills)

## Ecosystem Security (生态安全扫描)

- [**agent-skill-evaluator**](https://github.com/JeredBlu/eval-marketplace/tree/main/evaluator-tools/skills/agent-skill-evaluator)
    - **简介**: 专门用于评估 Agent Skill (.md 文件) 的安全性。它会自动检测 Prompt 注入攻击、隐藏指令、恶意代码模式以及潜在的数据泄露风险，并生成 0-100 的风险评分。
    - **标签**: `Security`, `Audit`, `Prompt Injection`, `Risk Assessment`

- [**mcp-evaluator**](https://github.com/JeredBlu/eval-marketplace/tree/main/evaluator-tools/skills/mcp-evaluator)
    - **简介**: 针对 MCP (Model Context Protocol) 服务器的安全评估工具。它分析服务器代码的漏洞、隐私风险和代码质量，结合社区反馈（如 GitHub Activity）提供综合的安全建议。
    - **标签**: `MCP`, `Vulnerability Scanning`, `Privacy`, `Code Quality`
