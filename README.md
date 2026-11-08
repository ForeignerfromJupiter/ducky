<img src="assets/icon.png" width="128" alt="Ducky icon">

# Ducky

A macOS menu bar app that puts every sound where you want it, at the level you want, and gets music out of the way when a call starts.

**[Download the latest release](https://github.com/ForeignerfromJupiter/ducky/releases/latest)** · macOS 15 or later

## What it does

- **Switch audio devices in one click** from the menu bar. The list updates as headphones, Bluetooth and monitors come and go.
- **Prefer the right device automatically.** Put your outputs and inputs in order once; when a device connects (or the one in use disconnects), Ducky picks the best one available, and undoes macOS jumping to a Bluetooth mic.
- **See what's playing where.** Each device shows the apps using it, and for Brave, Chrome, Edge and Arc, the tab names.
- **Give each app its own volume** when two or more apps share a device. Works with any app, including ones you install later.
- **Lower everything else during calls.** As soon as any app uses the mic (WhatsApp, Slack, Zoom, Teams, FaceTime, Meet, Granola…), other apps fade to a level you choose, and come back when the call ends.
- **Control a monitor's own volume** for displays macOS can't control, over the display cable.

## Install

1. Download `Ducky-<version>.zip` from [Releases](https://github.com/ForeignerfromJupiter/ducky/releases/latest) and unzip it.
2. Drag **Ducky** to your **Applications** folder and open it.
3. This early build isn't notarized by Apple yet, so macOS shows a warning the first time. Click **Done**, then go to **System Settings › Privacy & Security**, scroll down, and click **Open Anyway** next to Ducky. You only need to do this once.

Ducky lives in the menu bar (no Dock icon). Click its icon to start.

## Permissions

Ducky asks only when you use a feature that needs it:

| Permission | When | Why |
| --- | --- | --- |
| System Audio Recording | You first change an app's volume, or calls lower other apps | To pass that app's sound through Ducky at your level. Nothing is recorded or saved. |
| Accessibility | You click "Show which tab…" | To read the browser's tab names (read-only). |

If Ducky quits, every app plays at full volume again immediately.

## Privacy

Everything happens on your Mac. Ducky has no account, no analytics, and sends nothing anywhere.

## Known limits

- Two tabs in the same browser playing on the same device share one volume.
- macOS can't tell what's plugged into a monitor's headphone jack; you can name the monitor and pick an icon for it in Settings › Devices.
- Early alpha: expect rough edges. Feedback is welcome in [Issues](https://github.com/ForeignerfromJupiter/ducky/issues).
