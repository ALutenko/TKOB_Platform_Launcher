# TKOB Launcher — downloads

Installers for the **TKOB Launcher**, the desktop client for [The Kingdom Of Beasts](https://tkob.lutarea.com): games, books, comics, the animated series, tabletop and merch of the saga in one place. Sign in with your Lutarea account to add, buy, install and play the games.

This repository only hosts releases. Source code lives in a private repository; releases are published here automatically on every tag.

## Download

**[Latest release](https://github.com/ALutenko/TKOB_Platform_Launcher/releases/latest)** · [tkob.lutarea.com/launcher](https://tkob.lutarea.com/launcher)

| OS | File |
|---|---|
| macOS (Apple Silicon + Intel) | [`TKOB-Launcher-macOS.dmg`](https://github.com/ALutenko/TKOB_Platform_Launcher/releases/latest/download/TKOB-Launcher-macOS.dmg) |
| Windows 10/11 | [`TKOB-Launcher-Windows-Setup.exe`](https://github.com/ALutenko/TKOB_Platform_Launcher/releases/latest/download/TKOB-Launcher-Windows-Setup.exe) · [`.msi`](https://github.com/ALutenko/TKOB_Platform_Launcher/releases/latest/download/TKOB-Launcher-Windows.msi) |
| Linux | [`TKOB-Launcher-Linux.AppImage`](https://github.com/ALutenko/TKOB_Platform_Launcher/releases/latest/download/TKOB-Launcher-Linux.AppImage) · [`.deb`](https://github.com/ALutenko/TKOB_Platform_Launcher/releases/latest/download/TKOB-Launcher-Linux.deb) |

Every release also ships `manifest.json` (version, URLs, sizes, SHA-256) and `SHA256SUMS.txt`.

## Unsigned builds

There is no code-signing certificate yet, so the first launch needs one extra step:

- **macOS** — open the `.dmg`, drag the app to Applications, then right-click the app → *Open* (or System Settings → Privacy & Security → *Open Anyway*).
- **Windows** — if SmartScreen shows "Windows protected your PC": *More info → Run anyway*.
- **Linux** — `chmod +x TKOB-Launcher-Linux.AppImage && ./TKOB-Launcher-Linux.AppImage`, or `sudo dpkg -i TKOB-Launcher-Linux.deb`.

## Support

[support@lutarea.com](mailto:support@lutarea.com) · [lutarea.com](https://www.lutarea.com)

© Lutarea. All rights reserved.
