# stilo-themes
Minimalistic GTK themes

These themes are still in development. Things may change.

### Requirements
GTK 3.30+

<sub>The theme should work with 3.28 as well, or even 3.22. I just can't guarantee that everything will look right.</sub>

Some or all of these packages may already be installed by default on some distros.

* Debian/Ubuntu/Mint - `apt install gtk2-engines-murrine gtk2-engines-pixbuf fonts-roboto ninja-build git meson sassc`
* Arch/Manjaro/Antergos - `pacman -S gtk-engine-murrine gtk-engines ttf-roboto ninja git meson sassc`
* Opensuse - `zypper in gtk2-engine-murrine gtk2-engines google-roboto-fonts ninja git meson sassc`
* Fedora - `dnf install gtk-murrine-engine gtk2-engines google-roboto-fonts ninja-build git meson sassc`

Other distros may have named the above packages differently.

## Installation

Make sure you have `git`, `meson`, [ninja](https://github.com/ninja-build/ninja/wiki/Pre-built-Ninja-packages), and `sassc` installed.
```bash
git clone https://github.com/lassekongo83/stilo-themes.git
cd stilo-themes
meson build
sudo ninja -C build install
```
The themes will be installed in: `/usr/share/themes`
