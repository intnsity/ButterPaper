# Butter Paper v2
A CSS theme library plus a single-file HTML demo. One palette contract, three
official modes: **Butter Paper** (light), **Southwest Night** (juniper graphite,
desert bloom), **Nordic Night** (stone, snow, ember orange, cabin red).

- `butter-paper-v2.css` — theme tokens plus restrained `bp-*` layout primitives.
- `Butter-Paper-v2.html` — demo and photo/color library: switch themes, inspect
  tokens, copy one theme's CSS.
```html
<link rel="stylesheet" href="butter-paper-v2.css">
<html data-theme="paper">  <!-- paper | desert | nordic -->
```

Style with semantic roles, not hard-coded colors: `var(--bp-panel)`, `var(--bp-text)`,
`var(--bp-accent)`, `var(--bp-warning)`. Primitives: `.bp-app`, `.bp-sidebar`,
`.bp-panel`, `.bp-btn`, `.bp-btn-secondary`, `.bp-input`, `.bp-table`, `.bp-badge`,
`.bp-status-ok|warn|critical`. Each theme also defines legacy `--t-*` aliases; the demo
remembers the active theme in `localStorage` (`butter-paper-v2-theme`).

Apache License 2.0 · https://github.com/intnsity/ButterPaper
