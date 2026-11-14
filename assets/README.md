# Assets

- `ftorrent-icon.svg` — the fTorrent icon: a disc with a slanted "f" cut out of it (even-odd fill, so the letter is really transparent). Original artwork, forge palette (orange to red). It only uses what the forge icon rasterizer supports, so `forge build` turns it into `.icns` (macOS), `.ico` (Windows) and PNGs (Linux) without extra tools.
- `ftorrent-icon-512.png` — a 512 px preview rendered by forge's own rasterizer.

Liquid Glass layers (`icon/background.svg` and `icon/foreground-N.svg`) will be added when the app is built for macOS 26.
