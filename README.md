# KR Backup Releases

Public update feed for KR Backup portable Windows builds.

## Current release

- Version: `0.1.0`
- Package: `KR-Backup-v0.1.0-win-x64-portable.zip`
- SHA256: `d1b4d25e05617e908a54f029914f914c36a74ea34b1b58bcb27f89b23b884a70`
- Size: `70,278,686` bytes

## Update feed

`latest.json` is the machine-readable feed used by KR Backup.

```text
https://raw.githubusercontent.com/kanuracer/kr-backup-releases/main/latest.json
```

The app downloads the ZIP URL from `latest.json`, verifies SHA256 when present, and hands installation to `KrBackup.Updater.exe`.
