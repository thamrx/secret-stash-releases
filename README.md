# Secret Stash releases

Secret Stash is a homebrew app for jailbroken PS4 consoles. It browses package catalogs in the style of the
PlayStation Store, with search, sorting and filters, and downloads and installs packages on the console.

This repository holds only the release packages and their release notes. The source code is not published here.

## Install

You need a PS4 with a homebrew-enabled firmware (for example with GoldHEN) and its package installer.

1. Open the [latest release](../../releases/latest) and download `Secret-Stash-<version>.pkg`.
2. Optional: check the file against the `.sha256` file next to it (`sha256sum -c Secret-Stash-<version>.pkg.sha256`).
3. Copy the `.pkg` to the root of a USB drive formatted as exFAT or FAT32.
4. On the PS4, open **Settings > Debug Settings > Game > Package Installer**, choose the package and install it.
   Any other package installer works too, such as a remote installer over the network.
5. Start **Secret Stash** from the home screen (it is listed under Applications).

Installing a newer version over an older one keeps your settings and catalogs.

## Releases

Each release is built from a tagged version by GitHub Actions and carries the package, its SHA-256 checksum
and the release notes.
