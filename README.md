# PrimeX Video Downloader for Android: releases

Official Android builds of **PrimeX Video Downloader** by PrimeX Forge LLC.

- Download the app from **[primexforge.com](https://primexforge.com)**. This repository only hosts the files the app uses to update itself.
- Each release contains the APK for each phone type (`arm64-v8a` for most phones) plus `latest.json` and `latest.json.sig`.
- `latest.json` is signed (Ed25519). The app installs an update only when the signature, the APK's SHA-256 checksum and its signing certificate all match the official ones.

The app's source code is not published here.

## Remote config

`config.json` (+ `config.json.sig`) lets PrimeX apply small fixes for a site without a new app version (extra engine settings, an engine version to skip, a short notice). It is signed; the app ignores any file without a valid signature.
