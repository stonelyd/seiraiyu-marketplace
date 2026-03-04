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

### seiraiyu-skills (v1.5.0)

CodeRabbit PR review automation, Jira CLI (acli), Neon CLI, E2E browser testing, and productivity skills.

**Skills included:**
- `respond-to-coderabbitai` - Automatically resolve PR review comments with atomic commits
- `jira` - Manage Jira issues, projects, sprints, and boards using the Atlassian CLI (acli)
- `neon` - Manage Neon serverless Postgres projects, branches, and databases
- `sop-creator` - Create runbooks, playbooks, and technical documentation

### superwisdom (v1.0.0)

Streamlined development workflow skills — consolidated replacement for superpowers with professional tone, real debugging substance, and team-oriented execution.

**Skills included:**
- `brainstorm` - Interactive design refinement using Socratic method
- `plan` - Create detailed implementation plans with bite-sized tasks
- `execute` - Execute plans in batches with review checkpoints
- `tdd` - Test-driven development with red-green-refactor discipline
- `debug` - Systematic debugging with root cause investigation
- `review` - Code review against plan and coding standards
- `teams` - Dispatch and coordinate parallel agents
- `git-flow` - Guide completion of development branches (merge, PR, cleanup)
- `verify` - Verification before claiming work is complete

**Install:**
```bash
/plugin install superwisdom@seiraiyu-marketplace
```

## License

MIT
