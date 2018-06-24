Faba Icon Theme
===============

Faba is a sexy and modern FreeDesktop icon set with Tango and elementary influences. It is specifically designed to be a base icon set for the [Moka icon theme](https://github.com/snwh/moka-icon-theme.)

## Copying or Reusing

This project has mixed licencing. You are free to copy, redistribute and/or modify aspects of this work under the terms of each licence accordingly (unless otherwise specified).

The Faba icon assets are licenced under the terms of the [Creative Commons Attribution-ShareAlike 4.0 License](https://creativecommons.org/licenses/by-sa/4.0/).

Included scripts are free software licenced under the terms of the [GNU General Public License, version 3](https://www.gnu.org/licenses/gpl-3.0.txt).

## Installing & Using

You can build and install Faba from source using Meson.

```bash
# build
meson "build" --prefix=/usr
# install
sudo ninja -C "build" install
```

By default it installs to `/usr/` but you can specify a different directory with a prefix like: `/usr/local` or `$HOME/.local`.

After which you should be able to pick Faba as your icon or cursor theme in GNOME Tweak tool, or you can set either from a terminal with:

```bash
# set the icon theme
gsettings set org.gnome.desktop.interface icon-theme "Faba"
```

### Uninstalling Faba

To uninstall Faba, simply run the following. (If you installed it without superuser priveleges just omit the  `sudo`.)

```bash
sudo ninja -C "build" uninstall
```

Once uninstalled you can reset your icon and cursor theme to the default setting by running the following.

```bash
# reset icon theme to default
gsettings reset org.gnome.desktop.interface icon-theme
```

## Donate & Support

If you would like to support development by making a donation you can do so [here](https://snwh.org/donate) or by becoming a supporter on [Patreon](http://patreon.com/snwh/) or [Liberapay](http://liberapay.com/snwh/). &#x1F60A;
