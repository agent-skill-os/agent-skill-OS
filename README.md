# AgentSkill OS - Open Knowledge Registry

Empowering AI Agents with expert-level specialized capabilities through an open-source distribution layer.

## 🚀 What is AgentSkill OS?

**AgentSkill OS** is an open-specification ecosystem designed to distribute high-performance behavior prompts and instruction sets. This repository serves as the **Official Knowledge Registry**, hosting the core skill library that follows the [agentskills.io](https://agentskills.io) specification.

## 📋 Consumption Guide

### For AI Agents
Skills in this registry are designed to be "mounted" by AI agents (like Claude, GPT, or local LLMs). Each skill resides in the `skills/` directory and contains a `SKILL.md` file with standardized YAML frontmatter.

### Installation Format
```markdown
---
name: <skill-name>
description: <purpose-of-skill>
---
<System Instructions>
```

## 🧠 Expert Skills Library

Our current registry includes expert capabilities for:
- **Core Engineering**: `coding`, `debugging`, `database`, `terminal`.
- **Strategic Operations**: `planning`, `memory`, `search`, `browser`.
- **Creative & Design**: `writing`, `ui`, `ux`, `vision`.

## 🌐 Discovery Platform
Explore, preview, and interact with these skills on our premium discovery dashboard:
**[agentskill-os.vercel.app](https://agentskill-os.vercel.app)**

## 🤝 Contributing
This is an open ecosystem! If you have developed an expert prompt that follows the specification, please submit a pull request or contribute to the [development hub](https://github.com/agent-skill-os/agentskill-os-dev).

---
Distributed by the [AgentSkill OS Team](https://x.com/rakibulism).
