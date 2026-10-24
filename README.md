# UsageBar releases

Built installers for UsageBar, Stocksdigital's AI usage monitor for the Windows taskbar and the macOS menu bar. This repo only contains release files; the source code is private.

- **Download:** [latest release](https://github.com/StocksDigital/usagebar-releases/releases/latest) — `UsageBar_<version>_x64-setup.exe` (Windows x64) or `UsageBar_<version>_aarch64.dmg` (macOS, Apple Silicon).
- **macOS first install:** the app is ad-hoc signed (not notarised). If macOS says it can't be opened, run `xattr -dr com.apple.quarantine /Applications/UsageBar.app` once.
- **Updates:** installed copies of UsageBar check this repo's `latest.json` and update themselves (both platforms).

The usage engine is built from [Win-CodexBar](https://github.com/nesszer/Win-CodexBar) (MIT). Provider logos are trademarks of their owners.
