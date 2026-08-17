# Clipboard Vault

Private, local-first clipboard manager for Windows 11.

Clipboard Vault stores clipboard history on your PC using encrypted local storage. No account, cloud service or telemetry is required.

## Download

**Public version:** Clipboard Vault 1.00 Beta
**Technical version:** `1.0.2`
**Platform:** Windows 11 x64, build 22000 or newer

[Download Clipboard Vault](https://github.com/wh25s6t42y-tech/ClipboardVault-Releases/releases/download/v1.0.2/ClipboardVault-1.00-Beta-Windows11-x64.zip)

[View release notes](https://github.com/wh25s6t42y-tech/ClipboardVault-Releases/releases/tag/v1.0.2)

## Install or update

1. Download and extract `ClipboardVault-1.00-Beta-Windows11-x64.zip`.
2. If Clipboard Vault is already running, exit it using the tray icon.
3. Run `INSTALL.cmd`.
4. Open Clipboard Vault from the Start menu.

Installing an update preserves clipboard history, settings and encryption data.

## Verify the download

SHA-256:

```text
551136fc4165530f014258cf4c6e8b7e7f1c1e3d155e67e78761cbc49641e4b8
```

PowerShell:

```powershell
Get-FileHash .\ClipboardVault-1.00-Beta-Windows11-x64.zip -Algorithm SHA256
```

The result must match the checksum exactly.

[Download the SHA-256 file](https://github.com/wh25s6t42y-tech/ClipboardVault-Releases/releases/download/v1.0.2/ClipboardVault-1.00-Beta-Windows11-x64.zip.sha256)

## Windows security warning

This beta is not code-signed. Windows may display an **Unknown publisher** warning.

Download Clipboard Vault only from this repository and verify the SHA-256 checksum before installation.

## Privacy

Clipboard history and encrypted storage remain on the user's PC.

Clipboard Vault has:

* No required account
* No cloud clipboard
* No advertising
* No analytics
* No telemetry

The manual update check only reads `latest.json` from this repository. Clipboard Vault never sends clipboard content and never downloads or starts updates automatically.

## Uninstall

Remove Clipboard Vault through **Windows Settings → Apps → Installed apps**, or run `UNINSTALL.cmd`.

Uninstalling the application preserves local history and settings.

## About this repository

This repository contains official release packages, checksums, release notes and update metadata.

Application source code, tests, build tools, credentials and signing keys are not published here.
