# Anthracite Custom

A personal VS Code color theme, built to match the colors of [Bearded Theme's](https://github.com/BeardedBear/bearded-theme) **Anthracite** variant, with fixes for rendering issues in VS Code's newer UI.

## Why this exists

The original [Bearded Theme](https://marketplace.visualstudio.com/items?itemName=BeardedBear.beardedtheme) Anthracite theme has some rendering issues with VS Code's modern UI. This is a from-scratch theme using the same color palette, rebuilt with full coverage of current theme color keys (activity bar, command center, semantic tokens, bracket pair colors, etc.).

> **Note:** If parts of the UI (activity bar, status bar, title bar) still look transparent or ignore theme colors, that's very likely [a VS Code bug](https://github.com/microsoft/vscode/issues/326126) in "modern UI" (floating panels) mode, not this theme — VS Code forces those backgrounds transparent in that mode regardless of theme. Try disabling floating panels if you see this.

## Installation

**Manual (current setup):**

1. Copy this repo's `themes/` folder and `package.json` into a folder under `~/.vscode/extensions/`, e.g. `~/.vscode/extensions/anthracite-theme/`
2. Restart VS Code (a full quit, not just "Reload Window")
3. `Cmd+K Cmd+T` → select **Anthracite Custom**

## Palette

Colors sourced from Bearded Theme's build config ([`src/variations/classics.ts`](https://github.com/BeardedBear/bearded-theme/blob/master/src/variations/classics.ts)):

| Role | Color |
|---|---|
| Background | `#181a1f` |
| Sidebar / panel background | `#131519` |
| Border | `#0b0c0e` |
| Primary / accent | `#a2abb6` |
| Foreground | `#c8ccd4` |
| Comments / muted | `#515766` |
| Blue | `#3398DB` |
| Green | `#37ae6f` |
| Green (alt) | `#7E9E2D` |
| Orange | `#D26D32` |
| Pink | `#CC71BC` |
| Purple | `#935cd1` |
| Red | `#C13838` |
| Salmon | `#de456b` |
| Turquoise | `#24B5A8` |
| Yellow | `#c9a022` |

## Credit

Color palette derived from [Bearded Theme](https://github.com/BeardedBear/bearded-theme) by BeardedBear, licensed GPL-3.0. This theme is an independent rebuild of the Anthracite palette for personal use, not an official Bearded Theme release.

## License

GPL-3.0, in keeping with the source palette's license.
