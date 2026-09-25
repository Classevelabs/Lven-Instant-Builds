# Lven downloads

Installers for **Lven Instant** (voice to text on your own device) and **Lven Cloud** by [ClassEve](https://classeve.com), and the speech engine Lven Instant fetches on first run.

The current version of every download, with its size and SHA-256, is listed at **[classeve.com/releases/lven](https://classeve.com/releases/lven)**. Download from there: every link on that page points at a release here.

| | Windows | Linux | Android |
| --- | --- | --- | --- |
| Lven Instant | `Setup.exe` | `.deb`, `.rpm`, `.AppImage` | Google Play, or the `.apk` here |
| Lven Cloud | `Setup.exe` | `.deb`, `.rpm`, `.AppImage` | Google Play, or the `.apk` here |

## Check a download

Every file has a `.sha256` file beside it with the file's SHA-256.

- **Windows**, in PowerShell: `Get-FileHash .\<file>` and compare the hash with the `.sha256` file.
- **Linux**: put both files in one folder and run `sha256sum -c <file>.sha256`.

On first run, Windows SmartScreen can ask for confirmation: choose **More info**, then **Run anyway**, once the SHA-256 matches.

## Android

If you installed from Google Play, keep updating from Google Play. The APKs here are for devices without Play, and one cannot update an app installed from the other.

## Help

Support: [classeve.com/support](https://classeve.com/support) · Security: security@classeve.com · Official accounts: [classeve.com/official](https://classeve.com/official)

© ClassEve. All rights reserved.
