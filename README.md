# Seiraiyu Marketplace

A Claude Code plugin marketplace for skills, workflows, and productivity tools.

## Installation

### Claude Code

1. Add the marketplace:
   ```bash
   /plugin marketplace add stonelyd/seiraiyu-marketplace
   ```

2. Install plugins:
   ```bash
   /plugin install seiraiyu-skills@seiraiyu-marketplace
   ```

3. Verify installation:
   ```bash
   /help
   ```

## Available Plugins

### seiraiyu-skills (v1.0.0)

CodeRabbit PR review automation, MCP integration, and documentation skills.

**Skills included:**
- `respond-to-coderabbitai` - Automatically resolve PR review comments with atomic commits
- `mcp-client` - Universal MCP client for connecting to Zapier, GitHub, and any MCP server
- `sop-creator` - Create runbooks, playbooks, and technical documentation

## License

MIT
