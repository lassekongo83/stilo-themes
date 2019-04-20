# stilo-themes
Minimalistic GTK themes

These themes are still in development. Things may change.

### Requirements

- GNOME Shell 3.30+
- GTK 3.24.6+

<sub>I can't guarantee that the themes will look as intended on older versions.</sub>

Some of these packages may already be installed by default on some distros.

* Debian/Ubuntu/Mint - `apt install gtk2-engines-murrine gtk2-engines-pixbuf fonts-roboto ninja-build git meson sassc`
* Arch/Manjaro/Antergos - `pacman -S gtk-engine-murrine gtk-engines ttf-roboto ninja git meson sassc`
* Opensuse - `zypper in gtk2-engine-murrine gtk2-engines google-roboto-fonts ninja git meson sassc`
* Fedora - `dnf install gtk-murrine-engine gtk2-engines google-roboto-fonts ninja-build git meson sassc`

Other distros may have named the above packages differently.

## Installation

When the above requirements are installed, simply run these commands.
```bash
git clone https://github.com/lassekongo83/stilo-themes.git
cd stilo-themes
meson build
sudo ninja -C build install
```
The themes will be installed in: `/usr/share/themes`
