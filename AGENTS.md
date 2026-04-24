# Shared Agent Instructions

This repo is shared by multiple coding agents.

## Source Of Truth

- Local repo: `C:\Users\oeroh\Documents\agent-command-center`
- GitHub repo: `Edward577/-create_website-`

## Rules

1. Work in this repo only for this project.
2. Reuse existing docs before adding new top-level files.
3. Keep visuals in `docs/`.
4. Keep scripts in `scripts/`.
5. Use the same roadmap and dashboard instead of branching the project into duplicates.
6. Before strategy or execution work, sync recent ChatGPT/Codex/Claude updates into this repo so both sides share the same state.

## Agent Roles

- ChatGPT owns strategy, planning, coordination, analysis, reporting, and monetization thinking.
- Codex owns execution, implementation, setup, integrations, technical connection work, and operational follow-through.
- Claude / Cloud Code handles bounded delegated repo or platform tasks and reports back through shared handoff files.
- All agents read and write the same repo.

## Current Mission

Centralize the user's ideas, monetization plan, visuals, and execution system in one shared GitHub repo.

## Cross-Platform Sync Rule

The user may paste the same instruction into ChatGPT and Codex. Treat that as a request for both sides to sync through this GitHub repo, not through memory alone.

Required sync fields:
- recent work completed
- work completed while the user was away
- credit or cost usage noticed locally
- newly discovered agents, skills, connectors, or MCP servers
- system/config changes
- opportunities discovered
- unfinished work and blockers
- next owner and next action

Primary files:
- `memory/agent-sync-log.md`
- `memory/project-memory.md`
- `docs/agent-inventory.md`
- `docs/monetization-roadmap.md`
- `docs/hermes-cross-platform-report.md`

## graphify

This project has a graphify knowledge graph at graphify-out/.

Rules:
- Before answering architecture or codebase questions, read graphify-out/GRAPH_REPORT.md for god nodes and community structure
- If graphify-out/wiki/index.md exists, navigate it instead of reading raw files
- For cross-module "how does X relate to Y" questions, prefer `graphify query "<question>"`, `graphify path "<A>" "<B>"`, or `graphify explain "<concept>"` over grep — these traverse the graph's EXTRACTED + INFERRED edges instead of scanning files
- After modifying code files in this session, run `graphify update .` to keep the graph current (AST-only, no API cost)
