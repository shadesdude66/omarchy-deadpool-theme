<p align="center">
  <img src="images/logo.png" width="180" alt="Deadpool logo" />
</p>

<h1 align="center">Omarchy Deadpool Theme</h1>

<p align="center">
  A dark, blood-red <a href="https://omarchy.org">Omarchy</a> theme for anyone who runs their desktop at maximum effort.
</p>

<p align="center">
  <img src="preview.png" width="600" alt="Deadpool theme desktop preview" />
  <br/>
  <img src="unlock.png" width="600" alt="Deadpool theme lock screen preview" />
</p>

## Installation

**Option 1: Omarchy TUI**

Open the theme menu (`Super + Ctrl + Shift + Space` by default) and choose **Install**, then paste this repo's URL.

**Option 2: Omarchy CLI**

```bash
omarchy theme install https://github.com/shadesdude66/omarchy-deadpool-theme.git
```

This clones the theme into `~/.config/omarchy/themes/deadpool` and applies it automatically.

**Option 3: Manual clone**

```bash
git clone https://github.com/shadesdude66/omarchy-deadpool-theme.git ~/.config/omarchy/themes/deadpool
omarchy theme set Deadpool
```

## What's included

- `colors.toml` — accent red/black palette used across the terminal, Hyprland, and Waybar
- `icons.theme` — Yaru-red icon set
- `backgrounds/maximum-effort.jpg` — theme wallpaper
- `preview.png`, `preview-unlock.png`, `unlock.png` — screenshots used by the [Omarchy theme gallery](https://omarchy.org/themes)

Everything else (terminal configs, VS Code, btop, keyboard RGB, etc.) is generated automatically from `colors.toml` when the theme is applied — this repo intentionally doesn't ship `neovim.lua` or `vscode.json`, since Omarchy strips those from any git-installed theme for security (they'd be silently ignored anyway).

## Uninstall

```bash
omarchy theme remove Deadpool
```
