---
name: skills
description: >-
  Collection of AI agent skills for various tasks including
  MicroPython development for embedded systems.
---

# Skills

This repository contains AI agent skills that can be fetched with `npx skills`.

## Skills

| Skill | Description |
|-------|-------------|
| [micropython-skills](skills/micropython-skills/SKILL.md) | Program and interact with embedded development boards (ESP32, ESP8266, Raspberry Pi Pico, etc.) through MicroPython REPL |

## Installation

```bash
# Install all skills to OpenCode
npx skills add benkoben/skills

# Install specific skill by name
npx skills add benkoben/skills --skill micropython-skills -a opencode -y

# Install to specific agents
npx skills add benkoben/skills -a opencode -a claude-code
```

## Available Agents

- opencode: `.agents/skills/`
- claude-code: `.claude/skills/`
- cursor: `.agents/skills/`
- More agents supported via `npx skills`