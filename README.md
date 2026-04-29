# Hermes Agent — Add-ons & Skills Collection

A personal collection of skills, add-ons, and resources built for [Hermes Agent](https://github.com/NousResearch/hermes-agent) — the self-improving AI agent by Nous Research.

---

## What is Hermes Agent?

[Hermes Agent](https://github.com/NousResearch/hermes-agent) is an open-source, self-improving AI agent with a built-in learning loop. It creates skills from experience, improves them during use, builds a persistent model of who you are, and runs anywhere — from a $5 VPS to a GPU cluster.

Key features of Hermes Agent:
- **Skill system** — procedural memory that can be extended with custom skills
- **Multi-platform** — CLI, Telegram, Discord, Slack, WhatsApp, Signal
- **Any model** — OpenRouter, Nous Portal, OpenAI, NVIDIA NIM, and more
- **Self-improving** — autonomous skill creation after complex tasks
- **Scheduled automations** — built-in cron scheduler

> **Official docs:** [hermes-agent.nousresearch.com/docs](https://hermes-agent.nousresearch.com/docs/)

---

## About This Repository

This repository is a personal workspace for everything I build around Hermes Agent. Users are welcome to browse, download, and use any of the resources here in their own Hermes Agent setup.

Contents may include:

| Category | Description |
|---|---|
| **Skills** | Custom skills (`.md` files) that extend Hermes Agent's capabilities |
| **Descriptions** | System prompts, personality files, and SOUL.md templates |
| **Configurations** | Example config snippets and toolset definitions |
| **Guides** | Notes and how-tos for setting up or customising Hermes Agent |

---

## How to Use a Skill

1. Download the skill file (`.md`) you want.
2. Place it in your Hermes Agent skills directory:
   ```
   ~/.hermes/skills/
   ```
3. In Hermes Agent, call it with a slash command:
   ```
   /<skill-name>
   ```

For more details on the skill system, see the [Skills documentation](https://hermes-agent.nousresearch.com/docs/user-guide/features/skills).

---

## Repository Structure

```
/
├── skills/          # Custom Hermes Agent skills
├── descriptions/    # Personality and system prompt files
├── configs/         # Example configuration snippets
└── guides/          # Setup guides and notes
```

> Folders will be added as content is created.

---

## License

This project is licensed under the [Apache License 2.0](LICENSE).

---

## Related Links

- 🏠 [Hermes Agent — Official Repository](https://github.com/NousResearch/hermes-agent)
- 📖 [Hermes Agent Documentation](https://hermes-agent.nousresearch.com/docs/)
- 🌐 [agentskills.io — Open Skills Standard](https://agentskills.io)
- 💬 [Nous Research Discord](https://discord.gg/NousResearch)
