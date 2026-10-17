# Ocode releases

Official Windows installers, update metadata and corresponding source snapshots for Ocode.

## Download

Use [the latest release](https://github.com/diaomin66/Ocode-releases/releases/latest). Choose `Ocode-Setup-<version>.exe` for the installed application or the portable ZIP for a no-install copy.

The initial public release is Windows x64 only. Current builds are unsigned: Windows may display an unknown publisher or SmartScreen warning. Check the SHA-256 values supplied with each release before installation.

## Updates

Installed Windows builds from 0.21.0 onward use this public stable release channel, with the existing automatic download and restart-to-update flow. Portable builds default to manual updates. Earlier `0.21.0-beta.1` builds used a private channel and need one manual installer upgrade.

`latest.yml` belongs to the NSIS installer, not to portable builds. Release assets include blockmaps, checksums and build/installation verification evidence. No GitHub account or embedded access token is needed for public downloads.

## Source and licenses

Ocode is derived from [PI-Desktop](https://github.com/vastsa/PI-Desktop) by vastsa and contributors. Original authorship and LGPL-3.0 licensing are preserved. See [COPYING.LESSER](COPYING.LESSER) and [COPYING](COPYING). Third-party dependencies retain their own licenses.

Each release includes `Ocode-Source-<version>.tar.gz`: the full committed corresponding source for that binary, including licenses, dependency lockfiles, patches and build scripts. Extract it and read `docs/releases/source-build.md` to modify or rebuild the application. The source commit is recorded in `windows-verification.json`. The development repository and its history remain private; local configuration, user data and credentials are never part of the source archive.

This repository does not imply macOS/Linux binaries or remote Host bundles are available for the Windows-only release.
