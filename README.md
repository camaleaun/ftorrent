# fTorrent

<img src="assets/ftorrent-icon-512.png" alt="fTorrent icon: a disc with a slanted f cut out" width="128">

A small native BitTorrent-style client, built with [forge](https://github.com/camaleaun/forge) — a proof of concept for what forge can do beyond a hello world: a multi-screen installer, a classic desktop window (menu bar, toolbar, tree, table, tabs, status bar) and a very small binary.

**Status: work in progress.** Nothing is released yet.

## What this is

- The interface and the installer of fTorrent are modelled on the classic **2.2.1** generation of desktop torrent clients, studied through a written analysis with measurements and drawings (see [`docs/rea/`](docs/rea/)). The fTorrent version is therefore always **2.2.1** (pre-releases are `2.2.1-rc.N`).
- Everything here is original: our own name, icon, texts and drawings. No assets, logos or licence texts of other products are used or redistributed.
- The app is interface-first: the goal is to prove the toolkit (windows, screens, installer actions, size), not to ship a full BitTorrent engine.

## Layout

| Folder | Content |
|---|---|
| `docs/rea/` | Screen-by-screen analysis: measured sizes, controls, texts, states, flows, and drawings (SVG) |
| `assets/` | Our icon (SVG, Liquid Glass layers) and other original artwork |
| `app/` | The forge app: installer and main window |

## License

MIT, see [LICENSE](LICENSE).
