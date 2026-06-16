# Clash Premium — binary archive mirror

Archive mirror of **Clash Premium** binaries preserved by the community after Dreamacro removed the upstream repositories in November 2023.

Maintained by [JieMeiDev](https://github.com/JieMeiDev) as a read-only reference — no functional changes intended.

Mirrored from [zhongfly/Clash-premium-backup](https://github.com/zhongfly/Clash-premium-backup).

## Important: official source was never public

Dreamacro developed Clash Premium in a **private** repository. Only **compiled binaries** were published (free of charge). There is **no official public Git commit** matching the final Premium build.

| What | Status |
|------|--------|
| Official Premium **source** at final version | **Not available** |
| Official Premium **binaries** at final version | Archived in **this repository** |
| Community Premium **source** snapshot | [JieMeiDev/clash-premium](https://github.com/JieMeiDev/clash-premium) (best-effort mirror with TUN / TProxy / Fake-IP features) |

## This archive

| Field | Value |
|-------|-------|
| **Contents** | Premium release builds and nightly builds (all platforms) |
| **Final nightly** | `2023-09-05-gdcc8d87` |
| **Mirrored from** | [zhongfly/Clash-premium-backup](https://github.com/zhongfly/Clash-premium-backup) |
| **Nightly backups since** | 2022-01-10 |
| **Release backups since** | 2022-01-03 |

Premium-only features in these binaries include **TUN**, **TProxy**, **Fake-IP DNS**, **Rule Providers**, **Script rules**, and **Process-based routing**.

## Final official binaries (recommended)

The last Premium builds distributed by Dreamacro:

| Channel | Version | Git hash in filename |
|---------|---------|----------------------|
| GitHub Release tag `premium` | **2023.08.17** | `gdcc8d87` (13 commits after 2023.08.17) |
| Last nightly backup | **2023-09-05** | `gdcc8d87` |

Download all platforms from **[Release `2023-09-05-gdcc8d87`](https://github.com/JieMeiDev/clash-premium-backup/releases/tag/2023-09-05-gdcc8d87)**.

For router / OpenWrt (arm64 example):

```text
clash-linux-arm64-2023.08.17-13-gdcc8d87.gz
```

| Platform (router) | Asset example |
|-------------------|---------------|
| Linux amd64 | `clash-linux-amd64-n2023-09-05-gdcc8d87.gz` |
| Linux arm64 | `clash-linux-arm64-n2023-09-05-gdcc8d87.gz` |
| Linux arm64 (OpenClash) | `clash-linux-arm64-2023.08.17-13-gdcc8d87.gz` |

## Related archives

| Repository | Contents |
|------------|----------|
| [JieMeiDev/clash](https://github.com/JieMeiDev/clash) | Open-source Clash core **v1.18.0** (no Premium features) |
| [JieMeiDev/clash-premium](https://github.com/JieMeiDev/clash-premium) | Premium **Go source** community snapshot |
| [MetaCubeX/mihomo](https://github.com/MetaCubeX/mihomo) | Actively maintained open-source successor |

## Notes

- This repository is **not** affiliated with Dreamacro.
- For production use on a router today, prefer official **`gdcc8d87` binaries** from this archive, or migrate to **mihomo**.
- Community source builds ([clash-premium](https://github.com/JieMeiDev/clash-premium)) are **not** byte-identical to official Premium `gdcc8d87` binaries.
- Original upstream docs: [Clash Wiki](https://github.com/Dreamacro/clash/wiki) (archived).
