<div align="center">

<img src="icon.png" width="72" alt="Waypoint logo" />

# Waypoint

**A browser you get to redraw.**

[![Latest release](https://img.shields.io/github/v/release/RiseXS/Waypoint-Browser?label=release&color=c99b3d)](https://github.com/RiseXS/Waypoint-Browser/releases/latest)
[![License: MIT](https://img.shields.io/badge/license-MIT-c99b3d)](#license)

</div>

---

Waypoint is a small Electron browser: real Chromium underneath — address
bar, back and forward, reload — with one difference. The tab it opens to is
a homepage made of your own shortcuts, editable right from the page itself.
No config file, no rebuild.

## Features

- **Real Chromium.** Built on Electron, so pages render exactly like they
  would in any other Chromium-based browser.
- **A homepage that's yours.** Add or remove quick links (called
  *waypoints*) from a settings panel on the homepage itself.
- **Google search, built in.** Type a phrase in the address bar or the
  homepage's search box and it searches Google directly.
- **Built-in ad blocking.** Common ad/tracker domains are blocked outright,
  plus a best-effort fast-forward through YouTube ads.
- **Windows installer.** Download and run `Waypoint Setup.exe` like any
  other program — no Node.js required.

## Get it

**Windows:** download `Waypoint Setup.exe` from the latest release and run
it. That's it — Electron's runtime is bundled inside.

**Building from source (any OS):**

- **Windows:** unzip the source, then double-click `install.bat` once and
  `start.bat` any time after.
- **macOS / Linux:** unzip the source, run `npm install` once, then
  `npm start`.

Requires [Node.js](https://nodejs.org) only if building from source.

**[⬇ Download the latest release](https://github.com/RiseXS/Waypoint-Browser/releases/latest)**

## Customizing

Click the gear icon on the homepage to add or remove waypoints. For deeper
changes — default links, accent color, search engine, the app icon — see
the `README.md` inside the project folder once downloaded.

## License

MIT — do whatever you'd like with it.

---

<div align="center">
<sub>Made with <a href="https://claude.com">Claude</a></sub>
</div>
