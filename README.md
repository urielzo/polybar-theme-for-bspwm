# theme-polybar-macstyle for Bspwm

## Preview

## Clean
![clean](/preview/clean.png)
<br />
## Menus
![Menus](/preview/bspwm.png)

* Distro: [ArchLabs](https://archlabslinux.com/)
* Window manager: [bspwm]
* Bar: [Polybar](https://github.com/polybar/polybar)
* Launcher: [Rofi](https://github.com/davatorium/rofi)
* Compositor [picom (kawase-blur)](https://github.com/ibhagwan/picom)
* Display: [1600x900]

### Other prerequisites
* `mpc mpd ncmpcpp`
* `xdotool`
* `imagemagick`
* `nitrogen`
* `pamac`
* `scrot`
* `pavucontrol`
* `ttf-font-awesome` (AUR)
* `Sans` (or change the font to whatever you want)
* `Iosevka Nerd Font`


### add this lines to your bspwmrc

## polybar launch
pkill polybar
~/.config/polybar/dropdown/tablet_mode &


### optional add this lines to your sxhkdrc

## control_center open&close
super + BackSpace
    ~/.config/polybar/dropdown/polybar_modules/tablet_options toggle
