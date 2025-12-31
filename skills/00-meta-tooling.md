# 🛠️ Meta Tooling (元工具与开发流)

[🔙 返回首页](../README.md)

> 用于生成、管理、加载或标准化 Agent Skill 本身的工具，是构建 Agent 生态系统的基石。

## Skill Management & Loaders (管理与加载工具)
*用于在不同 Agent（Claude, Cursor, Windsurf）之间安装、同步和管理 Skill 的工具。*

- [**openskills**](https://github.com/numman-ali/openskills)
    - **简介**: 一个通用的 CLI 工具，允许在任何 AI 代码编辑器（如 Cursor, Windsurf, Aider）中使用 Anthropic 标准的 Skills。它支持从 GitHub 安装 Skill、自动更新 `AGENTS.md`、以及在不同项目间共享 Skill 配置。
    - **核心功能**: `Universal Loading` (通用加载), `Skill Sync` (同步), `Cross-Agent Support` (跨 Agent 支持)。
    - **标签**: `CLI`, `Infrastructure`, `Productivity`

## Skill Development (开发辅助)
*辅助编写和生成新 Skill 的工具。*

- [**skill-creator**](https://github.com/anthropics/skills/tree/main/skills/skill-creator)
    - **简介**: 这是一个“元技能”，专门用于指导用户创建新的 Claude Skill。它会引导用户定义技能的目标、生成标准的目录结构、编写符合规范的 YAML Frontmatter 元数据，并创建 SKILL.md 文件。
    - **标签**: `Meta-tool`, `Development`, `Workflow`
