### Showcase
<img src="https://raw.githubusercontent.com/eldritch-theme/eldritch-wezterm/screenshot.png" alt="Screenshot"/><br/>

Eldritch is a community-driven dark theme that draws inspiration from the GMK Terror Below keycap set. The theme is meant for the Lovecraftian horror fans and the people who enjoy the darker side of life.

Main Theme repo can be found at https://github.com/eldritch-theme/eldritch

### Installation
1. Download the `eldritch.toml` file from this directory.
2. Place it in `~/.config/wezterm/colors/eldritch.toml` (or wherever your wezterm configuration is located).
3. In your wezterm.lua file, add the following line:
```lua
-- The following two lines you probably already have, so skip those if you do
local wezterm = require("wezterm")
local config = wezterm.config_builder()

config.color_scheme = "Eldritch"
```
