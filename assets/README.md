# Assets

- `ftorrent-icon.svg` — the fTorrent icon: a green disc inside a white ring (with a hairline dark edge so the ring shows on light backgrounds), and a solid white "f" leaning to the left. Two parts of the f run into the ring, like the legs of the glyph in the classic logo: the foot at the bottom and the left end of the crossbar (the horizontal "cut" of the f) on the left. The hook at the top keeps a free end. Original artwork, a fresh green (#5fe08c to #1e9d55). It only uses what the forge icon rasterizer supports, so `forge build` turns it into `.icns` (macOS), `.ico` (Windows) and PNGs (Linux) without extra tools. The same icon is used for the window title bar and for the installer header.
- `ftorrent-icon-512.png` — a 512 px preview rendered by forge's own rasterizer, with a transparent background.

Liquid Glass layers (`icon/background.svg` and `icon/foreground-N.svg`) will be added when the app is built for macOS 26.
