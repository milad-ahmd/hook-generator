> [!NOTE]
> **This skill now lives in the main collection: [milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills/tree/main/skills/hook-generator)**. Please ⭐ star it there; that's where updates land first.
> Docs: **https://milad-ahmd.github.io/agent-skills/skills/hook-generator/** · Claude Code: `/plugin install all-skills --marketplace milad-ahmd/agent-skills`

<div align="center">

# 🪝 hook-generator

**Scroll-stopping hooks for videos, posts, emails and ads, scored and ranked. An Agent Skill for Claude Code, Cline, Cursor, Codex and other AI coding agents.**

[![License: MIT](https://img.shields.io/github/license/milad-ahmd/hook-generator)](LICENSE)
[![Stars](https://img.shields.io/github/stars/milad-ahmd/hook-generator?style=social)](https://github.com/milad-ahmd/hook-generator)
![Category](https://img.shields.io/badge/category-Marketing-blue)
![Works with](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Cline%20%7C%20Cursor%20%7C%20Codex-8A2BE2)

[Install](#-install) · [Usage](#-usage) · [How it works](skills/hook-generator/SKILL.md) · [All skills](https://github.com/milad-ahmd/agent-skills)

</div>

> Part of **[agent-skills](https://github.com/milad-ahmd/agent-skills)**, a growing collection of practical skills for AI coding agents.

## 📦 Install

**One command (installs the whole collection):**

```bash
curl -fsSL https://raw.githubusercontent.com/milad-ahmd/agent-skills/main/install.sh | bash -s -- hook-generator
```

**Manually (Claude Code):**

```bash
git clone https://github.com/milad-ahmd/hook-generator /tmp/hook-generator
mkdir -p ~/.claude/skills && cp -r /tmp/hook-generator/skills/hook-generator ~/.claude/skills/
```

**Per project:** copy `skills/hook-generator` into `<project>/.claude/skills/`.
**Any other agent:** paste [`SKILL.md`](skills/hook-generator/SKILL.md) into your rules or system prompt.

## 💬 Usage

Just ask your agent:

```text
Give me hooks for a video about X
Write 20 opening lines for this LinkedIn post
```

The full workflow, rules and output format are in [`SKILL.md`](skills/hook-generator/SKILL.md).

## 🧩 More skills

See the full collection: **[milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills)**.

## 🤝 Contributing

Issues and PRs are welcome, especially real-world before/after examples.

## 📄 License

[MIT](LICENSE) © Milad Ahmadi

<div align="center">

**If this skill saved you time, a ⭐ helps others find it.**

</div>
