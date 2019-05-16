# stilo-themes
Minimalistic GTK themes

![Stilo themes](preview.png?raw=true)
<sub>[Wallpapers](https://imgur.com/a/zrijHvk) | [Icons](https://github.com/vinceliuice/Tela-icon-theme) | Fonts: Roboto / SF Mono | GNOME shell extension: Dash to Panel</sub>

### Requirements

- GNOME Shell 3.30+
- GTK 3.24.6+

<sub>I can't guarantee that the themes will look as intended on older versions.</sub>

Some of these packages may already be installed by default on some distros.

* Debian/Ubuntu/Mint - `apt install gtk2-engines-murrine gtk2-engines-pixbuf fonts-roboto ninja-build git meson sassc`
* Arch/Manjaro/Antergos - Available in the Arch User Repository: [`stilo-themes-git`](https://aur.archlinux.org/packages/stilo-themes-git/)
* Opensuse - `zypper in gtk2-engine-murrine gtk2-engines google-roboto-fonts ninja git meson sassc`
* Fedora - `dnf install gtk-murrine-engine gtk2-engines google-roboto-fonts ninja-build git meson sassc`

Other distros may have named the above packages differently.

## Installation

When the above requirements are installed, simply run these commands:
```bash
git clone https://github.com/lassekongo83/stilo-themes.git
cd stilo-themes
meson build
sudo ninja -C build install
```
The themes will be installed in: `/usr/share/themes`

### Updating the theme

Navigate to the `stilo-themes` folder that was originally cloned. (If you removed it, do the steps above instead).

Then simply run:
```bash
git pull
sudo ninja -C build install
```

#### Changing themes

Use `gnome-tweaks` to change themes.

You can also change your GTK themes using a terminal.
```bash
# Changing the theme to Stiloetto-dark, simply run
gsettings set org.gnome.desktop.interface gtk-theme Stiloetto-dark

# Reverting the change to the default GNOME theme
gsettings set org.gnome.desktop.interface gtk-theme Adwaita
```
