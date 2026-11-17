# Typella releases

Downloads for Typella, inline AI autocomplete for macOS. It runs a local model, and nothing you type leaves your Mac. The source is private; this repo only holds the builds.

## Install

1. Download `Typella-<version>.zip` from the latest release, unzip it, and move `Typella.app` to Applications.
2. Open it. macOS blocks it the first time because it isn't notarized: open **System Settings → Privacy & Security** and click **Open Anyway**.
3. Allow Typella under **System Settings → Privacy & Security → Accessibility**, then download the recommended model when Typella offers it (3.4 GB).

Typella checks this repo for updates once a day and asks before installing one. Every build is signed with Typella's update key, and the app refuses one that isn't.
