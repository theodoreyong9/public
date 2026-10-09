# Aiwa — public files

What anybody (and every Claude session) can read without an account: the standards and tools Claude follows when it designs, builds a game or makes a promotional video, the Termux backend and its install scripts, the papers, and the promotional video.

- `access.json` — who may use the official build of the app: `enforce` (off until turned on), `level2` (everything), `level1` (GitHub Pages and Android APK only). This file is edited here, by hand.
- `docs/` — the papers, `GAME-FOUNDATION.md`, `PROMO-VIDEO.md`, `aiwa-promo.mp4`.
- `design-research/` — the design research tool and its catalogue.
- `video-kit/` — the promotional video kit.
- `android/backend/` — the Termux backend and `bootstrap.sh`.

The rest of the files here are copied from the main repository by a workflow (`scripts/sync-public.sh` there): change them there, not here.
