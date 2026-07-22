# 基础工具箱

<p class="guide-lead">
工具不是能力本身，但会决定你获取资料、阅读代码、复现实验和完成项目的效率。刚开始学 AI 时，不需要追求复杂配置，先把网络访问、AI 助手、编辑器和基础开发环境用顺手。
</p>

<div class="quick-path" markdown>

**最低目标：**  
能稳定访问官方文档和开源社区，能用编辑器写代码，能用 AI 辅助理解问题，能对最终结果负责。

</div>

## 工具总览

<div class="decision-table" markdown>

| 场景 | 推荐工具 | 你需要掌握到什么程度 |
| --- | --- | --- |
| 访问资料 | GitHub、官方文档、课程网站、论文网站 | 能找到一手资料，并遵守所在地法律法规、学校网络规定和网站条款 |
| AI 辅助 | ChatGPT、Claude、Gemini | 能让 AI 解释概念、拆任务、查错、辅助写代码，但会主动验证 |
| 代码编辑 | Visual Studio Code | 能写 Python、管理项目、连接远程服务器或 WSL |
| AI 编程 | Codex、Claude Code | 能让 agent 处理重复代码劳动，同时自己理解改动和风险 |

</div>

## 网络访问

学习计算机后，你会经常接触 GitHub、官方技术文档、开源社区、国外高校课程和论文网站。稳定地获取这些资料很重要。

- [Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev)  
  一款支持 Windows、macOS 和 Linux 的图形化代理客户端，可以管理代理配置、切换节点和设置分流规则。它只是客户端，本身不提供网络服务。

!!! warning "合规提醒"
    这里不提供代理节点或服务商推荐。请遵守所在地法律法规、学校网络规定以及相关网站的使用条款。

## AI 工具

常用的通用 AI 助手包括：

- [ChatGPT](https://chatgpt.com/)
- [Claude](https://claude.ai/)
- [Gemini](https://gemini.google.com/)

请尽早学会如何充值使用最先进的AI模型。不建议把豆包当成深入工作的主要依赖。它可以用于日常问答，但在复杂技术推理、代码协作和长上下文工作中，稳定性和能力边界需要谨慎评估。

使用 AI 时，至少要记住几件事：

1. **AI 会一本正经地犯错。** 涉及技术细节时，必须检查来源。
2. **提问质量决定回答质量。** 学会写 prompt，给出背景、目标、约束和你已经尝试过的东西。
3. **不要只要答案，也要过程。** 可以要求它解释思路、列出假设、指出不确定之处并给出验证方法。
4. **最终责任仍然在你。** AI 可以帮你思考和执行，但不能替你判断结果是否正确、是否安全、是否符合要求。

!!! tip "更好的用法"
    AI 最有价值的用法，不是替你跳过学习，而是帮你加快理解的过程。让它解释概念、生成练习、审查代码、指出盲区，然后你自己验证。

## 编程工具

- [Visual Studio Code](https://code.visualstudio.com/)  
  最常用的代码编辑器之一。VS Code 做科研和工程都很方便，可以通过 SSH 连接远程服务器，也可以直接在 WSL 中工作。

## AI Coding Agent

常见的 AI coding agent 包括：

- [Codex](https://openai.com/codex/)  
  OpenAI 的 AI coding agent。

- [Claude Code](https://code.claude.com/docs/en/overview)  
  Anthropic 的 AI coding agent。

Codex 和 Claude Code 都很强，但在使用 coding agent 之前，最好先掌握一些基础代码理解能力。

AI coding agent 可以替你完成很多代码劳动，但不能替代你的理解。

!!! warning "不要把仓库完全交出去"
    当你还看不懂代码时，让 agent 大规模重构很危险。更稳的方式是从小任务开始：修一个 bug、补一个函数、写一个测试、解释一段代码，再逐渐扩大任务范围。

## 最小配置清单

<div class="reading-path" markdown>

**开始 AI 学习前，至少准备好：**

- 一个能稳定写代码的编辑器。
- 一个能正常运行 Python 的环境。
- 一个能访问官方文档、GitHub 和课程资料的资料获取方式。
- 一个常用 AI 助手，用来解释、拆解和验证问题。

完成这些之后，就可以进入 [AI 学习基础路线](ai-basic-roadmap.md)。

</div>
