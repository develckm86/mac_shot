<div align="center">

<img src="docs/images/00-icon.png" width="88" alt="">

# ScreenCapture

**The Mac screenshot experience, on Windows.**
Drag a region and the PNG lands on your desktop right there.

[한국어](README.md) · English · [简体中文](README.zh-CN.md) · [日本語](README.ja.md)

### [⬇ Download ScreenCapture.exe (Windows 10 · 11 · 64-bit)](https://github.com/develckm86/mac_shot/releases/latest/download/ScreenCapture.exe)

Free · No installer · No account · Run it straight from the download

For screen recording, also grab [`ffmpeg.exe`](https://github.com/develckm86/mac_shot/releases/latest/download/ffmpeg.exe) and keep it **in the same folder**.
([Both files in one zip](https://github.com/develckm86/mac_shot/releases/latest/download/ScreenCapture-win64.zip))

<!-- Once the Microsoft Store listing is live, uncomment the line below and fill in the URL.
[<img src="https://get.microsoft.com/images/en%20dark.svg" width="200" alt="Get it from Microsoft">](https://apps.microsoft.com/detail/YOUR-STORE-ID)
-->
**Microsoft Store** — submission in progress. The badge will appear here once it is live.

</div>

---

## Why

Windows has a capture tool, but **saving is the tedious part.** It goes to the
clipboard, you click a notification, an editor opens, you pick a folder. On a Mac
you drag a region and a PNG is already on your desktop. This app brings that flow
to Windows.

There is no window. It lives in the tray, and you only need the shortcuts.

## What it does

### Drag and you're done — `Ctrl+Shift+4`

![Region capture](docs/images/03-region.png)

Drag with the crosshair and the file is saved the moment you let go. The size
readout follows the cursor, and holding `Ctrl` as you release sends it to the
clipboard instead of a file.

### The same toolbar as on macOS — `Ctrl+Shift+5`

![Screenshot tools](docs/images/02-toolbar.png)

Whole screen, window, region — plus screen recording and region recording. The
selection has eight handles, and dragging inside it moves the whole box.

### Save location, timer, microphone

![Options](docs/images/04-options.png)

The Options menu from macOS Screenshot, item for item and in the same order —
with one addition: **Language**.

### Recording that survives a crash

![Recording indicator](docs/images/05-recording.png)

While recording, a pill at the top of the screen shows elapsed time and a stop
button. **It never appears in the recording itself.** Frames are written to disk
in fragments, so if the app is killed mid-recording, everything up to that second
still plays.

### A thumbnail in the corner afterwards

![Floating thumbnail](docs/images/06-thumbnail.png)

Click it to open the file, drag it straight into another app, or right-click for
Open · Show in Folder · Copy · Delete.

### It tells you how it works on first launch

![Startup guide](docs/images/01-guide.png)

An app with no window is easy to lose track of. The shortcuts appear in the middle
of the screen for five seconds and fade out. The tray menu brings them back
whenever you want.

## Shortcuts

The Mac layout with `Cmd` swapped for `Ctrl`.

| macOS | Windows | What it does |
| --- | --- | --- |
| `Cmd+Shift+3` | `Ctrl+Shift+3` | Capture every display — one file each |
| `Cmd+Shift+4` | `Ctrl+Shift+4` | Drag to capture a region |
| `Cmd+Shift+4` → `Space` | same | Pick a window instead |
| `Cmd+Shift+5` | `Ctrl+Shift+5` | Screenshot tools |
| `Cmd+Ctrl+Shift+3/4` | `Ctrl+Alt+Shift+3/4` | To the clipboard instead of a file |
| `Cmd+Ctrl+Esc` | `Ctrl+Alt+Esc` | Stop recording |

While dragging, `Space` (move the box), `Shift` (one axis only), `Alt` (resize
symmetrically), `Ctrl` (to the clipboard) and `Esc` (cancel) behave exactly as
they do on a Mac.

## Install

1. Download [`ScreenCapture.exe`](https://github.com/develckm86/mac_shot/releases/latest/download/ScreenCapture.exe) and put it wherever you like.
2. Run it. It goes straight to the tray. **No installer, no admin rights.**
3. For screen recording, also download [`ffmpeg.exe`](https://github.com/develckm86/mac_shot/releases/latest/download/ffmpeg.exe) into the **same folder**.
   Without it, capture still works — only recording is unavailable.

To remove it, delete the file. Only your settings stay, in `%APPDATA%\ScreenCapture`.

> The executable is unsigned, so SmartScreen may ask once on first run:
> **More info → Run anyway**.

## Languages

The app runs in 12 languages. It follows your Windows display language by default,
and you can pick one in the Options menu.

한국어 · English · 日本語 · 简体中文 · 繁體中文 · Español · Português ·
Français · Deutsch · Русский · Italiano · Tiếng Việt

Per-language manuals live in [`docs/manual/`](docs/manual).

## About the ads

The app is free and funded by ads. A square banner appears above the taskbar
**only after a capture**, for nine seconds.

![Ad banner](docs/images/08-ad.png)

- It is always labelled as an ad and always has a ✕.
- It is dismissed before a capture starts — **it never ends up in your
  screenshots or recordings.**
- It never blocks a capture. With no internet the slot simply stays empty.
- Beyond fetching the banner image, **no data is collected or transmitted.**
  Your captures stay in the folder you chose.

## Requirements

| | |
| --- | --- |
| OS | Windows 10 version 2004 or newer / Windows 11 (64-bit) |
| Permissions | No admin rights needed |
| Disk | About 170 MB (app + ffmpeg) |

## License and redistribution

**Anyone may redistribute it as-is** — websites, blogs, USB sticks, company-wide
rollouts, no permission needed. What you may not do is ship a copy with the ads
removed or the ad links replaced; that is what keeps the app free. Full terms in
[LICENSE](LICENSE).

The bundled `ffmpeg.exe` is covered by FFmpeg's own license (LGPL/GPL).

---

<div align="center">
Found a bug or want a feature? Open an <a href="https://github.com/develckm86/mac_shot/issues">issue</a>.
</div>
