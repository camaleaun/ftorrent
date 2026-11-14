# Assets

- `ftorrent-icon.svg` — the fTorrent icon: a green disc inside a white ring (with a hairline dark edge so the ring shows on light backgrounds), and a solid white "f" leaning to the left. The two ends of the f's stem run into the ring: its start at the upper left and its foot at the bottom; the right end of the hook is free. Original artwork, a fresh green (#5fe08c to #1e9d55). It only uses what the forge icon rasterizer supports, so `forge build` turns it into `.icns` (macOS), `.ico` (Windows) and PNGs (Linux) without extra tools. The same icon is used for the window title bar and for the installer header.
- `ftorrent-icon-512.png` — a 512 px preview rendered by forge's own rasterizer, with a transparent background.

Liquid Glass layers (`icon/background.svg` and `icon/foreground-N.svg`) will be added when the app is built for macOS 26.
