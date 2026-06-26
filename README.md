# PCAE — Personal Comparative Advantage Engine

**本项目是一个帮助你在 AI 时代发现个人优势的 Skill，通过综合心理、认知、人格、职业发展及经济等多门学科，以对话方式分析|发掘个人在 AI 时代下的特色及优势，专注未来个人协同AI的发展方向**

[English](#english) | [中文](#中文)

---

<a name="中文"></a>

## 项目简介

PCAE 是一个基于 **Personal Comparative Advantage Theory (PCAT)** 的 Skill。它通过结构化的对话，帮助你发现自己的独特优势——不是简单告诉你"你适合当什么"，而是深入分析：

- 你的人生故事中隐藏了什么能力模式？
- 你的独特能力组合（天赋堆叠）是什么？
- 在你自己的能力中，哪个方向的机会成本最低？
- AI 会放大还是替代你的哪些能力？
- 未来 5 年你应该如何发展？

## 安装

PCAE 同时兼容 **Claude Code** 和 **Codex**

### Claude Code

```bash
# macOS / Linux
git clone https://github.com/KeGong-XKK/Personal-Comparative-Advantage-Engine-PCAE.git ~/.claude/skills/pcae

# Windows
git clone https://github.com/KeGong-XKK/Personal-Comparative-Advantage-Engine-PCAE.git %USERPROFILE%\.claude\skills\pcae
```

### Codex CLI

```bash
# 个人级安装（推荐）— macOS / Linux
mkdir -p ~/.agents/skills
git clone https://github.com/KeGong-XKK/Personal-Comparative-Advantage-Engine-PCAE.git ~/.agents/skills/pcae

# 个人级安装 — Windows
mkdir %USERPROFILE%\.agents\skills
git clone https://github.com/KeGong-XKK/Personal-Comparative-Advantage-Engine-PCAE.git %USERPROFILE%\.agents\skills\pcae

# 仓库级共享（让团队成员都能用）— 在你的项目目录下执行
mkdir -p .agents/skills
git clone https://github.com/KeGong-XKK/Personal-Comparative-Advantage-Engine-PCAE.git .agents/skills/pcae
```

> Codex 通过 `SKILL.md` 的 frontmatter 自动注册 Skill，无需额外配置。安装后启动 `codex` 即可识别。

## 使用方式

### Claude Code 支持的平台

PCAE 作为 Claude Code Skill，可以在所有 Claude Code 入口使用：

| 平台 | 启动方式 |
|------|----------|
| **终端 CLI** | 在终端运行 `claude`，进入后输入 `/pcae` |
| **桌面应用** | 打开 Claude Code 桌面版（Mac/Windows），输入 `/pcae` |
| **Web 应用** | 访问 [claude.ai/code](https://claude.ai/code)，输入 `/pcae` |
| **VS Code** | 安装 Claude Code 扩展，在侧边栏对话中输入 `/pcae` |
| **JetBrains** | 安装 Claude Code 插件，在工具窗口中输入 `/pcae` |

### Codex

| 入口 | 启动方式 |
|------|----------|
| **Codex CLI（终端）** | 运行 `codex`，输入 `/skills` 查看已注册 Skill，然后用 `$pcae` 显式调用 |
| **Codex IDE 扩展** | 在 IDE 对话框中输入 `$pcae` 触发，或直接描述需求让 Codex 隐式选用 |

### 命令

```
/pcae              # 开始完整的优势发现流程
/pcae start        # 同上
/pcae resume       # 从上次中断的地方继续
/pcae analyze      # 跳到分析阶段（需要先完成发现）
/pcae strategy     # 跳到战略阶段（需要先完成分析）
/pcae profile      # 生成个人比较优势档案 (PCAP)
/pcae review       # 重新审视和更新已有档案
```

### 自然语言触发

你也可以直接告诉 Claude 你的需求，无需使用 `/pcae` 命令，以下表达会自动触发 PCAE：

- "帮我分析一下我的职业优势"
- "我想知道 AI 时代我应该怎么发展"
- "我的优势是什么"
- "what am I good at"
- "discover my strengths"

## PCAT 九层模型

PCAE 基于 Personal Comparative Advantage Theory (PCAT) 的九层分析模型：

| 阶段 | Layer | 核心问题 |
|------|-------|----------|
| **Discovery 发现** | 1. Narrative 叙事 | 你的人生故事中隐藏了什么模式？ |
| | 2. Motivation 动机 | 什么在驱动你？ |
| | 3. Capability 能力 | 你的能力版图是什么？ |
| **Analysis 分析** | 4. Capability Combination 组合 | 你的独特能力堆叠是什么？ |
| | 5. Comparative Advantage 比较优势 | 你的相对优势在哪里？ |
| | 6. AI Amplification AI放大 | AI 会放大还是替代你的优势？ |
| **Strategy 战略** | 7. Market Opportunity 市场 | 你的优势匹配什么机会？ |
| | 8. Long-term Strategy 战略 | 你的战略核是什么？ |
| | 9. Feedback Loop 反馈 | 如何持续验证和迭代？ |

## 理论基础

PCAE 整合了多个学科的理论：

- **经济学**：Ricardo 比较优势理论（机会成本视角）
- **心理学**：Flow 心流理论、Growth Mindset 成长型思维、Ikigai 四圈模型
- **职业发展**：Designing Your Life (Stanford)、Appreciative Inquiry 欣赏式探询
- **认知科学**：Range 广度理论、Deliberate Practice 刻意练习
- **AI 时代**：Co-Intelligence (Mollick)、The Coming Wave (Suleyman)、WEF Future of Jobs
- **战略**：Good Strategy Bad Strategy (Rumelt)、Talent Stack (Adams)

## 输出

完成分析后，PCAE 会生成一份 **Personal Comparative Advantage Profile (PCAP)**，包含能力版图、天赋堆叠、比较优势排序、AI影响、战略核和行动计划。查看 [示例档案](examples/example-profile.md)。

## 许可

MIT License

## 作者

Ke Gong & AI

---

<a name="english"></a>

## What is this?

PCAE is a Claude Code Skill based on **Personal Comparative Advantage Theory (PCAT)**. Through structured conversations, it helps you discover your unique advantages — not by telling you "you should be a teacher," but by deeply analyzing:

- What capability patterns are hidden in your life stories?
- What is your unique talent stack (capability combination)?
- Among your own capabilities, which direction has the lowest opportunity cost? (This is your true comparative advantage)
- Which of your capabilities will AI amplify vs. replace?
- How should you develop over the next 5 years?

## Installation

PCAE works with both **Claude Code** and **OpenAI Codex CLI** — both use the Skill mechanism, just in different directories.

### Claude Code

```bash
# macOS / Linux
git clone https://github.com/KeGong-XKK/Personal-Comparative-Advantage-Engine-PCAE.git ~/.claude/skills/pcae

# Windows
git clone https://github.com/KeGong-XKK/Personal-Comparative-Advantage-Engine-PCAE.git %USERPROFILE%\.claude\skills\pcae
```

### Codex

```bash
# Personal install (recommended) — macOS / Linux
mkdir -p ~/.agents/skills
git clone https://github.com/KeGong-XKK/Personal-Comparative-Advantage-Engine-PCAE.git ~/.agents/skills/pcae

# Personal install — Windows
mkdir %USERPROFILE%\.agents\skills
git clone https://github.com/KeGong-XKK/Personal-Comparative-Advantage-Engine-PCAE.git %USERPROFILE%\.agents\skills\pcae

# Repo-shared (so teammates inherit it) — run inside your project root
mkdir -p .agents/skills
git clone https://github.com/KeGong-XKK/Personal-Comparative-Advantage-Engine-PCAE.git .agents/skills/pcae
```

> Codex auto-registers the Skill from `SKILL.md` frontmatter — no extra config needed. Just launch `codex` after install.

## Usage

### Claude Code Platforms

PCAE works across all Claude Code entry points:

| Platform | How to Start |
|----------|-------------|
| **Terminal CLI** | Run `claude` in terminal, then type `/pcae` |
| **Desktop App** | Open Claude Code desktop (Mac/Windows), type `/pcae` |
| **Web App** | Visit [claude.ai/code](https://claude.ai/code), type `/pcae` |
| **VS Code** | Install Claude Code extension, type `/pcae` in sidebar chat |
| **JetBrains** | Install Claude Code plugin, type `/pcae` in tool window |

### Codex CLI

| Entry Point | How to Start |
|-------------|--------------|
| **Codex CLI (terminal)** | Run `codex`, type `/skills` to list registered Skills, then invoke with `$pcae` |
| **Codex IDE Extension** | In the IDE chat, type `$pcae` to invoke, or just describe your need and let Codex pick it implicitly |

### Commands

```
/pcae              # Start the full discovery process
/pcae start        # Same as above
/pcae resume       # Continue from where you left off
/pcae analyze      # Jump to analysis phase (requires discovery first)
/pcae strategy     # Jump to strategy phase (requires analysis first)
/pcae profile      # Generate Personal Comparative Advantage Profile (PCAP)
/pcae review       # Review and update existing profile
```

### Natural Language Triggers

You can also describe your needs naturally — PCAE triggers automatically on phrases like "help me analyze my career advantages", "what am I good at", or "discover my strengths".

## Theory Foundation

PCAE integrates theories from multiple disciplines: Ricardo's Comparative Advantage, Flow Theory, Growth Mindset, Ikigai, Designing Your Life, Appreciative Inquiry, Range, Deliberate Practice, Co-Intelligence, Good Strategy Bad Strategy, and Talent Stack theory.

## License

MIT License

## Author

Ke Gong & AI
