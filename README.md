# Adwaita Dracula

[Adwaita](https://github.com/GNOME/gtk/tree/mainline/gtk/theme/Adwaita) with the [Dracula color scheme](https://github.com/dracula/dracula-theme)

## How to use

1. [Download](https://github.com/p00f/adwaita-dracula/releases) and then unzip `Adwaita-Dracula` to `~/.local/share/themes`(or `/usr/share/themes`)
2. Install [GNOME Tweaks](https://wiki.gnome.org/Apps/Tweaks) and [User Themes Extension](https://extensions.gnome.org/extension/19/user-themes/)
3. Open Tweaks and select `Applications` theme and `Shell` theme
4. <kbd>Alt</kbd> + <kbd>F2</kbd>; input `r`; <kbd>Enter</kbd> to refresh

## Colors I changed

See [`68ea503`](https://github.com/p00f/adwaita-dracula/commit/68ea50359b1fdbbf18ed43b5202b2d5de9c59d11) and [`3c62176`](https://github.com/p00f/adwaita-dracula/commit/3c621766a50a35070fb8cbdd7476b799e8596d6a)

## How to build by hand

You need install [SassC](https://github.com/sass/sassc) first. Then modify `src/gtk-3.0/_colors.scss` and `src/gnome-shell/gnome-shell-sass/_colors.scss` to change the colours if you want, then run `build.fish` (using `fish build.fish`. I believe any shell would work, there is nothing fish-specific in that file)

## Notes

Some apps use `$sidebar_bg_color`(Nautilus) for sidebars, but some apps use `$base_color`(Tweaks)

## Credits

Huge thanks to [@lonr](https://github.com/lonr) for [Adwaita-One-Dark](https://github.com/lonr/adwaita-one-dark)

## Screenshots

![alt text](https://raw.githubusercontent.com/p00f/adwaita-dracula/master/screenies/1.png)
![alt text](https://raw.githubusercontent.com/p00f/adwaita-dracula/master/screenies/2.png)
![alt text](https://raw.githubusercontent.com/p00f/adwaita-dracula/master/screenies/3.png)
![alt text](https://raw.githubusercontent.com/p00f/adwaita-dracula/master/screenies/4.png)
![alt text](https://raw.githubusercontent.com/p00f/adwaita-dracula/master/screenies/5.png)
![alt text](https://raw.githubusercontent.com/p00f/adwaita-dracula/master/screenies/6.png)
