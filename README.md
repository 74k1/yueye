# YuèYè 月夜 v0.1.8

YueYe is a high contrast, dark base16 theme. It consists of 16 colors (duh) and multiple themes/ports that I (and hopefully soon, others) created.

## Philosophy

I'll be blunt:

- This colorscheme and it's ports are **opinionated** — it reflects *my* preferences, and I won’t compromise on its core style.
  - **But!** You’re absolutely welcome to contribute:
    - Found a bug or inconsistency in my ports? Open a GitHub issue or submit a pull request!
    - Want to add your own port? Go for it! I’d love to see it!

And so; in my own opinion, the core rules should be:
- **Stay high-contrast and dark.** (Though *maybe* I'll cave and add a light mode <img src="https://user-images.githubusercontent.com/49000471/258223152-6c644f95-2fd7-4db3-b266-b387a95f150c.png" height="16px" width="16px"> <sub>as if...</sub>)
- **Stick to the palette below.**
  - If a theme *requires* flexibility (e.g., more colors), use Alpha values (with RGBA) instead.

### Versioning

I bump the version once I change a color of the Palette below.

```
v0.1.8
 ╰─┼─┼─ Release Version / When I feel like I've perfected it (perhaps in 10+ years)
   ╰─┼─ Major Version / After the palette has changed enough (when I update all of my [ports](#ports))
     ╰─ Minor Version / Very small updates to the palette
```


## Palette

| Base | Color | Name | HEX Value | Usage |
| :--- | :--- | :--- | :--- | :--- |
| `base0F` | ![#FA75C1](https://img.shields.io/badge/_-FA75C1?style=for-the-badge) | Hóng 红 | `#FA75C1` | Deprecated, Properties, Fields, Removed |
| `base0E` | ![#D387F7](https://img.shields.io/badge/_-D387F7?style=for-the-badge) | Lǜ 绿   | `#D387F7` | Identifier, Method Calls, Special syntax |
| `base0D` | ![#7CCBFB](https://img.shields.io/badge/_-7CCBFB?style=for-the-badge) | Jú 橘   | `#7CCBFB` | Updated |
| `base0C` | ![#FFE88A](https://img.shields.io/badge/_-FFE88A?style=for-the-badge) | Lán 蓝  | `#FFE88A` | Support, Regular Expressions, Escape Characters |
| `base0B` | ![#6EF791](https://img.shields.io/badge/_-6EF791?style=for-the-badge) | Zǐ 紫   | `#6EF791` | Secondary Accent, Input elements, Strings, Added |
| `base0A` | ![#F95AB3](https://img.shields.io/badge/_-F95AB3?style=for-the-badge) | Qīng 青 | `#F95AB3` | Classes, Markup Bold, Search Text Background |
| `base09` | ![#6DBFF9](https://img.shields.io/badge/_-6DBFF9?style=for-the-badge) | Yàn 艳  | `#6DBFF9` | lighter variant |
| `base08` | ![#7B84FC](https://img.shields.io/badge/_-7B84FC?style=for-the-badge) | Cuì 翠  | `#7B84FC` | Main Accent, Display Accents / Symbols, Keywords, Types |
| `base07` | ![#BFBDCA](https://img.shields.io/badge/_-BFBDCA?style=for-the-badge) | Xuě 雪  | `#BFBDCA` | Light Background |
| `base06` | ![#FFFFFF](https://img.shields.io/badge/_-FFFFFF?style=for-the-badge) | Bái 白  | `#FFFFFF` | Light Foreground |
| `base05` | ![#EBE9F1](https://img.shields.io/badge/_-EBE9F1?style=for-the-badge) | Dàn 淡  | `#EBE9F1` | Default Foreground |
| `base04` | ![#72708E](https://img.shields.io/badge/_-72708E?style=for-the-badge) | Qīng 青 | `#72708E` | Dark Foreground |
| `base03` | ![#4C4B69](https://img.shields.io/badge/_-4C4B69?style=for-the-badge) | Huī 灰  | `#4C4B69` | Comments |
| `base02` | ![#323246](https://img.shields.io/badge/_-323246?style=for-the-badge) | Àn 暗   | `#323246` | Selection Background |
| `base01` | ![#1C1B28](https://img.shields.io/badge/_-1C1B28?style=for-the-badge) | Mò 墨   | `#1C1B28` | Lighter Background |
| `base00` | ![#07060B](https://img.shields.io/badge/_-07060B?style=for-the-badge) | Hēi 黑  | `#07060B` | Default Background |


## Naming Convention

- **Display Names**
  - Use YuèYè (with diacritics) or YueYe (ASCII-only) in interfaces.
  - Optional: Append 月夜 for stylistic contexts (e.g., documentation, logos).
  - *Avoid* lowercase-only variants (e.g., yueye) in visible text.

- **Files & URLs**
  - **Always** use `yueye` (lowercase, no diacritics or Hanzi).
  - *Examples:* `yueye.nvim`, `yueye-theme.json`.
  - *Why?* Prevents filesystem/URL issues and keeps tooling predictable.

- **Exceptions**
  - If a tool requires deviation (e.g., case-sensitive conflicts), document it in the project's NOTES.md.

## Showcase

TODO: add example images

## Ports

Contributions welcome! Here's what exists so far:

| Application / Tool | Repository | status |
| --- | --- | --- |
| [GTK](https://www.gtk.org/) | [74k1/yueye.gtk](https://github.com/74k1/yueye.gtk) | in progress |
| [Kagi Search](https://kagi.com/) | [74k1/yueye.kagi.css](https://github.com/74k1/yueye.kagi.css) | in progress |
| [Neovim](https://github.com/neovim/neovim) | [74k1/yueye.nvim](https://github.com/74k1/yueye.nvim) | in progress, but an older version exists (not satisfied yet) |
| [Nix](https://nixos.org/) | [74k1/yueye.nix](https://github.com/74k1/yueye.nix) | in progress |

## Contributing

I've mentioned it like twice now. Here goes a third time: PLEASE CONTRIBUTE!
Open Source thrives on collaboration!

- Made a port? Show me! Submit a PR! I *want* to see it.
- Found an issue? Tell me! No gatekeeping here.

Thanks a ton, Tim
