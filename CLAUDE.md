# Shared Repo Rules

This is the canonical shared repo for both Claude and Codex.

## Canonical Repo

- Local path: `C:\Users\oeroh\Documents\agent-command-center`
- Remote repo: `https://github.com/Edward577/-create_website-`

## Working Agreement

Both agents should work in this same repo.
Do not create a second repo for the same project.
Do not split work by making separate agent-owned repos.

## Role Split

- Claude: planning, strategy, issue framing, prioritization
- Codex: implementation, file edits, automation, dashboards

## Handoff Rules

1. Read the existing docs first.
2. Update the same files instead of creating duplicates.
3. Use GitHub issues, commits, and PRs as the handoff surface.
4. Keep all roadmap, monetization, and dashboard work in this repo.
5. Before acting, write or read the latest cross-platform sync update in `memory/agent-sync-log.md`.

## Priority

The primary goal is to use the agents to make one monetizable system work first.
Current best lane: ecommerce plus content around the home-product niche.

## Cross-Platform Operating Rule

ChatGPT and Codex are expected to stay synchronized through this GitHub repo. If the user pastes the same instruction into both tools, both tools should treat this repo as the shared state layer.

- ChatGPT: strategy, planning, coordination, analysis, reporting, monetization thinking.
- Codex: execution, implementation, setup, integrations, technical connection work, operational follow-through.
- Claude / Cloud Code: bounded delegated work and handoff reporting.

Each platform should update:
- recent completed work
- overnight or background work
- credit/cost usage noticed locally
- newly discovered agents, skills, connectors, and MCP servers
- system/config changes
- blockers and unfinished work
- next recommended action and owner

## graphify

This project has a graphify knowledge graph at graphify-out/.

Rules:
- Before answering architecture or codebase questions, read graphify-out/GRAPH_REPORT.md for god nodes and community structure
- If graphify-out/wiki/index.md exists, navigate it instead of reading raw files
- For cross-module "how does X relate to Y" questions, prefer `graphify query "<question>"`, `graphify path "<A>" "<B>"`, or `graphify explain "<concept>"` over grep — these traverse the graph's EXTRACTED + INFERRED edges instead of scanning files
- After modifying code files in this session, run `graphify update .` to keep the graph current (AST-only, no API cost)
