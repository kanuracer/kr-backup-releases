# KR Backup Releases

Public update feed for KR Backup portable Windows builds.

## Current release

- Version: `0.1.2`
- Update asset: `KR-Backup-v0.1.2-update-from-0.1.x.zip`
- Update SHA256: `17d6b1e5f26cf8ba32d51816724cfe5962380e7313aba136308329d716422707`
- Full portable ZIP: `KR-Backup-v0.1.2-win-x64-portable.zip`
- Full portable SHA256: `38e92a74fe86569ee9a540d3f51c60ac65c106833fa883eb92f7879423f54deb`

## Update feed

`latest.json` is the machine-readable feed used by KR Backup.

```text
https://raw.githubusercontent.com/kanuracer/kr-backup-releases/main/latest.json
```

For `0.1.x`, the feed points at a small compatibility patch ZIP so the old updater can replace app binaries without touching locked runtime/updater files. The full portable ZIP is published alongside it for manual fresh installs.
