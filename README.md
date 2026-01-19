# Filament Claude Agents

Claude Code plugins for Filament PHP development. Improves clarity, consistency, and maintainability while preserving functionality.

## Installation

Install via the Claude Code plugin marketplace:

```bash
/plugin marketplace add optimacloud/filament-claude-agents
```

Then install the plugin you want:

```bash
/plugin marketplace install filament-simplifier
```

## Available Plugins

### filament-simplifier

A code refinement specialist for Filament resources, forms, tables, actions, and infolists. Focuses on:

- **Method chaining order** - Consistent ordering for better readability
- **Relationship handling** - Prefers `->relationship()` over manual options
- **Arrow functions** - Simplifies closures where appropriate
- **Filament v4 conventions** - Heroicon enums, layout components, proper imports
- **Action simplification** - Uses built-in features like `requiresConfirmation()`
- **Schema organization** - Groups related fields into logical sections

## Usage

The agent works automatically with Claude Code, refining recently modified Filament code for clarity and consistency while preserving all functionality.

## Requirements

- [Claude Code](https://claude.ai/claude-code)
- Filament v4

## License

MIT
