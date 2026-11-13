# Orpheus Releases

Public release distribution repository for **Orpheus** — a cross-platform YouTube Music & audio player built with Kotlin and Compose Multiplatform.

> Source code is maintained in a separate private repository. This repository hosts official compiled builds, release notes, and public distribution assets consumed by both Orpheus auto-updates and the official web download portal (`orpheus-web`).

## Download

- **Latest Release:** [github.com/alifconstantine/orpheus-release/releases/latest](https://github.com/alifconstantine/orpheus-release/releases/latest)
- **All Releases:** [github.com/alifconstantine/orpheus-release/releases](https://github.com/alifconstantine/orpheus-release/releases)

## Included Targets per Release

- **Desktop (Windows x64):** `Orpheus-Windows-installer.zip` (`.msix` + installer script)
- **Desktop (macOS Apple Silicon / Intel):** `.dmg`
- **Desktop (Linux x86_64):** `.AppImage`
- **Android (`full`, `foss`, `vivo`):** `.apk`

Desktop installers are **Packaged with Conveyor** ([hydraulic.dev](https://hydraulic.dev)).

## In-App Update & Web Endpoint

Both the Orpheus application update checker and the web download portal fetch release metadata from the public GitHub Releases API:

```text
https://api.github.com/repos/alifconstantine/orpheus-release/releases/latest
```

## Release Versioning

- Versioning follows Semantic Versioning prefixed with `v` (starting from `v1.0.0`).
- Each GitHub Release publishes platform installers, APKs, and release notes directly under this repository's Releases tab.
