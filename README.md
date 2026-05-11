# KR Backup Releases

Public update feed for KR Backup portable Windows builds.

## Current release

- Version: `0.1.6`
- Update asset: `KR-Backup-v0.1.6-update-from-0.1.x.zip`
- Update SHA256: `d68308c691582827dc7458ffcdf87557db9093409d7a5a4235a3905961566f52`
- Full portable ZIP: `KR-Backup-v0.1.6-win-x64-portable.zip`
- Full portable SHA256: `c07ce30abb657b6891d5cdcfc2df726cc6b2163cf0718aa6e71162437e793d33`

## Notes

UI polish: dark theme scrollbars now use themed dark track/thumb colors instead of white system defaults. Added AGENTS.md documenting the planning, coding, testing, QA, documentation, and release workflow for reuse in other projects.

## Update feed

`latest.json` is the machine-readable feed used by KR Backup.

```text
https://raw.githubusercontent.com/kanuracer/kr-backup-releases/main/latest.json
```

For `0.1.x`, the feed points at a small compatibility patch ZIP so the old updater can replace app binaries without touching locked runtime/updater files. The full portable ZIP is published alongside it for manual fresh installs.
