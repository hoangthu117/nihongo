# Nihongo Quest Sakura v3

Static PWA for GitHub Pages. Includes 187 vocabulary entries and 18 grammar patterns for lessons 26-31.

## Deploy

Unzip, open the `nihongo-quest` folder, and upload all eight files to the ROOT of your GitHub repository. Replace existing files, including `sw.js`. In repository Settings > Pages select Deploy from a branch, `main`, `/(root)`. Open the published URL in Safari and refresh. The service-worker cache has been bumped to v3.

## Data and progress

The original `words.json`, `grammar.json`, and localStorage key `nihongo-quest-v1` are preserved. To move progress between domains, use Stats > Backup progress and Stats > Restore progress. Never delete Safari website data before backing up.

## Improvements

- Pastel kawaii UI, Sakura mascot, touch-friendly buttons.
- Kanji colored pink, kana colored purple.
- Detailed vocabulary panel using existing hints and Japanese example sentences.
- Separate voice status and persistent Next button after answering.
- SRS, boss, grammar, statistics, JSON backup/restore.
- Safer output escaping and graceful unsupported-microphone handling.

## Known limits

Many vocabulary records lack verified Han-Viet readings, Vietnamese translations of their example sentences, or examples. The app does not invent them. Grammar self-checks are not auto-graded. Safari speech recognition depends on device and browser support. This release was syntax-checked but not tested on a physical iPad.
