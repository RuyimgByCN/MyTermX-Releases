# MyTermX Releases Project Info

Last updated: 2026-10-24

## Purpose

`MyTermX-Releases` is the public release channel for MyTermX. It contains
release-facing documentation, screenshots, issue tracking, and GitHub Release
attachments. It is not a source-code repository for the product.

## Release Boundary

- Installers and archives belong in GitHub Releases, not in the git tree.
- Source code stays in private development repositories.
- This repository should remain safe for public users to browse.
- README, screenshots, license, and issue templates are product-facing assets.

## Artifact Naming

Current release assets use the numeric version without the leading `v`:

| Platform | Pattern |
|---|---|
| macOS Apple Silicon | `MyTermX_<version>_aarch64.dmg` |
| macOS Intel | `MyTermX_<version>_x64.dmg` |
| Windows x64 NSIS installer | `MyTermX_<version>_x64-setup.exe` |
| Windows x64 MSI installer | `MyTermX_<version>_x64_en-US.msi` |
| Linux amd64 DEB package | `MyTermX_<version>_amd64.deb` |
| Linux amd64 AppImage | `MyTermX_<version>_amd64.AppImage` |

Add mobile artifact names here once Android/iOS release packaging is finalized.

Latest documented release: `v0.2.3`, published 2026-10-24.

## Important Design Decisions

- Keep this repo small. Do not commit binaries, generated installers, logs, or
  build outputs.
- Keep user-facing claims aligned with the latest shipped release, not merely
  with private mainline code.
- When the latest release changes, update the README download table and the
  static download snapshot in `../MyTermX-Web/src/app/page.tsx` in the same pass.
- Issues here are public product feedback. Internal implementation details,
  private repo paths, credentials, and unreleased security notes should stay out.
- The license is proprietary. Do not add open-source license language unless the
  product licensing decision changes.

## Release Checklist

Before publishing a release:

```text
1. Build artifacts in the private source repo.
2. Run release smoke/performance gates.
3. Upload installers to a GitHub Release here.
4. Update release notes with user-visible changes and known issues.
5. Keep the README download table accurate.
6. Update the website release snapshot in `../MyTermX-Web/src/app/page.tsx`.
```
