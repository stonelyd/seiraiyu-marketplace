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

### seiraiyu-skills (v1.3.0)

CodeRabbit PR review automation, Jira CLI (acli), Neon CLI, and productivity skills.

**Skills included:**
- `respond-to-coderabbitai` - Automatically resolve PR review comments with atomic commits
- `jira` - Manage Jira issues, projects, sprints, and boards using the Atlassian CLI (acli)
- `neon` - Manage Neon serverless Postgres projects, branches, and databases
- `mcp-client` - Universal MCP client for connecting to Zapier, GitHub, and any MCP server
- `sop-creator` - Create runbooks, playbooks, and technical documentation

## License

MIT
