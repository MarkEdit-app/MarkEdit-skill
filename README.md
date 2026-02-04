# MarkEdit Skill

An [AI skill](https://agentskills.io) for managing [MarkEdit](https://github.com/MarkEdit-app/MarkEdit), a free and open-source markdown editor for macOS.

## Features

- Install, upgrade, list, and remove extensions
- Configure advanced settings via `settings.json`
- Upgrade MarkEdit app
- Answer questions using official documentation

## Example Commands

```
Upgrade MarkEdit
Install MarkEdit Preview extension
List installed extensions
Enable autoSaveWhenIdle in MarkEdit
```

## Installation

### GitHub Copilot (VS Code)

```sh
mkdir -p ~/.copilot/skills/markedit
curl -fsSL "https://github.com/MarkEdit-app/MarkEdit-skill/blob/main/markedit/SKILL.md?raw=true" -o ~/.copilot/skills/markedit/SKILL.md
```

### Claude Code

```sh
mkdir -p ~/.claude/skills/markedit
curl -fsSL "https://github.com/MarkEdit-app/MarkEdit-skill/blob/main/markedit/SKILL.md?raw=true" -o ~/.claude/skills/markedit/SKILL.md
```

### Cursor / Windsurf / Others

- **Cursor**: Place [SKILL.md](https://github.com/MarkEdit-app/MarkEdit-skill/blob/main/markedit/SKILL.md) in `.cursor/rules/` directory
- **Windsurf**: Place [SKILL.md](https://github.com/MarkEdit-app/MarkEdit-skill/blob/main/markedit/SKILL.md) in `.windsurf/rules/` directory
- **Others**: Copy contents to your custom instructions or system prompt

## Requirements

- macOS with [MarkEdit](https://github.com/MarkEdit-app/MarkEdit) installed
- An AI assistant that supports custom instructions

## Related Links

- [MarkEdit](https://github.com/MarkEdit-app/MarkEdit)
- [MarkEdit Wiki](https://github.com/MarkEdit-app/MarkEdit/wiki)
- [Extensions List](https://github.com/MarkEdit-app/MarkEdit/wiki/Extensions)
