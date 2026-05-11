---
resource_id: "166fb83d-6fc7-4eb9-bc09-0d671eb65850"
resource_type: "agnostic_document"
resource_name: "0AGNOSTIC"
short_path_canonical: true
deep_breadcrumb_path: "layer_1/layer_1_projects/layer_1_project_school/layer_1_project_school/layer_2/layer_2_sub_projects/layer_2_sub_project_academic_societies/layer_2_sub_project_academic_societies/layer_3/layer_3_subx2_projects/layer_3_subx2_project_ai_society_breadcrumb/layer_4/layer_4_subx3_features/layer_4_subx3_feature_ai_workspace_example_breadcrumb"
---

# AI Workspace Example

## Identity

entity_id: "cf4d9dcb-a345-4e6f-8272-9a0b1d2c722f"

You are an agent at the **AI Workspace Example** entity — a teaching artifact for **coding-agent harness configuration**.

- **Role**: Worked example + catalog teaching how to configure and customize within existing coding-agent harnesses (Claude Code, Codex, Cursor, Gemini CLI) — without building your own agent, routing layer, or system prompts from scratch
- **Scope**: Configuration, customization, and harness engineering *within the surface area that stock coding agents already provide* (settings, hooks, skills, slash commands, MCP servers, agent definitions, rules, memory, status lines, keybindings, IDE integrations)
- **Not in scope (yet)**: Building your own agent loop, training your own model, custom routing/orchestration code that lives outside what coding agents offer. Those belong to future difficulty-tier siblings (see "Sibling Tiers" below)
- **Audience**: Anyone learning to set up an AI coding workspace — primarily AI Society members, but broadly applicable to anyone touching coding agents
- **Architecture**: This is a **short-path canonical entity** (experimental pattern, sibling of `short_ai_society` / `short_sandbox_program`). Canonical content lives at this shallow path; a navigation breadcrumb lives nested **inside the AI Society breadcrumb** in the deep school hierarchy at `.../layer_3_subx2_project_ai_society_breadcrumb/layer_4/layer_4_subx3_features/layer_4_subx3_feature_ai_workspace_example_breadcrumb/breadcrumb_0AGNOSTIC.md`, marking this entity as a conceptual sub-feature of AI Society.

## Conceptual Parent

This entity is a **sub-feature of the AI Society entity** (UUID `c2e6b731-cd7e-449c-9712-eff7f4e27c88`, canonical at `layer_1/layer_1_projects/short_ai_society/`). Pedagogically it lives under AI Society's "teach members how to build AI systems" charter — specifically the curriculum-gap thesis that BYUI's classes cover model-building well but cover *systems and harnesses around models* less well. This entity is one of the things that helps fill that gap.

## Inherited Rules (MANDATORY — from parent entities)

These cascade from AI Society and the school hierarchy via the deep-tree breadcrumb chain. Read the parent entity's `0AGNOSTIC.md` for the full rule sets.

**From AI Society (conceptual parent, `c2e6b731-cd7e-449c-9712-eff7f4e27c88`):**

| Rule | When |
|------|------|
| Curriculum-gap framing | When explaining *why* this entity exists — frame it as filling the systems-and-harnesses-around-models gap, not as a substitute for ML model coursework |
| Audience-first defaults | Examples and walkthroughs default to the audience that AI Society serves (mixed majors, mixed experience levels) — assume no prior agent-internals knowledge unless an example explicitly says otherwise |

**From School L1 (transitively, via AI Society):**

| Rule | When |
|------|------|
| Human-Only Submission / Send | If this entity ever generates content that gets posted publicly (Discord, blog, repo README) — humans send, not agents |
| Informal Citation | When citing tools, docs, or people in any teaching artifact here |

**Entity-specific (this entity)**: TBD as content is added. Will be tracked in `.0agnostic/02_rules/` once concrete patterns emerge from the first few worked examples.

## Child Features

This entity has child features that extend its teaching scope. Child features inherit the parent's rules and can be discovered via the deep-tree breadcrumb chain.

| Feature | UUID | Purpose |
|---------|------|---------|
| AI Portfolio Helper | `ada4ecf2-3202-4a30-a896-3d85d7f46be0` | Portfolio project discovery, skill-building alignment, implementation trade-offs. Helps learners determine what to build with their harness and how projects map to learnable skills. Canonical at `layer_1/layer_1_projects/short_ai_portfolio_helper/` |

## Sibling Tiers (planned)

This entity is the **basic / introductory tier** of a planned series of difficulty-tier sibling entities under AI Society. Each tier covers progressively deeper harness engineering. None of the siblings exist yet — this entity is the seed.

| Tier | Likely slug | Scope |
|------|-------------|-------|
| **Basic (this entity)** | `short_ai_workspace_example` | Configuration *within* existing coding-agent harnesses — settings, hooks, skills, slash commands, MCP servers, agent definitions, rules, memory, keybindings |
| Intermediate (planned) | `short_ai_workspace_example_intermediate` | Customizations that stretch the harness — non-trivial MCP servers, multi-agent coordination via the SDK, custom subagents that wrap external tools, plugin authoring |
| Advanced (planned) | `short_ai_workspace_example_advanced` | Harness engineering *outside* what stock coding agents offer — your own agent loop, your own routing/orchestration, your own system prompts, your own context management |

The siblings are **not yet built**; the table is a roadmap. When a sibling is created, it should follow the same short-path canonical pattern (with a peer breadcrumb under AI Society's breadcrumb) and add a row pointing back here as the previous-tier reference.

## Triggers

| Trigger | Action |
|---------|--------|
| User mentions "AI workspace example", "harness configuration teaching", "how to set up Claude Code / Codex / Cursor / Gemini CLI" — or asks how to teach someone coding-agent harness configuration | Load this 0AGNOSTIC.md |
| User asks for a worked example of a specific coding agent's customization surface (settings.json, hooks, skills, MCP, etc.) | Load this 0AGNOSTIC.md, then check `.0agnostic/01_knowledge/examples/` for an existing worked example before authoring a new one |
| User wants to add a new worked example or catalog entry | Load this 0AGNOSTIC.md + check `.0agnostic/01_knowledge/examples/` to avoid duplication |
| User wants to spin up an intermediate / advanced sibling tier | Load this 0AGNOSTIC.md (read "Sibling Tiers" above) + the short-path canonical pattern doc at `.0agnostic/01_knowledge/entity_lifecycle/short_path_launchpad_breadcrumb_patterns.md` (root repo) |
| Resuming work / new session | Load `.0agnostic/05_handoff_documents/` for latest handoff, then `.0agnostic/04_episodic_memory/` |

## Navigation

| Direction | Path |
|-----------|------|
| Conceptual parent (canonical) | `layer_1/layer_1_projects/short_ai_society/` (UUID `c2e6b731-cd7e-449c-9712-eff7f4e27c88`) |
| Deep-tree breadcrumb (where this entity appears in the school hierarchy, nested under AI Society's breadcrumb) | `layer_1/layer_1_projects/layer_1_project_school/.../layer_3_subx2_project_ai_society_breadcrumb/layer_4/layer_4_subx3_features/layer_4_subx3_feature_ai_workspace_example_breadcrumb/breadcrumb_0AGNOSTIC.md` (lives in the school submodule) |
| Conceptual grandparent | School L1 → Academic Societies L2 → AI Society (the deep-tree breadcrumb chain) |
| Future siblings (planned, not yet built) | `short_ai_workspace_example_intermediate`, `short_ai_workspace_example_advanced` (will sit at `layer_1/layer_1_projects/`) |

## .0agnostic/ Resources

This entity is freshly created and starts empty. Resources will be added as the first worked examples are written.

| Resource | Purpose | When to Read |
|----------|---------|--------------|
| `.0agnostic/01_knowledge/examples/` | (planned) One file per worked example of coding-agent harness configuration — stock agent X, customization Y, what was done, why, what to copy | When looking for an existing example, or before adding a new one |
| `.0agnostic/01_knowledge/agents/` | (planned) Per-coding-agent reference — the customization surface of Claude Code, Codex, Cursor, Gemini CLI | When orienting a learner to which knobs a specific agent exposes |
| `.0agnostic/02_rules/` | (planned) Entity-specific rules — e.g., "every example must show the before-and-after, not just the after" | TBD as patterns emerge |
| `.0agnostic/05_handoff_documents/` | Cross-session handoffs as the entity grows | Resuming work or onboarding a new contributor |

## Current Status

**Just created (2026-05-07)**. No worked examples yet. The entity exists as a placeholder for future teaching artifacts on coding-agent harness configuration. First content priorities (suggestion, not committed):

1. A worked example using **this very repo's own setup** (the `0_layer_universal` workspace with `.0agnostic/`, agnostic-sync, hierarchical triggers) as the reference example for what a non-trivial Claude Code workspace looks like — meta but useful
2. Per-agent reference notes for Claude Code, Codex, Cursor, Gemini CLI — what each agent's customization surface actually contains, with links to official docs
3. A "you don't need to build your own agent" framing doc that explicitly enumerates what stock coding agents already give you, so learners know where the line is between configuration (this tier) and harness engineering (later tiers)

---

*This is the source of truth for the AI Workspace Example entity. Tool-specific files (CLAUDE.md, GEMINI.md, AGENTS.md) are generated from this.*

*Architecture note: this entity uses the **short-path canonical** experimental pattern (sibling of `short_ai_society` / `short_sandbox_program`). Edits go HERE, at the shallow path. The deep-tree breadcrumb (nested inside the AI Society breadcrumb) is a navigation marker, not a source.*
