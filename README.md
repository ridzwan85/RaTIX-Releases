# RaTIX Releases

Official Android application distribution channel for **RaTIX – Radio and Technical Information Exchange**.

## Downloads

- Download the latest APK from [Releases](https://github.com/ridzwan85/RaTIX-Releases/releases/latest).
- The RaTIX app checks `latest.json` from the latest release to detect updates.
- Each release includes `RaTIX.apk` and `latest.json`.
- The app verifies the APK SHA-256 digest before opening Android's package installer.

## Security and source code

This repository contains release binaries and update metadata only. Application source code remains in the private [RADIX repository](https://github.com/ridzwan85/RADIX).

Do not upload signing keys, passwords, access tokens, private obfuscation symbols, or application source code to this repository.

## Release assets

Each versioned GitHub Release must publish:
- `RaTIX.apk` — signed Android package
- `latest.json` — version, version code, APK download URL, SHA-256, release notes and release page URL
