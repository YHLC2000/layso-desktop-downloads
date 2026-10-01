# Layso Desktop Downloads

Download the latest Layso desktop installer from [Releases](https://github.com/YHLC2000/layso-desktop-downloads/releases). Choose the file that matches your computer:

- **Mac with Apple silicon (M series):** `aarch64.dmg`
- **Mac with an Intel processor:** `x64.dmg`
- **Windows 64-bit:** `.msi`

Each release includes a `SHA256SUMS.txt` file for verifying installer downloads.

## Installation notes

On macOS, drag Layso to Applications. The current builds are ad-hoc signed and have not been notarized by Apple. If macOS blocks the first launch, try opening the app once, then follow [Apple's instructions](https://support.apple.com/guide/mac-help/mh40616/mac) to select **Open Anyway** in System Settings > Privacy & Security.

The Windows installer is not code-signed. Windows may show an unknown publisher or SmartScreen warning, and some managed devices may block installation. Download only from this repository and compare the file's SHA-256 checksum with the release's checksum file.

This public repository contains installers, download instructions, and license notices only. It does not contain the private Layso application source code. For the service and account portal, visit [layso.ai](https://layso.ai).
