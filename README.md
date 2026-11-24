# Secret Stash releases

Secret Stash is a homebrew app for PS4 consoles with GoldHEN: install games & apps on your PS4 from community catalogs.

This repository holds only the release packages and their release notes. The source code is not published here.

## Install

### From the PS4 browser

1. Start GoldHEN and turn on its payloader server: **GoldHEN > Server Settings > Enable PayLoader Server**.
2. Open the PS4 web browser and go to **[install.secret-stash.app](http://install.secret-stash.app)**.
3. Press **Install**. Secret Stash downloads, installs and opens.

### By hand

1. Open the [latest release](../../releases/latest) and download `Secret-Stash-<version>.pkg`.
2. Optional: check the file against the `.sha256` file next to it (`sha256sum -c Secret-Stash-<version>.pkg.sha256`).
3. Copy the `.pkg` to the root of a USB drive formatted as exFAT or FAT32.
4. On the PS4, open **GoldHEN > Debug Settings > Package Installer**, choose the package and install it.
5. Start **Secret Stash** from the home screen.

## Updates

Secret Stash updates itself: **Settings > About > Check for updates**. Your settings, catalogs and downloads stay.

## Ideas and problems

Suggest a feature or report a problem under [Issues](../../issues).

## Releases

Each release is built from a tagged version by GitHub Actions and carries the package, its SHA-256 checksum
and the release notes.
