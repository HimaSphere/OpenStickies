<div align="center">

# OpenStickies

**Sticky notes for your desktop. Simple, fast, private.**

Drop files, paste screenshots, set reminders — keep things visible where you work.

![Windows](https://img.shields.io/badge/Windows-10+-blue) ![Linux](https://img.shields.io/badge/Linux-AppImage-orange) ![macOS](https://img.shields.io/badge/macOS-soon-lightgrey) [![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-support-yellow?style=flat&logo=buy-me-a-coffee)](https://buymeacoffee.com/himasphere)

<br>

<img src="images/quick-capture.webp" alt="OpenStickies sticky notes app" width="700">

<br>

<a href="https://github.com/HimaSphere/OpenStickies/releases/latest">
  <img src="https://img.shields.io/badge/Download_Latest_Release-v2.5.0-brightgreen?style=for-the-badge&logo=github" alt="Download">
</a>

<br>

| Platform | File | Notes |
|----------|------|-------|
| Windows | `.exe` | Windows 10+ |
| Linux | `.AppImage` | Works on most distros |
| macOS | — | Coming soon |

</div>

---

## Features

### Paste anything

Files, folders, screenshots — drag it in, it becomes a clickable shortcut. 70+ file types supported.

<p align="center">
  <img src="images/paste-anything.webp" alt="File shortcuts in OpenStickies" width="600">
</p>

### Reminders

Set them right in the note. Color changes based on urgency — green, orange, red.

<p align="center">
  <img src="images/reminders.webp" alt="Reminders" width="600">
</p>

### Custom backgrounds

Images, GIFs, solid colors. Make each note yours.

<p align="center">
  <img src="images/custom-backgrounds.webp" alt="Custom note backgrounds" width="600">
</p>

### Rich text formatting

Bold, italic, headings, links, checkboxes with strikethrough.

<p align="center">
  <img src="images/rich-text-formatting.webp" alt="Text formatting" width="600">
</p>

### Grid snap + pinning

Align notes to a grid. Pin to lock position and prevent edits.

<p align="center">
  <img src="images/snap-to-grid.webp" alt="Grid snapping" width="500">
</p>

### Hover preview

Peek at note contents without opening them.

<p align="center">
  <img src="images/hover-preview.webp" alt="Hover preview" width="500">
</p>

### And more

- **Always-on-top** — keep notes above other windows
- **Auto-save** — never lose a note
- **Multi-monitor** — place notes across screens
- **11 languages** — including RTL Arabic
- **Fully offline** — no accounts, no cloud, no tracking

---

## Free vs Premium

|  | Free | Premium |
|--|------|---------|
| Notes | 5 | Unlimited |
| Reminders | 1 | Unlimited |
| GIF backgrounds | 1 | Unlimited |

Premium is a one-time purchase — **pay once, use forever**.

<div align="center">

<a href="https://openstickies.com/pricing"><strong>See pricing &rarr;</strong></a>

</div>

---

## Community

<div align="center">

[Discord](https://discord.gg/8gGZSUJjZd) · [r/OpenStickies](https://www.reddit.com/r/OpenStickies/) · [Report a bug](https://github.com/HimaSphere/OpenStickies/issues) · support@openstickies.com

If OpenStickies is useful to you, consider giving it a star — it helps others find it.

</div>

---

<details>
<summary><strong>Troubleshooting</strong></summary>

<br>

**Linux: AppImage won't run**
```bash
chmod +x OpenStickies*.AppImage
./OpenStickies*.AppImage
```

**Linux: Wayland issues**
```bash
QT_QPA_PLATFORM=xcb ./OpenStickies*.AppImage
```

**Windows: SmartScreen warning**

Click "More info" → "Run anyway". The app isn't signed yet.

**Reset everything**

Delete the config folder:
- Linux: `~/.config/OpenStickies/`
- Windows: `%APPDATA%\OpenStickies`

</details>

---

<div align="center">

Built by [Hima](https://github.com/HimaSphere) · [openstickies.com](https://openstickies.com)

OpenStickies is proprietary software. This repo is for free version releases only — no source code.

</div>
