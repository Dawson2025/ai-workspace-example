---
resource_id: "c3e050aa-c9f5-4489-b338-c993fdba3269"
resource_type: "rule"
resource_name: "short-path-canonical"
---

# AI Workspace Example — Short-Path Canonical Pin

You are inside the **canonical** AI Workspace Example entity. This is NOT a launchpad/mirror; this IS the source of truth. Edits go here.

## Canonical (this directory)

```
/home/dawson/dawson-workspace/code/0_layer_universal/layer_1/layer_1_projects/short_ai_workspace_example/
```

UUID: `cf4d9dcb-a345-4e6f-8272-9a0b1d2c722f`

## Conceptual parent (also canonical, peer at the same shallow level)

```
/home/dawson/dawson-workspace/code/0_layer_universal/layer_1/layer_1_projects/short_ai_society/
```

UUID: `c2e6b731-cd7e-449c-9712-eff7f4e27c88`

This entity is a **sub-feature of AI Society** — pedagogically nested under AI Society's curriculum-gap teaching charter. Inherited rules cascade from AI Society (and from the school hierarchy via AI Society's own breadcrumb chain). See this entity's `0AGNOSTIC.md` "Inherited Rules" section.

## Deep-tree breadcrumb (navigation marker, NOT a write target)

```
/home/dawson/dawson-workspace/code/0_layer_universal/layer_1/layer_1_projects/layer_1_project_school/layer_1_project_school/layer_2/layer_2_sub_projects/layer_2_sub_project_academic_societies/layer_2_sub_project_academic_societies/layer_3/layer_3_subx2_projects/layer_3_subx2_project_ai_society_breadcrumb/layer_4/layer_4_subx3_features/layer_4_subx3_feature_ai_workspace_example_breadcrumb/breadcrumb_0AGNOSTIC.md
```

The breadcrumb is **nested inside the AI Society breadcrumb**. This makes the conceptual hierarchy visible to anyone browsing the deep school tree: `school → academic_societies → AI Society → AI Workspace Example`. Never edit the breadcrumb as if it were canonical.

## Architecture pattern: short-path canonical (experimental)

This entity uses the **short-path entity pattern**, sibling of `short_ai_society` and `short_sandbox_program`:

| Pattern | Source of truth | Mirror / pointer |
|---------|----------------|------------------|
| Launchpad (DS 460) | Deep nested path | Shallow mirror at `layer_1/layer_1_projects/launchpad_ds_460/` (read-only) |
| **Short-path (this entity)** | **Shallow path here** | **Deep breadcrumb under AI Society's breadcrumb in the school submodule** (read-only) |

## Repo / commit mechanics

- This canonical lives in the **root repo** (`0_layer_universal`). All canonical edits commit to the root repo.
- The deep-tree breadcrumb lives in the **school submodule** (`Dawson2025/1-school`). Breadcrumb refreshes commit to the school submodule first, then the root repo bumps the submodule pointer.
- Per the **Submodule Integrity Protocol** (root `0AGNOSTIC.md`): commit/push order is bottom-up — school submodule first, then root.

## Sibling tier reminder

This entity is the **basic / introductory tier**. Future siblings (`short_ai_workspace_example_intermediate`, `_advanced`) are planned but not yet built. When a sibling is created, it should also live at the shallow `layer_1/layer_1_projects/` path with its own peer breadcrumb under the AI Society breadcrumb. See this entity's `0AGNOSTIC.md` "Sibling Tiers" section.
