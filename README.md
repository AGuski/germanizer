# germanizer

A skill for Claude Code and OpenCode that improves any text by making it more German.

Based on [humanizer](https://github.com/blader/humanizer) by blader.

## Installation

### Claude Code

Clone directly into Claude Code's skills directory:

```bash
mkdir -p ~/.claude/skills
git clone https://github.com/AGuski/germanizer.git ~/.claude/skills/germanizer
```

Or copy the skill file manually if you already have this repo cloned:

```bash
mkdir -p ~/.claude/skills/germanizer
cp SKILL.md ~/.claude/skills/germanizer/
```

### OpenCode

Clone directly into OpenCode's skills directory:

```bash
mkdir -p ~/.config/opencode/skills
git clone https://github.com/AGuski/germanizer.git ~/.config/opencode/skills/germanizer
```

Or copy the skill file manually if you already have this repo cloned:

```bash
mkdir -p ~/.config/opencode/skills/germanizer
cp SKILL.md ~/.config/opencode/skills/germanizer/
```

> **Note:** OpenCode also scans `~/.claude/skills/` for compatibility, so a single clone into `~/.claude/skills/germanizer/` works for both tools.

## Usage

### Claude Code

```
/germanizer

[paste your text here]
```

### OpenCode

```
/germanizer

[paste your text here]
```

Or ask the model to germanize text directly in either tool:

```
Please germanize this text: [your text]
```
