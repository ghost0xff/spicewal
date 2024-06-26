# spicewal
theme to sync spotify and pywal (with spicetify)

## Description
Just a theme to make your spotify client look like a TUI
and have the same color scheme as the rest of 
your system (using [pywal](https://github.com/dylanaraps/pywal)). Feel free to modify
any parameters on the css or on the colors selected
from pywal-generated palette. This is only posible if you use
[spicetify](https://spicetify.app/) to get the most out of your 
spotify client.

## Examples

![Solarized Theme(solarized)](screenshots/solarized.png?raw=true "solarized")

![Nord Theme(waifu)](screenshots/nord-waifu.png?raw=true "waifu")

![Nerv Theme(evangelion)](screenshots/evangelion-nerv.png?raw=true "nerv")

![Rei Theme(evangelion)](screenshots/evangelion-rei.png?raw=true "rei")

## Dependencies
- [spicetify](https://spicetify.app/)
- [pywal](https://github.com/dylanaraps/pywal)

## Installation
1. Clone this repo under the directory where spicetify looks for themes (on linux it's `~/.config/spicetify/Themes` )
 ```bash
    cd ~/.config/spicetify/Themes
    git clone https://github.com/ghost0xff/spicewal.git

 ```
2. Apply theme with
```bash
    spicetify config current_theme spicewal
    spicetify apply
```
3. Open Spotify


 ## Troubleshooting
"First time worked but now spotify theme doesn't change after
creating a new pywal colorscheme"

That's because you need to somehow notify spicetify that your color
scheme changed.
1) You can either manually re-apply theme with:
```bash
spicetify apply
```
2) Or automatically re-apply theme (script, key binding, etc...)
, just like I do it in [stheme (on my dotfiles)](https://github.com/ghost0xff/dotfiles), which
is a personal tool I use to sync the colorscheme of all my system (rgb,
wallpaper, terminals, window manager and other apps)


## Credits
Although modified a bit, css styles that make spotify look like [spotify-tui](https://github.com/Rigellute/spotify-tui) were "forked" from [darkthemer](https://github.com/darkthemer)
(who mantains [this repo](https://github.com/darkthemer/spicetify-themes) with various spicetify themes)
