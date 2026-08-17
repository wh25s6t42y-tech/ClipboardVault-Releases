# Clipboard Vault

Official Windows downloads and update information for Clipboard Vault.

## Current release

**Clipboard Vault 1.00 Beta**  
Technical version: `1.0.0`  
Platform: Windows 11 x64

[Download from GitHub Releases](https://github.com/wh25s6t42y-tech/ClipboardVault-Releases/releases/tag/v1.0.1)

Download `ClipboardVault-1.00-Beta-Windows11-x64.zip`, extract it, and run `INSTALL.cmd`.

This beta is not code-signed. Windows may show an **Unknown publisher** warning. Download only from this repository and verify the SHA-256 checksum before running it.

## SHA-256

```text
2d1dc32ec2cc9616f92ea849d94c0e9fa4cbecc16b001a56255a001873ec7b6b
```

PowerShell:

```powershell
Get-FileHash .\ClipboardVault-1.00-Beta-Windows11-x64.zip -Algorithm SHA256
```

The result must match the checksum above exactly.

## Privacy

Clipboard history and encrypted storage stay on the user's PC. Clipboard Vault has no required account, cloud clipboard, telemetry, advertising, or analytics.

A manual update check only reads `latest.json` from this repository. It never sends clipboard content and never downloads or starts an update automatically.

## About this repository

This repository contains release packages, checksums, release notes, and update metadata only. Application source code, tests, build tools, credentials, and signing keys are not published here.
