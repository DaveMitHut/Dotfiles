# Dotfiles

Contains all dotfiles neccesary to restore custom i3-gaps flair, keybindings and configuration.

## Dependencies

In oder to fully reproduce the i3 flair, you need to install the following packages after installing i3-gaps:

### rofi

`pacman -S rofi`

### Polybar

1. Clone the *polybar*-package from the **AUR** with `git clone https://aur.archlinux.org/polybar.git` and change into the repository
2. Verify the **PKGBUILD** and all other files
3. Install the package with `makepkg -si`

### Font-Awesome

1. Download the Font-Awesome package from their [website](https://fontawesome.com/how-to-use/on-the-desktop/setup/getting-started)
2. Unpack the fonts
3. Copy each font to their own folder in `/usr/share/fonts/`

### Additional programs

The programs named here are all used in the i3 configuration.

`pacman -S numlockx polkit scrot alsa alacritty mpd xss-lock i3lock-color ntfs-3g udisks2 alsa-utils feh ranger unzip`
