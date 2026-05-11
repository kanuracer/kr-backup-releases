# KR Backup Releases

Public update feed for KR Backup portable Windows builds.

## Current release

- Version: `0.1.1`
- Package: `KR-Backup-v0.1.1-win-x64-portable.zip`
- SHA256: `861f4b5ccb3e2292b0b2d064293cb44c8d7605f200131a8345da71413cdb78ee`
- Size: `70,279,002` bytes

## Update feed

`latest.json` is the machine-readable feed used by KR Backup.

```text
https://raw.githubusercontent.com/kanuracer/kr-backup-releases/main/latest.json
```

The app downloads the ZIP URL from `latest.json`, verifies SHA256 when present, and hands installation to `KrBackup.Updater.exe`.
