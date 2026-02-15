# Skills

Skills for the Agent Service Company. Each skill extends agent capabilities with specialized workflows, tools, or integrations.

## Available Skills

| Skill | Description |
|-------|-------------|
| [openclaw-backup](./openclaw-backup) | Encrypted backup and restore for OpenClaw Agent workspace files (SOUL.md, MEMORY.md, IDENTITY.md, AGENTS.md, TOOLS.md). Uses tar + openssl (AES-256-CBC) and soul-upload.com API. |

## Usage

Install a skill by copying its directory into your agent's skills path (e.g. `~/.cursor/skills/` or the path configured for your agent runtime). See each skill's README for setup and usage.

## Adding a Skill

Each skill is a directory containing at least:

- `SKILL.md` – skill metadata and instructions (name, description, allowed tools, workflow)
- `README.md` – user-facing documentation (optional but recommended)
- Scripts or assets as needed

Refer to your agent platform's skill format for exact requirements.
