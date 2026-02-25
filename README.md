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

### seiraiyu-skills (v1.2.0)

CodeRabbit PR review automation, Jira CLI, Confluence CLI, Neon CLI, and productivity skills.

**Skills included:**
- `respond-to-coderabbitai` - Automatically resolve PR review comments with atomic commits
- `jira` - Manage Jira issues, projects, and sprints from the CLI
- `confluence` - Read, create, update, search, and export Confluence pages from the CLI
- `neon` - Manage Neon serverless Postgres projects, branches, and databases
- `mcp-client` - Universal MCP client for connecting to Zapier, GitHub, and any MCP server
- `sop-creator` - Create runbooks, playbooks, and technical documentation

## License

MIT
