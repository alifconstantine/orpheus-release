# Orpheus Releases

Public release distribution repository for **Orpheus** — a cross-platform YouTube Music & audio player built with Kotlin and Compose Multiplatform.

> Source code is maintained in a separate private repository. This repository hosts official compiled builds, release notes, and public distribution assets.

## Download

- **Latest Release:** [github.com/alifconstantine/orpheus-release/releases/latest](https://github.com/alifconstantine/orpheus-release/releases/latest)
- **All Releases:** [github.com/alifconstantine/orpheus-release/releases](https://github.com/alifconstantine/orpheus-release/releases)

## In-App Update Endpoint

The Orpheus application checks for new versions via the public GitHub Releases API:

```text
https://api.github.com/repos/alifconstantine/orpheus-release/releases/latest
```

## Release Versioning

- Versioning follows Semantic Versioning prefixed with `v` (starting from `v1.0.0`).
- Each release includes build artifacts (e.g., Android `.apk` / Desktop installers) and release notes.
