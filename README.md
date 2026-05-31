# MyTermX Releases

Last checked: 2026-05-31

This repository is the public release channel for MyTermX installers and update
notes. Source code lives in private development repositories; this repository
should contain release-facing documentation, screenshots, and GitHub Release
attachments only.

## Current Status

No installer binaries are committed to the repository tree. Download artifacts
should be attached to GitHub Releases:

[GitHub Releases](https://github.com/RuyimgByCN/MyTermX-Releases/releases)

## Expected Artifacts

| Platform | Artifact |
|---|---|
| macOS Apple Silicon | `MyTermX-<version>-arm64.dmg` |
| macOS Intel | `MyTermX-<version>-x64.dmg` |
| Windows | `MyTermX-Setup-<version>.exe` |
| Linux | `MyTermX-<version>.AppImage` |
| Android | `MyTermX-<version>-android.apk` |

## Install Notes

### macOS

1. Download the matching `.dmg`.
2. Open it and drag MyTermX into Applications.
3. If macOS blocks the first launch, open System Settings -> Privacy & Security
   and allow the app.

### Windows

1. Download the `.exe` installer.
2. Run the installer and follow the prompts.

### Linux

```bash
chmod +x MyTermX-*.AppImage
./MyTermX-*.AppImage
```

### Android

1. Download the `.apk`.
2. Allow installation from the selected source.
3. Install the APK.

## Release Documentation Rules

- Keep implementation architecture and internal migration plans out of this
  repository.
- Put changelog entries in the GitHub Release body for each version.
- Keep screenshots under `screenshots/` and avoid committing generated
  installer binaries directly to git.

## License

Copyright 2026 Ruyimg. All rights reserved.
