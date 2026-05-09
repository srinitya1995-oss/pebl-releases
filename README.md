# Pebl Releases

Public download artifacts for **[Pebl](https://peblapp.com)**, a desktop wellness companion that knows when to speak.

The Pebl application source lives in a private repo. This repo hosts the DMG and the auto-updater manifest for public download.

## Download

Easiest path:

```
brew install --cask srinitya1995-oss/pebl/pebl
```

Or grab the DMG directly:

**[Latest release](https://github.com/srinitya1995-oss/pebl-releases/releases/latest)**

Requires macOS 12 (Monterey) or later.

## Notes on the build

The current build is **Apple Silicon only**. Universal (Intel + Apple Silicon) returns in v0.5.0 once a build-config issue with our prebuilt native dependency is resolved. Intel users on macOS 12+ should stay on v0.4.0 in the meantime.

The build is **unsigned and unnotarized**. The Homebrew cask handles this automatically by stripping the quarantine attribute on install. If you download the DMG directly instead, macOS Gatekeeper will block first launch; right-click the app, choose Open, then "Open Anyway." Signing is on the roadmap.

## License

Pebl is open source under the Apache License 2.0. See the [LICENSE](LICENSE) file.

## Security

To report a security vulnerability, see [peblapp.com/.well-known/security.txt](https://peblapp.com/.well-known/security.txt) or email hello@peblapp.com.
