# ClipForge AI — downloads

This repository hosts the **installers and update files** for ClipForge AI, a desktop app that turns long videos into short vertical clips.

There is no source code here. The app checks this repository for new versions and offers to update itself.

## Download

Get the newest installer from the **[Releases](../../releases/latest)** page:

| System | File |
|---|---|
| Windows 10 / 11 (64-bit) | `ClipForge-AI_x.y.z_x64-setup.exe` |
| macOS (Apple Silicon: M1 or newer) | `ClipForge-AI_x.y.z_aarch64.dmg` |

`SHA256SUMS.txt` on the same page lets you check that a download is intact.

## Installing

The installers are not signed with a paid certificate yet, so you will see a warning the first time:

- **Windows:** *"Windows protected your PC"* appears. Click **More info**, then **Run anyway**. The installer works for your user only and does not ask for administrator rights.
- **macOS:** open the `.dmg`, drag ClipForge AI to Applications. The first time, macOS says it cannot be opened: go to **System Settings → Privacy & Security**, scroll down and click **Open Anyway**.

On first launch, ClipForge guides you through a short setup and asks before it downloads any large AI model.

## Updating

Once installed, ClipForge checks for new versions by itself and asks before downloading or installing anything. Your projects, videos, settings and downloaded AI models are kept.

## Problems

Use the **Report a problem** button inside the app, or open an issue in this repository. Please do not paste API keys or personal information into an issue; issues here are public.
