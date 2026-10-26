# Offshore Oil & Gas Platforms review evidence

Recorded 26 October 2026 from the `codex/offshore-platforms` feature branch of
khanmjk/gods-eye-view, against upstream main a3a19883. Proposal:
https://github.com/bilawalsidhu/gods-eye-view/issues/1292

- `layer-panel.png`: actual Infrastructure panel toggle, legend, date and scope.
- `gulf-overview.png`: bounded Gulf overview.
- `platform-selection.png`: native platform click and shared selection card.
- `offshore-platforms.mp4`: panel toggle, camera movement, record selection and disable.
- `results.json`: 12 passing feature browser checks.

Command: `node scripts/qa-offshore-platforms.mjs --url http://127.0.0.1:4173 --record`.
Keyless app, Node 26.3.1, macOS arm64, headless system Google Chrome. The data is
BSEE's actual 2026-10-01 snapshot; no synthetic records were used in these visuals.
Basemap imagery is credited in the app. The layer is a dated inventory, not live
production status. Full source provenance and licensing accompany the feature PR.
