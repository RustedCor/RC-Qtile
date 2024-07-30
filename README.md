# QTileWM X11 Rice
![Config image 1](./screenshots/qtile1.png)
![Config image 2](./screenshots/qtile2.png)
![Config image 3](./screenshots/qtile3.png)
## Packages
- Qtile 
- Alacritty 
- Rofi (Will be customized in the future)
- Picom (with glx backend)
- Nitrogen (you must set the wallpaper manually)
- Flameshot
- NerdFonts (I use Iosevka Nerd Font)
- LightDM (But I don't customize it yet, so I don't include this in the repo yet)

## Installation

1. Clone the repository
`git clone https://github.com/JuanZuniga7/qtile-config.git`
2. Delete actual Qtile configuration
`rm -rf ~/.config/qtile`
3. Copy the configuration files to the Qtile directory
`mv ./qtile-config ~/.config/qtile`
4. Move Alacritty configuration file
`mv ~/.config/qtile/others/alacritty ~/.config/`
5. Move Picom configuration file
`mv ~/.config/qtile/others/picom ~/.config/`
6. Set the wallpaper with Nitrogen
`nitrogen ~/path/to/wallpaper --set-auto --save`
7. Restart Qtile pressing `Mod + Control + R`
8. Maybe you need to restart your computer to apply picom changes