
# Docs ![Icon](https://github.com/elementaryrevivals/docs/raw/master/data/icons/64/com.github.elementaryrevivals.docs.svg)

[![Get it on AppCenter](https://appcenter.elementary.io/badge.svg)](https://appcenter.elementary.io/com.github.elementaryrevivals.docs)

A fast developer docs reader
![Screenshot](https://raw.githubusercontent.com/elementaryrevivals/docs/master/data/images/screenshot-1.png)
![Screenshot](https://raw.githubusercontent.com/elementaryrevivals/docs/master/data/images/screenshot-4.png)

## Doc Sources:
 - Valadoc
 - DevDocs

## Build Dependencies:
 - libarchive-dev
 - libdevhelp-dev
 - libgee-0.8-dev
 - libgranite-dev
 - libgtk-3-dev
 - libwebkit2gtk-4.0-dev
 - meson
 - valac

## Install:
### Flatpak:
 Docs is avaliable on Flathub, install it by running:
 ```
 flatpak install flathub com.github.elementaryrevivals.docs
 ```

## Install From Source:
The following instructions should work on most debian-based systems:
```
sudo apt install libarchive-dev libdevhelp-dev libgee-0.8-dev libgranite-dev libgtk-3-dev libwebkit2gtk-4.0-dev meson valac
git clone https://github.com/elementaryrevivals/docs.git
cd ./docs/
meson build --prefix=/usr
cd build
ninja
sudo ninja install
```
