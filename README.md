# Filament Claude Agents

Claude Code agents for simplifying and refining Filament PHP code. Improves clarity, consistency, and maintainability while preserving functionality.

## Available Agents

### filament-simplifier

A code refinement specialist for Filament resources, forms, tables, actions, and infolists. Focuses on:

- **Method chaining order** - Consistent ordering for better readability
- **Relationship handling** - Prefers `->relationship()` over manual options
- **Arrow functions** - Simplifies closures where appropriate
- **Filament v4 conventions** - Heroicon enums, layout components, proper imports
- **Action simplification** - Uses built-in features like `requiresConfirmation()`
- **Schema organization** - Groups related fields into logical sections

## Installation

Copy the agent file to your project's `.claude/agents/` directory:

```bash
mkdir -p .claude/agents
cp agents/filament-simplifier.md .claude/agents/
```

Or add as a git submodule:

```bash
git submodule add git@github.com:optimacloud/filament-claude-agents.git .claude/filament-agents
```

## Usage

The agent works automatically with Claude Code, refining recently modified Filament code for clarity and consistency while preserving all functionality.

## Requirements

- [Claude Code](https://claude.ai/claude-code)
- Filament v4

## License

MIT
