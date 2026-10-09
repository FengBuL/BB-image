# BB-image

A Cursor skill that turns a piece of announcement copy into a vertical **3:4** social cover in a distinctive house style: ink-black × signal-blue × paper-white, thin and slightly muted typography, and a large brand wordmark.

- `BB-image/` — the skill itself (`SKILL.md`, colour guide, typography rules, 15 style hooks under `styles/`).
- `gallery/` — one sample cover per style, all native 1086×1448 (3:4). `_overview.jpg` shows them together.

## How it works

1. Read the copy, extract the brand / product name (must span at least 1/3 of the canvas width).
2. Pick a colour family (A ink-black, B paper-white, C signal-blue, D red-black narrative, E light-top / dark-bottom) via `COLOR-GUIDE.md`.
3. Pick a style hook (`THEME-GUIDE.md`, `styles/NN-*.md`) and vary it (`VARIATIONS.md`).
4. Apply `TYPOGRAPHY.md`: thin / light weights, slightly muted text colour, no bold or heavy display type.
5. Generate natively at 3:4 and verify pixel size. Never crop or stretch to fix the ratio.

Sample covers use "Claude" product-update copy purely as example content; no usernames or handles appear on any cover.
