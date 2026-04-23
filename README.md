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

### superwisdom-db (v0.1.0)

DB-backed variants of the superwisdom skills. Persists brainstorm and plan artifacts in Postgres (Subaya platform schema: `documents`, `initiatives`, `work_items`, `design_reviews`, `review_*`) instead of writing `docs/plans/*.md` files. Pairs with a spec-ui review surface that provides section-level approve/reject, line-anchored comments with resolve/edit/delete, and round-aware revision snapshots.

**Skills included:**
- `brainstorm-db` - Interview → design document + initiative upsert (DB-backed)
- `plan-db` - Plan document + work_items (epics/stories/tasks) population; requires approved design
- `execute-db` - Walk plan tasks, update work_items; requires approved plan
- `review-db` - Agent-side review; writes `review_comments` with `author_type='agent'`
- `debug-db` - Investigate failing work_item, fix code, update `test_status` + notes
- `tdd-db` - Red-green-refactor with `test_location` and `test_status` updates

**Requires:** `psql` client, authenticated `neon` CLI (`neon cs` returns a valid connection string), and `jq`.

**Install:**
```bash
/plugin install superwisdom-db@seiraiyu-marketplace
```

## License

MIT
