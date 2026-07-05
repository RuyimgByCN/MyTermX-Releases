# Release Checklist

Use this checklist before publishing a GitHub Release in `MyTermX-Releases`.

## Build Source

- [ ] Build artifacts from the private `MyTermX` source repository.
- [ ] Confirm the source commit/tag that produced the artifacts.
- [ ] Run release smoke and performance gates in the source repository.
- [ ] Verify no debug/dev/self-test UI is enabled by default.

## Artifacts

- [ ] macOS Apple Silicon DMG: `MyTermX-<version>-arm64.dmg`
- [ ] macOS Apple Silicon archive: `MyTermX-<version>-arm64-mac.zip`
- [ ] Windows installer: `MyTermX.Setup.<version>.exe`
- [ ] Windows archive: `MyTermX-<version>-win.zip`
- [ ] Linux AppImage: `MyTermX-<version>.AppImage`
- [ ] Linux archive: `mytermx-<version>.tar.gz`
- [ ] Android/iOS artifacts, if this release includes mobile packages.
- [ ] Checksums generated and stored with the release notes or artifacts.

## Release Notes

- [ ] User-visible changes are listed.
- [ ] Security or privacy changes are described without exposing sensitive implementation details.
- [ ] Known issues and upgrade notes are listed.
- [ ] Download table matches the uploaded artifact names.
- [ ] Version number matches the app metadata and release tag.

## Public Repository Hygiene

- [ ] No binaries committed to git.
- [ ] No private repo paths, credentials, hostnames, tokens, logs, or internal-only notes in public text.
- [ ] README still points to the latest release channel.
- [ ] Issue templates are suitable for this release's supported platforms.
