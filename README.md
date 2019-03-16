# stilo-themes
Minimalistic GTK themes

Alpha version. Things may change.

### Requirements
GTK 3.30+

<sub>Some or all of these packages may already be installed by default on some distros.</sub>

* Debian/Ubuntu/Mint - `apt install gtk2-engines-murrine gtk2-engines-pixbuf ttf-ubuntu-font-family`
* Arch/Manjaro/Antergos - `pacman -S gtk-engine-murrine gtk-engines ttf-ubuntu-font-family`
* Opensuse - `zypper in gtk2-engine-murrine gtk2-engines ubuntu-fonts`
* Fedora - `dnf install gtk-murrine-engine gtk2-engines`

## Installation

This installation method is to try out the theme while developing it.

Make sure you have `git`, `meson`, [ninja](https://github.com/ninja-build/ninja/wiki/Pre-built-Ninja-packages), and `sassc` installed.
```bash
git clone https://github.com/lassekongo83/stilo-themes.git
cd stilo-themes
meson build
sudo ninja -C build install
```
The themes will be installed in: `/usr/share/themes`
