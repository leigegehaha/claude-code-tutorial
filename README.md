# Claude Code 学习教程

从零开始掌握 Anthropic 推出的 AI 编程助手 Claude Code，涵盖入门、中级、高级用法。

## 在线预览

👉 **[点击这里查看教程](https://leigegehaha.github.io/claude-code-tutorial/)**

## 内容大纲

- **快速开始**：安装环境、**三大终端 AI 编程工具对比**
- **入门篇**：基础命令、第一个任务、斜杠命令、文件引用语法
- **中级篇**：CLI 高级标志、管道与脚本、CLAUDE.md 配置、Git 工作流、多会话管理
- **高级篇**：Hooks 钩子系统、技能系统、MCP 集成、多代理协作、CI/CD 自动化、权限与安全、子代理系统、记忆系统、即时通讯集成、桌面端应用
- **附录**：速查表、常见问题

---

## 📊 三大终端 AI 编程工具对比

> 教程内含完整详细对比，以下是核心要点速览。

2025-2026 年，终端 AI 编程工具爆发式增长。三款最具代表性的工具各有特色：

| 维度 | 🟠 Claude Code | 🔵 OpenAI Codex CLI | 🟢 OpenCode |
|------|---------------|--------------------|--------------| 
| **开发商** | Anthropic | OpenAI | 开源社区（Charmbracelet） |
| **许可证** | 闭源 | 开源（Apache 2.0） | 开源（MIT） |
| **底层模型** | Claude Opus 4.6 / Sonnet 4.6 | GPT-5.4 / GPT-5.3-Codex | 多模型（Claude/GPT/Gemini 等） |
| **工作流哲学** | 交互式 · 开发者在环 | 异步委派 · 事后审查 | 轻量交互 · 多模型切换 |
| **SWE-bench** | **80.8%** 🏆 | 64.7% | — |
| **Terminal-Bench** | 65.4% | **77.3%** 🏆 | — |
| **上下文窗口** | **200K Token** 🏆 | 128K Token | 取决于模型 |
| **Token 效率** | 标准 | **约 3x 更省** 🏆 | 取决于模型 |
| **入门价格** | $20/月（Pro） | $20/月（Plus） | **免费** 🏆 |
| **进阶价格** | $100/月（Max 5x） | $200/月（Pro） | 免费 + API 费用 |

### 🟠 Claude Code — 深度推理之王

**优势**：SWE-bench 80.8% 遥遥领先、200K 超长上下文、Skills/Hooks/MCP 丰富生态、6 种权限模式、多平台全支持（CLI/IDE/Desktop/IM）

**不足**：价格较高（深度推理消耗大 Token）、闭源、终端调试偏弱

**适合**：复杂架构设计、大型代码库重构、重视代码质量胜过成本的开发者

### 🔵 OpenAI Codex CLI — 效率与速度之王

**优势**：Token 效率约 3 倍、终端调试 77.3%、开源 CLI、异步委派工作流、GitHub 云端集成、ChatGPT 生态衔接

**不足**：复杂推理偏弱（SWE-bench 64.7%）、128K 上下文较小、信用点滚动限制、可定制性有限

**适合**：Bug 修复、终端调试、定义明确的工单、追求速度和成本效益的开发者

### 🟢 OpenCode — 开源多模型瑞士军刀

**优势**：完全免费（MIT）、多模型自由切换、精美 TUI 界面、轻量快速、无厂商锁定

**不足**：项目已归档（迁移至 [Crush](https://github.com/charmbracelet/crush)，仍早期）、功能较基础、无官方支持、API 费用自理

**适合**：预算有限的学生/开发者、需要多模型切换、偏好开源工具的用户

### 💡 如何选择？

- **复杂重构 / 架构设计** → Claude Code
- **Bug 修复 / 终端调试** → OpenAI Codex
- **零预算 / 多模型切换** → OpenCode
- **高级建议**：同时使用 Claude Code + Codex，各取所长

---

## 特色

- 📱 响应式设计，支持手机/平板/电脑
- 🎨 深色主题，保护眼睛
- 🖼️ 10+ 原创SVG 架构图
- 🔄 交互式 Tab 切换和手风琴组件
- 📋 一键复制代码块
- 🔍 侧边栏搜索导航
- 📊 三大工具对比（Claude Code / Codex / OpenCode）

## 本地运行

```bash
# 克隆仓库
git clone https://github.com/leigegehaha/claude-code-tutorial.git

# 直接用浏览器打开
open index.html
```

## 作者

📚 **磊哥哥科技拆解室**

本教程引用的开源代码和网页内容均已标注来源，版权归原作者所有。

## 开源协议

本项目采用 [Apache License 2.0](LICENSE) 开源协议。
