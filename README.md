# PCAE — Personal Comparative Advantage Engine

**帮助你在 AI 时代发现个人比较优势的 Claude Code Skill**

[English](#english) | [中文](#中文)

---

<a name="中文"></a>

## 这是什么？

PCAE 是一个基于 **Personal Comparative Advantage Theory (PCAT)** 的 Claude Code Skill。它通过结构化的对话，帮助你发现自己的独特优势——不是简单告诉你"你适合当什么"，而是深入分析：

- 你的人生故事中隐藏了什么能力模式？
- 你的独特能力组合（天赋堆叠）是什么？
- 在你自己的能力中，哪个方向的机会成本最低？（这才是真正的比较优势）
- AI 会放大还是替代你的哪些能力？
- 未来 5 年你应该如何发展？

## 安装

```bash
# 方式一：克隆到 Claude Code 技能目录
git clone https://github.com/YOUR_USERNAME/pcae.git ~/.claude/skills/pcae

# 方式二：使用 gh skill 命令（需要 GitHub CLI v2.90+）
gh skill install YOUR_USERNAME/pcae --agent claude-code
```

## 使用

在 Claude Code 中输入：

```
/pcae              # 开始完整的优势发现流程
/pcae start        # 同上
/pcae resume       # 从上次中断的地方继续
/pcae analyze      # 跳到分析阶段（需要先完成发现）
/pcae strategy     # 跳到战略阶段（需要先完成分析）
/pcae profile      # 生成个人比较优势档案 (PCAP)
/pcae review       # 重新审视和更新已有档案
```

你也可以直接告诉 Claude 你的需求，比如"帮我分析一下我的职业优势"或"我想知道 AI 时代我应该怎么发展"，PCAE 会自动触发。

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

完成分析后，PCAE 会生成一份 **Personal Comparative Advantage Profile (PCAP)**，包含能力版图、天赋堆叠、比较优势排序、AI影响地图、战略核和行动计划。查看 [示例档案](examples/example-profile.md)。

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

```bash
# Option 1: Clone to Claude Code skills directory
git clone https://github.com/YOUR_USERNAME/pcae.git ~/.claude/skills/pcae

# Option 2: Using gh skill command (requires GitHub CLI v2.90+)
gh skill install YOUR_USERNAME/pcae --agent claude-code
```

## Usage

In Claude Code, type:

```
/pcae              # Start the full discovery process
/pcae start        # Same as above
/pcae resume       # Continue from where you left off
/pcae analyze      # Jump to analysis phase (requires discovery first)
/pcae strategy     # Jump to strategy phase (requires analysis first)
/pcae profile      # Generate Personal Comparative Advantage Profile (PCAP)
/pcae review       # Review and update existing profile
```

You can also describe your needs naturally, such as "help me analyze my career advantages" or "what should I focus on in the AI era" — PCAE will trigger automatically.

## Theory Foundation

PCAE integrates theories from multiple disciplines: Ricardo's Comparative Advantage, Flow Theory, Growth Mindset, Ikigai, Designing Your Life, Appreciative Inquiry, Range, Deliberate Practice, Co-Intelligence, Good Strategy Bad Strategy, and Talent Stack theory.

## License

MIT License

## Author

Ke Gong & AI
