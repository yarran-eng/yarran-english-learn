# English Learn —— 英文口语学习笔记

> 粘贴英文对话/字幕（YouTube、美剧、播客、日常对话）→ 自动生成**完整双语原文 + 精选句子笔记 + 单词表**。只收录真正高价值的表达，不做逐行注释。

这是一个 **AI Agent 技能（Skill）**：当用户粘贴一段英文对话文本并想"整理一下 / 做笔记 / 出原文 / 出口语笔记"时触发。技能将 Agent 设定为"加州母语者朋友"视角——像朋友划重点那样，标出生活中真正会用的句子。

## ✨ 核心特性

- **完整双语原文** —— 全文中文对照，方便复习定位
- **高价值句子笔记** —— 只选高频、地道、可复用、易误解的表达，不逐行注释
- **单词模块** —— 提炼值得记忆的词汇，附用法语境
- **母语者视角** —— 笔记像"朋友帮你划重点"，不是教科书批注
- **用途广泛** —— YouTube 视频、美剧台词、播客、日常对话均可

## 🧠 工作原理

1. 接收用户粘贴的英文对话/字幕原文
2. 按技能规则生成双语原文（全文对照）
3. 筛选**真正高价值**的表达（高频、习语、可复用、易误解）写入笔记区
4. 提炼单词模块

## 📦 安装

```bash
# 将技能目录放入你的 Agent 技能发现目录（如 ~/.agents/skills/）
git clone https://github.com/yarran-eng/yarran-english-learn ~/.agents/skills/yarran-english-learn
# 或手动将 yarran-english-learn 目录复制到技能目录
```

支持任何能加载技能（Skill）的 Agent，包括 ZCode、Claude Code、Codex、Trae 等。

## 🚀 使用方法

| 用户输入示例 | 触发行为 |
|---|---|
| 粘贴英文对话 + "整理一下" | 生成双语原文 + 笔记 + 单词表 |
| "帮我做笔记 / 口语笔记" + 英文文本 | 同上 |

> 配套使用：[English Chat](https://github.com/yarran-eng/yarran-english-chat) 负责"想说不会说"（中文转口语），本技能负责"听过想记住"（口语转笔记）。

## 📁 目录结构

```
yarran-english-learn/
└── SKILL.md        # 技能主文档（角色设定 + 笔记结构规则）
```

## 🤖 兼容性

技能仅定义行为规则，不依赖特定平台 API，适用于所有支持技能调用机制的 AI Agent。

## 🔗 系列技能

| 技能 | 仓库 |
|---|---|
| Browser Prevention（浏览器隐私防护） | [yarran-browser-prevention](https://github.com/yarran-eng/yarran-browser-prevention) |
| Code Magician（编码纪律） | [yarran-code-magician](https://github.com/yarran-eng/yarran-code-magician) |
| Code Style（编码行为准则） | [yarran-code-style](https://github.com/yarran-eng/yarran-code-style) |
| English Chat（中译美式口语） | [yarran-english-chat](https://github.com/yarran-eng/yarran-english-chat) |
| Find Skill（技能发现编排） | [yarran-find-skill](https://github.com/yarran-eng/yarran-find-skill) |
| Paper Reader（论文深度阅读） | [yarran-paper-reader](https://github.com/yarran-eng/yarran-paper-reader) |
| ROS2 Code（ROS2 编码规范） | [yarran-ros2-code](https://github.com/yarran-eng/yarran-ros2-code) |
| Windows Cleanup（C 盘清理卸载） | [yarran-windows-cleanup](https://github.com/yarran-eng/yarran-windows-cleanup) |

## 📄 许可

MIT License（见仓库 LICENSE 文件）。
