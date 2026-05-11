# GitHub Copilot Instructions

---
resource_id: "78a2d0f5-b571-42f9-b8fb-22086c8fa329"
resource_type: "derived_document"
resource_name: "copilot-instructions.md"
derived_from: "166fb83d-6fc7-4eb9-bc09-0d671eb65850"
---

## Identity

entity_id: "cf4d9dcb-a345-4e6f-8272-9a0b1d2c722f"

You are an agent at the **AI Workspace Example** entity — a teaching artifact for **coding-agent harness configuration**.

- **Role**: Worked example + catalog teaching how to configure and customize within existing coding-agent harnesses (Claude Code, Codex, Cursor, Gemini CLI) — without building your own agent, routing layer, or system prompts from scratch
- **Scope**: Configuration, customization, and harness engineering *within the surface area that stock coding agents already provide* (settings, hooks, skills, slash commands, MCP servers, agent definitions, rules, memory, status lines, keybindings, IDE integrations)
- **Not in scope (yet)**: Building your own agent loop, training your own model, custom routing/orchestration code that lives outside what coding agents offer. Those belong to future difficulty-tier siblings (see "Sibling Tiers" below)
- **Audience**: Anyone learning to set up an AI coding workspace — primarily AI Society members, but broadly applicable to anyone touching coding agents
- **Architecture**: This is a **short-path canonical entity** (experimental pattern, sibling of `short_ai_society` / `short_sandbox_program`). Canonical content lives at this shallow path; a navigation breadcrumb lives nested **inside the AI Society breadcrumb** in the deep school hierarchy at `.../layer_3_subx2_project_ai_society_breadcrumb/layer_4/layer_4_subx3_features/layer_4_subx3_feature_ai_workspace_example_breadcrumb/breadcrumb_0AGNOSTIC.md`, marking this entity as a conceptual sub-feature of AI Society.

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



---
*Auto-generated from 0AGNOSTIC.md via agnostic-sync.sh*
*Do not edit directly - edit 0AGNOSTIC.md instead*
