# APA 7 Reference by Icarus

Complete APA 7th edition citation and formatting skill for AI coding agents.

## Overview

This skill provides comprehensive APA 7th edition guidelines for:
- In-text citations (parenthetical & narrative)
- Reference list formatting
- Hanging indent setup
- DOI/URL rules
- Common reference types (journal, book, web, etc.)
- APA 6 → 7 changes
- Common errors and corrections

## Installation

### For Codex (this repo)

Codex automatically scans `~/.agents/skills/`. Simply clone:

```bash
git clone https://github.com/IcarusYe12138/apa7-reference-icarus.git ~/.agents/skills/apa7-reference-icarus
```

### For Other Agents

Symlink or copy to your agent's skill directory:

```bash
# Claude Code / Cursor / Grok / etc.
ln -s ~/.agents/skills/apa7-reference-icarus ~/.claude/skills/apa7-reference-icarus
```

## Usage

Trigger phrases:
- "APA citation"
- "reference format"
- "引用格式"
- "参考文献"
- "hanging indent"

The skill activates automatically when APA-related questions are detected.

## Features

| Feature | Coverage |
|---------|----------|
| In-text citations | All author counts, special cases |
| Reference list | Complete formatting rules |
| Reference types | 7+ types with examples |
| Formatting | Hanging indent, spacing, sorting |
| APA 6→7 | Key differences |
| Error checking | Common mistakes table |

## File Structure

```
apa7-reference-icarus/
├── SKILL.md          # Main skill file (required)
└── README.md         # This file
```

## Version

- **v1.0.0** (2026-11-21): Initial release

## Author

**Icarus Ye** ([@IcarusYe12138](https://github.com/IcarusYe12138))

## License

MIT License - feel free to use and modify.

## References

- [APA Style Guidelines](https://apastyle.apa.org/style-grammar-guidelines)
- [Academic Writer](https://academicwriter.apa.org/)
