# Changelog

Public release notes for Flare Drive, newest first.

## 2.2.4 — 2026-11-23

- Faster head-unit reads on connecting: status appears straight away while companion plugins are checked in parallel.
- Downloading a newer release for a plugin now deletes previous versions stored on the phone once the new download is verified.
- Removed the built-in default password and added opt-in on-device encrypted password saving backed by Android Keystore.
- Switched to a signed, minified release APK (3.53 MB).
- Fixed Status briefly showing "The last read failed" while the first read after connecting was still running.
- Fixed a stray symbol at the end of "Checking for updates…" and "Downloading…" on plugin pages.
