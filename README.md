<div align="center">

# 🦞 OpenClaw 小龙虾教程中文版

### 让中文开发者把 OpenClaw 当成有组织、有边界、有记忆的多 Agent 工作单元

> 💎 **不是 API 列表，而是为中文新手重写的双路径教程：理解篇负责心智模型，官方篇负责事实基准——两条路径同时跑，不替代彼此。**

[![类型](https://img.shields.io/badge/类型-Tutorial-blue?style=for-the-badge)](https://aiworkflowtutorials.com/docs/openclaw)
[![章节](https://img.shields.io/badge/章节-20_篇-brightgreen?style=for-the-badge)](https://aiworkflowtutorials.com/docs/openclaw)
[![语言](https://img.shields.io/badge/语言-简体中文-DC322F?style=for-the-badge)](#)
[![事实基准](https://img.shields.io/badge/事实基准-OpenClaw_官方仓-E63946?style=for-the-badge)](https://aiworkflowtutorials.com/docs/openclaw)
[![繁体](https://img.shields.io/badge/繁体-zh--Hant-9b59b6?style=for-the-badge)](https://aiworkflowtutorials.com/docs/openclaw)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-orange?style=for-the-badge)](CONTRIBUTING.md)

</div>

---

> 🎯 **多 Agent 框架不缺，缺的是「能让中文开发者真的把多 Agent 当成有组织、有边界的工作单元」的版本。**
>
> 这份教程基于 OpenClaw 官方仓库源码、设计文档和真实生产实践重写，按「中文新手 → 第一性原理 → 循序渐进」组织。
> 10 篇 **从原理到实战** 帮你建立心智模型，2 个分组的 **官方教程中文版** 覆盖入门安装与 Gateway 运行时细节。
>
> 完整教程托管在翔宇工作流的中文教程站，本仓库是公开门面入口，负责发现、反馈和样章预览。

<div align="center">

[🚀 立刻开始阅读](https://aiworkflowtutorials.com/docs/openclaw) · [🧠 从原理到实战](https://aiworkflowtutorials.com/docs/openclaw/understanding) · [📚 官方教程中文版](https://aiworkflowtutorials.com/docs/openclaw/official) · [🐛 反馈问题](https://github.com/xiangyugongzuoliu/openclaw-tutorial/issues)

</div>

---

## 📖 这是什么 (What)

> 💡 **核心定位**：中文开发者的 OpenClaw 学习入口 —— 把多 Agent 系统当成「公司」来设计：每个 Agent 有自己的家、自己的工作空间、自己的记忆、自己的权限边界。

这是《AI 编程教程中文版》里的 OpenClaw 主题，由 [aiworkflowtutorials.com](https://aiworkflowtutorials.com/docs/openclaw) 发布完整内容。本 GitHub 仓库只放门面入口、学习路线和样章摘录。

### 📐 双路径结构

| 路径 | 适合谁 | 章节数 | 入口 |
|------|--------|:------:|------|
| 🧠 **从原理到实战** | 想理解多 Agent 为什么需要 Workspace、Channel、Session 这套结构 | **10 篇** | [开始 →](https://aiworkflowtutorials.com/docs/openclaw/understanding) |
| 📚 **官方教程中文版** | 想直接查安装、配置、Gateway 运行时、API 用法 | **10 篇** | [开始 →](https://aiworkflowtutorials.com/docs/openclaw/official) |

两条路径**结构对称、互相引用**：理解篇遇到「具体怎么配」时跳官方篇，官方篇遇到「为什么要这样」时跳理解篇。

### 🎯 这份教程的不同

- 🇨🇳 **为中文新手重写**：把多 Agent 系统翻译成「公司、办公室、工位、消息流」这套生活化比喻
- 🏗️ **从设计哲学讲起**：不是 API 列表，先讲「为什么 Agent 需要一个家」「为什么消息要走 Channel」
- 📐 **真实生产视角**：每章从单 Agent 出发，逐步演化到多 Agent 协作、Session 与心跳、安全边界
- 🔁 **简繁双语**：简体 + 繁体同时维护，海外华人开发者直接可用

---

## 🚀 怎么用 (How to Use)

> 💡 **最佳用法 · 交给 AI Agent 讲给你听**
>
> 把本仓库 clone 下来或整段贴给 **Claude Code / OpenAI Codex** 这类 AI 编程 Agent，让它读完 README 后**按你的节奏一篇一篇讲**——不懂的随时打断追问，比自己埋头通读高效得多。

### 推荐阅读顺序

1. 先读从原理到实战 **01-03**，建立 OpenClaw 为什么把多 Agent 放进组织结构的心智模型
2. 再读官方教程中文版的「**入门与安装**」，跑通第一个 OpenClaw 工作单元
3. 回到真实场景，用一个最小用例练习"单 Agent → 双 Agent 协作 → Session 持续运行"的渐进闭环
4. 最后进入 **记忆 / Context 管理 / Workspace / Channel 安全 / 设计复盘**，把多 Agent 沉淀成可演进的协作系统

### 🧠 从原理到实战（10 篇）

| # | 章节 | 链接 |
|:-:|------|------|
| 01 | 为什么 AI 需要一个家 | [阅读 →](https://aiworkflowtutorials.com/docs/openclaw/understanding/01-ai-home) |
| 02 | 一条消息的旅程 | [阅读 →](https://aiworkflowtutorials.com/docs/openclaw/understanding/02-message-journey) |
| 03 | Agent 的大脑是怎么工作的 | [阅读 →](https://aiworkflowtutorials.com/docs/openclaw/understanding/03-agent-brain) |
| 04 | 记忆系统：短期、长期、可检索记忆 | [阅读 →](https://aiworkflowtutorials.com/docs/openclaw/understanding/04-memory-system) |
| 05 | Context 管理：为什么 AI 会忘记、截断和压缩 | [阅读 →](https://aiworkflowtutorials.com/docs/openclaw/understanding/05-context-management) |
| 06 | Workspace：Agent 的工作空间和身份容器 | [阅读 →](https://aiworkflowtutorials.com/docs/openclaw/understanding/06-workspace) |
| 07 | 多 Agent：什么时候拆、怎么协作 | [阅读 →](https://aiworkflowtutorials.com/docs/openclaw/understanding/07-multi-agent) |
| 08 | Session 与心跳：时间如何进入 Agent | [阅读 →](https://aiworkflowtutorials.com/docs/openclaw/understanding/08-session-heartbeat) |
| 09 | Channel 与安全：谁能进来、能做什么 | [阅读 →](https://aiworkflowtutorials.com/docs/openclaw/understanding/09-channel-security) |
| 10 | 设计复盘：OpenClaw 为什么这样设计 | [阅读 →](https://aiworkflowtutorials.com/docs/openclaw/understanding/10-design-review) |

### 📚 官方教程中文版（2 个分组 · 10 篇）

| 分组 | 主题 | 篇数 | 入口 |
|------|------|:----:|------|
| 🟢 **入门与安装** | 第一次跑通 OpenClaw 的最少必要操作 | 4 | [开始 →](https://aiworkflowtutorials.com/docs/openclaw/official/00-getting-started) |
| 🟡 **Gateway 运行时** | Gateway / 消息路由 / 部署 / 运维 | 6 | [开始 →](https://aiworkflowtutorials.com/docs/openclaw/official/01-gateway-runtime) |

### 💡 第一次启动一个 OpenClaw 工作单元

```text
你（在 OpenClaw 项目里对 Claude Code / Codex）：

  我想用 OpenClaw 跑通最小协作场景：一个 PM Agent 接收任务，
  拆解后交给一个 Engineer Agent 执行，结果回到 PM Agent 汇报。
  先帮我列出最小可工作的目录结构 + 配置文件，
  然后告诉我每一个文件该写什么、为什么这样写。
```

> 🎯 **OpenClaw 的核心是把 Agent 当员工设计**——先想清楚组织结构（谁负责什么、谁向谁汇报），再想消息流（怎么传递任务和反馈），最后想权限（谁能动什么）。

---

## 🤝 怎么贡献 (Contribute)

本仓库**只接受 issue 反馈**，不接受完整教程正文 PR（完整内容在私有生产仓维护）。

适合提交的 issue：

- 🐛 **错别字 / 死链 / 事实错误**：教程站任意章节
- 🔗 **官方资料链接更新**：OpenClaw 仓发布或文档结构调整的同步
- ✨ **样章表达问题**：本仓 `samples/` 里的样章
- 💡 **学习路径建议**：哪一章顺序应该调整、哪一篇应该补案例

[🐛 提交 Issue](https://github.com/xiangyugongzuoliu/openclaw-tutorial/issues) · [📜 完整贡献指南](CONTRIBUTING.md) · [🔒 版权说明](COPYRIGHT.md)

如果这份教程帮到你，给本仓库一个 ⭐ 是最直接的鼓励——也方便其他中文开发者发现它。

---

## 👋 关于翔宇 (About)

> 🚀 **翔宇 — AI Agent 工作流研究者。**
>
> 把 AI 工具变成能持续运转的生产系统，专注 Claude Code / Codex 等 AI 编程 Agent 的真实工程化用法，把「AI 怎么帮普通人解决真实问题」作为长期方向。

### 📚 公开内容矩阵

| 平台 | 内容 | 链接 |
|------|------|------|
| 🌐 **翔宇工作流官网** | AI 编程 / Agent / 自动化深度教程 | [xiangyugongzuoliu.com](https://xiangyugongzuoliu.com) |
| 📺 **YouTube 频道** | AI 编程实战、Agent 知识库实战、视频教程 | [@xiangyugongzuoliu](https://www.youtube.com/@xiangyugongzuoliu) |
| 💻 **GitHub Profile** | 公开仓库 + 个人简介 | [@xiangyugongzuoliu](https://github.com/xiangyugongzuoliu) |
| 𝕏 **X / Twitter** | 工作流碎片 + 实战记录 | [@xiangyuworkflow](https://x.com/xiangyuworkflow) |
| 💬 **微信公众号** | 应用场景引流文 + 工作流案例 | 翔宇工作流 |

### 🎯 推荐先看

- 🤖 [**AI 编程教程中文版**](https://aiworkflowtutorials.com) — 本仓库所属的教程站全集
- 🎬 [**YouTube · Agent 知识库实战**](https://www.youtube.com/@xiangyugongzuoliu) — Claude Code / Codex 真实项目录屏
- 🌐 [**翔宇工作流官网**](https://xiangyugongzuoliu.com) — 项目复盘、踩坑记录、长文工作流

### 🎓 AI 编程实操课

想系统学习 AI 编程 / Agent 工作流（Claude Code / Codex 实战），可以看翔宇的 AI 编程实操课：

- 🇨🇳 **国内版（FlowUS）**：https://flowus.cn/xiangyugongzuoliu/share/d392dcad-b537-44ee-a3e2-56ff5af02bce
- 🌍 **国际版（Buy Me a Coffee）**：[buymeacoffee.com/xiangyu](https://buymeacoffee.com/xiangyu)

> 🎁 **会员附赠**：跟着课程一起交付的实战脚手架 + 多 Agent 协作模板，把"读懂"变成"装进自己的工作流"。

---

<div align="center">

### ⭐ 如果这个教程对你有用，给一个 Star 让翔宇知道

[![翔宇官网](https://img.shields.io/badge/🌐_官网-xiangyugongzuoliu.com-FF6B35?style=for-the-badge)](https://xiangyugongzuoliu.com)
[![YouTube](https://img.shields.io/badge/📺_YouTube-频道-FF0000?style=for-the-badge)](https://www.youtube.com/@xiangyugongzuoliu)
[![GitHub](https://img.shields.io/badge/💻_GitHub-Profile-181717?style=for-the-badge)](https://github.com/xiangyugongzuoliu)

> 🎯 **工具一直在变，工作流不变。**
>
> 🛠️ **普通人对抗专业壁垒的唯一武器，就是工具。**

</div>
