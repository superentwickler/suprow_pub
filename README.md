# suprow

A lightweight browser for web apps – built for people who care about focused workflows and tidy desktops.

This repository is **not** the full source code of suprow.  
It is a public hub for:

- **App downloads** (macOS, Windows, Linux)
- **Release notes & changelogs**
- **Screenshots and marketing assets**
- **Issues and pull requests** from the community

---

## What is suprow?

suprow is a **lightweight desktop browser for web apps**.  
It focuses on **fast startup, minimal UI and keyboard‑centric workflows**, so you can keep separate, focused spaces for different kinds of work.

### Key ideas

- **Lightweight browser**  
  Not a bloated, general‑purpose browser, but a focused shell‑style browser for web apps. Fast startup, minimal chrome, maximum focus.

- **Spaces instead of tabs**  
  Organise your tools into spaces like _work_, _deep‑focus_, _playground_.  
  Each space can have its own apps, settings and windows.

- **Keyboard‑centric UI**  
  Terminal‑like vibes with a command palette and clear text UI.  
  suprow feels more like a **window manager for web apps** than a classic browser.

---

## Downloads

> **Note**: Downloads are provided via GitHub Releases in this repository.  
> The desktop app is the primary way to use suprow today – the CLI shown in screenshots is illustrative only.

- **macOS**  
  - `.dmg` for Intel & Apple Silicon  
  - See the latest macOS builds under **Releases → macOS**

- **Windows**  
  - Classic installer and portable `.exe` builds  
  - See the latest Windows builds under **Releases → Windows**

- **Linux** (experimental)  
  - `AppImage` and `.deb` packages (Beta)  
  - See the latest Linux builds under **Releases → Linux**

The `releases/` folder in this repo may contain mirrors or helper files, but the canonical downloads live under GitHub Releases.

---

## Current Beta – v0.9.0‑beta (Desktop)

- **Stage**: Beta · Desktop only

### New features

- Space‑based window management for your web apps (e.g. Work / Side / Focus)
- Built‑in ad blocker via `@ghostery/adblocker-electron`
- Start page with space overview, editable grids and quick links
- Picture‑in‑picture windows for mini‑browsers, video players or dashboards
- Tab switcher / command palette (`⌘K` / `Ctrl+K`) for jumping between tabs, apps and history
- One‑click incognito mode (👻) with isolated session and no history
- Settings view for default space, start URL, theme and privacy options
- Import/export of spaces and settings for easy backups and sharing

### Improvements

- More stable window handling and better shortcuts
- Faster app startup through optimised preload
- Improved error pages & dialogs
- Early translation/locale hooks (not fully exposed yet)

### Known limitations

- No auto‑updates in the beta
- No multi‑user profile support (yet)
- Linux builds are experimental

---

## Screenshots & assets

The `assets/` directory contains the public marketing images used on the website and in this README.

### App previews

![suprow browser](assets/browser.png)

![suprow spaces](assets/space.png)

![suprow tab switcher](assets/tab_switch.png)

### Settings & terminal teaser

![suprow settings](assets/settings.png)

![suprow terminal concept](assets/terminal.png)

You can also reference these assets from other places (websites, blog posts, etc.) by pointing to the raw file URLs on GitHub or via a CDN that serves GitHub assets.

---

## CLI concept (illustrative)

Some screenshots show a terminal prompt like:

```text
suprow@desktop: ~
λ suprow --space work --app mail
↳ launching focused mail space…
λ suprow --space side --app github --pip
↳ picture‑in‑picture debug browser enabled
```

This is **illustrative only**.  
suprow is a **desktop app today**, not a real CLI tool (yet).  
If a future CLI becomes available, it will be documented here.

---

## How to use this repository

- **Releases & downloads**: grab the latest builds from the **Releases** section.
- **Issues**: report bugs, request features, or ask questions via GitHub Issues.
- **Pull requests**: propose fixes to docs, assets, or metadata via PRs.

If you are looking for the full application source code, it is currently **not** part of this repository.

---

## License

Unless stated otherwise in specific subfolders, assets and documentation in this repository are provided for use with the suprow app and website.  
If you are unsure about a particular use case, please open an Issue to ask.

