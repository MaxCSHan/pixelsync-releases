# PixelSync releases

Downloads for **PixelSync**, a Mac app for photographers, designers and creators who keep everything: browse your whole library, develop RAW files with film-style looks, and always know which photos are safely backed up.

**Latest:** [PixelSync.dmg](https://github.com/MaxCSHan/pixelsync-releases/releases/latest/download/PixelSync.dmg) · macOS 14 or later · Apple silicon and Intel

This repository holds release downloads and notes only. The app's source is not public.

## Install

1. Open the DMG and drag **PixelSync.app** to Applications.
2. The first launch is blocked by macOS, because the app has no Apple Developer ID. Open **System Settings › Privacy & Security** and click **Open Anyway**.
3. Upgrading from an earlier version? Quit PixelSync and copy `~/Library/Application Support/PixelSync/` to a dated folder first. 1.8.0 upgrades your data, and older builds then open it read-only.

Check a download with `shasum -a 256 PixelSync-1.8.0.dmg`; each release lists its SHA-256.

All rights reserved.
