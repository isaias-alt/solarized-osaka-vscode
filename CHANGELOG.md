# Changelog

## 0.1.2

Initial release.

- Dark variant **Solarized Osaka**
- Light variant **Solarized Osaka Light**
- Palette transcribed from `solarized-osaka.nvim` (`lua/solarized-osaka/colors.lua`)
- Workbench colors mapped from the Neovim `groups/editor.lua` highlight groups
- Token colors derived from `groups/syntax.lua`, `groups/treesitter.lua` and
  `groups/semantic_tokens.lua` rather than the repository's stale Sublime
  `.tmTheme` extras, which still carry markup from an unrelated theme
- Terminal ANSI palette follows Solarized conventions
- Extension ID is `solarized-osaka-vscode` because the Marketplace reserves
  extension names globally and `solarized-osaka` was already taken
