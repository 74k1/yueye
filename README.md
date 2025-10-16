# YuèYè 月夜 v0.2.4

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
v0.2.4
 ╰─┼─┼─ Release Version / When I feel like I've perfected it (perhaps in 10+ years)
   ╰─┼─ Major Version / After the palette has changed enough (when I update all of my [ports](#ports))
     ╰─ Minor Version / Very small updates to the palette
```


## Palette

| Base | Color | Name | HEX Value | Usage |
| :--- | :---: | :--- | :--- | :--- |
| `base00` | ![#07060B](https://img.shields.io/badge/_-07060B?style=for-the-badge) | Hēi 黑  | `#07060B` | Default Background |
| `base01` | ![#1C1B28](https://img.shields.io/badge/_-1C1B28?style=for-the-badge) | Mò 墨   | `#1C1B28` | Lighter Background |
| `base02` | ![#323246](https://img.shields.io/badge/_-323246?style=for-the-badge) | Àn 暗   | `#323246` | Selection Background |
| `base03` | ![#4C4B69](https://img.shields.io/badge/_-4C4B69?style=for-the-badge) | Huī 灰  | `#4C4B69` | Comments |
| `base04` | ![#72708E](https://img.shields.io/badge/_-72708E?style=for-the-badge) | Qīng 青 | `#72708E` | Dark Foreground |
| `base05` | ![#BFBDCA](https://img.shields.io/badge/_-BFBDCA?style=for-the-badge) | Dàn 淡  | `#BFBDCA` | Default Foreground |
| `base06` | ![#EBE9F1](https://img.shields.io/badge/_-EBE9F1?style=for-the-badge) | Bái 白  | `#EBE9F1` | Light Foreground |
| `base07` | ![#FFFFFF](https://img.shields.io/badge/_-FFFFFF?style=for-the-badge) | Xuě 雪  | `#FFFFFF` | Light Background |
| `base08` | ![#FF4B72](https://img.shields.io/badge/_-FF4B72?style=for-the-badge) | Hóng 红 | `#FF4B72` | Variables, XML Tags, Markup Link Text |
| `base09` | ![#FF9A5B](https://img.shields.io/badge/_-FF9A5B?style=for-the-badge) | Chéng 橙| `#FF9A5B` | Integers, Boolean, Constants |
| `base0A` | ![#FFE15A](https://img.shields.io/badge/_-FFE15A?style=for-the-badge) | Yín 银  | `#FFE15A` | Classes, Markup Bold |
| `base0B` | ![#54FF80](https://img.shields.io/badge/_-54FF80?style=for-the-badge) | Cuì 翠  | `#54FF80` | Secondary Accent, Strings, Inherited Class, Markup Code |
| `base0C` | ![#5BEBEB](https://img.shields.io/badge/_-5BEBEB?style=for-the-badge) | Tiān 天 | `#5BEBEB` | Support, Regular Expressions |
| `base0D` | ![#7089FF](https://img.shields.io/badge/_-7089FF?style=for-the-badge) | Lán 蓝  | `#7089FF` | Main Accent, Functions, Methods, Attribute IDs |
| `base0E` | ![#AB72FF](https://img.shields.io/badge/_-AB72FF?style=for-the-badge) | Zǐ 紫   | `#AB72FF` | Keywords, Storage, Selector, Markup Italic |
| `base0F` | ![#E366D9](https://img.shields.io/badge/_-E366D9?style=for-the-badge) | Fěi 翡  | `#E366D9` | Deprecated, Removed |

## Naming Convention

- **Display Names**
  - Use YuèYè (with diacritics) or YueYe (ASCII-only) in interfaces.
  - Optional: Append 月夜 for stylistic contexts (e.g., documentation, logos).
  - *Avoid* lowercase-only variants (e.g., yueye) in visible text.

- **Files & URLs**
  - **Always** use `yueye` (lowercase, no diacritics or Hanzi).
  - *Examples:* `yueye.css`, `yueye-theme.json`.
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
| [Nix](https://nixos.org/) | [74k1/yueye.nix](https://github.com/74k1/yueye.nix) | in progress |

## Contributing

I've mentioned it like twice now. Here goes a third time: PLEASE CONTRIBUTE!
Open Source thrives on collaboration!

- Made a port? Show me! Submit a PR! I *want* to see it.
- Found an issue? Tell me! No gatekeeping here.

Thanks a ton, Tim
