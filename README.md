# YuèYè 月夜 v0.0.3

YueYe is a high contrast, dark theme. It consists of 22 colors and multiple themes/ports that I (and hopefully soon, others) created.

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
v0.0.3
 ╰─┼─┼─ Release Version / When I feel like I've perfected it (perhaps in 10+ years)
   ╰─┼─ Major Version / After the palette has changed enough (when I update all of my [ports](#ports))
     ╰─ Minor Version / Very small updates to the palette
```


## Palette

| Color | Name | HEX Value | Usage |
| --- | --- | --- | --- |
| ![#816BFF](https://img.shields.io/badge/_-816BFF?style=for-the-badge) | Jīn 金 | `#816BFF` | Main Accent, Display accents / symbols |
| ![#4CBF67](https://img.shields.io/badge/_-4CBF67?style=for-the-badge) | Yín 银 | `#4CBF67` | Secondary Accent, Input elements, Strings |
| ![#FF5487](https://img.shields.io/badge/_-FF5487?style=for-the-badge) | Hóng 红 | `#FF5487` | Properties, Fields, Important elements, Removed |
| ![#54FF80](https://img.shields.io/badge/_-54FF80?style=for-the-badge) | Lǜ 绿 | `#54FF80` | Added |
| ![#FFE375](https://img.shields.io/badge/_-FFE375?style=for-the-badge) | Jú 橘 | `#FFE375` | Updated |
| ![#6682FF](https://img.shields.io/badge/_-6682FF?style=for-the-badge) | Lán 蓝 | `#6682FF` | Keywords, Types |
| ![#F76DE2](https://img.shields.io/badge/_-F76DE2?style=for-the-badge) | Zǐ 紫 | `#F76DE2` | Identifier, Method Calls, Special syntax |
| ![#4CCEFE](https://img.shields.io/badge/_-4CCEFE?style=for-the-badge) | Qīng 青 | `#4CCEFE` | Folders, Navigation |
| ![#FF6593](https://img.shields.io/badge/_-FF6593?style=for-the-badge) | Yàn 艳 | `#FF6593` | lighter variant |
| ![#77FF9A](https://img.shields.io/badge/_-77FF9A?style=for-the-badge) | Cuì 翠 | `#77FF9A` | lighter variant |
| ![#FFE188](https://img.shields.io/badge/_-FFE188?style=for-the-badge) | Chéng 橙 | `#FFE188` | lighter variant |
| ![#8399FF](https://img.shields.io/badge/_-8399FF?style=for-the-badge) | Tiān 天 | `#8399FF` | lighter variant |
| ![#F08EFF](https://img.shields.io/badge/_-F08EFF?style=for-the-badge) | Fěi 翡 | `#F08EFF` | lighter variant |
| ![#74D9FE](https://img.shields.io/badge/_-74D9FE?style=for-the-badge) | Líng 泠 | `#74D9FE` | lighter variant |
| ![#EBE9F1](https://img.shields.io/badge/_-EBE9F1?style=for-the-badge) | Xuě 雪 | `#EBE9F1` | Main Text |
| ![#BFBDCA](https://img.shields.io/badge/_-BFBDCA?style=for-the-badge) | Bái 白 | `#BFBDCA` | Subtext |
| ![#938FA8](https://img.shields.io/badge/_-938FA8?style=for-the-badge) | Dàn 淡 | `#938FA8` | Overlay, Comments |
| ![#72708E](https://img.shields.io/badge/_-72708E?style=for-the-badge) | Qīng 青 | `#72708E` | Overlay |
| ![#4C4B69](https://img.shields.io/badge/_-4C4B69?style=for-the-badge) | Huī 灰 | `#4C4B69` | Surface |
| ![#323246](https://img.shields.io/badge/_-323246?style=for-the-badge) | Àn 暗 | `#323246` | Lighter Background |
| ![#1C1B28](https://img.shields.io/badge/_-1C1B28?style=for-the-badge) | Mò 墨 | `#1C1B28` | Default Background |
| ![#07060B](https://img.shields.io/badge/_-07060B?style=for-the-badge) | Hēi 黑 | `#07060B` | Darker Background |


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
