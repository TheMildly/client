# Mildly (BETA STATE)

A friendly client for AI services (Claude, ChatGPT, Gemini, OpenRouter, a local Ollama and
others), with an optional personal server.

This repository holds the **releases** of the Mildly app: installers for Mac and Windows, and
the update files installed apps check at start-up. The app's source is closed and lives
elsewhere.

## Install

Download the newest release from [Releases](../../releases/latest):

- **Mac:** `Mildly_…_universal.dmg` (Apple Silicon and Intel). Open it and drag Mildly to
  Applications. Until the app is notarised, macOS blocks the first launch: run
  `xattr -dr com.apple.quarantine /Applications/Mildly.app` once in Terminal, or allow it
  under System Settings → Privacy & Security → Open Anyway.
- **Windows:** `Mildly_…_x64-setup.exe`. Until the installer is signed, SmartScreen asks
  first: More info → Run anyway.

After that, Mildly updates itself: a new version downloads in the background and opens the
next time you start the app.

## Related

- [TheMildly/server](https://github.com/TheMildly/server) — the personal server Mildly pairs
  with (open source, Apache-2.0).

Mildly is © 2026 Project Mildly. The app is closed source with permission to use it; the
Mildly name, character and artwork are free for anyone to use.
