# DevKitty Native releases

This repository hosts public application downloads and the signed Sparkle update
feed for DevKitty Native. It does not contain the application source code.

**Platform:** macOS 27 or newer, Apple Silicon.

## Downloads

App downloads will appear under [Releases](https://github.com/egor-xyz/devkitty-releases/releases)
after Developer ID signing and Apple notarization are complete. No app download
has been published yet.

## In-app updates

Updater-enabled versions use this HTTPS feed:

https://raw.githubusercontent.com/egor-xyz/devkitty-releases/main/appcast.xml

The app verifies Ed25519 signatures on the feed and update packages. Release
packages must also be Developer ID signed and notarized. The private update key
is never published here.

An empty feed means no installable update has been published. Install the first
updater-enabled release manually; later releases can update within the app.
