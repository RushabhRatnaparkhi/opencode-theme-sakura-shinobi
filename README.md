# Sakura Shinobi for OpenCode

A custom OpenCode theme blending vivid pink highlights with deep violet panels.

## Install

Copy `sakura-shinobi.json` into your OpenCode themes directory:

```bash
mkdir -p ~/.config/opencode/themes
cp sakura-shinobi.json ~/.config/opencode/themes/sakura-shinobi.json
```

Then set it in your TUI config:

```json
{
  "$schema": "https://opencode.ai/tui.json",
  "theme": "sakura-shinobi"
}
```

Restart OpenCode to apply the theme.

## Project-local install

You can also install it per-project:

```bash
mkdir -p .opencode/themes
cp sakura-shinobi.json .opencode/themes/sakura-shinobi.json
```

## Theme identity

- Name: `sakura-shinobi`
- Style: purple and pink primary palette
- Format: OpenCode `theme.json` schema
