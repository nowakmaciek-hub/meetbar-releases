# MeetBar releases

Notarized builds of MeetBar, a macOS menu-bar app that records and transcribes meetings on your Mac. This repository holds only the release zips; the source is private.

## Install

You need an Apple Silicon Mac (M1 or later) with macOS 14 or later.

1. Open the [latest release](https://github.com/nowakmaciek-hub/meetbar-releases/releases/latest) and download `MeetBar-<version>.zip` from **Assets**.
2. Double-click the zip and drag **MeetBar.app** into **Applications**.
3. Open MeetBar. It lives in the menu bar (microphone icon), not in the Dock.

The app is signed with a Developer ID and notarized by Apple, so it opens without warnings.

## First recording

macOS asks once for **Microphone** and **System Audio Recording**. The first recording downloads about 1–2 GB of speech models. Recordings and transcripts stay on your Mac in `~/meetings`. Optional Claude features send meeting text only after you turn them on.

## Updates

MeetBar checks this repository at startup and every 24 hours and offers **Update** when a newer version is out. It installs an update only when the SHA-256 checksum matches and the app is signed by the same developer team (MG2NC4K2LV).
