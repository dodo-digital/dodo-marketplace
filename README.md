# Dodo Digital Marketplace

Claude Code plugins by Dodo Digital.

## Installation

```bash
/plugin marketplace add dodo-digital/dodo-marketplace
```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| **create-hook** | Scaffold Claude Code hooks with templates, validation, and conflict analysis |
| **agent-pipelines** | Build, manage, and run autonomous agent workflows with stages, pipelines, and tmux sessions |

### Install a plugin

```bash
/plugin install create-hook
/plugin install agent-pipelines
```

## Adding More Plugins

To add a new plugin to this marketplace, add an entry to `.claude-plugin/marketplace.json`:

```json
{
  "name": "new-plugin",
  "description": "What it does",
  "version": "1.0.0",
  "source": {
    "source": "github",
    "repo": "dodo-digital/new-plugin-repo"
  }
}
```
