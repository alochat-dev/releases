# Alo releases

This repository holds the downloadable desktop installers for **Alo**, and
nothing else. It contains no source code.

Alo is a cross-language messenger: each person reads and writes in their own
language, and a private AI translates with the context of the relationship.
It runs on the web at <https://app.alochat.ai>, on iPhone and Android, and on
desktop with these installers.

## Downloading

The files can be fetched directly from the latest release:

- macOS, Apple silicon and Intel in one file:
  [`Alo.dmg`](https://github.com/appology/alo-releases/releases/latest/download/Alo.dmg)
- Windows, 64-bit:
  [`Alo-Setup.exe`](https://github.com/appology/alo-releases/releases/latest/download/Alo-Setup.exe)
- Linux, 64-bit:
  [`Alo.AppImage`](https://github.com/appology/alo-releases/releases/latest/download/Alo.AppImage)
  or, for Debian and Ubuntu,
  [`Alo.deb`](https://github.com/appology/alo-releases/releases/latest/download/Alo.deb)

The macOS app is signed and notarized by Apple. The Windows installer is
**not code-signed yet**, so Windows SmartScreen shows a warning the first time
you run it. Choose **More info**, then **Run anyway**.

On Linux, calls depend on the system's web engine. If it can't place a call,
Alo offers to open the call in your browser instead.

Each release also carries a `latest.json` and signatures ending in `.sig`.
Those are for the app's built-in updater and are not meant to be downloaded
by hand. The desktop app updates itself; the `.deb` does not, so reinstall it
from here to update.

## Where the code is

The source is in a private repository, which is why this one exists: it is the
public place to get the built programs. Releases are produced automatically
from that repository, and nothing is ever edited here by hand.
