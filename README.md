# Solarized Osaka for Visual Studio Code

A Visual Studio Code port of [**solarized-osaka.nvim**](https://github.com/craftzdog/solarized-osaka.nvim)
— a clean, elegant take on Ethan Schoonover's Solarized palette.

![Solarized Osaka](https://raw.githubusercontent.com/isaias-alt/solarized-osaka-vscode/main/icon.png)

## Variants

| Variant | `uiTheme` |
| --- | --- |
| **Solarized Osaka** | dark |
| **Solarized Osaka Light** | light |

## Install

From the Marketplace: search for **Solarized Osaka** in the Extensions view.

From a `.vsix` file:

```bash
code --install-extension solarized-osaka-0.1.0.vsix
```

Then: `Ctrl/Cmd + K` → `Ctrl/Cmd + T` → pick **Solarized Osaka**.

## Credits

This theme is a port. **All of the color work belongs to the original author.**

- **Original project:** [solarized-osaka.nvim](https://github.com/craftzdog/solarized-osaka.nvim)
- **Author:** Takuya Matsuyama ([craftzdog](https://github.com/craftzdog))
- **YouTube:** [@devaslife](https://www.youtube.com/@devaslife)

The palette is transcribed from the Neovim implementation
(`lua/solarized-osaka/colors.lua`) so the hex values match the original exactly.
Solarized itself was designed by [Ethan Schoonover](https://ethanschoonover.com/solarized/).

If you like this theme, go star the original repository and subscribe to the channel.
This port exists because that work is worth porting.

## What was adapted

- Neovim highlight groups → VS Code workbench colors (`colors`)
- Treesitter captures → TextMate scopes (`tokenColors`) and `semanticTokenColors`
- Terminal ANSI colors follow the Solarized convention

Known deviation: the upstream light variant uses a very low contrast gray for
comments on a cream background. This port uses a darker gray (`#576d74`) for
legibility in the light variant. Everything else follows the upstream palette.

## License

Apache License 2.0 — see [LICENSE](LICENSE) and [NOTICE](NOTICE).
