# STAR-MBTI stable backup

Baseline: `cbdd9d9c816136b66f42d98dfb8773e9c7ef8ce3` — 2026-11-18 17:33:43 Asia/Shanghai. This is the latest commit before 2026-11-19 morning.

The snapshot adds original PNG/SVG artwork that was ignored by Git. Application code is identical to the baseline.

The complete Git bundle will be attached to the GitHub release [backup-before-2026-11-19](https://github.com/shelter-qing/STAR-MBTI/releases/tag/backup-before-2026-11-19). The source ZIP is also available in this repository.

## Restore with full Git history

```sh
git clone STAR-MBTI-before-2026-11-19.bundle mbti-Star-restored
cd mbti-Star-restored
git switch codex/backup-before-2026-11-19
```

The tag `backup-before-2026-11-19-original` preserves the original unmodified commit.

## Restore without Git

Extract `STAR-MBTI-before-2026-11-19-source.zip` and import its folder in WeChat DevTools.
