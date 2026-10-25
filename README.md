# UsageBar releases

Built installers for UsageBar, Stocksdigital's AI usage monitor for the Windows taskbar, the macOS menu bar and the Linux system tray. This repo only contains release files; the source code is private.

- **Download:** [latest release](https://github.com/StocksDigital/usagebar-releases/releases/latest) — `UsageBar_<version>_x64-setup.exe` (Windows x64) `UsageBar_<version>_aarch64.dmg` (macOS, Apple Silicon) or `UsageBar_<version>_x86_64.AppImage` (Linux x86_64).
- **macOS first install:** the app is ad-hoc signed (not notarised). If macOS says it can't be opened, run `xattr -dr com.apple.quarantine /Applications/UsageBar.app` once.
- **Linux first install:** `chmod +x UsageBar_*_x86_64.AppImage` and run it. It needs FUSE 2 (Arch/CachyOS: `sudo pacman -S fuse2`). Keep it somewhere permanent such as `~/Applications`; updates replace that file.
- **Updates:** installed copies of UsageBar check this repo's `latest.json` and update themselves (all platforms).

The usage engine is built from [Win-CodexBar](https://github.com/nesszer/Win-CodexBar) (MIT). Provider logos are trademarks of their owners.
