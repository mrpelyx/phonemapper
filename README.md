# Mr Pelyx PhoneMapper

Play Android games on Windows with your keyboard and mouse.

Developed by Jean David.

## Download

Get the installer from the [latest release](../../releases/latest) and run it
once. Everything is included — you do not need Python, adb or scrcpy.

Windows will warn that the app is not recognised the first time, because the
installer is not code-signed yet. Choose **More info → Run anyway**.

## Updates

PhoneMapper updates itself. When a new version exists it offers it when you
start the app; one click downloads, verifies and installs it, and the app
restarts on the new version. Your profiles and settings are kept — they live
in `%APPDATA%\MrPelyx\PhoneMapper` and updates never touch that folder.

## What is in this repository

Only what the updater needs:

- `release.json` — the update manifest the app reads on startup. It carries
  the current version, the download URL and the SHA-256 of the package, which
  the app verifies before installing anything.
- The release assets themselves, attached to each tagged release.

## Requirements

- Windows 10 or 11, 64-bit
- An Android phone with USB debugging enabled, connected by cable
