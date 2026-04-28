<div align="center">
<img src="image/logo.png" alt="logo" style="zoom:%;" />



# Palind.skill

这是我用来润色写作的 skill。使用 [同事.skill](https://github.com/titanwings/colleague-skill) 蒸馏。

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-black.svg)](https://github.com/openai/codex)
[![Language: zh-CN](https://img.shields.io/badge/language-zh--CN-red.svg)](#)

[快速开始](#-快速开始) · [使用示例](#-使用示例) · [仓库结构](#-仓库结构) · [文档导航](#-文档导航) · [来源与限制](#-来源与限制)

</div>

---

# 🧭 TL;DR

`Palind.skill` 是仓库名和安装目录名。

`palind_style` 是实际使用时的 Skill 触发名。

它用于生成 Palind 式中文长文：第一人称回忆叙事、校园经验、童年误解、技术启蒙、LLM agent 体验，以及“先好笑，后有点难过”的回环式散文。

Skill 触发名：

```text
palind_style
```

---

# 🚀 快速开始

把本仓库作为一个完整 Skill 目录放进 Codex skills 目录：

```powershell
git clone <your-repo-url> "$env:USERPROFILE\.codex\skills\Palind.skill"
```

或者手动复制整个目录到：

```text
~/.codex/skills/Palind.skill
```

安装后，在 Codex 中直接点名使用：

```text
使用 palind_style，写一篇关于第一次使用 Git 的 Palind 式回忆长文。
```

---

# ✍️ 使用示例

```text
使用 palind_style，把“第一次看见 LLM agent 自动修 bug”写成一篇校园回忆风格的中文长文。
```

```text
使用 palind_style，写一篇关于大学第一次被绩点教育的长文，要求有校园场景和技术类比。
```

```text
使用 palind_style，改写下面这段经历，保留事实但改成 Palind 式叙事节奏：<粘贴你的经历>
```

更多例子见 [examples/prompts.md](examples/prompts.md)。

---

# 📦 仓库结构

```text
.
├── SKILL.md
├── work.md
├── persona.md
├── work_skill.md
├── persona_skill.md
├── manifest.json
├── meta.json
├── knowledge/
│   └── research/
│       ├── raw/
│       │   ├── 01_core_profile.md
│       │   ├── 02_conversations_and_material.md
│       │   └── 03_expression_and_reception.md
│       └── merged/
│           └── summary.md
├── docs/
│   ├── design-notes.md
│   └── source-notes.md
└── examples/
    └── prompts.md
```

根目录就是 Skill 根目录，`SKILL.md` 是默认入口。

---

# 📚 文档导航

- [SKILL.md](SKILL.md)：合并后的主 Skill 入口
- [work.md](work.md)：写作方法、结构、节奏、生成流程
- [persona.md](persona.md)：表达 DNA、心智模型、边界与 agentic protocol
- [docs/design-notes.md](docs/design-notes.md)：蒸馏设计说明
- [docs/source-notes.md](docs/source-notes.md)：来源、版权与 grounding 说明
- [knowledge/research/merged/summary.md](knowledge/research/merged/summary.md)：本地研究摘要
