# Project HQ — Releases

Public mirror for signed binary releases of [Project HQ](https://github.com/DigiTallyINC/project-hq).

## Download

**[⬇ Download latest installer (.msi)](https://github.com/DigiTallyINC/project-hq-releases/releases/latest/download/Project-HQ_1.0.0_x64_en-US.msi)**

Alternative installer:
- [Setup .exe (NSIS)](https://github.com/DigiTallyINC/project-hq-releases/releases/latest/download/Project-HQ_1.0.0_x64-setup.exe)

All releases: https://github.com/DigiTallyINC/project-hq-releases/releases

## Install

1. Download the `.msi` above
2. Windows SmartScreen will warn ("Unknown publisher") — click **More info** → **Run anyway**
3. Existing DigitallyInc HQ users: uninstall the old app first; your DB auto-migrates on first launch

## Verification

Every binary is signed with [minisign](https://jedisct1.github.io/minisign/). The app's auto-updater verifies signatures using the embedded public key on every update. The matching `.sig` files are published alongside each binary.

Source code lives in the private `DigiTallyINC/project-hq` repo.
