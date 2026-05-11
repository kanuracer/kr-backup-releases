# KR Backup Releases

Public update feed for KR Backup portable Windows builds.

## Current release

- Version: `0.1.5`
- Update asset: `KR-Backup-v0.1.5-update-from-0.1.x.zip`
- Update SHA256: `65d9139ccb5a101b16605dcf1c48eb92425603cf68837f80b12bab358ef1e6db`
- Full portable ZIP: `KR-Backup-v0.1.5-win-x64-portable.zip`
- Full portable SHA256: `f83c934b93fdb6b2ce8a657238200ecbd4b52415976bc623417a29c6b77efec8`

## Notes

Update UI polish: Changelog and Update-Log now sit side by side; tab content uses vertical scrolling instead of clipping when space is tight; horizontal scrollbars stay disabled with wrapped text.

## Update feed

`latest.json` is the machine-readable feed used by KR Backup.

```text
https://raw.githubusercontent.com/kanuracer/kr-backup-releases/main/latest.json
```

For `0.1.x`, the feed points at a small compatibility patch ZIP so the old updater can replace app binaries without touching locked runtime/updater files. The full portable ZIP is published alongside it for manual fresh installs.
