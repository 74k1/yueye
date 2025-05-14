# YuèYè 月夜 v0.0.1

YueYe is a high contrast, dark theme. It consists of 24 colors (tried to adopt Base24) and multiple themes that I created.

## Philosophy

Let's be blunt:

- This colorscheme and it's ports are **opinionated** — it reflects *my* preferences, and I won’t compromise on its core style.
  - **But!** You’re absolutely welcome to contribute:
    - Found a bug or inconsistency in my ports? Open a GitHub issue or submit a pull request!
    - Want to add your own port? Go for it! I’d love to see it!

And so; in my own opinion, the core rules should be:
- **Stay high-contrast and dark.** (Though *maybe* I'll cave and add a light mode <img src="https://user-images.githubusercontent.com/49000471/258223152-6c644f95-2fd7-4db3-b266-b387a95f150c.png" height="16px" width="16px"> <sub>as if...</sub>)
- **Stick to the palette below.**
  - If a theme *requires* flexibility (e.g., more colors), use Alpha values (with RGBA) instead.

## Palette

Inspired by [Base24](https://github.com/tinted-theming/base24/blob/main/styling.md), but with my own adjustments.


| Color | Name | HEX Value | Color Use | Usage |
| --- | --- | --- | --- | --- |
| ![#06040D](https://img.shields.io/badge/_-06040D?style=for-the-badge) | base00 | `#06040D` | Background | Default Background |
| ![#161223](https://img.shields.io/badge/_-161223?style=for-the-badge) | base01 | `#161223` | Black | Lighter Background |
| ![#251F38](https://img.shields.io/badge/_-251F38?style=for-the-badge) | base02 | `#251F38` | Bright Black | Selection Background |
| ![#352D4E](https://img.shields.io/badge/_-352D4E?style=for-the-badge) | base03 | `#352D4E` | Grey | Comments, Invisibles |
| ![#443A63](https://img.shields.io/badge/_-443A63?style=for-the-badge) | base04 | `#443A63` | Light Grey | Dark Foreground |
| ![#E1E1ED](https://img.shields.io/badge/_-E1E1ED?style=for-the-badge) | base05 | `#E1E1ED` | Foreground | Default Foreground 
| ![#C8C3D9](https://img.shields.io/badge/_-C8C3D9?style=for-the-badge) | base06 | `#C8C3D9` | White | Light Foreground |
| ![#D8D1E6](https://img.shields.io/badge/_-D8D1E6?style=for-the-badge) | base07 | `#D8D1E6` | Bright White | Light Background |
| ![#FF5487](https://img.shields.io/badge/_-FF5487?style=for-the-badge) | base08 | `#FF5487` | Red | Classes, Types |
| ![#54FF80](https://img.shields.io/badge/_-54FF80?style=for-the-badge) | base09 | `#54FF80` | Green | Commands, Operations |
| ![#FFE375](https://img.shields.io/badge/_-FFE375?style=for-the-badge) | base0A | `#FFE375` | Yellow | Properties, Fields |
| ![#816BFF](https://img.shields.io/badge/_-816BFF?style=for-the-badge) | base0B | `#816BFF` | Indigo | Strings, Content |
| ![#4CCEFE](https://img.shields.io/badge/_-4CCEFE?style=for-the-badge) | base0C | `#4CCEFE` | Cyan | Functions, Methods |
| ![#6682FF](https://img.shields.io/badge/_-6682FF?style=for-the-badge) | base0D | `#6682FF` | Blue | Keywords, Important UI |
| ![#EB6AFF](https://img.shields.io/badge/_-EB6AFF?style=for-the-badge) | base0E | `#EB6AFF` | Magenta | Special syntax |
| ![#4CCEFE](https://img.shields.io/badge/_-4CCEFE?style=for-the-badge) | base0F | `#4CCEFE` | Cyan Alt | Folders, Navigation |
| ![#08060E](https://img.shields.io/badge/_-08060E?style=for-the-badge) | base10 | `#08060E` | Darker Black | Darker Background |
| ![#050307](https://img.shields.io/badge/_-050307?style=for-the-badge) | base11 | `#050307` | Darkest Black | Darkest Background |
| ![#FF6593](https://img.shields.io/badge/_-FF6593?style=for-the-badge) | base12 | `#FF6593` | Bright Red | Brighter Red |
| ![#77FF9A](https://img.shields.io/badge/_-77FF9A?style=for-the-badge) | base13 | `#77FF9A` | Bright Green | Brighter Green |
| ![#FFE188](https://img.shields.io/badge/_-FFE188?style=for-the-badge) | base14 | `#FFE188` | Bright Yellow | Brighter Yellow |
| ![#8399FF](https://img.shields.io/badge/_-8399FF?style=for-the-badge) | base15 | `#8399FF` | Bright Blue | Brighter Blue |
| ![#F08EFF](https://img.shields.io/badge/_-F08EFF?style=for-the-badge) | base16 | `#F08EFF` | Bright Magenta | Brighter Magenta |
| ![#74D9FE](https://img.shields.io/badge/_-74D9FE?style=for-the-badge) | base17 | `#74D9FE` | Bright Cyan | Brighter Cyan |

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

| Application / Tool | Repository |
| --- | --- |
| [Neovim](https://github.com/neovim/neovim) | [74k1/yueye.nvim](https://github.com/74k1/yueye.nvim) |
| [Kagi Search](https://kagi.com/) | [74k1/yueye.kagi.css](https://github.com/74k1/yueye.kagi.css) |

## Contributing

I've mentioned it like twice now. Here goes a third time: PLEASE CONTRIBUTE!
Open Source thrives on collaboration!

- Made a port? Show me! Submit a PR! I *want* to see it.
- Found an issue? Tell me! No gatekeeping here.

Thanks a ton, Tim
