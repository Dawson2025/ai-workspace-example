# AI Workspace Example

A teaching catalog for **coding-agent harness configuration** — how to configure and customize within existing coding agents (Claude Code, Codex, Cursor, Gemini CLI) without building your own agent, routing layer, or system prompts from scratch.

## What this teaches

Configuration and customization *within the surface area that stock coding agents already provide*:

- Settings files and per-tool config
- Hooks (pre/post-tool, on-prompt, on-stop)
- Skills, slash commands, and subagents
- MCP servers
- Agent / agent-definition formats
- Rules and memory systems
- Status lines, keybindings, IDE integrations

**Not in scope** (covered by planned future tiers): building your own agent loop, training models, custom routing/orchestration outside what coding agents already offer.

## Who this is for

Anyone learning to set up an AI coding workspace — students, early-career engineers, anyone touching coding agents who wants to skip the "build the routing layer first" trap.

## Repository structure

This repository follows an entity-system pattern:

| Path | Purpose |
|------|---------|
| `0AGNOSTIC.md` | Source of truth for entity identity, scope, rules |
| `.0agnostic/` | On-demand resources (knowledge, rules, protocols, episodic memory) |
| `CLAUDE.md`, `AGENTS.md`, `GEMINI.md`, `CURSOR_AGENT.md` | Auto-generated tool-specific context files — do not edit directly |
| `.claude/`, `.cursor/`, `.github/` | Tool-specific configuration |

Edit `0AGNOSTIC.md`; tool-specific files regenerate via `agnostic-sync.sh` (upstream tooling).

## Status

Newly scaffolded — content (worked examples, per-agent reference docs) will be added over time.

## License

[PolyForm Noncommercial License 1.0.0](LICENSE.md) — source-available, free for non-commercial use.

| Use case | OK? |
|---|---|
| Personal study, hobby projects | Yes |
| Educational institutions, public research, non-profits, government | Yes |
| Internal use at a for-profit company | No — requires permission |
| Building a commercial product on top | No — requires permission |
| Republishing as your own | No |
| Using as training data for AI models | No — requires permission |

**Required Notice** (must be preserved in any redistribution):

> Required Notice: Copyright (c) 2026 Dawson

For commercial licensing, contact the copyright holder.

## Attribution

If you build on this work in any context where attribution is appropriate, please credit:

> Based on the AI Workspace Example by Dawson (https://github.com/Dawson2025/ai-workspace-example)
