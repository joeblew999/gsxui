---
name: gsxui
description: Install and use gsxui — shadcn-style gsx components, copy-in, type-checked, server-rendered. Use when adding UI components to a gsx project or when asked about gsxui components, themes, or styling.
---

# gsxui

shadcn-style components for gsx: copy-in, type-checked, server-rendered. The
`gsxui` CLI copies component source into your project — you own the code.

## Commands

- `gsxui add <component>` — copy a component into your project
- `gsxui add --all` — copy every component
- `stylegen` — regenerate style sources (`stylegen --check` verifies without writing)

## Rules

- Components come from `gsxui add`, never hand-written.
- Compositions follow gsxui's own site.
- `ui/` is vendored by gsxui; hashes are tracked in `gsxui.json`.
- Invoke the `gsx` skill before editing any `.gsx`.
