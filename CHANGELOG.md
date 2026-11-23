# Changelog

Public release notes for Flare Drive, newest first.

## 2.2.7 — 2026-11-23

- New in-app updates in **Settings › About › App info**: Flare Drive checks the signed catalog for newer versions, shows an update row on **Status** and a dot on **Settings** when one is available, verifies the download, and opens Android's installer.

## 2.2.6 — 2026-11-23

- Turning on **Sound through Android Auto** in **Plugins › Android Auto › Settings** now prompts to restart the head unit so song info in the cluster and on the Media tile starts straight away.
- **Use the car's GPS** in **Plugins › Android Auto › Settings** now notes that the phone's Location setting must stay on for navigation apps.

## 2.2.5 — 2026-11-23

- New opt-in **Share compatibility results** switch under **Settings › About** (off by default): sends anonymous pass or fail results for each firmware, iDrive version, and plugin version once online to help verify compatibility across EntryNav2 units.
- Removed the release list URL from **Settings › About › App info**.

## 2.2.4 — 2026-11-23

- Faster head-unit reads on connecting: status appears straight away while companion plugins are checked in parallel.
- Downloading a newer release for a plugin now deletes previous versions stored on the phone once the new download is verified.
- Removed the built-in default password and added opt-in on-device encrypted password saving backed by Android Keystore.
- Switched to a signed, minified release APK (3.53 MB).
- Fixed Status briefly showing "The last read failed" while the first read after connecting was still running.
- Fixed a stray symbol at the end of "Checking for updates…" and "Downloading…" on plugin pages.
